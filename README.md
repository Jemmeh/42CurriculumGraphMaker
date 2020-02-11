# 42CurriculumGraphMaker
Update the curriculum graph more easily. (AKA Holy Graph / Curriculum Galaxy)
Currently you can use this to click on the graph and add the text. This will give you a list of coordinates you can enter in 42Intra.

You can use the graph maker here: https://editor.p5js.org/JemCope/sketches/QMqfaOHA
Click the Run button. 

![ExampleImage](https://github.com/Jemmeh/42CurriculumGraphMaker/blob/master/Screen%20Shot%202020-01-30%20at%205.35.39%20PM.png?raw=true)


### Currently in Development:
#### DONE Goal#1: File > Save Graph
  
  Will save into a .txt file
  
#### DONE Goal#2: File > Upload Graph
  
  You can upload the .txt file so you don't have to start from scratch every time.
  
#### Goal#3: Connections: 
  
  Draw the connections between nodes and get the coordinates. This will correlate to the "By" of Project Data in the 42API.


Format:
The link path, under the 'project_id, x1, y1, x2, y2, ...' format. One child per line
I think you can have an array of links for nodes with multiple connections.

#### Goal#4: File > Upload to 42Intra
Call the 42API to upload the new graph to the intra.
  Goal 4.1
    Will need to add the projectID to the node array to be able to do this. This will probably necessitate a "Node Settings" side bar--something that was probably going to be needed for later features anyways.
  
 -----
 #### Goal#5: Node Size
  Change the size of the shape.
  
 #### Goal#6: Additional Shapes
   Rectangles, Diamonds, Triangles, etc
  
#### Goal#7: Multi-Select
  Hold down Ctrl and select multiple nodes/connections so you can move entire sections at a time. This will be useful for updating entire branches. 
 
 #### Goal#8: Box Select / Magic Wand Select
  Select all nodes inside of a box.  It may be a good idea to also allow drawing a selection for better targeting.
 



