# php_oop
personal notes on oops pattern of programming in PHP language.


## Abstract class (extend is used)
an object cant be initiated using abstract classes.
we need to only define methods in abstract classes and these methods can be defined in object when abstract class get extended.

## Interface (implement is used)
it cant have construct
it can have varibales
it cant have private/protected functions.(it can only have public functions)

## Static members
normally when we need to access any variable or method of a class, we need initiate a object and then using object we can access variables and methods.
But using static variable and method we can access directly vairable & method of an class.
class_name::$variable_name;
class_name::function_name();

In case of extending, if we want to call parent function (re-writing of function within class) we will 
parent::function_name(); (this fetches function from parent class before getting over-written by child)
