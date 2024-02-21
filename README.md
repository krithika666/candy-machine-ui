# Candy Machine UI Setup 

## Overview
This README provides a step-by-step guide to set up the user interface (UI) for your Candy Machine, enabling users to mint NFTs with the SPL token you've generated. The UI utilizes the SPL token as the payment method, and users can mint NFTs by connecting their Phantom wallet.

### Prerequisites
Before starting, ensure you have:

- A configured Candy Machine with specified details in its `config.json` file.
- A Phantom wallet designated as the minting wallet.

### Steps

1. **Set Up the SPL Token**
   - If not done already, create the SPL token following Lesson Three guidelines. Note down the SPL token's address.

2. **Update Candy Machine Config**
   - Open the `config.json` file of your Candy Machine and update the following fields:
     - `splTokenAccount`: Replace with the SPL token account address.
     - `splToken`: Replace with the SPL token address.

3. **Set Up the UI**
   - Refer to the "Quick Node: Set Up a Minting Site" tutorial for creating a user interface. This UI enables users to connect their Phantom wallets and mint NFTs using the SPL token.

4. **Modify Minting Logic**
   - In your SPL project's minting logic (Lesson Three), adjust to mint NFTs to the Phantom wallet address or modify the transfer function accordingly.

5. **Testing**
   - Test the setup by transferring or minting the SPL token to a Phantom account. Use the created UI to mint NFTs, allowing users to pay with the configured SPL token.

### Additional Tips
- For complete Candy Machine logic and minting functionality, consult the [Candy Machine Repository](link).
- SPL token creation referenced [The SPL Token Program by MetaCrafters](link).
- Verify that addresses and token details in `config.json` match your created addresses and tokens.
- Ensure clear UI instructions for connecting Phantom wallets and minting NFTs.
- Customize your UI based on design preferences.

## Conclusion
Following these steps, you'll successfully establish a Candy Machine UI for users to mint NFTs with your SPL token. Users can connect Phantom wallets, utilizing the SPL token as payment to mint NFTs from your Candy Machine. Thoroughly test before public deployment.
