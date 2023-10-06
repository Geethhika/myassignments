# myassignments

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<style>
    body{        
    padding-top: 60px;
    padding-bottom: 40px;
    margin: 0;
}
.container{
    width: 80%;
    padding-top: 5px;
}
.fixed-header, .fixed-footer{
    width: 100%;
    position: fixed;        
    background: #333;
    padding-top: 20px;
    padding-bottom: 20px;
    color: #fff;
}
.fixed-header{
    top: 0;
    text-align: center;

}
.fixed-footer{
    bottom: 0;
    text-align: left;
    padding-left: 50px;
}   
nav a{
    color: #fff;
    text-decoration: none;
    padding: 7px 25px;
    display: inline-block;
}
.Assignment{
    text-align: center;
    padding-top: 200px;
}
button{
    background-color: rgb(155, 149, 149);
    padding: 10px;
}
.pfp{
    width: 50px;
            height: 50px;
            border-radius: 50%; 
            margin-right: 10px;
            float: right;
}
</style>
<title>My Assignment</title>
</head>
<body>
    <div class="fixed-header">
        <div class="container">
            <nav>
                <a href="#">21MIC7092</a>
                <a href="#">Geethika</a>
                <img src="Default.jpg" alt="its a picture" class="pfp">
            </nav>
        </div>
       
    </div>
    <div class="Assignment">
        <h3>My Assignments</h3>
    	<button onclick="myFunction1()">Assignment1</button><br><br>
        <button onclick="myFunction2()">Assignment2</button><br><br>
        <button onclick="myFunction3()">Assignment3</button><br><br>
        <button onclick="myFunction4()">Assignment4</button><br><br>
    </div>  
    
    <div class="fixed-footer">
        <div class="container">ph.no:+91 93980 15794 <br>E-mail:geethikamulugu@gmail.com</div>        
    </div>
</body>
<script>
    function myFunction1(){
        location.href = "https://www.google.com/"
    }
    function myFunction2(){
        location.href = "https://www.youtube.com/"
    }
    function myFunction3(){
        location.href = "https://www.instagram.com/"
    }
    function myFunction4(){
        location.href = "https://www.twitter.com/"
    }
</script>
</html>
