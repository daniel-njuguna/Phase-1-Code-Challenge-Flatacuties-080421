# Phase-1-Code-Challenge-Flatacuties-080421
# Flatacuties

Today you'll be building an app for voting for the cutest animal! You will be
using a local API and building out the frontend for our app, Flatacuties.

## Demo

Use this gif as an example of how the app should work.

![Demo](assets/demo.gif)

> To view in VSCode, right click on the README.md file and select "Open Preview".

## Setup

Run this command to get the backend started:

```sh
json-server --watch db.json
```

Test your server by visiting this route in the browser:

[http:
Samuel Kuria10:11 PM
[http://localhost:3000/characters](http://localhost:3000/characters)

Then, open the `index.html` file on your browser to run the application.

Write your code in the `src/index.js` file. The base URL for your API will be
[http://localhost:3000](http://localhost:3000).

## Deliverables

As a user, I can:

1. See all characters names in a `div` with the id of `"character-bar"`. Create
   a `span` tag with the character's name and add it the `div#character-bar`
   once you have retrieved the char
```txt
   GET /characters/:id

   Example Response:
   {
    "id": 1,
    "name": "Mr. Cute",
    "image": "https://thumbs.gfycat.com/EquatorialIckyCat-max-1mb.gif",
    "votes": 0
   }
   ```

3. When the `form#votes-form` is submitted, add the number of votes from
   the input field to the character displayed in the `div#detailed-info`. **No
   persistence is needed**.

### Bonus Deliverables

These bonus deliverables are here if you want an extra challenge and won't
affect your score. **Make
