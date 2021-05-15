# Creating a Rails API from Scratch

## Learning Goals

- Use `create-react-app` to generate a new React application within a Rails
  project
- Use the `foreman` gem to run React and Rails together
- Proxy requests from React to Rails in development

## Introduction

In the last lesson, we created a Rails API from scratch. Now it's time to see
how we can add a React frontend application as well.

There are a number of ways to use React and Rails together, such as using the
[`webpacker` gem](https://github.com/rails/webpacker) to manage JavaScript as
part of your Rails application. However, we like the simplicity and the tooling
that you get out of using [`create-react-app`](https://create-react-app.dev/) to
generate a new React application within Rails. If you've used `create-react-app`
before, you should feel right at home! We can also add a few additional tools to
the process to make running React and Rails together a bit easier.

## Generating a React Application

To get started, let's spin up our React application using `create-react-app`:

```sh
npx create-react-app client --use-npm
```

This will create a new React application in a `client` folder, and will use npm
instead of yarn to manage our dependencies.

## Conclusion

When creating a new Rails API project from scratch, you can use the `--api` flag
to have Rails optimize your project for building a web API.

We also saw how to use the `resource` generator, which can help quickly set
up the code we need to create RESTful routes and CRUD functionality for one
single resource.

## Resources

