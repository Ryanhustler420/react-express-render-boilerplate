# React & Express Boilerplate

Basic react and express app to deploy on render.com as docker image.

### Requirement

- [Render](https://render.com) profile
- [Docker](https://hub.docker.com) profile

### Repository Env

- RENDER_SERVER_HOST_URL: `https://abc-xyz.onrender.com`
- RENDER_APP_SERVICE_ID: `srv-cgnlgo61101c73al966g`
- RENDER_PROFILE_AUTH_API_TOKEN: `rnd_xkQiKV...`
- DOCKER_IMAGE_NAME: `prof/app:latest`
- DOCKER_PASSWORD: `admin123`
- DOCKER_USERNAME: `user69`
- SLACK_WEBHOOK_URL: `https://something`

### Important

- It wakes up the render server
- It has three stage
  - ci [skip ci]
  - stage
  - prod

### Todo

- Improve the app workflows
