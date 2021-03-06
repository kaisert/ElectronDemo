# Digital Bitbox Playground

Welcome to the Digital Bitbox Playground. This application serves as a tutorial that will guide you in developing a wallet based on Node.js and Electron.

## How To Use with Docker

Ensure that Docker is installed.

Build both Docker images:
```
docker build --tag electron_demo-ci -f Dockerfile.travis .
docker build --tag electron_demo_x11-ci -f Dockerfile.x11 .
```

Run the ElectronDemo inside of Docker:
```
./run-ElectronDemo-x11.sh
```

## How To Use without Docker

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/digitalbitbox/ElectronDemo/
# Go into the repository
cd ElectronDemo
# Install dependencies
yarn install
# Run the app
yarn start
```

## Resources for Digital Bitbox

- [digitalbitbox.com/api](https://digitalbitbox.com/api) - API documentation for the Digital Bitbox

## License

To be defined.
