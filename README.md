# GRAPHQL API EXAMPLE

The goal of this project is to give you a general overview of how a GraphQL API works, how its pieces interact, and what a full implementation might consist of.

## TOOLS USED IN THIS PROJECT

### NODEJS
### APOLLO GRAPHQL

## ARCHITECTURE

## FOLDER STRUCTURE

This is the folder and package structure of SDK source code and the description

  - **db**: Main Database["Not Using actual database. Instead we'll just use a simple array that will work just fine for example purposes, though our data will of course reset every time our server does."]
  - **pets**: Pets models, mutations and queries.
   - **models**: functions responsible for interacting with our data layer (database) and returning the corresponding information to our controllers.
   - **mutations**: Contains functions that are used to modify data in an API.
   - **queries**: Contains functions used to fetch data from an API