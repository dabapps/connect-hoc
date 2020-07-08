# @dabapps/connect-hoc

**Types for react-redux connect that work inside HOCs**

## Install

```shell
npm i @dabapps/connect-hoc -P
```

(`-P` is shorthand for `--save-prod` and will add it to your `package.json` dependencies)

## Usage

```tsx
import { ConnectHOC } from '@dabapps/connect-hoc';
import { connect } from 'react-redux';

// ...

(connect as ConnectHOC)<StateProps, DispatchProps, Etc>(
  mapStateToProps,
  mapDispatchToProps
)(MyComponent);
```

## Contributing

1. Clone the repo
2. Ensure you are using the correct version of node with [nvm](https://github.com/nvm-sh/nvm)
3. Install dependencies with `npm ci`
4. Make your changes
5. Run tests with `npm test`
6. Open pull request

## Code of conduct

For guidelines regarding the code of conduct when contributing to this repository please review [https://www.dabapps.com/open-source/code-of-conduct/](https://www.dabapps.com/open-source/code-of-conduct/)
