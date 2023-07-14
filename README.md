# my-sceptre-project

### Overview
- Sceptre is a tool to drive CloudFormation. Sceptre manages the creation, update and deletion of stacks while providing meta commands which allow users to retrieve information about their stacks. Sceptre is unopinionated, enterprise ready and designed to run as part of CI/CD pipelines. Sceptre is accessible as a CLI tool or as a Python module.  
- Sceptre is used by defining CloudFormation, Jinja2 or Python templates, with corresponding YAML configuration files. The configuration files include which account and region to use as well as the parameters to supply the templates.  
- For a tutorial on using Sceptre, see [Get Started](https://docs.sceptre-project.org/4.2.1/docs/get_started.html), or find out more information about Sceptre below.

### Install Sceptre
```shell
docker run -it --entrypoint='' -v $(pwd):/project -v ~/.aws/:/root/.aws/:ro cloudreach/sceptre:latest sh
```

### Usage
```shell
sceptre new project <project-code>
sceptre list stacks <path>
sceptre launch <path>
```