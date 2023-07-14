# Linked Lists

A linked list is a way to make a list data points in which one "node" in the list points to the one before it and the next one after. 
Like finding clues to a treasure map, or that Geo tagging game. You find a node using the link from the last node, 
and that new node gives you the clue (link) to find the next one, and each time you're getting some more data.


The most common use for a linked list that most people know is a Spotify playlist, each node will contain a link to the 
song from the server, and when the song is done it has an address inside the node that points to the next song and which 
server it's on, and will play it. It's also used for Undo functionality within programs. 


The usefulness for this is mostly when you don't need to traverse the entire node structure to find something within it.
One just needs to step-through the list, instead of parsing and inserting in the middle.
When going from node to node is the most beneficial. Like Spotify playlists, Undo, and even your back button inside the browser.
Of course you can parse the entire linked list and choose an individual node within it, if that happens the node before and after will get updated.
