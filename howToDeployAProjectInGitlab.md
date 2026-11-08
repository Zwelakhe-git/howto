## example shows deploy for a react-vite project
```yml
image: node:18

pages:
  stage: deploy
  script:
    - cd frontend
    - npm ci
    - npm run build
    - mkdir -p ../public
    - cp -r dist/* ../public/
  artifacts:
    paths:
      - public
  rules:
  - if: $CI_COMMIT_BRANCH == "main"
```
