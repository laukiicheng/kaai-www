### Technical
* [ReactJS](https://react.dev/learn)
* Routing - [React Router](https://reactrouter.com/start/framework/installation)
  * [Routing Docs](https://reactrouter.com/start/framework/routing)
* Typing - Typescript
  * [Using Typescript](https://react.dev/learn/typescript). Typescript is NOT a default in React
* [React Developer Tools](https://react.dev/learn/react-developer-tools) for browser debugging
* Deployment - TODO Github Actions
* Production assets stroage - AWS S3.
  * Build the website and upload to the AWS bucket
  * `arn:aws:s3:::kaai-academy-www-build-prod`
* CDN - Cloudfront. Content delivery network
  * [Deploying react app to S3/cloudfront](https://wolovim.medium.com/deploying-create-react-app-to-s3-or-cloudfront-48dae4ce0af)
* DNS service - Route 53 - Allows user to navigate to (Ka'ai Academy)[www.kaaiaacademy.com]
  * In this case Route 53 is forwarding to Cloudfront.
* State management - TODO React query
* Dependency Injection - TDB
* Database - TBD
* Videos Storage - TODO AWS S3
* Authentication - TBD - Amazong Coginito

### Local Development
* start app `npm run dev`
* http://localhost:5173


## Notes
* I tried using Github Pages, however it only serves static html and assets. So rather than making the build ouput static files, I chose to use AWS S3, cloudfront and Route53 to store and host the website.
  * [Github Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
  * [github-pages](https://create-react-app.dev/docs/deployment/#github-pages)