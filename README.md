# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [ ] Create your own version of this repo - Fork
- [ ] Add your TL as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This should contain the link to your completed codepen from part 2 as well as the review questions/answers
  - [ ] Run your usual git commands for adding/committing and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your TL as a reviewer on the Pull-Request
- [ ] TL then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:
1. fork this codepen https://codepen.io/BritHemming/pen/eYYEoPa?editors=1100
2. You will be marking up all of the HTML and styling it to look like this: https://codepen.io/BritHemming/full/jONmxOm using CSS
* this should be review from yesterday/ extra practice
3. After you are finished please copy the review questions into your .txt file and answer them
4. don't forget to add, commit and push your changes.


## Stretch
Stretch Review questions: 
    1. What is the difference between an inline element and a block element?
    2. What happens when an element is positioned absolutely? 
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
    5. In your own words, explain the box model. What is the fix for the box model? 
Stretch Git Tasks
- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independently research the following topics to learn more about Git.
  - [ ] Research and understand what a `merge conflict` is and how to resolve it.
  - [ ] Research the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the master branch.
  - [ ] Research the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and amends previous commits you have made.

- [ ] Research and set up a Graphical User Interface (GUI) Git console. 

- [ ] Research and setup SSH keys with GitHub, so that you do not need to input your username/password each time you push. 


    1. What is Semantic HTML? Semantic HTML gives your code meaning and structure by using the proper elements. 
   
    2. What is HTML used for? HTML is the Hypertext Markup Language and it is used to create pages to be displayed on the internet. 
   
    3. What is an attribute and where do we put it? Attributes are properties used to provide additional informatin about an element. Attributes are defined within the opening tag, after an element's name.
    
    4. What is the h1 tag used for? How many times should I use it on a page? h1 tag is the primary heading of a page or section, and subsquent headings should use <h2><h3>...<h6>.

    5. Name two tags that have required attributes? Two tags that have required attributes are img src and a href. 

    6. What do we put in the head of our HTML document? Metadata[<title><style><meta><link><script>] is put in the head of HTML. 

    7. What is an id? id an attribute that specifies a unique id for an element.

    8. What elements can I add an id to? any

    9. How many times can I use the same id on a page? one unique id that belongs to that single element.

    10. What is a class? used to define equal styles for elements with the same class name.

    11. What elements can I add a class to? inline elements 

    12. How many times can I use the same class on a page? can be used multiple times

    13. How do I get my link to open in a new tab? with an a href attribute

    14. What is the alt attribute used for? To give the link a description and for easier accessiblity.

    15. How do I reference an id? with the #

    16. What is the difference between a section and a div? If content adds to the document outline and represent a thematic group content then you'll use section whereas, if it's being grouped for styling purposes only and doesnt provide value to the the document then div would be best used. 

    17. What is CSS used for? Cascasding style sheet is used to give your page design.

    18. How do we select an element? Example - every h2 on the page #h2{;}

    19. What is the difference between a class and an id? - A class selector is a name preceded by a . and an id selector is a name preceded by a #. The difference between an id and class is that an id can be used to identify one element and a class can be used to identify more than one. Ex. .p{;} vs #nav{;}

    20. How do we select classes in CSS? .p {font-weight:bold;}

    21. How do we select a p element with a single class of “human””? human p{;}

    22. What is a parent child selector? When would this be useful? the parent child selector is placed between two css selectors. it matches only those elements matched by the second selector that are the direct children of elements matched by the first. it is useful because it is stricter.

    23. How do you select all links within a div with the class of sidebar? by using descendant selectors. #sidebar a:link {;}

    24. What is a pseudo selector? is a selector that selects elements that are in a specific state.

    25. What do we use the change the spacing between lines? line-height property

    26. What do we use to change the spacing between letters? letter-spacing

    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize? text-transform

    28. How do I add a 1px border around my div that is dotted and black? div {border-style: dotted; border-width: 1px; border-color: black;}

    29. How do I select everything on the page? * selector

    30. How do I write a comment in CSS? /* this is how */

    31. How do I find out what file I am in, when I am using the command line? 

    32. Using the command line - how do I see a list of files/folders in my current folder? ls

    33. How do I remove a file via the command line? Why do I have to be careful with this? rm, and you have to be careful because you can delete something thats you cant recover.

    34. Why should I use version control? 

    35. How often should I commit to github? As often as needed, but not for every change.

    36. What is the command we would use to push our repo up to github? git push

    37. Walk me through Lambda's git flow. 
    Fork repo, Clone repo git clone URL, make changes and run git status, the stage the  changes git add, commit the changes using git commit -m "our message" git push to 

Stretch Questions

    1. What is the difference between an inline element and a block element?
    Inline elements do not begin on a new line. They fall into the normal flow of a document, lining up one after the other and only keep the width of their content, whereas, block-level elements begin on a new line, stacking one on top of the other and occupy any available width.

    2. What happens when an element is positioned absolutely? it is positioned automatically to the starting point of its parent element.

    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 

    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default? 3 elements that are display block are: <div> <h1>-<h6> <p> 2 elements that are display inline are: <span> <a> and 1 element that is <li>.

    5. In your own words, explain the box model. What is the fix for the box model? The box model describes the structure of page elements as they are laid out on the web page. Margin, padding, and border.
