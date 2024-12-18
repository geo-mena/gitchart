# GitHub Contribution Chart Generator

Generates an image of all your **GitHub** contributions since you have signed up, so you can use it in social media.

The API for this project lives in the `src/pages/api` directory since GitHub doesn't provide a way to access user statistics through it's official API.

## Requirements

- A valid github account.
- Open activity in setting (`Settings` > `Public profile` > `Contributions & Activity`).
  - [ ] Make profile private and hide activity

## Install

Install the packages using [NPM](https://nodejs.org/en/):

```
$ npm install
```

## How to run

Running locally:

```
$ npm run dev
```

## Deployment

This project is deployed on [Vercel](https://vercel.com/).

## Example

<div align="center">
  <img src="screenshot.png" width="676">
</div>

## Contributing

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Changelog

Every release, along with the migration instructions, is documented on the GitHub [Releases](https://github.com/sallar/github-contributions-chart/releases) page.

## License

[MIT license](https://opensource.org/licenses/MIT)
