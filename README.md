# github-actions-with-aws-sam

This is an example of continuous / deployment integration for an AWS lambda function.

- hello_earth - This is an example of a single AWS lambda in your repo.
- goodbye_mars - This is another example of an AWS lambda in your repo.
- template.yaml - A template that defines the application's AWS resources (in this instance it is just lambdas).
- .github\workflows\dev.yml - This file controls how GitHub actions are handled when a commit is made to the dev branch.
- .github\workflows\prod.yml - This file controls how GitHub actions are handled when a commit is made to the prod branch.
