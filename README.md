Shamir's Secret Sharing Simplified
This project implements a simplified version of Shamir's Secret Sharing algorithm to calculate the constant term (c) of a polynomial using given roots provided in JSON format. The solution uses Lagrange Interpolation to determine the polynomial's coefficients and compute the secret.

Features
Parses input roots from a JSON file.
Handles roots encoded in various bases (e.g., binary, octal, decimal, etc.).
Implements Lagrange Interpolation to calculate the constant term.
Provides error handling for missing or incomplete data.
Requirements
Node.js v12 or later.
An IDE or text editor (e.g., VS Code) for development.
Clone the repository:

bash
git clone <repository-url>
Navigate to the project directory:

bsh
cd <project-folder>
Install Node.js (if not installed). Download here.

Create a JSON file with your test cases (e.g., testcase.json).

Run the script:

Edit
node index.js
