- ```alert()``` and ```console.log()```
- ```document.getElementById("<id>").innerHTML = <content>```: change content
- ```document.getElementById("<id>").onclick = <function>```: add event
- ```document.getElementById("<id>").style.<property>```: change style
  - No hyphen ```-``` in JavaScript, e.g. ```font-size``` => ```fontSize```
  - ```style.display="none/block"``` to hide/display the element
- ```document.getElementById("<id>").value```: retrieve value of ```<input>```, ```<select>```
- Array 
[[variable-array]()]
  - Add element to the end of array: ```push()```
  - Remove element: ```splice(<start_index>, <number_of_element_to_remove>)```
  - Add element before a specific index: ```splice(<index>,0,<element>)```


# Notes - Tips 
- JavaScript code can be typed and execute in the console section of the browser development tool
- Debug in the console section of the browser development tool
- [HTML] Generate HTML template in VSCode: type ! => Enter
- Placing scripts at the bottom of the <body> element improves the display speed, because script interpretation slows down the display.