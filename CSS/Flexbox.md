# Display  [[https://css-tricks.com/snippets/css/a-guide-to-flexbox/]]

***Float*** is good for layout style like one side and image and on the other hand explanation about image

***Flexbox*** is good for overall page structure and easy to use
example : <div class="container">     [index.html]
          <div class="one"><p>.....<p> </div>

          .container{
          display : flex;         
          gap: 10px;
          }
## 
## Direction
Flex-direction : row ;  [main-axis : left to right]                                                 .container (parent)
                                                            .container > * (child)
Flex-direction : columns ; [main-axis : top to bottom]
flex-basis : 100px ; [its changes the width each of item ]                          
           if we use this in row it will change width
           if we use this in column it will change height


### Layout
  order property
  order : 1 ....;
  flex-wrap : wrap ;
  justify-content : flex-start; [space left]
justify-content : center ; [select all item in center]
justify-content : space-between ;

