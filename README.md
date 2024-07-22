# OFT Example Deployment

This repository serves the purpose of demonstrating how to deploy an Omnichain Fungible Token (OFT) into a production environment. For context, the OFT refers to the LayerZero protocol's extension to the standard ERC20 implementation that most in blockchain are familiar with. <br>

By adopting the OFT standard, liquidity can flow where it is needed and blockchains can communicate seamlessly, in alignment with LayerZero's vision for connecting all blockchains through their leading interoperability technology.

---

Begin by ensuring you have your development environment set up:

- Node.js
- NPM
- IDE (code editor) such as Visual Studio Code

---

Proceed to install the necessary dependencies to enable you to write, compile and deploy your OFT.

Run `npx create-lz-oapp@latest` in your terminal or code editor. You should be greeted by the LayerZero CLI utility:

![LZ-Oapp](https://github.com/user-attachments/assets/28010f36-f51a-443d-b441-2de34064bf76)

---

Then, follow the project wizard steps to get your project template set up:

![LZ-Oapp2](https://github.com/user-attachments/assets/ae13ff04-034b-4061-bbb5-9acb2c571c6a)

---

Once you have set up your `.env` file and crafted your smart contract to your requirements, proceed to compile the contracts by running `pnpm compile` and this will compile in both Hardhat and Forge development frameworks:

![LZ-Oapp3](https://github.com/user-attachments/assets/3a4fca81-f53b-4ec9-aaa2-98dc672295b8)

---

Then run tests (in either Forge or Hardhat) or both; by simplyy running `pnpm test` and you should see the following result if all passes:

![LZ-Oapp4](https://github.com/user-attachments/assets/b9498c10-0266-4da5-bb3e-acf45a788733)

---

Then deploy your contracts using the command `npx hardhat lz:deploy`

![image](https://github.com/user-attachments/assets/e1c0c239-4a6d-4b05-b6f2-eff0468495d7)


---
![LayerZero](https://github.com/user-attachments/assets/334a4032-acb6-4f0d-b436-72c4521b1b27)

- [LayerZero Docs](https://docs.layerzero.network/v2) 
- [LayerZero X](https://twitter.com/LayerZero_Labs)
