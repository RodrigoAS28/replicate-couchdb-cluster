# Building

## Prerequisites

1. You must have the master branch checked out
2. You must have npm access
3. You must have docker hub access

## What does the build do?

1. Sets package version
2. Commits to master
3. Creates and pushes a new tag
4. Publishes to npm
5. Builds and pushes new docker images

## Building

    $ ./build.sh <version>

Then visit the releases tab in GitHub and add the relevant PRs to the newly created tag
