# Additional Practice: Woof Woof Welcome to Doggo Bark Bark

THIS GOOD APPLICATION FOR LOOKING AT DOGS BOW WOW.

WHEN LOOKING AT PUP PUPS USER SHOULD BE ABLE TO:

 - Click on dogs in the dog bar to see more info about the good pupper;
   - More info includes dog's name, image and number of treats dog has;
 - Click on "Add Treats" button to add more treats to dog's treats.
 - Click on "Reset Treats" button to reset treats to 0.

## EXAMPLE:
![Showcasing the full functionality](Demo.gif)

### STEP 1: VIEW THE DATA

All of the dog data is stored in the `db.json` file. You'll want to access this data using a json server. In order to do this, run `$ npm install -g json-server` and then `$ json-server --watch db.json`.

This will setup the data on a server using restful routes at http://localhost:3000/pups. Go ahead and head to that url in your browser to view the data. Familiarize yourself with the attributes for each pup. Try going to `/pups/:id` to see an individual pup as well.

### STEP 2: ADD PUPS TO DOG BAR
On the page, there is a `div` with the id of `"dog-bar"`. On page load, make a fetch to get all of the pup objects. When you have this information, you'll need to add a `span` with the pup's name to the dog bar (ex: `<span>Mr. Bonkers</span>`).

### STEP 3: SHOW MORE INFO ABOUT EACH PUP
When a user clicks on a pup's `span` in the dog bar, that pup's info (`name`, `image`, and `treats`) should show up in the `div` with the id of `"dog-info"`.

### STEP 4: ADD MORE TREATS
When a user submits treats form, The total number of treats should increase by that number.

### STEP 5: RESET TREATS
When a user clicks on reset treats button, the total number of treats should reset to 0.
