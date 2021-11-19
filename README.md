# browserify-redstone-flash-storage

This repo contains a very simple example is using redstone-flash-storage module along with ethers.js in a pure HTML-JS application.

## How to use

### 1. Install dependencies
```sh
npm install
```

### 2. Compile redstone-flash-storage using browserify
```sh
npm run browserify-compile
```
You should have `redstoneFlashStorage.js` file in the root repo folder after running this command.

### 3. Open the index.html file in browser
You can simply open the html file in browser or use a tool like [http-server](https://www.npmjs.com/package/http-server). After opening the file in your browser open the dev console and explore logs. They should look like this:

```
{ethers: {…}, redstoneFlashStorage: {…}, tokenContractInstance: Contract}

{wrappedContract: Contract}

Got balance: 99900000000000000

Got solvency:  172.7%
```

### 4. Explore the code
After running the code you can analyze the index.html file, index.js file and the `browserify-compile` script in the package.json to understand how it works.
