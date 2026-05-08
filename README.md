# Simple Blockchain

A minimal blockchain implementation written in Go, demonstrating the core concepts of blockchain technology including block creation, hashing, and chain validation.

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Go | Programming language |
| crypto/sha256 | SHA-256 hashing algorithm |

## Features

- Genesis block creation
- Block structure with timestamp, data, and hash references
- SHA-256 cryptographic hashing
- Chain of blocks with previous hash linking
- Simple transaction data storage

## Prerequisites

- Go 1.16 or higher

## Installation

1. Clone the repository:
```bash
git clone https://github.com/nikolaykolibarov/simple-blockchain.git
cd simple-blockchain
```

2. Build the project:
```bash
go build
```

## How to Run

Execute the compiled binary or run directly:

```bash
go run .
```

The program will create a blockchain with a genesis block and add sample transactions, then print the chain to the console.

## Project Structure

```
simple-blockchain/
├── main.go          # Entry point - creates blockchain and adds blocks
├── block.go         # Block struct and hashing logic
├── blockchain.go    # Blockchain struct and chain management
└── .gitignore
```

> **Note:** This project was created for educational/course purposes to understand the fundamental concepts of blockchain technology.
