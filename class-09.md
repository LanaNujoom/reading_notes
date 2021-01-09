# Class 09

# Forms:


## Building Blocks

***Adding Text***

- Text Input 

- Password Input 

- Text Area

***Making Choices***

- Radio Buttons

- Checkboxes

- Drop-down boxes

![img](https://www.roseindia.net/tutorialfiles/26957.RadioCheckboxPick.gif)



![img](https://cdn.pixabay.com/photo/2013/07/12/17/00/drop-down-select-box-151649_960_720.png)

## Submitting Forms:

1. Submit buttons

2. Image buttons

3. Uploading Files:

![img](https://www.homeandlearn.co.uk/WD/images/chapter8/forms_1.gif)



![img](https://www.htmlgoodies.com/imagesvr_ce/1902/HTML%20Form.PNG)

## Form Structure

    <form id = ''>   put an id 
    <fieldset>     container for our input tags given
    <legend> </legend>
    <label for = ''>
    </label>
    <input name= 'name' type = ''text>
    
    
    
   
#  Lists, Tables & Forms:

## Bullet Point Styles 

**list-style-type**


allows  to control the shape
or style of a bullet point

![img](https://th.bing.com/th/id/OIP.Sv8mws2XzfgXsTGUCcmzeQHaCy?pid=Api&rs=1)
     
     
        ol {
        list-style-type: lower-roman;}
        
        
        
**list-style-image**

 specify an image to act
as a bullet point


![img](https://red-team-design.com/dist/uploads/2012/02/css3-ordered-list-styles.png)


**list-style-position**


     ul {
    width: 150px;}
    li {
    margin: 15px;}
    ul.illuminations {
    list-style-position: inside;}
    ul.season {
    list-style-position: outside;}
    
    
**list-style**

  shorthand for list
styles. 


    ul {
    list-style: inside circle;
    width: 300px;}
    li {
    margin: 10px 0px 0px 0px;}




     ul {
     list-style-image: url("images/star.png");}
     li {
     margin: 10px 0px 0px 0px;
     
     
  # Table Properties:
  
  **empty-cells**
  
  
     td {
    border: 1px solid #0088dd;
    padding: 15px;}
    table.one {
    empty-cells: show;}
    table.two {
    empty-cells: hide;}
    
    
 1. show 
 
 2. hide 
 
 3. inherit
 
 **Gaps Between Cells**
 
 control the distance between adjacent cells. 
 
 ![img](https://i.ytimg.com/vi/GuQ5aUFVysY/maxresdefault.jpg)
 
  
 ![img](https://www.w3.org/wiki/images/0/02/Csslist2_table-collapse.png)

  #Events:
  
  *JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page*
  
       <element event='some JavaScript'>
       
   examples of HTML events:
   
   - An HTML web page has finished loading
   
   - An HTML input field was changed
   
   - An HTML button was clicked
   
   ![img](https://cdn.javascripttutorial.net/wp-content/uploads/2020/02/JavaScript-event-bubbling.png)


