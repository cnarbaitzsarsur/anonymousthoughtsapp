# anonymousthoughtsapp

**Purpose and Target Group

The purpose of this app was, to create a map interface to accumulate thoughts about a certain place. Similar to the website: “queeringthemap.com", the idea was to create a space for people to share their thoughts with others, in this case about the location itself or about the general feeling a user may have had at that location. This way, people new to the area, tourists or anyone with an interest in places around the world can experience an area through the thoughts of others. Additionally, the user can put the thought in a category that best fits the specific feeling they had at that location.

**Methodology

Initially, the idea was to create four activities. One for the map, another to put thoughts into a list and display them, one to be able to filter by the emotions and one activity to chose between the list view and the map. Rather quickly it was clear that only those four activities would not be enough to encase all the functionalities that were needed for an optimal run through of the app. Towards the beginning the consensus within the group was also to use MapBox instead of GoggleMaps for the map activity, but after a lengthy process of attempting to initialize MapBox, the decision was made to go with the somewhat easier map implementation, all be it losing some of the aesthetically pleasing elements that come with MapBox.
Additionally, after trying to implement a filtering function, where the user could filter the markers on the map by the emotions of the thoughts, for many hours, the decision was made to implement this in future developments of the app.

**Read_me:
To use the app in the emulator correctly, one has to first upload the database that is stored in the assets folder, into the data/data/com.example.googlemapstest/database folder. This action is only possible after writing at least one thought into a database, using the “Add Thought Activity”.

**Activities 

“Title Activity” 
The first activity in the app is the launcher activity. Here, the app name is animated to look like a typewriter is writing it.

“About Page” 
This next activity gives a quick overview of the app’s functionalities and invites the user to start exploring.

“Select Mode” 
In this activity the user can decide whether they want to explore a list of the thoughts that are stored in the database or whether they would like to   look at the map with markers placed for each of the individual thoughts.

“List Activity” 
Here, all thoughts from the database are stored and can be explored. All entries include a thought, the authors name (or an alias) and the authors emotion. The location of the thought can not be seen in this view - but is stored in the database nonetheless. Additionally, user have the option to add a new thought or to go to the map and explore the thoughts at their corresponding locations.

“Add Thought Activity” 
Here the user has the opportunity to add their own thought and the corresponding emotion by using the drop down menu. By clicking on the “Get my location” button, the GPS location of the user is called. When the user is satisfied with their input, they can click the “Map my thought” button, which consequently saves the thought and all the corresponding data from the user input in a database. If this worked, the user will get a message saying “Added successfully”.
