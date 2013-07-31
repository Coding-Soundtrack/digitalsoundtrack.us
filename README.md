# DigitalSoundtrack.us

Digital Soundtrack is a collaborative online jukebox.

## Getting Started

Before you begin you will need to have nodejs, redis, and mongodb installed.
Homebrew is recommended for OS X users.

    brew install nodejs mongodb redis
    redis-server &
    mongod &

Once you have them installed, go ahead and clone the repository.

    git clone git@github.com:Coding-Soundtrack/digitalsoundtrack.us.git
    cd digitalsoundtrack.us

You will need to fetch the dependencies and then you can start up the server.

    npm install
    node soundtrack.js

## Contributing

This code originated with [soundtrack.io](https://github.com/martindale/soundtrack.io) but has moved here in hopes to broaden the community's ability to decide upon changes to the site.
