# Tricks
Here is a small collection of tricks!

# [nvm](https://github.com/nvm-sh/nvm): easily install and switch between multiple node versions

Node version manager allows you to install `node` per-user, and to easily switch and use different versions in different shell sessions.

Install and use specific version of Node:
```shell
nvm install 15.4.0
nvm use 15.4.0
```

For the latest version of node:
```shell
nvm install node
nvm use node
```


# [npx](https://www.npmjs.com/package/npx): run an npm package binary in an easy way
Instead of installing a package globally, you can use `npx`:
```shell
npx create-react-app my-app --template typescript
```

# [localtunnel](https://github.com/localtunnel/localtunnel): expose localhost to the world
```shell
npx localtunnel --port 3000
```

# [live-server](https://github.com/tapio/live-server): run a web development server with reload capability

```shell
npx live-server
```

# [concurrently](https://www.npmjs.com/package/concurrently): run multiple commands concurrently

```shell
npx concurrently "<command1>" "<command2>"
```

```shell
npx concurrently "npx live-server" "npx localtunnel --port 8080"
```

# [nodemon](https://www.npmjs.com/package/nodemon): run command on file changes
```shell
npx nodemon --exec "python -v" ./app.py
```

```shell
npx nodemon --ext js,ts,tsx --watch src/ --exec "npm run"
```
