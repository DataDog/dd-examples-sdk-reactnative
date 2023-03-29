# Contributing

First of all, thanks for contributing!

This document provides some basic guidelines for contributing to this repository.
To propose improvements, feel free to submit a PR or open an Issue.

## Setup your developer Environment

To get started with the project, follow the installation instructions in each app.

### Project structure overview

The sample application is for shopping furniture and retrieves its resources from [shopist](https://shopist.io) - except for the hybrid applications.

It contains the following pages:

1. Login Page

   - You can use any username but for the password use '1234' for all projects except `codepush` that has a password of '12345'

2. Categories page

   - On the top right, there's a button used to crash the app and test the wizard
   - Click on a category to go the corresponding products

3. Products page

   - Choose the products you want to add to your list
   - You can add each product only once
   - You can add products from different categories

4. Cart's page

   - You can find here the list of products you've created

You can use any username for the login page but for the password use '1234' for all projects except `codepush` that has a password of '12345'

If you are using Visual Studio Code, please make sure to set workspace version of TypeScript instead of the native Typescript bundled with Visual Studio, check [this](https://stackoverflow.com/a/39676463/3222695) to see how to do it.

### Running the apps

You can then run the individual apps using the following commands

```sh
# Run the Android sample
yarn android

# Run the ios sample
yarn ios
```

## Submitting Issues

Many great ideas for new features come from the community, and we'd be happy to
consider yours!

To share your request, you can open an [issue](https://github.com/DataDog/dd-sdk-reactnative-examples/issues/new)
with the details about what you'd like to see. At a minimum, please provide:

- The goal of the new feature;
- A description of how it might be used or behave;
- Links to any important resources (e.g. Github repos, websites, screenshots,
  specifications, diagrams).

## Found a bug?

For any urgent matters (such as outages) or issues concerning the Datadog service
or UI, contact our support team via <https://docs.datadoghq.com/help/> for direct,
faster assistance.

You may submit bug reports concerning the Datadog SDK for Android by
[opening a Github issue](https://github.com/DataDog/dd-sdk-reactnative-examples/issues/new).
At a minimum, please provide:

- A description of the problem;
- Steps to reproduce;
- Expected behavior;
- Actual behavior;
- Errors (with stack traces) or warnings received;
- Any details you can share about your configuration including:
  - Android API level;
  - Datadog SDK version;
  - Versions of any other relevant dependencies (OkHttp, …);
  - Your proguard configuration;
  - The list of Gradle plugins applied to your project.

If at all possible, also provide:

- Logs (from the tracer/application/agent) or other diagnostics;
- Screenshots, links, or other visual aids that are publicly accessible;
- Code sample or test that reproduces the problem;
- An explanation of what causes the bug and/or how it can be fixed.

Reports that include rich detail are better, and ones with code that reproduce
the bug are best.

## Have a patch?

We welcome code contributions to the library, which you can
[submit as a pull request](https://github.com/DataDog/dd-sdk-reactnative-examples/pull/new/master).
Before you submit a PR, make sure that you first create an Issue to explain the
bug or the feature your patch covers, and make sure another Issue or PR doesn't
already exist.

To create a pull request:

1. **Fork the repository** from <https://github.com/DataDog/dd-sdk-reactnative-examples> ;
2. **Make any changes** for your patch;
3. **Write tests** that demonstrate how the feature works or how the bug is fixed;
4. **Update any documentation** especially for
   new features;
5. **Submit the pull request** from your fork back to this
   [repository](https://github.com/DataDog/dd-sdk-reactnative-examples) .

The pull request will be run through our CI pipeline, and a project member will
review the changes with you. At a minimum, to be accepted and merged, pull
requests must:

- Have a stated goal and detailed description of the changes made;
- Include thorough test coverage and documentation, where applicable;
- Receive at least one approval from a project member with push permissions.

Make sure that your code is clean and readable, that your commits are small and
atomic, with a proper commit message.
