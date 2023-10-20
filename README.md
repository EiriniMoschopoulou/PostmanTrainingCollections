# API Test Postman Collection

## Overview

This repository contains a Postman collection designed for testing the API that set up a coffee shop. The collection includes a set of predefined requests and tests to ensure the API's functionality, performance, and reliability.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)

  


## Getting Started

Before you can start using this Postman collection to test the API, make sure you have the necessary prerequisites in place and follow the installation instructions below.

## Prerequisites

To use this Postman collection, you need the following:

1. **Postman**: You should have [Postman](https://www.postman.com/downloads/) installed on your local machine.

2. **API Access**: You must have access to the [Api course]https://github.com/vdespa/automation-with-postman-course , including API key(s) or authentication credentials if required.

## Installation

1. Clone this GitHub repository to your local machine:

   ```bash
   git clone git@github.com:EiriniMoschopoulou/PostmanTrainingCollections.git
2. Open Postman

3. Import the Postman collection

   In Postman, click on the "Import" button.
   Select the 'Example API Testing' file located in the repository's root directory.



4. You are now ready to use the collection to test the API.

## Usage
1. Open Postman.

2. Navigate to the 'Example API Testing' in the Postman sidebar.

3. You will find a list of requests grouped by folders, each corresponding to a specific API endpoint or functionality.

4. Click on a request to open it and review the request details and parameters.

5. Click the "Send" button to execute the request against the API.

6. Postman will display the response, and any associated tests will automatically run to validate the response.

7. Review the test results to ensure the API is behaving as expected.


## Folder Structure
The Postman collection is organized into the following folders:

 - status: Get the status of the API.

 - products: Contains requests and tests related to products-related endpoints.

 - clients: Contains requests and tests related to clients-related endpoints.

 - orders: Contains requests and tests related to order-related endpoints.


## Github Actions
This postman Repo is running through Github Actions 
1. Just go to Actions tab
2. Open the alreaady established workflow 'Automated API tests using Postman CLI'
3. Click on re-run on the last running job 
4. Or you can make a change to the collection and push --> This will trigger a new run automatically

   
