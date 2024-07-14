# 5.flex-box
## program
```
<!DOCTYPE html>
<html>
  <head>
    <title>flex box</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <h2>Sport Day</h2><div class="context">
      <div class="content">
        <h4>event1</h4>
        <p>foodball match</p>
      </div>
      <div class="content">
       <h4>event2</h4>
      <p>cricket match</p>
      </div>
      <div class="content">
        <h4>event3</h4>
        <p>baseball match</p>
      </div></div>
      <div class="info">
        <h5>upcoming event:</h5>
        <div>foodball match timing:4:30PM to 5:45PM<strong>(semi-final)</strong></div>
        <div>cricket match timing:2:00PM to 3:30PM<strong>(final)</strong></div></div>
        <footer>.</footer>
      
      
  </body>
</html>
h2{
  background-color:tomato;
  text-align:center;
  color:white;
  margin-top: 0;
  padding:0;
}
body{
  font-family:Arial;
  background-color:#f0f0f0;
}
.context{
  display:flex;
  justify-content:space-evenly;
  
}
.content{
  background-color:white;
  border-radius:2px;
  box-sizing:border-box;
  
 
  
}
h4{
  color:#f32343;
}
footer{
  background-color:tomato;
  height:20px;
}
.info{
  background-color:white;
  border-radius:2px;
  margin-bottom:10px;
}
h5{
  border-bottom:2px solid tomato;
  margin-bottom:5px;
  width:100px;
}
```
## output:

![WhatsApp Image 2024-07-14 at 22 24 05_8a67aac1](https://github.com/user-attachments/assets/5c5b961f-ac7b-4f15-9521-47d077d931ca)
