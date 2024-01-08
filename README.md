Displays all character names in a div with ID “characterbar”. Create a span tag with the character name and add it to the div# character bar after downloading the character data from the server. To retrieve character data, you need to send a GET request to the following endpoint:
When you click a character in the div# character bar, the character's details are displayed in div#detailed-info. You can use the character information from the first query or send a new query to this endpoint to get detailed character information:
In
index.html
there is additional HTML code that is now commented out under the Reset Grades button. Remove comments (delete <!-- and --> around elements) so you can complete additional elements.

After clicking the “Reset Votes” button, reset the vote count to 0.

After submitting form#characterform, add a new character to div#characterslash. When clicked, a new character should behave like other characters in the character bar (his details should appear at the bottom and he should have the ability to add voices).

In addition to adding the character to the div#character-bar after submitting the form, the character details should immediately appear in div#detailed-info.