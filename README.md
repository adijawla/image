<!DOCTYPE HTML>  
<html>  
    <head>  
        <title>  
            Change the element ID 
        </title>  
  
        <script src = 
"https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"> 
        </script> 
      
        <style> 
            #myCol { 
                background: green; 
            } 
            #newID { 
                background: red; 
            } 
            table { 
                color: white; 
            } 
            td { 
                padding: 10px; 
            } 
        </style> 
    </head>  
      
    <body> 
        <center>      
            <h1 style = "color:green;" >  
                IRIS SOFTWARE WEB APPLICATION 
            </h1>     
              
            <table> 
                <colgroup> 
                    <col id= "myCol"
                        span= "3"> 
                    <col style= "background-color:green"> 
                </colgroup> 
                  
                <tr>
					<th>Company</th>
					<th>Contact</th>
					<th>Country</th>
				</tr>
				<tr>
				<td><a href="http://www.google.com" id="googleLink" name="google" target="_blank">Google</a></td>
				<td><a href="url">link text</a></td>
				<td><a href="url">link text</a></td>
				</tr>
				<tr>
				<td><label for="fname" name="FirstName" ID="FirstNameLabel">First name:</label></td>
				<td><input type="text" id="fnameInput" name="fname"><br><br></td>
				<td><a href="url">link text</a></td>
				</tr>
                
            </table> 
            <br> 
              
            
              
            <script>  
                
				var start = new Date;
				setInterval(function() {
					 $("col").attr('id', 'newID');
					   $("#googleLink").attr('name', 'TestGooogle');
					    $("#googleLink").attr('name', 'TestGooogle');
					    $("#googleLink").attr('href', 'http://www.google.com');
					     $("#FirstNameLabel").attr('id', 'FirstName123');
					     $("#fnameInput").attr('name', 'fnameTestGooogle');
					}, 6000);
            </script>  
        </center> 
    </body>  
</html>
