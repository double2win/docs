# Capital

The amount of Capital you are allowed to contribute is dependent on the DDC (Double Down Club NFTs) you have in your wallet. See the [DDC](/DDC.html) page for more details.

You can create a liquidity position with any token in Double. However, the token must have a pool/pair on your selected AMM and also have tokens available in the Double Token Vault in order to be a valid pair. 

To learn how to add tokens to the double vault see the Deposit Tokens Section under the [Token Page](/Token.html) in this manual.

## Checking Your Capital Allowance 
1. To start you need to check your **Capital Allowance**
2. Navigate to the **DDC Page**
3. If you are holding DDC in your wallet you will be able to deposit the DDC to the Smart Contract
4. Click the **Dropdown Arrow** next to the **Deposit** row
5. Select the DDC you would like to Deposit
*⁃ Note: if you don’t have any DDC see the [DDC](/DDC.html)  page in this guide for more information*
6. Click **Deposit** and confirm the transaction in your wallet

## Creating a New Position
1. Navigate to the **Capital Page**
2. Click **New Position**
3. Select your desired Capital Type (Celo, cUSD, ETH, etc.)
4. Next, select or import the token from its contract address
5. Input the amount of Capital or the number of Tokens you would like to use in the transaction
6. Approve the double smart contract to transact with each of the assets (if you have not approved them yet - you only need to do this once per asset)
7. Click **Add Liquidity** to approve the transaction
8. Confirm the prompt from your wallet to sign the transaction
9. You can view the progress, as well as the success or failure of the transaction in the block explorer popup once your transaction is submitted
10. Once your transaction is processed by the network the position will appear on your dashboard

*Note: When creating a new position Double sources tokens from the* **Double Vault - Not your personal wallet**. *If the Vault does not have enough tokens you will not be able to make your position. The vault can be accessed on the [Token page](app.double2win.xyz/token). You can request more tokens to be added to the vault from the project, deposit tokens yourself, or wait for tokens to become available.*

## Close a Position
In order to close a position you will need to supply the borrowed tokens back to the contract. if tokens are owed you will need to source the remaining balance of tokens owed from an AMM or another wallet before you may close your position.

1. Select the correct AMM using the **AMM Selector** dropdown
2. Click the **dropdown arrow** next to the position you would like to close, to expand details on the position.
3. Click **Remove Liquidity**    
    *1. If you owe tokens due to impermanent loss then the contract will ask you to repay the token amount and approve the transaction*
    *2. If you do not owe tokens click approve to finalize the transaction*
