# Next.js Project with CI/CD deploying to Azure App Service (POC)

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Using Dockerfile from NextJS to run on [Azure App Service (Linux)](https://azure.microsoft.com/en-in/products/app-service/).

## How to deploy

- Edit .github/workflows/main.yml and set the web app name to your App Service name
  -   AZURE_WEBAPP_NAME: '** Your app name here **'
- Download your App service publish profile and add it to your repository secrets under the name AZURE_WEBAPP_PUBLISH_PROFILE 
