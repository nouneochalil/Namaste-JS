<!-- -Functions are first class citizens in javascript.

-You can take one function and pass it into another function.

-passing function is called call back function-it is very powerful

-js ->synchrounous single threaded language ->only one thing at a 

atime-> due to call back we can do async thing in call back. -->

//////////////////////////////////////////////
<!-- y is the call back function

-now it's upto x when to call y. 

-see call back use in `Asynchronous task`. -->

    Garbage Collection 
<!-- -Eventlistner is heavy
-it takes lot of memory-somany closure- remove Eventlistner whenever not in use- all the variables used in Eventlistner wl become like Garbage  
Event listeners consume a lot of memory which can potentially slow down the website therefore it is good practice to remove if it is not used.-->
setTime out register the call back function inside the webAPI.
-
Here setTimeout will call the call back function only after 5s.Till it become 5s it execute other  function

setTimeout(function xy(){
console.log("timer")                
},5000)


function x(){
console.log("x")
}   
x(function (y){
console.log("y")
})

o/p
///////
x
y
timer
