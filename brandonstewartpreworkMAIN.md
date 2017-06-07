# Turing School Prework

### Task A- Practice Typing:
4/3 <img width="903" alt="typingio1" src="https://cloud.githubusercontent.com/assets/20469703/24640199/6ec83396-18b2-11e7-99c2-7dc46ea57396.png">
4/4
<img width="996" alt="4 4 typing" src="https://cloud.githubusercontent.com/assets/20469703/24682596/b642f6c0-1957-11e7-9284-f630741dcdde.png">


### Task B- Algorithmic Thinking & Logic:
* screenshots of completed sections will be posted in comments

### Task C- Create your Gist:

### Task D- Set up your Environment:

* Did you run into any issues?
- No, I did not.
* How do you open Atom from your Terminal?
- atom <filename>
* What is the file extension for a Ruby file?
- .rb
* What is the Atom shortcut for hiding/ showing your file tree view?
- cmd-k, cmd-b or cmd-\
* What is the Atom shortcut for quickly finding a file (fuzzy finder)?
- cmd-t or cmd-p

### Task E- The Command Line:
* screenshots of your terminal after each exercise will be posted in comments

**Day One Questions:**
* What does pwd stand for, and how is this command helpful?
- Present working directory - it allows you to tell what directory you are in on the CLI
* What does hostname tell you, and what shows up in YOUR terminal when you type hostname?
- It tells you the FQDN of your PC.

### Task F- Learn Ruby:

#### Option 1 Questions:
**IRB**
* How do you start and stop irb?
- To start it you type 'irb' in the command prompt.  To exit, type 'exit'
* What might you use irb for?
- To test single lines of ruby code without saving it to a particular file

**Variables**
* How do you create a variable?
- You can create it by initializing it with a value.  ( apples = 3 )
* What did you learn about the rules for naming variables?
- Local, instance, class, and other variables start with different characters.  The starting character defines the scope of a variable in Ruby
* How do you change the value of a variable?
- reassign it or use a method to manipulate the value such as variable.reverse

**Datatypes**
* How can you find out the class of a variable?
- variable.class
* What are two string methods?
- .reverse and .upcase.  you can find methods for a string by typing stringvariablename.methods
* How can you change an integer to a string?
- integervariable.to_s

**Strings**
* Why might you use double quotes instead of single quotes in Ruby?
- To allow for string interpolation
* What is this used for in Ruby: #{}?
- To call a variable.  "this is my #{stringvariable}."
* How would you remove all the vowels from a string?
- str.gsub(/[aeiou]/i, '') - shamelessly stolen from the internet.  

**Input & Output**
* What do 'print' and 'puts' do in Ruby?
- They both print the output, but puts adds a newline.
* What does 'gets' do in Ruby?
- Gets receives a user input.
* Add a screenshot in the comments of the program you created that uses 'puts' and 'gets', and give it the title, "I/O".

<img width="508" alt="i o" src="https://cloud.githubusercontent.com/assets/20469703/24684499/aca807f2-1963-11e7-8e35-d75f26a9cf3f.png">


**Numbers & Arithmetic**
* What is the difference between integers and floats?
- A float contains decimals, whereas an integer is a whole number
* Complete the challenge, and post a screenshot of your program in the comments with the title, "Numbers".

<img width="661" alt="screen shot 2017-04-04 at 9 42 34 pm" src="https://cloud.githubusercontent.com/assets/20469703/24688802/a625ffbc-197f-11e7-8120-4eaa905fbcdb.png">

**Booleans**
* What do each of the following symbols mean?
  * ==
  - equivalence
  * >=
  - greater than or equal to
  * <=
  - less than or equal to
  * !=
  - not equal to
  * &&
  - boolean AND operator
  * ||
  - boolean OR operator
* What are two Ruby methods that return booleans?
- true and false

**Conditionals**
* What is flow control?
- A way of controlling the execution flow of a script or program.  Examples of flow control are else, for, while, and if statements.
* What will the following code return?
- The string Not many apples

```
apple_count = 4

if apple_count > 5
  puts "Lots of apples!"
else
  puts 'Not many apples...'
end
```
* What is an infinite loop, and how can you get out of one?
- A loop that contains a condition that does not meet the criteria for ending the loop.  You can end this by stopping the execution of the program through ctrl-c or the UI.
* Take a screenshot of your program and terminal showing two different outputs, and post it in the comments with the title, "Conditionals".

<img width="653" alt="screen shot 2017-04-05 at 9 16 17 pm" src="https://cloud.githubusercontent.com/assets/20469703/24736409/2308e434-1a45-11e7-86ff-839fec1a4dba.png">


**nil**
* What is nil?
* A nil is Ruby for a null.
* Take a screenshot of your terminal after working through Step 4, and post it in the comments with the title, "nil".

<img width="241" alt="screen shot 2017-04-05 at 9 30 47 pm" src="https://cloud.githubusercontent.com/assets/20469703/24736752/2c5ae030-1a47-11e7-904a-cb1590c8d019.png">


**Symbols**
* How can symbols be beneficial in Ruby?
- Symbols are useful for use with groups of variables that hold a similar structure.  A good example of this is using a symbol to hold :citytemperature.  If you use the zip code, temp, and city name string variables it is much more efficient in terms of memory to store a symbol that references each value.  This is similar to a dictionary.
* Does naming symbols use the same rules for naming variables?
- Yes.
* Take a screenshot of your terminal after working through Step 4, and post it in the comments with the title, "Symbols".

<img width="262" alt="screen shot 2017-04-05 at 9 38 59 pm" src="https://cloud.githubusercontent.com/assets/20469703/24736943/51f9aabe-1a48-11e7-941f-bc569a9d3c21.png">


**Arrays**
* What method can you call to find out how many elements are in an array?
- Array.length
* What is the index of pizza in this array: ["pizza", "ice cream", "cauliflower"]?
- [0]
* What do 'push' and 'pop' do?
- push adds an element to the end of an array
- pop returns the last element from an array and deletes it from the array

**Hashes**
* Describe some differences between arrays and hashes.
- A hash is basically a dictionary, while an array is an ordered list of objects.  A hash can contain other hashes.
* What is a case when you might prefer an array? What is a case when you might prefer a hash?
- An array is useful if you are storing a list of things that don't share descriptive qualities.
- A hash is useful if there are descriptive qualities of an object or if there are related attributes to the original hash * value.
* * Take a screenshot of your terminal after working through Step 2, and post it in the comments with the title, "Hashes".

<img width="583" alt="screen shot 2017-04-05 at 10 35 56 pm" src="https://cloud.githubusercontent.com/assets/20469703/24738070/603fe3ce-1a50-11e7-88fc-576ca64e3737.png">


### Task G- Prework Reflection:
* Were you able to get through the work? Did you rush to finish, or take your time?
- I took my time.  Most of the concepts were already familiar to me since I have some experience with C#.  Most of my time was spend understanding the Ruby syntax.  I had a particularly tough time understanding how to encase a conditional loop in Ruby using the 'end' statement.
* What are you most looking forward to learning more about?
- I really like the idea of symbols.  They aren't seen in other languages as much, but I feel like this could make a large iteration in a program run very efficiently.
* What topics would you most like to see reinforced by instructors?
- Coding style is particularly important.  I was briefly exposed to the idea of how to format variable names based on their content.  I think things like that would be very good to reinforce throughout the learning process since they are things that aren't as obvious and help distinguish hobby code from production code.
* What is most confusing to you about what you've learned?
- I was very confused by the 'end' statements in the loops initially, but once I got the conditional challenge working and reviewed my code it started to make sense
* What questions do you have for your student mentor or for your instructors?
- I don't have any questions at this time.




## Pre-work Tasks- One Month Schedule
##### (Note: You will most likely only get to the following sections if you have more than a week for your pre-work. If you are doing the one week pre-work schedule, you may delete this section of the Gist.)

### Railsbridge Curriculum, cont.
* Loops: Take a screenshot of your "Challenge" program, and post it as a comment in your Gist.

<img width="658" alt="screen shot 2017-04-06 at 6 54 03 pm" src="https://cloud.githubusercontent.com/assets/20469703/24781125/72a7cebe-1afa-11e7-9ae2-022dd5aa4835.png">


* What challenges did you try for "Summary: Basics"? Post a screenshot of one of your programs.
* Functions: How do you call a function and store the result in a variable?
First you have to define the function using def function
Once you create the function you can call it by the function name depending on the syntax of the function
* Describe the purpose of the following in Ruby classes: initialize method, new method, instance variables.
* How to Write a Program: Screenhero with your student mentor and share your program. Write a bit about what you found most challenging, and most enjoyable, in creating your program.

### Launch School Ruby Book
* screenshots will be posted in comments
* What are your three biggest takeaways from working through this book?

### CodeSchool
* screenshots will be posted in comments
* What are your two biggest takeaways from working through this tutorial?
* What is one question you have about Git & GitHub?

### Workflow Video
* Describe your thinking on effective workflow. What shortcuts do you think you'll find most useful? What would you like to learn or practice that will most help you improve your speed and workflow?

### Michael Hartl's Command Line Book
As you complete each section, respond to the related questions below (mostly taken directly from the tutorial exercises):
* 1.3: By reading the "man" page for echo, determine the command needed to print out “hello” without the trailing newline. How did you do it?
* 1.4: What do Ctrl-A, Ctrl-E, and Ctrl-U do?
* 1.5: What are the shortcuts for clearing your screen, and exiting your terminal?
* 2.1: What is the "cat" command used for? What is the "diff" command used for?
* 2.2: What command would you use to list all txt files? What command would you use to show all hidden files?
* 3.1: How can you download a file from the internet, using the command line?
* 3.3: Describe two commands you can use in conjunction with "less".
* 3.4: What are two things you can do with "grep"?
