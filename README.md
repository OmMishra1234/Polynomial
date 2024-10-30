# Shamir's Secret Sharing Scheme Implementation

This project implements Shamir's Secret Sharing scheme, a cryptographic algorithm that allows a secret to be divided into parts, giving each participant its own unique part.

## Description

Shamir's Secret Sharing is used to secure a secret in a distributed way, particularly useful for:
- Distributed key management
- Access control
- Secure multi-party computation

This implementation allows for the reconstruction of the secret given a sufficient number of shares.

## Features

- Reads input from a JSON file
- Supports various number bases (2 to 36)
- Implements polynomial interpolation for secret reconstruction
- Handles large numbers using Python's built-in support for arbitrary-precision arithmetic

## Requirements

- Python 3.x

## Usage

1. Ensure you have Python 3.x installed on your system.
2. Place your input data in a file named `input.json` in the same directory as the script.
3. Run the script:
