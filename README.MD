JAVA SCRIPT -
JS CODE MUST BE INSIDE A SCRIPT <SCRIPT>INSIDE HERE JS CODE </SCRIPT>
    -PRogramming language  we use to create dynamic and interactive web pages 
JS offers user interactivity and reactivity.

language that runs on the browser ON JS engines e.g V8,SpiderMonkey

INTERACTIVITY-enabling a user to interact with a webpage,e.g click,scrolling, submit,typing =listen to user events
REACTIVITY- Making our pages dynamic where a page changes by itself based on data without full reloads.

VARIABLE- NAMED CONTAINER USED TO STORE VALUES: 
HOW TO DECLARE VARIABLES USE; THE BELOW 
            LET- allows you to resign values to variables 
            CONST-Constant -NO reassignement
            VAR-Outdated and replaced by LET-FIND OUT WHY
JS DATA TYPES: Strings,Numbers,Booleans,

JAVA SCRIPT ARRAYS:
ARRAY-NAMED CONTAINER USED TO STORE MULTIPLE VALUES OF DIFFERENT TYPES 
    -An array is a special variable/data structure used to store/hold more than 1 value at a time.-This array is equivalent to a list in PYTHON.
        PROPERTIES:
            1.-they are ordered.-elements can be accessed with index which is 0-based.
            2.-its Mutable-it can be chnaged/altered eg change in value, size where increase or decrease,update
            3.-stores multiple items of different data types -can store string, numbers,booleans,bigint,list
ARRAYS are dynamic which means you can add,remove or modify elements-elements are comma separated.


                WHY USE ARRAYS:
    -Cause it can store multiple items,have ordered items, can manipulate multiple items, do iteration,

SYNTAX- let array_name=[ values ]    

ARRAY- ONE DIMENSIONAL (1DR) =[1,2,"JOHN DOE"]
^& MULTIDIMENSIONAL(2DRA)=

                    ARRAY OPERATIONS
    -Actions that can be perfomed/TAKEN to manipulate arrays/This operations can range from creating arrays,updating values, adding or removing values e.tc        
   1. Accessing Elements in an array      
   2. Update or Modify elements in an array- use indexes
   3. Checked the size of an array
   4. Add elements to an array
            -add elements at the end.-(.push)
            -add elements at the start of an array-(.unshift)
   5. Remove elements from an array
            -Remove element at the end of an array(.pop)
            -remove element at the start of an array(.shift)     

TASK -SLIDE 53,69,70 
USE SPLICE TO ADD AND REPLACE ELEMENTS
USE SORT -GIVE ME THE OBSERVATION ON WHAT HAPPENS ON SORTING NUMBERS.1000,200,300,600          


REMOVING ELEMENTS SPLICE()
    1.Can Remove
    2. Can add 
    3. can replace elements



OBJECTS
    Are data structures used to store values of data in key value pairs,equivalent to a dictionary in python.e.g key:Value
Key: value -they combine to form a property.
CHARACTERISTIC OF OBJECTS
        1.Store data in Key value pairs.
        2.They are Mutable.
        3.object keys are essentially strings
        4.Values can be of any data type.
        5.They have methods and operations 

KEYS:-Identifiers of the property.
        1.no spacing
            -if your key is to have spaces it needs to be in string form
            full name:"John Doe" - Invalid KEY
            "full name":"John Doe"   - VALID KEY
        2.can contain ,letters,digits and underscore and dollar sign.
        3.Can only start with _or letter.
VALUES:- These are data stored in the above property.


WHY USE OBJECTS/DICT INSTEAD OF ARRAYS:
    1.You can group related data in a single container
    2.use it to store complex structured data.
    3.Represent /model real world entities.
OBJECTS can be created in 2 ways:
    1.Object literal Syntax like the first one in the objects.html/creates key value pairs-RECOMMENDED ONE
    2.Using Object Constructor- built in object() constructor

ACCESSING PROPERTIES:/VALUES 
    1.Using dot(.)notation-
    advantage:simpler-
    e.g let person{
        name:"John"
        age:25
    }
    person.name
    person.age
    disadvantage: cant access values whose keys are in string form and are spaced e.g full name:"Akinyi"


    2.using bracket notation-dynamic where if Key has a space one must access using bracket Notation
    object["key"]-can access any key even when the values have spaces
    person["name"]
    person["full address" ]


OBJECT METHODS-Operations you can carry out on an object
Object.keys(object)  - returns the names of the keys in string form in an array.
Object.values(object) -returns the values of the object in an array
Object.entries(object) - returns key value pairs- all properties-returns an array or arrays
N/B all data above is stored in ARRAYS


HOW TO UPDATE VALUES 
        person["name"]="jane";