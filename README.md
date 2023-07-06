# Serverless Wordpress with genezio

[![deployed with: genezio](https://img.shields.io/badge/deployed_with-genezio-6742c1.svg?labelColor=62C353&style=flat-square)](https://github.com/genez-io/genezio)

A live demo is available [here](https://purple-cute-capybara.app.genez.io).
This project is a minimalist wordpress-like blog deployed and hosted using [genezio](https://github.com/Genez-io/genezio).

The project has the following features:

- admins accounts (register, login, update information)
- editors accounts (register, login, update information)
- tags management (create, get, update, delete)
- enable global settings for using options (create, get, update, delete)
- posts/articles management (create, get)
- minimal UI build to interact with

You can interact with a deployed [demo](https://purple-cute-capybara.app.genez.io/posts) to get the gist of the project.

## Technical details

The project is deployed using [genezio](https://github.com/Genez-io/genezio) for both backend and frontend.

The CI/CD is automated using a Github Action in `.github/workflows/deploy.yaml.`
For more details on how to use this action, check out the official [documentation](https://github.com/Genez-io/genezio-github-action/blob/main/README.md).

Also, we needed a database to store the information about user accounts and posts.
We choose to use MongoDB because it is easy to set up and use.

Head over to [MongoDB website](https://www.mongodb.com/atlas/database) to create a free account and see how to host your MongoDB database.
After you create a Mongo database, copy its URI and paste it in your `.env` file.

## Suggestions

If you have any suggestions or difficulties in using the project, drop us an issue or even a PR.

We are more than happy to improve the project <3

## Resources

To get in-depth information about the technologies we used check out the following docs:

- [genezio official documentation](https://genez.io/docs)
- [genezio github action documentation](https://github.com/Genez-io/genezio-github-action/blob/main/README.md)
- [MongoDB official tutorials](https://www.mongodb.com/atlas/database)
