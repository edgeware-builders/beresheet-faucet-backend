# Edgeware Testnet Faucet - Beresheet - Backend

This project serves as backend for beresheet faucet you can find the frontend [here](https://github.com/edgeware-builders/beresheet-faucet-frontend), which can be used to obtain test EDG for development purposes, like deploying contracts.

Define the following environment variables or simply save them in a `.env` file inside the main folder:
 
``` 
TOKENS_TO_PAY_PER_REQUEST = 10
REQUEST_LIMIT= 3
LIMIT_UNIT = DAY # MIN | HOUR | DAY - Defaults to DAY
FAUCET_ACCOUNT_MNEMONIC = '' # Mnemonic for account with Test EDG - will be used as dispenser
URL_TEST_NET= 'ws://127.0.0.1:9944' # For edgeware local node see: https://github.com/hicommonwealth/edgeware-node/
TOKEN_DECIMALS = 18 
NETWORK_PREFIX = 42
NODE_ENV = 'production'
```

## Pre-requisites
- An account on Edgeware with Test EDG - or local node running (for local edgeware blockcahin)

Currently, the app can be used on https://faucet-beresheet.vercel.app/, but the domain is likely to change and shall be updated here.

## Getting Started

Clone this repo ```git clone https://github.com/edgeware-builders/beresheet-faucet-backend.git```

### Installing

To successfully run the backend:

Install dependencies using ```yarn```

```
yarn
```

Run the app in the development mode

```
yarn start:dev
```
Open [http://localhost:9000](http://localhost:9000) to view it in the browser.

To build the app for production:
```
yarn build
```

Builds the app for production to the `./dist` folder.
It correctly bundles the app in production mode and optimizes the build for the best performance.
The build is minified and the filenames include the hashes.
The app is now ready to be deployed!

## Built With

* [TypeScript](https://www.typescriptlang.org/) - Typed JavaScript at Any Scale.
* [ExpressJS](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
* [NeDB](https://github.com/louischatriot/nedb) - A Lightweight JavaScript Database

## Contributing

Please submit pull requests to us using the format described while making a pull request.

## Authors

* **[Raj Ranjan](https://www.linkedin.com/in/iamrajranjan/)**
* **[Sameer Kumar Kushwaha](https://www.linkedin.com/in/kushwahasameerkumar/)**
* **[Sayan Kar](https://www.linkedin.com/in/sayan-kar-/)**
* **[Nimish Agrawal](https://www.linkedin.com/in/realnimish/)**
* **Furqan Ahmed** - [Contact](https://www.flow.page/FurqanAhmed)


## Main

See also the list of [contributors](https://github.com/edgeware-builders/beresheet-faucet-backend/contributors) who participated in this project.

## Acknowledgments

* [Drew Stone](https://github.com/drewstone/)
    
