# X-Team NN Style Guide

<brief description of your team's opinion or philosophy regarding Style Guides>

## Naming conventions

<brief statement describing your team's naming conventions>
### Examples
<<<<<<< HEAD
* interfaces: Captalize each word within the name no spaces (ex. SearchTreeADT)

* classes: Captalize each word within the name no spaces (ex. BalancedSearchTree)

* exception types: Captalize each word within the name no spaces (ex. IllegalArgumentException)

* fields: No underscores, first word lowercase, the rest capitalize the first letter with 
descriptive word choice (ex. numNodes)

* methods: camelCase and underscore basis (ex. isEmpty)

* parameters: camelCase with descriptive word choices
=======
* interfaces
  Captalize each word within the name no spaces
* classes
  Captalize each word within the name no spaces
* exception types
  Captalize each word within the name no spaces
* fields
  No underscores, first word lowercase, the rest capitalize the first letter with descriptive word choice
* methods
  Camel and for tests we do have underscores
    public void search() throws Exception
    {
    ...
    }
    public void getHeight() throws Exception
    {
    ...
    }
    public void test01_Height_On_Empty_Tree()
    {
    ...
    }
* parameters
  camel case with descriptive word choices
>>>>>>> 94d81dec2404e461450ec26148c6d177b86b973e
* local variables
  camel case
* instance constants
  All capitalized letters
* class constants
  All capitalized letters

## Commenting style for public and private members of a class or interface:

<brief statement of your team's commenting style>

### Examples

* classes
* fields
* constructors
* methods
* coding style (brackets, horizontal, and vertical spacing) for:
  Open curly brackets and close ones right under the 
  * if statements
  * switch statement
  * while loops
  * for loops
  * enhanced for loops
