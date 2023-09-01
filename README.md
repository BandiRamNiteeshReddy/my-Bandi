# my-Bandi
# Bandi Ram Niteesh Reddy
###### Newyork
> **Newyork** is the best place to hangout.
> ***Time square*** is the best place in Newyork 
> we can see lot of pepole there
# Ordered List
1. Visit shops
2. Explore 
3. Pictures
# Unordered List
* Biryani
* Hamburgers
* Pizza<br>
[Link to MyStats](https://github.com/BandiRamNiteeshReddy/my-Bandi/blob/main/MyStats.md)
# Sports and Games
|Sport or game|Reason|Hours per Week|
| :---: | :---: | :---: |
|Swimming|Improves body structure|20hrs|
|Cricket|Helps in Managment|10hrs|
|Running|Improves strength|10hrs|
|Jogging|Improves breath intake|20hrs|
# Pithy Quotes
>“Everything is theoretically impossible until it is done.” – *Robert A. Heinlein*<br>
>“If we knew what it was we were doing, it would not be called research, would it?” – *Albert Einstein* 
# Code Fencing
>Test if String Starts With Certain Characters in PHP<br>
> Stackoverflow link <https://stackoverflow.com/questions/2790899/how-to-check-if-a-string-starts-with-a-specified-string><br>
>We can test if a certain string is the exact start of another string:<br>
'''
<?php 
  
function startsWith($string, $startString) { 
  $len = strlen($startString); 
  return (substr($string, 0, $len) === $startString); 
} 

// usage
echo startsWith("cat", "c"); // true
echo startsWith("dog", "x"); // false

?> 
'''
>Testing the position in the string, making sure it’s at 0, works too:<br>
'''
function startsWith($string, $startString) {
  return strpos($string, $startString) === 0;
}
'''
>The strncmp function is also directly for this purpose:<br>
'''
function startsWith($string, $startString) {
  return strncmp($string, $startString, strlen($startString)) === 0;
}
'''
>You can always RegEx too!<br>
'''
function startsWith($string, $startString) {
  return preg_match('#^' . $startString . '#', $string) === 1;
}
'''
> Snippet Source link <https://css-tricks.com/snippets/php/test-if-string-starts-with-certain-characters-in-php/>