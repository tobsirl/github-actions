# GitHub Actions

## What is GitHub Actions?

GitHub Actions is a feature that enables you to automate your workflow. It is a tool that allows you to build, test, and deploy your code right from GitHub. It is integrated with GitHub and you can find it in the Actions tab of your repository.

## What is CI/CD?

CI/CD stands for Continuous Integration and Continuous Delivery/Deployment. It is a set of principles and practices that help teams deliver features faster and more reliably. CI/CD is a solution to the problems integrating new code can cause for development and operations teams (AKA "integration hell").

### Continuous Integration

Continuous Integration is the practice of merging all developers' working copies to a shared mainline several times a day. It is a process of automating the build and testing of code every time a team member commits changes to version control.

### Continuous Delivery

Continuous Delivery is the practice of automating the release of software so that it can be released at any time. It is a software development practice where code changes are automatically prepared for a release to production.

## GitHub Actions Fundamentals

### Workflows

A workflow is a configurable automated process made up of one or more jobs. You must create a YAML file to define your workflow configuration. The file must be named `main.yml` and placed in the `.github/workflows` directory of your repository.

### Jobs

A job is a set of steps that execute on the same runner. By default, a workflow with multiple jobs will run those jobs in parallel. You can also configure a workflow to run jobs sequentially.

### Steps

A step is an individual task that can run commands in a job. A step can be either an action or a shell command. Each step in a job executes on the same runner, allowing the actions in that job to share data with each other.

### Events (Workflow Triggers)

Events are specific activities that trigger a workflow. For example, activity such as creating a pull request or pushing to a repository can trigger a workflow. You can configure a workflow to run when a specific event occurs in your repository.

### Actions

Actions are standalone commands that are combined into steps to create a job. Actions are the smallest portable building block of a workflow. You can create your own actions, or use actions created by the GitHub community.
