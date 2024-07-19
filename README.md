# Shared Github Actions

## coding-standard.yml
This workflow is for checking the coding standards of a Magento 2 module. It runs when called by another workflow `workflow_call`.

## integration.yml
This workflow is for running integration tests on a Magento 2 module with various Magento and PHP versions.
It also runs when called by another workflow and takes two inputs `module_name and composer_name`.

## mess-detector.yml
This workflow ensures that every time code is pushed or a pull request is made, PHP Mess Detector will analyze the code
for any potential issues, helping maintain high code quality throughout the development process.

## phpstan.yml
The `phpstan.yml` file sets up a GitHub Actions workflow for running PHPStan on a Magento 2 project.
PHPStan is a static analysis tool that detects potential bugs and code quality issues.