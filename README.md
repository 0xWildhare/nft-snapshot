# 📸 NFT Collection Snapshot
## ⚡ Snapshot an entire NFT collection owners. 

---   

📤 Exports as CSV file with column labels.

🔰 &nbsp;Use at your own risk, always verify, do your own research.  

🔼 Get your Alchemy API key on https://www.alchemy.com/  

&nbsp;

## Requirements  

---

- Node.js
- Alchemy API key  

*This tool was created with Node 18.1.0, and have not been tested with other versions of Node.* 

&nbsp;

## Usage  

---

- Clone or download this repo to your local machine. 
- Install dependencies with `npm install`
- Make a new `.env` file in the directory with your Alchemy API key like so:
> `ALCHEMY_KEY="<YOUR-ALCHEMY-KEY-GOES-HERE>"`  

- Configure the snapshot in `config.json` file: 
> - Set the contract address,  
> - Target block (leave empty for latest block),  
> - withBalances

- Run `node index` to snapshot.  

&nbsp;

## Maintenance  

---

Hit me up on Twitter [@vngnc](https://twitter.com/vngnc) for anything you have in mind about this code (or everything else). 🖤