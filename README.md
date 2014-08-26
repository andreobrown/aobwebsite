Website for Any Other Business (...aob)
=========================================

master
-----------
This branch contains the base code - html, css, javascript and images only.

heroku
-----------
This beanch contains the configurations necessary for serving this as a Ruby app on Heroku.

Used heroku-static-site gem.

workflow
-----------
* Make changes on main branch
* Switcht to heroku branch:

   ``` git checkout heroku```

* Checkout changes from main branch (eg. agency.css):
    
    ```git checkout master css/agency.css```

* Commit changes

    ```git commit -am "Commit changes"```
    
* Push changes to heroku

    ```git push heroku heroku:master```
 
