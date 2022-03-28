This template is designed to work with sites that can be distributed as static sites only (hosted on AWS S3)

This repository makes the assumption your frontend is Node.js based, please see the [CI's build steps][ci-build] and make changes according to your needs.

The CI runs the following steps:
- Unit test
- build static site
- sync with s3 bucket for your project domain


[ci-build]: ../../.github/workflows/ci.yml#L9-L45

### Note

I had an issue with the SSO auth and I was just able to  finish a local enviroment for the HOP project.
The code for a local enviroment can be found here: https://github.com/vicjicaman/commit-hop-support-restaurants
