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


|     |     |
| main item--- |    justify-content
|     |     |
align-item

align-items : flex-start , flex-end , center

height : 70 vh   vh is viewport height which we basically see the window


(make this item separate) align-self : flex - start
align-content : center {only for wrap (flexbox wrap)}

#### Flex sizing :
content width < width < flex basis < min-width / max-width

	flex-basis : 0 ;
	 flex-grow : 1 ;
	 flex-shrink : 1;       flex : 1 1 0
	                    grow shrink basis








