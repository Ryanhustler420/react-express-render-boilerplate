# React & Express Boilerplate

Basic react and express app to deploy on render.com as docker image.

### Repository Env

- RENDER_SERVER_HOST_URL: `https://abc-xyz.onrender.com`
- RENDER_APP_SERVICE_ID: `srv-cgnlgo61101c73al966g`
- RENDER_PROFILE_AUTH_API_TOKEN: `rnd_xkQiKV...`
- DOCKER_IMAGE_NAME: `prof/app:latest`
- DOCKER_PASSWORD: `admin123`
- DOCKER_USERNAME: `user69`

### Important

- It wakes up the render server
- It has three stage
  - ci
  - stage
  - prod

### Todo

- Improve the app workflows

<!--

### Fly deplyment via cli

https://fly.io/docs/hands-on/install-flyctl/

docker run -it 3565a89d9e81 bash
curl -L https://fly.io/install.sh | sh

export FLYCTL_INSTALL=\"$flyctl_install\"
export PATH=\"\$FLYCTL_INSTALL/bin:\$PATH\"
export FLY_API_TOKEN=fo1_7mXDasFuDfeHCQTGbBaWw-PEIzx4Q7UiW1M7794XcUo
-->
