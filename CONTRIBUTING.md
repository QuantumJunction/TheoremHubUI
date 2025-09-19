# Contributing

## Handling Dependencies

We use **npm** as our package manager.  
To install it on Linux (Debian/Ubuntu-based), run:

```shell
sudo apt install npm
```

Installing Dependencies

To install the exact same dependency versions as defined in the package-lock.json, use:

```shell
npm ci
```

To install dependencies while allowing updates within the version ranges specified in package.json, use:
```shell
npm install
```