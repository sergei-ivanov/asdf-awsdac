# Contributing

Testing Locally:

```shell
asdf plugin test awsdac https://github.com/sergei-ivanov/asdf-awsdac.git "awsdac --help"
```

If you have a local checkout, you can test your changes (all changes must be committed):

```shell
asdf plugin test awsdac file://$(pwd) "awsdac --help"
```

Tests are automatically run in GitHub Actions on push and PR.
