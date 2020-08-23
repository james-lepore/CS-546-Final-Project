# CS-5466-Final-Project

Install packages with "npm install". To set up email sending,  ------. Start the server with "npm start". Populate the server with seed data using "npm seed". 

When opening our website for the first time, you will be directed to the hompepage in which you can view all items that are being and have been sold. There is a sorting filter that allows you to choose between multiple options on what order you would like to view the items. There is also a checkbox that hides sold items, which allows you to see what items are currently available. The nav bar contains a search bar that allows you to search by title or tags of items. If you click on a link to an item, you can view the details such as end date and current bid. However, if you would like to bid or comment on the item, you must sign in or create a new account. 

Signup is a form that once filled out logs you into the newly created account. There is validation for proper format such as checking for empty input or invalid inputs. On top of this, you cannot use a preexisting email or username. After signup, you are redirected to your newly created profile.

Login is a form that uses your created username and password to sign you in. There is validation for wrong inputs or empty inputs. After login, you are shown a welcome message. 

You now have the capability to create a new item. Here, there are mandatory and non-mandatory fields to fill out in posting a new item for bid. There is validation for empty fields. The only field that is non-mandatory is tags. Once submitted, you are redirected to a item confirmation page for submission.

If you go back to home and click an individual item, you now have the ability to bid on items that aren't yours as well as comment on any item. Bidding allows only numbers greater than current bid and comments do not allow number only inputs. 


You can logout but clicking "Logout" in the nav bar. 