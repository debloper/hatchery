# Hatchery
Prototype PWA for Red Hat idea incubation lab

## Prerequisites

This app is primarily developed and tried on Fedora Linux, running Node.js 6.x with npm 
In order to run the app you need to have the following:

* Node.js >= 6.x platform (on top of your favorite OS)
* npm >= 3.x (v5.x recommended)
* DB of your choice (uses SQLite by default)
* ...

## Development setup

1. **Clone the repo:** `$ git clone https://github.com/debloper/hatchery && cd hatchery`
2. **Install dependencies:** `$ sudo npm run setup`
3. **Customize config:** `$ cp config.js.sample config.js`
4. **Install Packages:** `$ npm install`
5. **Build the app:** `$ npm run build`
6. **Run the app:** `$ npm start`
7. **Test the app:** `$ npm test`

## Deployment

Hatchery is built keeping PaaS deployment in mind, so various platform and infrastructure related setup informations are already abstracted away (but can be tinkered with in the configs). 

> Various PaaS deployment information **coming soon**.

## Contributing

1. Convention Guidelines:
2. Communication Channels:
3. Patch acceptance process:
