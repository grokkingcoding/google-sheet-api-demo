### About

- A step by step guide on setting up Google Sheets API

### Getting Started

1. go to google cloud platform

2. click "Getting Started for free"

3. You will be redirected to the google cloud console

4. Follow the steps ato setup a billing account. You will need to enter credit card deatils to get started.

5. So becareful in how you setup the API.

6. Once you are in the Google Console dashboard, click on the APIs & Services section on the left-hand menu.

7. click Enable Api and Services on the top of the screen

8. search for Google Sheets API and click enable

9. go back to the API & Seervices dashboard

10. click on the credentials tab

11. create a new Service Account - this is the account that allow us to keep track of how you use the API.

12. follow the steps to create Service Account

- give it a name
- choose Owner for permission role
- click done

13. Then go to your google sheets account sheets.google.com

14. create a new sheet

15. click share and copy your service account email into the shre section of your google sheet

16. go back to your google console and click on the service account and then click the edit button next to your service account

17. click add Key and choose JSON format (keep your service account details secret)

18. install an npm package - run the folliwng commands in your terminal

    - npm init
    - npm i --save google-spreadsheet

19. copy your service account details into credentials.json

20. copy and paste your google sheets ID - this is the code after .../d/

21. check that you can edit the google sheet you just added to your index.js

22. after you have finished setting up your index.js run: node index.js and you should see your google sheet title changed

23. for more information on how to use the npm package visit:

- https://www.npmjs.com/package/google-spreadsheet
