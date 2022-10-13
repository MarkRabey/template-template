# Template Template

A template for creating GitHub template repositories.

## How to use this template

> **DO NOT FORK!** This is meant to be used from the **[Use this template](https://github.com/MarkRabey/template-template/generate)** feature.

1. Click on [Use this template](https://github.com/MarkRabey/template-template/generate)
2. Give your project a name (e.g. `my-project`)
3. Wait for GitHub Actions to finish before cloning your new repo
   - This will update template files with your project information
4. Clone your new project, and happy coding!

## Included in this template

This template creates the initial setup for a React Component Library that is configured to use the following:

- GitHub Issue Templates
- GitHub Actions
- A sample README for your project (see below)

## <!--  DELETE THE LINES ABOVE THIS AND WRITE YOUR PROJECT README BELOW -->

# project_name

[![npm](https://img.shields.io/npm/v/project_name)](https://www.npmjs.com/project_name)
[![npm](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/author_name/project_name/blob/main/LICENSE)

![coverage-functions](./coverage/badge-functions.svg)
![coverage-lines](./coverage/badge-lines.svg)
![coverage-statements](./coverage/badge-statements.svg)

> project_description

## Installation

With `yarn`:

```
yarn add project_name
```

With `npm`:

```
npm install project_name
```

## Usage

```jsx
import {MyComponent} from 'project_name';

const App = () => {
  return <MyComponent />;
};

export default App;
```
