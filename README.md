# Voting System Smart Contract

This is a Solidity smart contract that implements a basic voting system. It allows users to vote for their favorite candidates from a predefined list.

## Contract Details
-Solidity Version: ^0.8.18
-License: MIT

## Description
The `VotingSystem` contract contains the following components:

- `Candidate` struct: Represents a candidate with a name and a vote count.
- `candidates` array: An array that holds the list of candidates.
- `constructor`: Initializes the list of candidates with default values.
- `vote` function: Allows users to vote for a candidate by providing the candidate's index and their age. Only users older than 18 can vote.
- `InvalidCandidateIndex` error: An error thrown when an invalid candidate index is provided.
- `getCandidateSafe` function: Safely retrieves candidate information by index, handling out-of-bounds errors.

## IDE
REMIX: The Native IDE for Web3 Development. [ https://remix-project.org/ ]

## Execution of the program
-Copy the code from this Github Repo
-Verify the solidity version and compile the code.
-Deploy the smart contract and play around.

## Author
Shresth Varshney

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
