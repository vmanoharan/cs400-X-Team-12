# X-Team 12 Style Guide

<brief description of your team's opinion or philosophy regarding Style Guides>

## Naming conventions

<brief statement describing your team's naming conventions>
### Examples

* interfaces: Captalize each word within the name no spaces (ex. SearchTreeADT)

* classes: Captalize each word within the name no spaces (ex. BalancedSearchTree)

* exception types: Captalize each word within the name no spaces (ex. IllegalArgumentException)

* fields: No underscores, first word lowercase, the rest capitalize the first letter with 
descriptive word choice (ex. numNodes)

* parameters: camelCase or lower case with descriptive word choices (ex. item or currentNode)

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

* local variables: camelCase (ex. numNodes, root)

* instance constants: All capitalized letters (CONSTANT)

* class constants: All capitalized letters (CONSTANT)

## Commenting style for public and private members of a class or interface:

<brief statement of your team's commenting style>

### Examples

* classes
  according to javadoc
  /** 
  * ...
  */
* fields
  double slash for fields
  int size; //size of tree
* constructors
  according to javadoc
* methods
  according to javadoc
* coding style (brackets, horizontal, and vertical spacing) for:
  Open curly brackets and close ones right under the if, while, ect.
  all the condtions for following have a space between each word, variable, <,>,==, ect.
  the contents of the if, while, ect. should be 4 spaces or tab over.
  all contents of the if statment are in the line following the bracket
  * if statements
    if(x == 5)
    {
      ...
    }
  * switch statement
  * while loops
  * for loops
  * enhanced for loops
