# Scrape-Right-Move
Scraping Property Search Pages Using Puppeteer Saved In MongoDb Local Host

This assumes some prior knowledge and installation of MongoDb, npm and Node Js.

1. Go to rightmove.co.uk and search the properties you wish.
2. Input the url after rightmove.co.uk starting with "/" search into line 32 of index.js to initialize puppeteer onto the correct pages.
3. Make sure you have mongod daemon running in your terminal (run command mongod in your terminal). https://docs.mongodb.com/manual/tutorial/manage-mongodb-processes/
4. Make sure you have the requisite npm packages installed.
5. Run node index.js

You should see an instance of Chromium running before all the properties are added in your local database.

This code could be adopted to scrape for page pagination for any website using puppeteer by changing the model and page selectors (css classes).

