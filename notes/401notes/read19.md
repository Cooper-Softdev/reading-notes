# Reading

## Pure Functional Programming and YOU

1. Can you change the state of a data structure using functional programming?

No, datastructures in functional programming are typically? immutable. Meaning you cannot change the state of a data structure directly. You instead would
need to perform operations on them to return new data structure with the changes to state.

2. Define purely functional programming.
Purely functional is a programming ideology that treats all code as the evaluation of a mathematical function. I wish I knew exactly what this meant, but
I've seen a lot of videos on it. Haskell videos mostly. The output value of a function depends on the aruments that are input, and will always return the
same values, given the same input, unlike in regular languages like Java which do not always return the same values.

I asked GPT to give me an example of this.
``` Haskell
import System.Random
import Data.Time.Clock.POSIX

randomNumber :: IO Int
randomNumber = do
    time <- round `fmap` getPOSIXTime
    return $ fst (randomR (1, 100) (mkStdGen time))
```
In Haskell you must use an I/O from the system to generate seeds that can then be used to generate a random number. But in Java you can use Random();

This was confusing as I was curious what a function looks like that doesn't return the same value for the same given input, so here's a Java example, which seems
obvious in hindsight. BufferedReader with readLine(); will read one line, then when passed the same file.txt as an argument it will read the next line, therefore
returning a different value for the same given input to a function.
``` Java
BufferedReader reader = new BufferedReader(new FileReader("file.txt"));
String line = reader.readLine();
```

3. How do you think purely functional programming will differ from the programs you’ve written so far in this course?

   Since this seems like some long extinct advanced alien tech, I'm going to guess, lots.
