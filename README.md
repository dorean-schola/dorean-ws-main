# Dorean Schola Web Service Main

Doreán Schola serverless main application.

### Requirements
- [Node.js version 8.10.0](https://nodejs.org/download/release/v8.10.0/)
- [Serverless Framework](https://serverless.com/)

We use Node.js v8 because that's the latest version that the AWS Lambda runtime supports. For a development environment where multiple node versions are used, [NVM](https://github.com/creationix/nvm) is suggested.
Although vs code is not a requirement, it's recommended for a better coding experience, due to it's 'workspace configuration'.

### Environment Variables
- export AWS\_ACCOUNT_ID="***"
- export AWS\_ACCESS\_KEY_ID="***"
- export AWS\_SECRET\_ACCESS_KEY="***"
- export USER\_POOL_ID="***"
