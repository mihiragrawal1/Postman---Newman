
🚀 Postman & Newman API Testing Collection

Explore this repository to discover a comprehensive collection of API testing scripts and workflows using Postman and Newman. 

🔗 What is Postman?
Postman is a powerful API testing and development tool that simplifies the process of designing, testing, and documenting APIs. It provides a user-friendly interface to create and manage API requests and collections.

🏗️ What is Newman?
Newman is the command-line companion for Postman. It allows you to run Postman collections and environments directly from your terminal, enabling automation and integration with CI/CD pipelines.

🚀 Get Started:
1. Clone this repository to your local environment.
2. Explore the collection and enviromant file given/provided.
3. 3.You can install newmman globally by-
    npm install -g newman   (for installing newman globally)
    newman run your-collection.json (to run collection in newman)
    newman run your-collection.json -e your-environment.json (to pass the enviroment file while running collection)
    newman run your-collection.json -d your-data.csv (to pass the csv-data file while running collection)

4. For running the above provided collection we will run following command -
    --> newman run Gorest.postman_collection new.json -e gorest token.postman environment.json -d new data file.csv -r htmlextra
        (this command will run the collection using the passed envirronmant and data file and generate a detailed html report)

6. For a feature-rich HTML report, you can install the "newman-reporter-htmlextra" plugin:
npm install -g newman-reporter-htmlextra  (globally install the reporter)
Once installed, generate the report using:
newman run your-collection.json -r htmlextra



Happy API testing! 🧪✨
