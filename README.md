# hackerone
i used it
deploy:
  stage: deploy
  script:
    - echo "Example"
  environment:
    name: production
    url: https://google.com
    kubernetes:
      namespace: <img src=x onerror=alert(1)>
  only:
  - master
