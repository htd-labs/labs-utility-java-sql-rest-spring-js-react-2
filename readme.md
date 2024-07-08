# Welcome to LabLoader
This repository is a utility to help you access Revature coding labs.

# Labs
You can run the Labs utility using the command `java -jar labs.jar`, see below the list of labs for usage guide or
use the command 'help'.

# Java
- java-helloworld
- java-methods
- java-parameters
- java-returntypes
- java-methodparameters
- java-combinestrings
- java-comparisons
- java-ifstatement
- java-instantiation
- java-introtooop
- java-constructors
- java-whileloop
- java-forloop
- java-booleanoperators
- java-arrays
- java-lists
- java-sets
- java-exceptions
- java-uncheckedexception
- java-throwcustomexception
- java-casting
- java-math
- java-statickeyword
- java-bankaccount
- java-map
- java-queue
- java-stack
- java-stringmethods
- java-otherstringmethods
- java-parentobjectclassmethods
- java-overriding
- java-interfaces
- java-generic
- java-advancedbooleans
- java-streams
- java-reflections
## Java coding challenges
- cc-add
- cc-subtract
- cc-greaterorlesser
- cc-evenorodd
- cc-hardcodedlogin
- cc-returnarraycontents
- cc-setallarrayelementston
- cc-fizzbuzz
- cc-guessinggame
- cc-arraysum
- cc-average
- cc-getmax
- cc-contains
- cc-doesnotcontain
- cc-indexof
- cc-issorted
- cc-arraysareequal
- cc-maxminusmin
- cc-containsduplicates
- cc-pyramid
- cc-search2darray
- cc-returnlongeststring
- cc-removeallcharacter
- cc-parsepathparameter
- cc-deserialization
- cc-json
- cc-insertposition
- cc-istheresum
- cc-arrayabsolutevalue
- cc-piglatin
- cc-combinearrays
- cc-wordcount
- cc-isogram
- cc-fibonacci
- cc-reverseastring
- cc-largestsum
- cc-charcomparison
- cc-mostcommoncharacter
- cc-stringispalindrome
- cc-subarray
- cc-wordcountmap
## SQL
- sql-createtable
- sql-droptable
- sql-insert
- sql-selectall
- sql-primarykey
- sql-selectwhere
- sql-update
- sql-delete
- sql-selectwhereandor
- sql-grocerylist
- sql-foreignkey
- sql-innerjoin
- sql-outerjoin
- sql-selectcolumns
- sql-orderby
- sql-truncate
- sql-altertable
- sql-aggregatefunctions
- sql-groupby
- sql-createview
## Javalin
- jav-creatingendpoints
- jav-statuscodes
- jav-pathparameters
- jav-requestbody
## Spring
- spr-di
- spr-applicationcontext
- spr-beanscopes
- spr-boot
- spr-restcontroller
- spr-entity
- spr-lombok
- spr-jpacrud
- spr-fitnessapi
- spr-requestparam
- spr-relationships
- spr-jpamultiplicity
- spr-namedqueries
- spr-artapi
- spr-query
- spr-responseentity
- spr-transactional
## HTML/CSS/JavaScript
- js-homepage
- js-cssinline
- js-cssselectors
- js-boxmodel
- js-buttonclick
- js-buttoncounter
- js-input
- js-ifstatement
- js-login
- js-attributes
- js-typecoercion
- js-truthyfalsy
- js-forloop
- js-arrays
- js-callbackfunction
- js-appendingelements
- js-arraymethods
- js-objects
- js-eventobject
- js-eventlistener
- js-errors
- js-asyncawait
- js-fetch
- js-fetchimage
- js-spreadrest
## React
- react-components
- react-props
- react-state
- react-events
- react-conditional-rendering
- react-component-styling
- react-lists-and-keys
- react-routing
- react-forms
- react-use-effect
- react-model-classes
- react-axios
- react-lifting-state
- react-context
- react-higher-order-components
## Optional Java labs
- java-sort
- java-binarysearch
- java-customserializer
- java-encryption
- java-urlvalidation
## Optional Java coding challenges
- cc-anagram
- cc-bracketsaroundperiod
- cc-prime
- cc-returnduplicates
- cc-reverseallwords
- cc-reversearray
- cc-rotate
- cc-secondhighest
- cc-secondstohhmmss
- cc-movezeroes
- cc-issubset
- cc-parentheses

# How to use
## CLI
This utility will function as a Command Line Interface written as an executable jar. A jar is like a set of Java classes that have been packaged together for easy transport & use. you can start it up opening the terminal in your IDE and using the command
`java -jar labs.jar`
When you've run the Jar correctly, a set of text should appear instructing you how to open up a lab. labs are not case sensitive, so, for instance, if you'd like to open the java-helloworld lab, you can use the command 
`open java-helloworld`
## Github configuration
Before you begin the labs at all, you will need to have a personal github account, which is able to push, properly installed & configured on your computer. You can test whether the utility is properly configured using the command
`check`
after you have run the labs jar as shown above.
## Other commands
You also have the commands
`help`
`clear` (this will destroy your labs folder without saving, if you'd like to reopen a lab in its previous state)
`save` (this will manually save your lab, although your progress is already saved whenever you use the open command)
## Unit testing
Many of the labs feature unit testing and TDD. Unit testing is a strategy used extensively in the professional world consisting of some code that can automatically run to ensure that some part of your code runs correctly. In this case, the test cases are there to quickly verify if you've successfully completed the lab. Because the labs provided use a variety of technologies, there are a couple different ways in which the labs need to be run.
### HTML/CSS/JavaScript labs
If tests are present, they are tested using Maven, JUnit, and Selenium. Selenium requires a chrome web driver that might not be properly configured for your environment, so you should instead opt for manual testing via the browser. The HTML file associated with any particular lab may be opened directly in your browser: you can open the HTML file in your file explorer (either by navigating to your workspace's folder or finding the option to do so by right clicking on the file in your IDE.) After that, you can open any HTML file in your browser. The browser will display all the information you need to test your lab, and you can simply refresh the browser to display the most recent changes from your IDE.
### React labs
You will be required to have a working version of node, which will come with npm. You can verify that it is installed npm --version. You will need to start the labs using npm start. These labs do not have tests written yet, so you will need to rely on feedback from the broswer.

lab content & labloader authored by ted balashov, do not distribute content.

https://github.com/RevvingUpThatHill