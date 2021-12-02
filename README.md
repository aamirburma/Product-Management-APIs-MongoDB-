# Product-Management-APIs-MongoDB-
<h1 style="text-align:center" align="center">SCHEMA</h1>
<ol>
    <li><h4>PRODUCT</h4></li>
    <ul>
        <li>product id : String</li>
        <li>title : String</li>
        <li>price : String</li>
        <li>category : Array of String</li>
        <li>company id : String</li>
        <li>seller id : Array of String</li>
    </ul>
    <li><h4>COMPANY </h4></li>
    <ul>
        <li>company id : String</li>
        <li>name : String</li>
        <li>product ids : Array of String</li>
    </ul>
    <li><h4>SELLER</h4></li>
    <ul>
        <li>seller id : String</li>
        <li>name : String</li>
        <li>product ids : Array of String</li>
    </ul>
</ol>
<hr />
<h1 style="text-align:center" align="center">Operations</h1>
<ol>
    <li>ADD</li>
    <ul>
        <li>Add new company</li>
        <li>Add new seller</li>
        <li>Add new product</li>
    </ul>    
    <li> RETRIEVE </li>
    <ul>
        <li>Fetch company details based on product name</li>
        <li>Fetch seller details based on product name</li>
        <li>Fetch all products of a company</li>
        <li>Fetch all products of a seller</li>
    </ul>
    <li> UPDATE </li>
    <ul>
        <li>Update company (add/remove products)</li>
        <li>Update seller (add/remove products)</li>
        <li>Update product (add/remove category)</li>
    </ul>
    <li> DELETE </li>
    <ul>
        <li>Delete company</li>
        <li>Delete seller</li>
        <li>Delete product</li>
    </ul>
</ol>
<hr />
<img src="./Postman/1.png" width="400px" />
<hr />
<img src="./Postman/2.png" width="400px" />
<hr />
<img src="./Postman/3.png" width="400px" />
<hr />
<img src="./Postman/4.png" width="400px" />
<hr />
<img src="./Postman/5.png" width="400px" />
<hr />
<img src="./Postman/6.png" width="400px" />
<hr />
<img src="./Postman/7.png" width="400px" />
<hr />
<img src="./Postman/8.png" width="400px" />
<hr />
<img src="./Postman/9.png" width="400px" />
<hr />
<img src="./Postman/10.png" width="400px" />
<hr />
<img src="./Postman/11.png" width="400px" />
<hr />
<img src="./Postman/12.png" width="400px" />
<hr />
<img src="./Postman/13.png" width="400px" />
<hr />
