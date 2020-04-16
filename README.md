# Node.js + Docker + Github Actions + Google Cloud Container Registry Template

A very simple template to get you started with Node.js and Docker and some simple CI/CD with Github Actions and Google Cloud!


## Prerequisites
Google Cloud account && project

## Getting Started

1. Make a new repository with this template
2. Go to Settings->Secrets and add GCLOUD_CONTAINER_URL, the complete URL, for example: eu.gcr.io/project-id-here/container-name-here. Then add the base64 encoded json key from your Compute Engine default service account as GCLOUD_SERVICE_KEY
3. Change something in the code, commit and push to master
4. You should now see that the Github Action builds your container and pushes it to your private Google Cloud Container registry!
5. Pull the image from your server and deploy it:)

## Contributing

Contributing is more than welcome!

1. Fork the repository
2. Create a new branch
3. Implement/fix whatever you want
4. Make sure to use Eslint!
5. Open a pull request:)

## Planned additions:
Deployment
Tests

## Authors

* **Jonas Scholz** - [Code42Cate](https://github.com/Code42Cate)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
