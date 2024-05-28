# spark-entity-mapper

Generate a pyspark code for the following userstories:
I want to retrieve entity data from the program. The program should be able to map the data fields from the input file to the corresponding fields in the output file based on predefined mapping rules. This includes mapping the product code (F007-COD-PROD) to specific values (CA-DEPOSIT1, CA-DEPOSIT2, CA-DEPOSIT3, CA-LOAN) and performing computations for the available amount (F007-AMT-AVA1) based on other fields (F007-DEBTBAL, F007-AMT-CAP, F007-AMT-ITR, F007-AMT-COM). The program should also handle different operations for different product codes and ensure the correct computation of the available amount.
I want to initialize the database to handle program failures.
I want each record in the input file to be exactly 750 characters long so that I can ensure consistency in the data.
I want the program to calculate the return percentage based on certain conditions. This calculation will be different for the product code CA-LOAN and other scenarios.
I want the program to calculate the available amount for specific product codes. This calculation will be based on predefined field values and will determine the amount available for each product.
I want the program to identify the product code and perform different operations based on the type of product. This will allow for specific calculations and processing steps to be applied to each product.

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/spark-entity-mapper.git
cd spark-entity-mapper
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
