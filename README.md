# Dev-Docs

## Init Project

### Install Node.js LTS version

```shell
#　check node version
$ node -v
v16.14.0

$ nvm install --lts
$ nvm alias default 16

```

### Install Antora

```shell

$ node -e "fs.writeFileSync('package.json', '{}')"
$ npm i -D -E @antora/cli @antora/site-generator
$ npx antora -v

@antora/cli: 3.0.1
@antora/site-generator: 3.0.1

```

## Build Project

```shell
$ npx antora --fetch antora-playbook.yml --stacktrace

```