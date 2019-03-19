# xl-jetpack

Initial file directory for getting started with xl-jetpack

# STEP 1: Pre-requisites
- Install Docker / Docker Compose
- Install XL CLI (https://docs.xebialabs.com/xl-platform/how-to/install-the-xl-cli.html)
- Optional: Install AWS CLI

# STEP 2: xebialabs-compose:
- Docker compose file for deploying xl-release and xl-deploy in local containers
- Also includes configuration file for configuring xl-deploy with xl-release
  - xl apply -f configure-xl-devops-platform.yaml

# STEP 3: OPTIONAL - jenkins-compose
- Docker compose file for deploying jenkins in a local docker container
- Also includes configuration file for configuring jenkins with xl-release
  - xl apply -f configure-xl-devops-platform.yaml

# STEP 4: Create new directory for each XL Blueprint
- Example for Monolith App
  - Run in  /dev/xl-jetpack/monolith/
