# Devs on a boat

A whitepaper style approach to the problem of how a developer might effectively work remotely indefinitely from a sailboat. It is intended to be an open discussion and knowledge pool, with that in mind contributions are eagerly welcomed.

Can be viewed online at [floatingdevs.com](https://floatingdevs.com)

This is currently very early days, entire sections are currently missing and will be filled in as I can get to them.

# Contributing

To contribute to devs-on-a-boat, fork this repository and clone it to your local machine. When you're ready, submit a pull request back to the main repo.

You can use a variety of markdown editors to work on this content. Some of the more popular extensions for Visual Studio Code are [listed here](https://code.visualstudio.com/docs/languages/markdown). However, even without an extension, you can press Ctrl-Shift-V to preview changes to a markdown file within VS Code.

This website uses [Jekyll](https://jekyllrb.com/) to build the website, along with the [just-the-docs theme](https://pmarsceill.github.io/just-the-docs/) which incidently contains the documentation on how to use this theme!

## Local development
In order to run a local development server without polluting your local machine with dependencies please follow instructions in the snippet below. This will expose a local version of the website at http://localhost:4000 which you can visit with your favourite browser.

The container will constantly watch for source code updates so there's no need to do anything once you'd stood up the development server.

Since the container downloads all project specific dependencies at runtime it can take 10-15 seconds before the service will become available.

```bash
# From the root of this repository
docker-compose up
# or if you'd like to run this in the background to keep your terminal
docker-compose up -d

# In order to destroy when you're done
docker-compose down
```
