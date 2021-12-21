### accessig objects
you can access objects with . or [].
example 
  var hotelname = hotel.name;
  var hotelname = hotel ['name'];

### DOM tree 
document object model
selecting an individual - getElementId(), queryselectir()
selecting multiple element - getElementByClassName(), getElementByTagName(), queryselectorall()
innerHTML- allows access to child element
textContent
adding nodes - createElement(),createTextNode()
remove nodes - appendChild(), removeChild()
working with attributes - className, Id
hasAttribute() - checks if an attribute exists
getAttribute() - gets the value
setAttribute() - updates the value
removeAttribute() - removes an attribute

accessing element more than once example
  getElementById('one');
  
storing element in a variable example
  var itemOne = getElementById('one');

returning single element node
  getElementById('id')
  querySelector('css selector')

returning multiple element nodes
  getElementByClassName('class')
  getElementByTagName('tagName')
  querySelectorAll('css selector')

selecting an individual element example
document.getElementById('one');

