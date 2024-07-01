# gql-data-retrieval
Support for IXO GQL queries

## Description
This project supports the GQL queries required to retrieve data from the IXO Blocksync endpoints.
Find the query explorer here:
- https://blocksync-graphql.ixo.earth/graphiql
- https://testnet-blocksync-graphql.ixo.earth/graphiql
- https://devnet-blocksync-graphql.ixo.earth/graphiql

Additional support is required in order to fetch additional data structures after an initial query.
For example, a query to return all data for a specific Entity will return endpoints to Cellnode and IPFS.
These endpoints contain further nested structures that may also contain nested structures, etc.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/username/gql-data-retrieval.git
    cd gql-data-retrieval
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv myenv
    source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
    ```

3. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
Instructions on how to use your project.

## Contributing
Guidelines for contributing to your project.

## License
This project is licensed under the Apache 2.0 License - see the LICENSE file for details.