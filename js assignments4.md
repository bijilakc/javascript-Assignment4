# JavaScript
# Assignment 4

## 1.Write a chained if / else-if statement to fill in the following conditions
## val < 5  => Tiny
## val  < 10  => Small
## val < 15  => Medium
## val< 20  =>Large
## val >= 20  =>Huge 
### Ans. let val = 10
###       If(val < 5){
###       Console.log(“tiny”)};
###       else if(val < 10){
###       console.log(“small”)};
###       else if(val < 15){
###       console.log(“Medium”)};
###       else if(val < 20){
###       console.log(“Large”)};
###       else if(val >= 20){
###       console.log(“Huge”)}
## 2.Use the switch case and create an application with the following roles.
##       admin => gets full access
##       subAdmin =>gets access to create and delete courses
##        testPrep =>gets access to create and delete tests
##        user => gets access to consume contents
### Ans.  let  access = “admin”
 ###        switch (access) {
 ###       case  “admin” :
 ###       console.log (“gets full access”);
 ###     break;
 ###     case  “subAdmin” :
 ###      console .log(“gets access to create and delete courses”);
 ###      break;
 ###     case “testPrep” :
 ###     console.log(“gets access to create and delete tests”);
 ###    break;
  ###   case “user” :
   ###  console.log(“gets access to consume contents”);
  ###   break;
###     default:
###     console.log(“wrong choice”);}
       

