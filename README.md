# pwpr preprod
**For deploying to Pre Production**

To use the 'build_image' script you must have an aws profile named pwpr-preprod saved in ~/.aws/credentials file with the correct credentials for the pwpr preprod account.

Specify the tag to be deployed in the Dockerrun.aws.json file then deploy using eb cli.
