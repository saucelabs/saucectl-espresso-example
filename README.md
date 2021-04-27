# saucectl espresso example

Example running saucectl with espresso.

## What You'll Need

The steps below illustrate one of the quickest ways to get set up. If you'd like a more in-depth guide, please check out
our [documentation](https://docs.saucelabs.com/testrunner-toolkit/installation).

### Install `saucectl`

```shell
curl -L https://saucelabs.github.io/saucectl/install | bash
```

⚠ Make sure saucectl version is newer than **v0.36.0**

### Set Your Sauce Labs Credentials

```shell
saucectl configure
```

## Running The Examples

Simply check out this repo and run the appropriate command below :rocket:

### In Sauce Cloud

```shell
saucectl run --test-env sauce
```

![sauce cloud example](assets/sauce_cloud_example.gif)

## The Config

[Follow me](.sauce/config.yml) if you'd like to see how saucectl is configured for this repository.
