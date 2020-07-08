# Explaining the Mid-Term.

### capitalizeSentences

1. Make a new empty string that will hold our result.
2. Loop through each index in our paragraph.
3. If the paragraphs character at the current index of the loop -2 is equal to a period or the index is 0.
4. Add to the result string the character at our current index, but uppercased.
5. Otherwise:
6. Add the lowercased version instead.
7. Return the result when loop is over.

### isValidPassword

1. Make an if statement that checks if the password argument length is less than 12 characters.
2. If it is, we want it to return false. The password must be more than 12 characters.
3. Run a for loop to loop through the password indexes.
4. Use another if statement to check if any index equals to a space so it can return false if it does.
5. Now return true so if everything checks out it will allow password.

### makeHalfSquares

1. Create an empty array that will hold our results.
2. Loop through each index (which will be numbers) in the array.
3. Below our for loop we want to push results into our empty array.
4. Inside the brackets of our push we want to square the indexes and then divide them in half.
5. Then return our results.

### countAs

1. Make a count variable starting at 0. We will be using this to count the grades above 90.
2. Loop through the grades.
3. Check with an if statement that the grade indexes are equal to or greater than 90.
4. Now we want to use our count variable adding 1 to it each time a grade returns true from our if.
5. Return count to see results.

### deleteMiddleCharacter

1. Create a empty string for our results.
2. Use a variable to get the middle index.
3. Make an if statement to check if length is odd.
4. Return string with the slice method to get the index from the middle of the string.
5. Using return again with the slice method for even numbers.

### lastIndexOfSpace

1. Using a for loop, loop backwards to find the index of the last space.
2. Make an if statement using string index to equal to space.
3. Now return the index to get the given number of the last space index.

### hyphenateName

1. Make an empty string for the result.
2. Loop through the string indexes.
3. Use if statement, here we want when the index is equal to the last space index of the name argument, this is where we want the hyphen.
4. Now add the hyphen in the empty string variable.
5. Use else to add name indexes to the empty string.
6. Return the results.


