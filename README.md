# postman-tutorial
A very basic Postman tutorial for testing and training purposes.
This repository contains the following files: The Postman Collection(`PostmanTutorial.postman_collection`), The Data File(`  postman.data.json`), and this `ReadMe` file.

## Requirements:
- [NPM](https://nodejs.org/en/)
- [Newman](https://www.npmjs.com/package/newman)
  - $ `npm install newman --global;`
 

## Instructions:
1. Download/Clone this repository.
2. In a new Terminal window, navigate to your newly downloaded/cloned `postman-tutorial` project.

### Running the Collection:
1. In a new Terminal Window, Navigate to the folder containing the `PostmanTutorial.postman_collection` and the `postman.data.json` files. (cd into the project directory).
2. Run $`newman run PostmanTutorial.postman_collection --insecure -d postman.data.json` 
