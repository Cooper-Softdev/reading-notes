# Reading

## Stacks and Queues: Magic the Gathering and Dungeons and Dargoons.

### Stacks

In Magic the Gathering, the stack is where spells and abilities are put when they are played and where they wait to resolve. 
This is similar to a stack in programming. When you cast a spell in Magic, it goes on top of the stack. 
If you cast another spell before the first one resolves, it goes on top of the first spell in the stack. 
This is similar to the "push" operation in a programming stack, where items are added to the top.

When spells resolve in Magic, they do so from the top of the stack downwards. 
The last spell you cast is the first one to resolve. This is similar to the "pop" operation in a programming stack, 
where items are removed from the top.

When we do the "Peek" operation this is similar to the ability "Scrying" in MtG. This allows you to look at the top card of your library without drawing it.
This is almost identical to the "peek" operation in the programming stack, where you can look at the top item without removing it. I bet they scried all over
them punch cards looking for bits to put into their stupid little card game.

So, in both Magic and programming, the last item added to the stack is the first one to be removed, 
which is why we say stacks follow a "Last-In, First-Out" (LIFO) principle. Also be sure to Scry as often as possible.

### Queues 

This one is a bit more difficult to explain via Magic, it would essentially just be a turn order. First players goes then the next and so on.

So a better analogy might be Dungeons and Dragons. In D&D or Patherfinder or almost any other TTRPG, when a combat encounter happens you "roll for initiative"
to see who will go first, as well as the enemy combatants. This creates a queue and as players take their turn they are dequeing and going to the back of the line... or dying.

  + Enqueue Operation (Joining the Combat): When a new character or creature joins the combat, 
    they roll for initiative and are added to the turn order based on their roll. This is similar to the enqueue operation in a programming queue,
    where items are added at the end.

  + Dequeue Operation (Taking a Turn): The character or creature with the highest initiative roll takes their turn first. 
    After they complete their turn, they are effectively removed from the front of the queue, and the character or creature 
    with the next highest initiative roll takes their turn. This is similar to the dequeue operation in a programming queue, 
    where items are removed from the front.

So, in both D&D and programming, the first item added to the queue (the character or creature with the highest initiative roll) 
is the first one to be removed (to take their turn), which is why we say queues follow a "First-In, First-Out" (FIFO) principle.
