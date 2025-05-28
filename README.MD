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

        TYPE CASTING 
-Explicitly Changing the data type of a value from one to another.
    1.Number:
        a} Number()
        b} ParseInt()
        c} ParseFloat()
    2.String:
    a}String()
    b}toString()     


    OPTIONAL CHAINING-tying to make the uncaught error to undefined error(USE OF TERBARY OPERATOR)
        -This is a feature that allows you to safely access deeply nested properties of an object without worrying if part of the chain is null or undefined.

      -Instead of throwing an error when you try to access a null/undefined property optional chaining returns undefined immediately and stops uses this symbol(?)  

   Once OPTIONAL CHAINING ENCOUNTERS THE FIRST INSTANCE OF NULL/UNDEFINED IT STOPS AT THAT POINT.   

    TYPE OF ERRORS ON JAVA SCRIPT FRAMEWORKS 
   UNCAUGHT TYPE ERROR CANNOT READ PROPERTIES....
   //you went from car, past onwers then got lost on .fifth not there and you still went further yet its an error.
    -You got to undefined point or A WRONG KEY and still went further to try and access other nested objects.

    UN DEFINED
    //Tried accessing a value using a wrong key or undefined key that is not there and then you stopped there.


                    SPREAD OPERATOR
    Feature that allows you to spread /expand/unpack elements of an iterable(something that can be looped through) e.g arrays, objects,strings USES (...)
         
    1.Copy Arrays
    2.Merging Arrays 
    3.Copy Objects
    4.Merging Objects       

                        OPERATORS
-Symbols or key words used to perform operations on values/variables

             TYPES OF OPERATORS 
          -Arithmetic- e.g:+, -, /, *, %, **,++, --
          -Comparison/comparing values - e.g: <,>,==,>=,<=,!- 
             ===(strict Equality Operator)-Checks for the value and type 
            !==(strict Inequality Operator)-Checks for the value and type 
          -Assignment- e.g: =, +=, -=,/=,*=.**=,%=,
          -logical - e.g:   AND-Returns True if all conditions are true, (&&)
                            OR-Returns True if atleast 1 is true, (||) 
                            NOT-returns the opposite value- BOOLEAN (!)      

    POLYMORPHISIM-Taking more than 1 form e.g:
    -Called operator overloading
    + means ADD & also means concat(combine strings )    that is why string and number on js will concat the 2 values 

    /, *, ** signs will returns Numbers because this dont have any other functions except only for arithmetic operations they are unique to arithmetic operations.( they are not overloaded)


                                COMPARISON OPERATORS:
thEY RETURN bOOLEAN VALUES - like Truth Values

===(strict Equality Operator)-Checks for the value and type & !==(strict Inequality Operator)
        - Checking for comparison in both values and data types 
        ==loose equality Operator

    1.STRICT EQUALITY TO RETURN TRUE  OPERANDS HAVE TO BE EQUAL IN BOTH VALUE AND DATA TYPE. 
    2.STRICT INEQUALITY CHECKS THAT THEY DONT HAVE TO BE EQUAL IN BOTH DATA TYPE AND VALUE

                        ASSIGNMENT OPERATORS:
    +=(adds and assigns at the same time/at one go)- COMPOUDN ASSIGNEMNET
    -=(subtrcats and assigns in one go/at the same time ) 

                     CONDITIONAL STATEMENTS:
    -They allow your program to make decisions based on whether a condition is true or false or whether the condition is met or not.
     1.IF... ELSE IF....ELSE
        IF -covers the first condition if its met instruction under IF  executes
        ELSE: Excecutes when condition specified is not MET.
    IF
    ...../First condition(If not met move to the next e.g)
    ELSE IF
    ....../second condition
    ELSE
    ...../Excecute when NONE of the above conditions are MET    
CONDITIONAL STATEMENTS IN JS ARE WRITTEN IN BLOCK FORM
{}

if (condition){
    statement to execute
}

//``(called backticks)-EQUIVALENT TO Fstring on PYTHON Use of backticks and use $ sign

     2.TERNARY OPERATOR -?  -Short-hand for IF ELSE                
        -This is a short-hand for writting IF....ELSE statement in J.S
        (only handles 2 conditions to be met if and else only that 2 options)
        SYNTAX= condition ? expression _if_true(means condition is met) : expression_if_false(condition not met)

        LOOPING/ITERATION
-Repetition of a block of code until a specified condition is met ?
    1. Perform repetitive task efficiently 
    2. Parse through large amounts of data e.g in an array.
    
                        TYPES OF LOOPS 
    1.For Loops-knows how many times you are going to loop through an array or object (known number of loops)
    2.do while- will execute at least once before checking the condition 
    3.while- checks for the conditione before executing (unknown number of loops )

                 BASIC STRUCTURE OF A LOOP
         1. Have an initialization- the starting point 
         2. condition- condition  for the loop to continue
         3.Update-update values in the loop    
        

        FUNCTIONS
  Reusable block of codes designed to perform specific tasks     
             WHY USE FUNCTIONS:
    1. For Reusability
    2. For readability-organization
    3.Minimize repetition.
    4.For Modularity- break of code in small chunks helps in debugging , find errors and read easily.

SYNTAX OF FUNCTION-
    //Function Definition
    function  function_name (){
                block to be executed
}
    functioncall
    function_name()

    ARROW FUNCTIONS 
    -Shorter way to write functions in java script.
    use: const function_name=()=>{
        
    }