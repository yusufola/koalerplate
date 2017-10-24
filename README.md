# Project Title

A simple Koa 2 boilerplate for API's using ES6.

## What's in the package?

* Routing with koa-router.
* Parsing request with koa-bodyparser.
* CORS middleware with @koa/cors.
* koa-respond for helper functions on the context.
* koa-helmet for important security headers.
* nodemon for development to auto-restart when your files change.
* dotenv for environment variable management.

## Getting Started

```
git clone https://github.com/dbalas/koalerplate.git
cd koalerplate
mv .env.sample .env
npm run dev // or yarn dev
```

By default the API server starts on port 3000, http://localhost:3000.

### Prerequisites

* node >= v7.6.0
* *npm run dev* use nodemon

```
npm install -g nodemon
```

## Contributing

Feel free to submit pull request or suggestions [here](https://github.com/dbalas/koalerplate/issues/new)

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Daniel Balastegui** - *Initial work* - [dbalas](https://github.com/dbalas)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
