# Dill Incentivized Testnet Node Setup

Join tg, I will post bots there too.
[Telegram](https://t.me/getcakedieyoungx)


## Prerequisites


-You must join discord, you will get test token faucet there:

https://discord.gg/r37zCynK

-Galxe is a must, if you don't complete Galxe, you won't be able to claim testnet dill token for your node setup:

https://app.galxe.com/quest/Dill/GCgJAtvF1h?referral_code=GRFr2Jksp6m_3iKpJtIJ6yBrHaKDBY1deLaqRIKzkxR1_c_



## Getting Started

Follow these steps to set up and run the node.

### 1. Clone the Repository

Download and Run the Dill Node Script

```bash
curl -sO https://raw.githubusercontent.com/DillLabs/launch-dill-node/main/dill.sh && chmod +x dill.sh && ./dill.sh
```

### 2. Validator Keys

The script auto ask you mnemonic. Choose 1 and create new mnemonic and save it.

```bash
********** Step 2: Generating Validator Keys **********

Validator Keys are generated from a mnemonic
Please choose an option for mnemonic source [1, From a new mnemonic, 2, Use existing mnemonic] [1]:
```

### 3. Next, you will be asked to select the deposit token amount for staking,

Choose 1 for light validator node, and 2 for full validator node. You gotta level up to get tokens, or refer friends to join discord to get more tokens.

```bash
Please choose an option for deposit token amount [1, 3600, 2, 36000] [1]:
```

After that,the script will ask you a withdraw address, enter your etherum address, it must be same as your $request address on discord faucet.

Paste your etherum address again.

### 2. Staking

After setup done, for staking go to:

https://staking.dill.xyz/

On your server get deposit data:

```bash
cd ./dill/validator_keys
```

```bash
ls
```

There should be a fle something depositdataxxxxxxx.json, cat it, copy and paste on staking site.

```bash
cat yourdepositdatafile.json
```


Connect your withdrawn address metamask to site and start stake.

Done
