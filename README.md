# HttpConnect Website

## Website URL
[https://http-connect.github.io/](https://http-connect.github.io/)

## Development

### Requirements

In order to setup the project locally, you will have to install `node`, `yarn` and `ruby` as this project was built upon these.

| Requirement | Version minimum | Installation Instructions                                                 |
|-------------|-----------------|---------------------------------------------------------------------------|
| Node.js     | 10.0            | [nodejs.org](https://nodejs.org/en/download/package-manager/)             |
| Yarn        | 1.21.0          | [yarnpkg.org](https://classic.yarnpkg.com/en/docs/install)                |
| Ruby        | 2.5.0           | [ruby-lang.org](https://www.ruby-lang.org/en/documentation/installation/) |

### Installation

After cloning the repository, make sure you install all the necessary ruby and node dependencies.
You can achieve this by opening a Terminal tab, navigating to the recently cloned repository directory and running:

```bash
bundle
yarn install
```

All the commands mentioned in this part of README should be ran from the project root directory.

### Creating the build

In order to create the production build of the project, run:

```bash
yarn run prod
```

### Serving the website locally

Open two separate Terminal tabs and run the following.

First Terminal Tab:
```bash
yarn run watch
```

Second Terminal Tab:
```bash
bundle exec jekyll serve
```

Now navigate to the http://127.0.0.1:4000 and you should be able to see the working development environment site running.
