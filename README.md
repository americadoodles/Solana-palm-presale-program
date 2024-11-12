# Solana Palm Presale Smart Contract

This smart contract, developed with the Anchor framework, enables the presale of SPL tokens through a secure and configurable mechanism, including a ticket-based allocation system for token reservations.

## Key Features

- **Token Sale:** Users can directly purchase SPL tokens from the contract, functioning as an automated vending system.
  
- **Presale Mechanism:** A configurable presale phase provides exclusive token access for a defined period before the public sale.

- **Allocation Tickets:** During the presale phase, users can obtain tickets to reserve spots for token purchases.

- **Flexible Configuration:** Easily customizable parameters for presale and public sale timings, token pricing, and ticket allocation limits.

## Prerequisites

Ensure you have the following tools installed:

- [Rust](https://www.rust-lang.org/tools/install)
- [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)
- [Anchor CLI](https://project-serum.github.io/anchor/getting-started/installation.html)
- [Node.js](https://nodejs.org/en/download/)
- [Yarn](https://yarnpkg.com/getting-started/install)

## Getting Started

1. **Installation:** Clone the repository and install dependencies.

   ```bash
   cd Solana-palm-presale-program
   yarn
   ```

2. **Build the Smart Contract:**

   ```bash
   anchor build
   ```

3. **Run Tests:**

   ```bash
   anchor test
   ```

4. **Deploy:**

   Switch to your desired network and deploy:

   ```bash
   anchor deploy
   ```

## Raise an issue on this and make PR for a new idea
For inquiries or support related to this repository, please reach out. I'll be happy to discuss suitable communication options.