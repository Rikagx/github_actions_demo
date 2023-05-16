# github_actions_demo

A github action allows us to create workflows that are triggered by a github action such as a push or pull to a branch
Workflows can include tests, markdown renders, shell scripts, or deployments. They can be as simple or as complicated as you need. Open-source community provides a ton of examples of actions. 

Integration
- practice of automating the integration of code changes including running tests or validations

Deployment
- practice of automating the deployment of your code to an environment like Connect

## Steps to deploy a Shiny app to Posit Connect

Create a Connect API key

Add your API Key and Server URL to secrets in your Github repository

Use renv to maintain consistency between the development and build environments

Create your YAML file in .github/workflows

- Use rsconnect package to register your Connect server (directly or in your yaml)
- Create a manifest.json (directly 


