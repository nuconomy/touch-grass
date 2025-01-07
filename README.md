# Touch Grass Meme Token

This is a simple memecoin to experiment with deploying a token to Lens via Third Web.

## Third Web Notes

Interact with this contract from your app
Install the latest version of the SDK:

```
npm i thirdweb
```

Initialize the SDK and contract on your project:

```
import {
  createThirdwebClient,
  getContract,
} from "thirdweb";
import { defineChain } from "thirdweb/chains";

// create the client with your clientId, or secretKey if in a server environment
const client = createThirdwebClient({
  clientId: "YOUR_CLIENT_ID",
});

// connect to your contract
const contract = getContract({
  client,
  chain: defineChain(37111),
  address: "0xE5D45Cd408fC63e690De1d02ACD50fC842C55282",
});
```
