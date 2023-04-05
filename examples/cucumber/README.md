# saucectl espresso & cucumber example

Example running saucectl with espresso & cucumber.

## What You'll Need

The steps below illustrate one of the quickest ways to get set up. If you'd like a more in-depth guide, please check out
our [documentation](https://docs.saucelabs.com/dev/cli/saucectl/#installing-saucectl/).

_If you're using VS Code, you can use [Runme](https://marketplace.visualstudio.com/items?itemName=stateful.runme) to run the following commands directly from VS Code._

### Install `saucectl`

```shell
curl -L https://saucelabs.github.io/saucectl/install | bash
```

### Set Your Sauce Labs Credentials

```shell
saucectl configure
```

## Running The Examples

Simply check out this repo, navigate into `examples/cucumber` and run the command below :rocket:

```bash
saucectl run
```

## The Config

[Follow me](.sauce/config.yml) if you'd like to see how saucectl is configured for this example.

### Used applications for testing

Applications that we use for testing (`./examples/cucumber/apps/*.apk`) were built by using this [repository](https://github.com/cucumber/cucumber-android/tree/master/cukeulator)  