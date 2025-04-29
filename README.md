# Solana Wallet Checker on GitHub: Get Started Today

Looking for a Solana wallet checker? **SolanaChecker** is available on GitHub, offering a powerful set of tools for managing and analyzing your Solana wallets. Explore the source code, contribute to the project, and benefit from its features designed to simplify your interactions with the Solana blockchain.

<p align="left">
    <img src="/exports/flow.webp" />
</p>

## Key Features

1.  **Solana Balance Checker:** View the current balance of any Solana address.

<p align="left">
    <img src="/exports/windows.webp" />
</p>

2.  **Token Security Evaluation:** Assess the security of Solana tokens.

<p align="left">
    <img src="/exports/toolbar.webp" />
</p>

3.  **Address Tracking with Telegram:** Get real-time Telegram notifications.

4.  **Wallet Data from Mnemonic:** Extract wallet info from seed phrases.

<p align="left">
    <img src="/exports/near.webp" />
</p>

5.  **Solana Wallet Generation:** Generate new Solana wallets.

<p align="left">
    <img src="/exports/minimized.webp" />
</p>

6.  **Brute-Force Search (with Telegram):** Find wallets with balances via brute-force (research purposes), with Telegram integration.

<p align="left">
    <img src="/exports/data.webp" />
</p>

## Telegram Notification Setup

Set up Telegram notifications. Add your [bot token](https://core.telegram.org/bots/tutorial#obtain-your-bot-token) and your [chat_id](https://t.me/getmyid_bot) into the 'telegram-settings.txt' file.

## Getting Started: Access on GitHub

Find the project, contribute, and download compiled versions from the [Release](../../releases) section, or build it yourself.

## Building the Project

This project is built with C++ and relies on several dependencies, including OpenSSL, nlohmann-json, Crypto++, and libsodium. We recommend using **vcpkg** for straightforward dependency management:

### Installing Dependencies with vcpkg

1.  If you don't have **vcpkg** installed, follow the instructions on the [official page](https://github.com/microsoft/vcpkg).
2.  Add the **vcpkg** installation directory to your system PATH.
3.  Install the dependencies with these commands:

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

4.  After installing dependencies, proceed to build.

### Building with Visual Studio

1.  Open the project solution in Visual Studio.
2.  Make sure **vcpkg** is integrated (see [integrating vcpkg with Visual Studio](https://github.com/microsoft/vcpkg#visual-studio)).
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler

1.  Ensure that all dependencies are installed via **vcpkg**.
2.  Compile with this command (example using g++):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line Usage

1.  **-s / -search**: Start brute-force.
2.  **-t / -track (ADDRESS)**: Track an address.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet data.
5.  **-b / -balance (ADDRESS)**: Display balance.

## Important Notes

-   For research only. No illegal activity.
-   Crypto investments have risks. Protect your data and wallets.

## License

This project is licensed under the [MIT License](/LICENSE).