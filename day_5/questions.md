## Day 5 Questions

1. What is a Hash, and how is it different from an Array in Ruby?

    A hash is an unordered collection where the data is organized into "key/value pairs". Arrays are usually lists of data.

1. In the space below, create a Hash stored to a variable named `pet_store`.  This hash should hold an inventory of items and the number of that item that you might find at a pet store.

    pet_store = {dog food: 4, cat food: 6, dog beds: 3, cat beds: 1}

1. given the following `states = {"CO" => "Colorado", "IA" => "Iowa", "OK" => "Oklahoma"}`, how would you access the value `"Iowa"`?

    states[:IA]

1. With the same hash above, how would we get all the keys?  All the values?

    states.keys
    states.values

1. What is another example of when we might use a hash?  In this case, why is a hash better than an array?

    When you have to take one value and "look up" another value.

1. What questions do you still have about hashes?
