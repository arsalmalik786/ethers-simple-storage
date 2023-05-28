# SIMPLE STORAGE SMART CONTRACT

HI EveryOne,
There is my first github repository practice on SimpleStorage smart contract. wow I did it.

# GET STARTED

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [Nodejs](https://nodejs.org/en/)
  - You'll know you've installed nodejs right if you can run:
    - `node --version` and get an ouput like: `vx.x.x`
- [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/) instead of `npm`
  - You'll know you've installed yarn right if you can run:
    - `yarn --version` and get an output like: `x.x.x`
    - You might need to install it with npm
- [ganache-cli](https://www.npmjs.com/package/ganache-cli)
  - You'll know you did it right if you can run: 
    -   `ganache-cli --version` and get an output like: `x.x.x` 
    - You might need to install it with npm 
  - You can alternatively use  [ganache](https://trufflesuite.com/ganache/) or [hardhat](https://hardhat.org/)


## Usage

1. Run your ganache-cli local chain, by hitting `quickstart` on your ganache application

> Save the workspace. This way, next time you open ganache you can start the workspace you've created, otherwise you'll have to redo all the steps below.

2. Copy the `RPC SERVER` sting in your ganache CLI, and place it into your `.env` file similar to what's in `.env.example`.


`.env` Example:

```
RPC_URL=http://0.0.0.0:8545
```

3. Hit the key on one of the accounts, and copy the key you see and place it into your `.env` file, similar to what you see in `.env.example`.

`.env` Example:

PRIVATE_KEY=0x11ee3108a03081fe260ecdc106554d09d9d1209bcafd46942b10e02943effc4a

4. Compile your code

Run

```yarn compile```

You'll see files `SimpleStorage_sol_SimpleStorage.abi` and `SimpleStorage_sol_SimpleStorage.bin` be created.

5. Run your application

```node deploy.js```

### Deploying to a testnet

Make sure you have a [metamask](https://metamask.io/) or other wallet, and export the private key.

**IMPORTANT**

USE A METAMASK THAT DOESNT HAVE ANY REAL FUNDS IN IT. Just in case you accidentally push your private key to a public place. I _highly_ recommend you use a different metamask or wallet when developing.

1. [Export your private key](https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key) and place it in your `.env` file, as done above.

2. Go to [Alchemy](https://alchemy.com/?a=673c802981) and create a new project on the testnet of choice (ie, Sepolia)
3. Grab your URL associated with the testnet, and place it into your `.env` file.
4. Make sure you have [testnet ETH](https://faucets.chain.link/) in your account. You can [get some here](https://faucets.chain.link/). You should get testnet ETH for the same testnet that you made a project in Alchemy (ie, Sepolia)
5. Run

```node deploy.js```

---

# Thank you!

If you appreciated this, feel free to follow me or donate!

ETH/Polygon/Avalanche/etc Address: 0xCF837162Ba826f2D04c2f03d056eE22Ad75bb7e9

[![Arslan Akbar Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Arsal_malik786)
[![Arslan Akbar YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@dappinside)
[![Arslan Akbar Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arsalmalik786/)
[![Arslan Akbar Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)][def]

[def]: https://medium.com/@arsalmalik786/