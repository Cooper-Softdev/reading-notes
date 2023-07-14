# Linked Lists

A linked list is a way to make a filepath of sort for data so one "node" in the file path points to the next one. 
Like finding clues to a treasure map, or that Geo tagging game. You find a piece of data using the data from the last node, 
and that new node gives you the clue to find the next one, and each time you're getting some more data.


The most common use for a linked list that most people know is a Spotify playlist, each node will contain a link to the 
song from the server, and when the song is done it has an address inside the node that points to the next song and which 
server it's on, and will automatically play it. It's also used for Undo functionality within programs. 


The usefulness for this is mostly when you don't need to traverse the entire node structure to find something within it. 
When going from node to node is the most beneficial. Like Spotify playlists, Undo, and even your back button inside the browser.
