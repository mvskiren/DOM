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
 ### Create element and append to its child
 let para= document.createElement('p')
 body.appendChild(para);
 ### InnerHtml vs TextContent 
 InnerHtml exposed your site to cross site scripting(XSS) and beacuse of inline html element
 
 
 
 
 
 
 -------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Part -2
 # Events 
  * Inline events
  * Inline properties
  * Event Listners
### Note: Important: an attribute value can be used without quotes under certain conditions.

### What conditions?

Well there are a lot of intuitive rules. If your attribute value has spaces in it, then things will break. This will work:

button class="beautiful funky"

But, as I'm sure you already know, this will break:

button class=beautiful funky
 
button onclick="test()"
 ---------------------------------
