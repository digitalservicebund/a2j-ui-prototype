# A2J UI component library prototyping

Feel free to add more examples.

## Prerequisites

### Node.js and Homebrew

We aim to use the current active [LTS version of Node.js](https://nodejs.dev/en/about/releases/), which is V22 at the time of writing. There is a `.tool-versions` file to simplify setup using [nodenv](https://github.com/nodenv/nodenv) (install Node version by running `nodenv install`) or [asdf](https://github.com/asdf-vm/asdf-nodejs) (check and install used Node version by running `asdf current`) and a `.nvmrc` file to simplify setup using [nvm](https://github.com/nvm-sh/nvm) (check and install Node version by running `nvm use`).

Additionally we use [Git Hooks](#git-hooks) that can be installed with [Homebrew](https://brew.sh/), please check if brew is available on your machine with `brew -v` command.

For the provided Git hooks you will need to install [lefthook](https://github.com/evilmartians/lefthook)
(git hook manager) `brew install lefthook`. Afterwards execute `lefthook install` to initialize the hooks or run `lefthook run pre-commit` before commiting new changes. See `lefthook.yml` for more details in regards to the currently configured git hooks.

## Getting started

Project was set up with `npm create vite@latest` and the `react-ts` template.

```sh
# install dependencies
npm i
```

## Usage

Local development URL should be [http://localhost:5173/](http://localhost:5173/), have a look at the terminal output.

```sh
# start local development
npm run dev
```

## Contributing

[Deutsche sprache weiter unten](#mitwirken)

Everyone is welcome to contribute! You can contribute by giving feedback, adding issues, answering questions, providing documentation or opening pull requests. Please always follow the guidelines and our [Code of Conduct](CODE_OF_CONDUCT.md).

To contribute code, simply open a pull request with your changes and it will be reviewed by someone from the team. By submitting a pull request you declare that you have the right to license your contribution to the DigitalService and the community under the license picked by the project.

## Mitwirken

Jede:r ist herzlich eingeladen, die Entwicklung der _Project_ mitzugestalten. Du kannst einen Beitrag leisten, indem du Feedback gibst, Probleme beschreibst, Fragen beantwortest, die Dokumentation erweiterst, oder Pull-Requests eröffnest. Bitte befolge immer die Richtlinien und unseren [Verhaltenskodex](CODE_OF_CONDUCT.md).

Um Code beizutragen erstelle einfach einen Pull Requests mit deinen Änderungen, dieser wird dann von einer Person aus dem Team überprüft. Durch das Eröffnen eines Pull-Requests erklärst du ausdrücklich, dass du das Recht hast deine Beitrag an den DigitalService und die Community unter der vom Projekt gewählten Lizenz zu lizenzieren.
