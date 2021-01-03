# Class 07

## Domain Modeling

*process of creating a conceptual model in code for a specific problem.*

    var parentElement = document.getElementsByTagName('body');
    var h1 = document.createElement('h1');
    h1.textContent = shopObject.location;
    parentElement.appendchild(h1);
    

### Generate Random Nomber

    function getRandomCustomersNumber(min, max) {
    var result = Math.floor(Math.random() * (max - min + 1) + min);
    return result;
}


## Tables 

![img](https://ictacademy.com.ng/wp-content/uploads/2017/10/HTML-Table-Structure.png)
       



    Each row is created with the <tr> element.
    
    
    each row there are a number of cells
    represented by the <td> element (or <th> if it is a
    header).
    
    
    
   ![img](https://www.t4tutorials.com/wp-content/uploads/2017/02/table-in-html.png)
    
    
 ***In long tables  split the table into a thead,tbody, and tfoot***
