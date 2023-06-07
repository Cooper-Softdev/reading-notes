# Reading 03

## React Docs - lists and keys

1. Map returns a new array with the results of the function that is being invoked on each index of another array.
2. To loop through an array and display each value in JSX in React you'd have to use a `key` prop.
3. Each list item needs a unique `key`.
4. The `key` provides context for React to know which parts to change during reconciliation. Arrays can be modified so the index may change for a particular item and this may cause issues with updating the items in the list.

## Spread Operator

1. The spread operator is a syntax within JS that allows you to take an object, or array and combine them.
2. Spread Operator can be used for concatenating arrays, or adding a few items into a list when using .push would be inadvisable for whatever reason, combing multiple objects together like racerObj = {...raceCarObj, ...driverObj}, and lastly you can use it to change props into a component.
3. firstArr = [1, 2, 3] secondArr = [9, 4, 5] firstnsecond = [...firstArr, ...secondAarr];
4. anArr = [1, 2, 3]; itemToAdd = 4; addedItemArr = [...anArr, itemToAdd];
5. carObj = {wheels, frame, engine, fuel}; driverObj = {driver, racesuit, helmet, gloves}; raceReadyObj = {...carObj, ...driverObj};

## Passing Functions between Components

1. The first step was to connect the increment function to the / as a prop so the state can update it when the funciton is called? Something like that.
2. The increment function is a shorthand for the i ++ functions we've been writing.
3. Pass a method from parent to child as a prop.
4. If there is a props method like hello, it can be be invoked via something like a click={props.hello}.
