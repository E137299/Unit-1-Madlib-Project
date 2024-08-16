# Unit 1: Madlib-Project


Notes: [print(), variables, input(), casting, math and string operators](https://colab.research.google.com/drive/1JSrOECf5FeozLVAlGu7IDqGoR6bf3mR1?usp=drive_link)

**Objective:**  
Write a Python script that generates a fun and creative story (Madlib) based on user input. The program will ask the user for different types of words (e.g., nouns, verbs, adjectives, numbers) and then insert those words into a pre-written story template.

**Requirements:**

1. Your story must include **at least ten variables** where the user will provide inputs.
2. Among these ten variables:
   - **Two variables must be numbers** (e.g., an age, a year, a quantity).
   - You must perform at least one **mathematical operation** on these numeric variables (e.g., addition, subtraction, multiplication).
   - The **result of the mathematical operation** must be included in the final story output.

**Instructions:**

**Step 1: Create a Story Template**

1. Write a short, creative story template with blanks for words such as nouns, verbs, adjectives, numbers, etc.
2. Ensure that your story template includes a place to insert the result of the mathematical operation.
   - For example:
     ```
     Last summer, I went to the [place] with my [relative]. We stayed there for [number] days, and it was [adjective]! During the trip, we saw [number_of_animals] animals, which is [half_number_of_animals] times less than expected!
     ```

**Step 2: Prompt the User for Input**

3. Ask the user to provide words or numbers for each blank in your story:
   - Prompt the user for a noun, a verb, an adjective, two numbers, and other types of words your story requires.
   - Store each user input in a separate variable.

**Step 3: Perform a Mathematical Operation**

4. Perform at least one mathematical operation using the two numeric inputs. For example, you could calculate the total number of items, the difference in years, or multiply a quantity.
5. Store the result of this mathematical operation in a new variable.

**Step 4: Generate the Madlib**

6. Use the user's input to fill in the blanks in your story template. You can use string concatenation or f-strings to insert the user's words and the result of your mathematical operation into the template.

**Step 5: Output the Final Story**

7. Print the final story with the user's words and the result of the mathematical operation inserted into the appropriate places.

**Example**

Here’s an example of how your program might run:

```python
# Example story template:
# "Last summer, I went to the [place] with my [relative]. We stayed there for [number] days, and it was [adjective]! During the trip, we saw [number_of_animals] animals, which is [half_number_of_animals] times less than expected!"

place = input("Enter a place: ")
relative = input("Enter a relative's name: ")
adjective = input("Enter an adjective: ")
number = int(input("Enter a number (days): "))
number_of_animals = int(input("Enter a number of animals: "))

# Perform a mathematical operation
half_number_of_animals = number_of_animals // 2

madlib = (f"Last summer, I went to the {place} with my {relative}. "
          f"We stayed there for {number} days, and it was {adjective}! "
          f"During the trip, we saw {number_of_animals} animals, which is "
          f"{half_number_of_animals} times less than expected!")

print("\nHere is your Madlib story:")
print(madlib)
```

**Sample Output:**

```
Enter a place: beach
Enter a relative's name: Aunt Lisa
Enter an adjective: amazing
Enter a number (days): 7
Enter a number of animals: 20

Here is your Madlib story:
Last summer, I went to the beach with my Aunt Lisa. We stayed there for 7 days, and it was amazing! During the trip, we saw 20 animals, which is 10 times less than expected!
```

**Step 6: Customize Your Story (Optional)**

8. Get creative! Feel free to customize the story template, add more blanks, or even create multiple templates that the user can choose from.

