# simplest-stack

## Purpose

I want to bang together the simplest thing that works. It may not do much, but at least it'll fog a mirror.

The components will be:

- Some kind of Python backend JSON "API"
- A simple frontend site
  - .. possibly rudimentary HTML and JS for now
- DevOps infrastructure for frontend and backend
  - .. probably built using [Terraform](https://www.hashicorp.com/products/terraform), but possibly including [CDK for Terraform](https://www.hashicorp.com/blog/cdk-for-terraform-enabling-python-and-typescript-support)
  - .. also including very light use of [Terratest](https://terratest.gruntwork.io/) from the git-go
- CI/CD for frontend and backend
  - Package both into separate Docker containers
  - Run them on [ECS](https://aws.amazon.com/ecs/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc&ecs-blogs.sort-by=item.additionalFields.createdDate&ecs-blogs.sort-order=desc) or [Fargate](https://aws.amazon.com/fargate/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc&fargate-blogs.sort-by=item.additionalFields.createdDate&fargate-blogs.sort-order=desc) at first?


## Organization

- Each project will have its own subdirectory root at this level. They'll be listed under each section below.

## Projects

### Backend

- Starting with [How to build a JSON API with Python](https://www.freecodecamp.org/news/build-a-simple-json-api-in-python/)
- Project root: `flask-jsonapi-demo`.
