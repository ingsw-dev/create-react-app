# react-scripts

This package includes custom configuration of the scripts used by [Create React App](https://github.com/facebookincubator/create-react-app).<br>
Please refer to its documentation:

* [Getting Started](https://github.com/facebookincubator/create-react-app/blob/master/README.md#getting-started) – How to create a new app.
* [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md) – How to develop apps bootstrapped with Create React App.

## Usage

You can use this scripts with the normal [create-react-app](https://www.npmjs.com/package/create-react-app), just adding the parameter `scripts-version` to point to this project.

```bash
$ create-react-app <app-name> --scripts-version @ingenious-agency/react-scripts
```

## Development Guidelines

### Versioning

To keep the same versions of the original `create-react-app`, add a dash following with an incremental number at the end of the version number. Ex: `1.0.17-2` represent the version `1.0.17` of `create-react-app` and the version `2`of this fork.

### Branches

This repo keeps the current development in the `develop` branch and the stable code in the `stable` branch. Keeping the `master` branch in sync with `create-react-app`.
