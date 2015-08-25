# Deployment configuration for dev.hird.io

This is the deployment configuration for my remote dev environment.

It is managed through a currently closed-source infrastructure-as-code project
of mine and deployed with:

    curl -XPUT --data-binary @deploy.yml \
      -H 'Content-Type: text/yaml' \
      http://service-name/stacks/dev-box
