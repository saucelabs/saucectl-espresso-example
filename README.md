# saucectl espresso example

Example running saucectl with espresso.

## What You'll Need

The steps below illustrate one of the quickest ways to get set up. If you'd like a more in-depth guide, please check out
our [documentation](https://docs.saucelabs.com/testrunner-toolkit/installation).

_If you're using VS Code, you can use [Runme](https://marketplace.visualstudio.com/items?itemName=stateful.runme) to run the following commands directly from VS Code._

### Install `saucectl`

```shell
curl -L https://saucelabs.github.io/saucectl/install | bash
```

⚠ Make sure saucectl version is newer than **v0.82.0**

### Set Your Sauce Labs Credentials

```shell
saucectl configure
```

## Running The Examples

Simply check out this repo and run the appropriate command below :rocket:

```shell
saucectl run
```

![sauce cloud example](assets/sauce_cloud_example.gif)

### Running the Full Configured Examples

```shell
saucectl run --config .sauce/full-config.yml
```

## Support
Espresso only works on sauce cloud for both Android Emulators and Real Devices. 

[Docker mode](https://docs.saucelabs.com/testrunner-toolkit/configuration/common-syntax/index.html#mode) is not supported.


## The Config

[Follow me](.sauce/config.yml) if you'd like to see how saucectl is configured for this repository. This config file provides the basic suite to run test on Android Emulator. For full config example, please [check here](.sauce/full-config.yml).

Our IDE Integrations (e.g. [Visual Studio Code](https://docs.saucelabs.com/testrunner-toolkit/ide-integrations/vscode)) can help you out by validating the YAML files and provide handy suggestions, so make sure to check them out!
