# Open-rts website
This repository contains the source code for the open-rts [websiite](https://www.open-rts.com/).

## Running the website locally

Start by cloning the repository:
```bash
git clone git@github.com:open-real-time-strategy/website.git
```

## Installing dependencies
Start by installing composer packages using the `install_composer_packages` service. This can be done
by running the following command:
```bash
docker compose run install_composer_packages
```

Next, install npm packages using the `install_npm_packages` service. This can be done by running the following command:
```bash
docker compose run install_npm_packages
```

## Starting the server locally
To start the server locally, run the following script:
```bash
docker compose up -d frontend website
```


