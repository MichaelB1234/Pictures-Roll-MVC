# Pictures-Roll-MVC
A Java Script - ed View for an MVC app that optionally rolls pictures, with 2-stage zoom, un-zoom to look like an old-fashioned 
camera roll.
A different way to show pictures, different to normal containers.
The background color is a shade of red to imitate a photographers film devoloping den.
Images on the left and right position as the page resizes or loads to form an illusion of looking at a roll from a camera.
2 central images needs to be composed with a basic drawing tool (I used Microsoft Paint for all image work.) Your image 
displays must go adjacently,pixel 
perfectly from left to right, to form a banner of digital photographs.
1 of these includes a frame around each image to match the left and right images so as to look right.
1 of them has no frame.
So, if Roll is engaged:
  For no zoom: Left and Right images display. Framed central banner is used.
  For zoom: Left and Right images don't display and framed central banner is used, and something else not mentioned yet,
            a fibonnaci sequence is used in reverse to roll the image into place with the "left" style setting.
 If Roll is disengaged:
   For no zoom: Left and Right images don't display. Non-framed central banner is used.
   For zoom: Left and Right images don't display. Non-framed central banner is used. The images just snap into place by varying the
             "left" style setting.
             
             That is the explanation of what it does and it is a lot to read, check it out to really see.
             
             A technique whereby an outer div is relatively positioned whilst an inner div is absolutely 
             positioned is key and crucial to allowing everything to display right.
