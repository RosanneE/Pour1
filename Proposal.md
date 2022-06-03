I will make an app that allows the user to input the items in their liquor cabinets (through a dynamic search of pre-listed items) and returns drinks that the user is able to make with the listed ingredients.  

Views will include Home (where the user can input their ingriedients and get back the menue of makable drinks - this will be a list of drink names that can be clicked on to view their details), an index of drinks, a show page for individual drinks (accessable by clicking from their menue or the index page), an add page for drinks, an update page for drinks, and an about page.

It will be a full CRUD app, and will have a confirmation for users before they delete items.  I currently plan to use Django, but I may switch to React/Mongodb over the weekend if I have trouble using postgres (the M1 has sqlite3 preloaded (so it is what i have used on Finch), but sqlite3 does not work with a heroku deployment).

MVP:
1.Full CRUD
    Views:
        1. Home
        2. Index
        3. Show
        4. Add
        5. Edit
        6. About
 2. Use Django (or React/Mongodb) for a deployment through heroku
 3. Delete route, with verification of delete
 4. Dynamic search bar for Drink Ingredients
 5. Menu feature shows drinks makable with only the ingredients in the list
 6. Use either pre-created API (several are availible) or create my own (this is what I want to do, already have advice/examples from Keisha)

The above is the MVP of the project, stretch goals include:
    User Auth (would also add views/changes to views)
    User created lists (favorites, things to try, things I've tried)
    Parameters for drink menue (all drinks must include X ingredient, no drink should include X ingredient)
    A Random drink page that pulls up a random drink from the drinks list
    A feature that determines what one ingredient added to your home bar would allow you to make the most new drinks
    User voting on suggested drink additions
    
Wire Frames:    
![Screen Shot 2022-06-03 at 10 41 28 AM](https://user-images.githubusercontent.com/6979738/171877339-0270d575-4d35-462a-a5c3-7d7ceaf9c29b.png)
![Screen Shot 2022-06-03 at 10 41 36 AM](https://user-images.githubusercontent.com/6979738/171877356-824d1938-8c21-4f73-b1a5-a2e411e462a6.png)
![Screen Shot 2022-06-03 at 10 41 42 AM](https://user-images.githubusercontent.com/6979738/171877368-80d2288d-263f-46bb-b4a2-47af5486e657.png)
![Screen Shot 2022-06-03 at 10 41 46 AM](https://user-images.githubusercontent.com/6979738/171877383-32d16983-e067-4674-ab8c-54a0890483c1.png)
![Screen Shot 2022-06-03 at 10 41 51 AM](https://user-images.githubusercontent.com/6979738/171877394-84906685-d6fc-4e7d-95bc-30bd51f02e84.png)
![Screen Shot 2022-06-03 at 10 41 56 AM](https://user-images.githubusercontent.com/6979738/171877402-92908c26-67fe-4ca9-af6e-abae7961533e.png)
![Screen Shot 2022-06-03 at 10 42 01 AM](https://user-images.githubusercontent.com/6979738/171877419-dde70c37-7651-4658-b98f-96a43bc7ec07.png)
