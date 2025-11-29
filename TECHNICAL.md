### Technical
* [ReactJS](https://react.dev/learn)
* Routing - [React Router](https://reactrouter.com/start/framework/installation)
  * [Routing Docs](https://reactrouter.com/start/framework/routing)
* Typing - Typescript
  * [Using Typescript](https://react.dev/learn/typescript). Typescript is NOT a default in React
* [React Developer Tools](https://react.dev/learn/react-developer-tools) for browser debugging
* Deployment - AWS Amplify
  * [Deploy React to AWS Amplify](https://docs.aws.amazon.com/hands-on/latest/build-react-app-amplify-graphql/module-one.html)
* DNS service - Route 53 - Allows user to navigate to (Ka'ai Academy)[www.kaaiaacademy.com]
  * [Configure AWS Apmlify for custom Route53 domain](https://docs.aws.amazon.com/amplify/latest/userguide/to-add-a-custom-domain-managed-by-amazon-route-53.html)
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