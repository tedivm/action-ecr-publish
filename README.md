# ECR Publish

This action is used to publish images to the Elastic Container Registry on AWS.

It uses the magic of Github OIDC linked with AWS to grant permission to a repository on Github to publish to an Image Repository on AWS as long as they share the same name. This action then handles the whole build process.

[Check out this blog post for more information.](https://blog.tedivm.com/guides/2021/10/github-actions-push-to-aws-ecr-without-credentials-oidc/)
