# ECR Publish

This action is used by Explosion to publish images to our Elastic Container Registry on AWS.

It uses the magic of Github OIDC linked with AWS to grant permission to a repository on Github to publish to an Image Repository on AWS as long as they share the same name. This action then handles the whole build process.
