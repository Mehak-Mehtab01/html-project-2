<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title> Forms </title>
</head>
<body>
    
     <form> 
     <fieldset> 
     <legend> ADDMISSION FORM </legend>
     	         Name: 
                   <input type="text" name="name" reduired=" " placeholder="please enter your name "  />
     	<br/>  
     	<br/>
     	Address:  
          <textarea placeholder="enter your address" readonly=""></textarea> 
     	<br/>  
     	<br/> 
     	gender:
     	<input type="radio" value="m"name="gender" /> Male 
     	<input type="radio" value="f" name="gender" checked="" /> Female
     	<input type="radio" value="o" name="gender" />Other  
     	<br/> 
     	<br/> 
     	
     	Which subject do you want to choose :
     	
     	<input type="radio"  value="web" name="Which subject do you want to choose "/>web development  
     	   <br/>    
     	<input type="radio"  value="graphic" name="Which subject do you want to choose "/> graphic designing  
     	 <br/> 
     	<br/> 
     	Country: 
     	<select> 
     	<option> please select a country </option>  
     	    <optgroup label="ASIA"> 
     		<option value="Pakistan"> Pakistan </option> 
     		<option value=India> India </option>  
     		</optgroup>
     		<option value=USA> USA</option> 
     		 
     	</select>
          <br/> 
     	<br/>
     	  
     	  Hobbies: 
     	  <input type="checkbox" name="hobbies[]">Dancing 
     	  <input type="checkbox" name="hobbies[]">singing  
            <input type="checkbox" name="hobbies[]">painting 
     	  <br/> 
     	  <br/> 
             Image:
            <input type="file" name="image"/> 
            <br/> 
          <br/>  
          Email:          
           <input type="email " name="email"> 
           <br/> 
          <br/> 
           Password:          
           <input type="password" name="password">  
            <br/> 
          <br/> 
           Age:         
           <input type="number" name="age">  
            <br/> 
             <br/> 
        
          Secret:  
          <input type="hidden" name="Secret"/>  
           <br/> 
          <br/> 
          Date: 
          <input type="date" name="date"/>  
          <br/> 
          <br/> 
          Date Time: 
             
          <input type="datetime-local" name="date"/>   
           <br/> 
          <br/>  
          Time:  
          <input type="time" name="time"/> 
            <br/> 
          <br/> 
          Months:  
          <input type="month" name="month"/>  
           <br/> 
          <br/> 
          Range:  
          <input type="Range" name="range" min="00" max="200" /> 
          <br/> 
          <br/>   
     
     	<input type="submit" value="submit"/>  
     	<br/> 
     	<br/>
     	<input type="reset"value="Reset"/>    

          </fieldset>  
     	

     </form> 

      
</body>
</html>
