# Hosting a Full-Stack Application

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent

- AWS CLI

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

- circleCi

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres.
1. In AWS, provision a s3 bucket for hosting the uploaded files.
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## hosted site

this site is hosted via s3 on http://hassanlity2.s3-website-us-east-1.amazonaws.com/home

## architecture diagram

    (./screenshots/digram.PNG)

## pipe line process

    (./screenshots/circlecibuild.PNG)
