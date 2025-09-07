# argus-api-tester
Open source API testing tool 

argus/
  pyproject.toml
  README.md
  requirements.txt
  argus_api_tester/
    __init__.py
    config.py
    models.py
    utils.py
    anonymize.py
    parsers/
      __init__.py
      postman.py
      openapi.py
      wsdl.py
    scanner/
      __init__.py
      core.py
      http.py
      registry.py
      plugins/
        __init__.py
        base.py
        methods_enum.py
        headers_security.py
        cors_policy.py
        rate_limit.py
        soap_basic.py
        auth_weak.py
        mass_assignment_template.py   (template, gated)
        injection_template.py         (template, gated)
    reporting/
      __init__.py
      report.py
      templates/
        report.html
    cli.py
    web/
      __init__.py
      app.py
      auth.py
      db.py
      templates/
        base.html
        index.html
        upload.html
        run.html
        results.html
      static/
        style.css
  .github/
    workflows/ci.yml
  docker/
    Dockerfile
    gunicorn_conf.py

