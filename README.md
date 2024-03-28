<div align="center">
  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/73050798/300852436-6e7b551e-df7c-4a1c-b969-e97931252c3d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240327%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240327T132603Z&X-Amz-Expires=300&X-Amz-Signature=567e128db3dca323ad61b9c4bc6a26b8ca08d1b02e98393f11152931c0e24965&X-Amz-SignedHeaders=host&actor_id=73050798&key_id=0&repo_id=643162841" width="100" align="center">

  # SASS Pire

  *Just more mixins and functions with SCSS for more productive projects.*
</div>

## Getting Started
NPM
```
npm i -D sass-pire
```

Yarn

```
yarn add sass-pire --dev
```

## Usage
After installing `sass-pire` using your favorite package manager, you can import it into any `SCSS` file you want and use it easily.

Example:
If you are at `index.scss` file, you can import the `sass-pire.scss` using `@import` statement:
```
@import "/path/to/root/directory/node_modules/sass-pire/src/sass-pire.scss";
```

Or by using `@use` statement:
```
@use "/path/to/root/directory/node_modules/sass-pire/src/sass-pire.scss" as *;
```

## Features

* `Mixins` with its vendor prefixes.
* Useful `Functions` to use easily.
* `Media queries` with a sufficient amount of screens to match all of it.

## Contribute
You can contribute to `sass-pire` by making a fork of this repository and cloning it in your local device.

It is very important to make a `new branch` to your `feature` or `solve a bug` or `solve an issue`.

## Do you want more features?
Please, set a new issue and labeled it as `Feature` and insert what you want.


## License
[MIT](https://github.com/krypton225/sass-pire/blob/master/LICENSE.md)
