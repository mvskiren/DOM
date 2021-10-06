# DOM
Refreshing DOM Concepts

### getElementById - Returns a Element Node 
Disadvantages: 
* Id should be unique
* You can access only one element

### getElementByClassName - Returns HTML Collections (Not a true array)
Disadavntages:
* Returns Collections not an array (ForEach can't be used to iterate since it was not an array ,use normal For loop to iterate)

### getElementByTagName -  Returns HTML Collections (Not a true array)
Disadavntages:
* Performance ineffcient

### querySelector - Returns only one node element

### querySelectorAll - Returns NodeList (True Array )
Advantages: We can loop through forEach method unlike all above methods which returns not a true array.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Nodes
<html>
<head>
  <title>hello there</title>
  </head>
  </html>
  Total Nodes: (html,head, returns new line, space, title, return new line)
  
 # DOM Traversal
 ParentNode - ParentElement
 
 ### Three Important DOM Object and properties
 
 Window
 Document
 HTMLElement (Document.documentElement)
 
 ### FirstNode , LastNode ,PreviousSibiling, nextSibiling, ParentNode, ParentElement
 
 ### Children Vs ChildNodes  
 Childrens returns HTMLCOllection  (includes only type of element)
 ChildNodes returns NodeList (including whitespaces ,returns and text nodes ) 
![Root Node](https://github.com/[mvskiren]/[DOM]/blob/[main]/Screenshot 2021-10-07 at 12.08.45 AM.png.jpg?raw=true)
