# JavaScript basics

1] Difference between == and ===</br>
== allows comparison w/o coercion.</br>
Be careful while using them with non-premitive(function, array, objects) types.</br>
Non premitive types contain reference so [1,2,3] == [1,2,3] will be false.</br>
However, [1,2,3] == "1,2,3" will return true as arrays are by-default converted to strings with , between the values.</br>

2] String, number comparison using <, ></br>
"a" < "b" // true</br>
"1" < "2" // true</br>

1 < "2" //true</br>

When both are strings, comparison is made alphabatically</br>
When 1 or none are string, converted to number and then compared.</br>

Special case:</br>
When comparing 2 < "ab", 2 > "ab", 2 == "ab" all return false</br>
Because "ab" is converted into an invalid number(NaN)</br>

3] Variables can't start with numbers or special characters except $ and _ and can't be special keywords.</br>

4] Normal JS follows function scoping</br>
i.e variable declared on any line inside a function is available to the whole function through hoisting.</br>
ES6 has an option of block scoping using let keyword. i.e the variable will be available only inside its {, }</br>

5] IIFE format and use -</br>
(function(){</br>
})();</br>

It doesn't pollute the global scope.</br>

6] Closure</br>
A function that remembers its scope.</br>
When you assign a function to a variable and pass it using return statement, that function can be used anywhere as it remembers its inner scope.</br>
The best use of this conecpt is in module pattern.</br>

7] Module pattern</br>
function User {</br>
  var username, password;</br>
  
  function authenticate(us, pw) {</br>
    username = us;</br>
    password = pw;</br>
  }</br>
  
  var publicAPI = {</br>
    login: authenticate;</br>
  }</br>
  
  return publicAPI;</br>
}
