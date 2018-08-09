# postman-tutorial
A very basic [Postman](https://www.getpostman.com/) tutorial for testing and training purposes.
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

### Editing the Data Tested:
1. Open the `postman.data.json` file in your preffered IDE, notepad or terminal window.
2. Make edits, save, and ReRun the collection.


### Editing Tests:
1. Open [Postman](https://www.getpostman.com/)
2. Once Postman is open, On the Top Navigation Bar, click `Import`
3. Import the `PostmanTutorial.postman_collection` file.
4. Navigate to your newly imported `PostmanTutorial` collection in Postman.
5. Click *Tests* to view the Tests for the collection.
6. Click *Save* to save your changes.
7. Hover over your Postman Collection name and click the three dots (*...*)
8. Cick *Export*
9. Select the *Collection v2* option and click *Export*
10. Save to the same folder location and overwrite `PostmanTutorial.postman_collection`.
11. Run your Collection.

### [Generating Run Reports](https://github.com/postmanlabs/newman#reporters):
1. Install newman html reporter by doing a $`npm install -g newman-reporter-html` in a terminal window.
#### Usage:
In order to enable this reporter, specify html in Newman's `-r` or `--reporters` option.
- **Example:** $`newman run PostmanTutorial.postman_collection --insecure -d postman.data.json -r html`

