# What kind of Text do we use when applying it to an HTML or CSS document?

## What are the two types of markup?

1. **Structural Markup** These are specific elements that are used to describe paragraph and heading tags.
2. **Semantic Markup** These tags will provide more information that is needed for the webpage. Some ways that it provides more information are: where you need to place emphasis in a sentence and acronym meanings.

### What are some Tags

1. **Headings h1-h6**
- When utilizing a header, just remember that the h1 header is used for the main heading of the website and the h2 through h6 headers are used for subheadings. Also depending on which header you use the content will be displayed in different sizes; h1 being the biggest and h6 being the smallest that the content will be displayed. 

2. **Paragraph tags or "P Tag" for short** 
When you are trying to create a paragraph in your website, you will need to have an opening P tag, then you will type in the information that you want for your paragraph, and then the closing p tag.

3. **Bold and Italic**
- These tags are used when trying to bold or italicize a word or phrase. 

4. **Superscript and Subscript**
-Superscript (Sup): This tag is used when trying to contain specific characters in the superscript. For example: dates, mathematical equations or concepts.
-Subscripts (sub): This tag is used when trying to contain specific characters in the subscript. For example: Foot notes, or specific fomulas like a chemical formula Na or Co2.

**Remember that the closing tag will also have an extra forward slash in it** (/)

### Visual Editors and Code Views

- **Visual Editors** These sometime are similar to word processors.
- **Code Views** This is the code created by the Visual Editor and this allows you to manually edit the document and it allows you to also enter in new code. 

## Introducing CSS

### What does CSS do?
- *CSS allows us to create complex rules that are specific on how content of elements are supposed to be displayed on the website or document.*
- For example: **you can change the background of a specific box for the page, an element inside of the body element like the h1 or p tag. You can add boarders and and boxes that you can change the width, height, or the font color.** 

### What is external CSS?
- Link tag: this tag lets the browser know where to find the specific file that you used to add whatever style to the page. 
- href tag: Specific path to the CSS file. 
- type: This is used to specify what type of document is linked to the document.  
- rel: When using the link, it will tell you the relationship between the HTML page and the file it's linked to. 

### What is internal CSS?
- Style: This element tells you what attributes are being used and what specific style is being used in the CSS document. 

### What are some Selectors?
1. **Universal Selector** This is applied to all elements in the document. (Ref HTML and CSS book page 238)
2. **Child Selector** Matches an element that is a direct child of another. (Ref HTML and CSS book page 238)
3. **Adjacent Sibling Selector** Matches an element that is the next sibling of another. (Ref HTML and CSS book page 238)

**Remember that the closing tag will also have an extra forward slash in it** (/)

## Basic Javascript Instructions
- What is a Script and what is its purpose? 

- It is a set of instructions that the program will follow one-by-one and every single step is known as a statement. 
- Always remember that a step will be ending with a semicolon. 
- Remember to always add comments to your code, in the long run it will make it easier for everyone to understand what the code is doing. 

## What are Variables and how is it important?

A variable is a temporary storage that stores some information from the script. It is important because the data stored can be changed every time a script runs. 

Variable example: var quantity: "var" is the variable keyword and "data" is the variable name.

To assign a value to a variable it would look like this: data=3; "data=variable name, = is the assignment operator, 3= variable value"

## Different Data Types

1. Numeric data type: This data type handles numbers, "5.25".
2. String data type: This data type is constructed of letters and other characters, " 'what's up, Chris".
3. Boolean data type: This data is strictly true or false.

- *Remember that variables cannot use keywords*

## What are Expressions and Operators?

*An expression evaluates into a single value and there are two types of expressions*(Reference Javascript book page 74):

1. Expressions that assaign a value to a variable.
2. Expressions that use tow or more values to return a single value.

- *Expressions need operators because they allow programmers to create a single value from one or more values*.
- **Assignment Operators**: Assign a value to a variable
- **Arithmetic Operators**: Perform basic math. 
- **String Operators**: Combine two strings.
- **Comparison Operators**: Compare two values and return true or false.
- **Logical Operators**: Combine expressions and retun true or false.

## Loops
*Check the condition, once it comes back true then a code block will run.*

**The three different types of loops**
1. For loop: is when you run a code a specific number of times. 
2. While loop: is used when you dont know how many times you should be running the code. 
3. Do While loop: This loop will continue to run the loop in a curly braces even if the condition comes back as false. 