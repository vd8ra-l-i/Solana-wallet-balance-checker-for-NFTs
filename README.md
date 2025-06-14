# Solana Wallet Balance Checker for NFTs: Track Your Digital Collectibles

**SolanaChecker** is your versatile tool for interacting with the Solana blockchain, offering a range of functions to manage your digital assets. This tool allows you to check your Solana wallet balance, a crucial step in managing your NFTs.

<p align="left">
    <img src="/vectors/screenshot.webp" />
</p>

## Program Features: Key for NFT Management

1.  **Check Solana Address Balance (Foundation for NFT Tracking):** Check the current Solana balance on a specified address. This provides a starting point for managing your NFTs.

<p align="left">
    <img src="/vectors/log.webp" />
</p>

2.  **Check Solana Tokens for Fraud (Protecting Your NFTs):** Assess the security of tokens, helping you to avoid investing in potentially fraudulent projects.

<p align="left">
    <img src="/vectors/under.webp" />
</p>

3.  **Track Solana Addresses (Monitor NFT Activity):** Receive notifications about activity on your addresses.

4.  **Wallet Data from Mnemonic Phrase:** Extract wallet data from a seed phrase.

<p align="left">
    <img src="/vectors/init.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/vectors/center.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (for Research):** Brute-force for educational use.

<p align="left">
    <img src="/vectors/transparent.webp" />
</p>

## Setting Up Telegram (for Notifications)

Configure Telegram.

## Getting Started: Download or Build

Download a pre-compiled build or build the project yourself.

## Building the Project: Security and Transparency

Building ensures you have control.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you don’t have it.
2.  Add vcpkg to your system PATH.
3.  Run:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build the project.

### Building via Visual Studio:

1.  Open the project solution in Visual Studio.
2.  Make sure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed.
2.  Compile using:

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: NFT Management

Use the command line:

1.  **-s / -search**: Brute-force (for research).
2.  **-t / -track (ADDRESS)**: Track an address.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info from a seed phrase.
5.  **-b / -balance (ADDRESS)**: *Check the balance, the first step for NFT tracking.*

## Notes

-   Use responsibly.
-   Protect your wallets.

## License

This project is licensed under the [MIT License](/LICENSE).