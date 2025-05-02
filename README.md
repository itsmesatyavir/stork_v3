# Stork v3

A Node.js-based tool that automates tasks using account credentials.

## Installation

Clone the repository and navigate into it:

```bash
git clone https://github.com/itsmesatyavir/stork_v3.git
cd stork_v3
unzip stork_v3
```

## Setup

Create a file named `accounts.txt` in the root directory:

```bash
nano accounts.txt
```

Add your accounts in the following format (each on a new line):

```
email@example.com|password123
another@example.com|pass456
```

## Usage

Run the tool using Node.js:

```bash
node main
```

## Requirements

- Node.js
- `unzip` utility (for extracting the contents of the repo if zipped)

## Notes

- Make sure the `accounts.txt` file is correctly formatted with one account per line using the `email|password` format.
- Do not share your credentials publicly.
- This tool is intended for educational purposes only.

## Author

- [itsmesatyavir](https://github.com/itsmesatyavir)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
