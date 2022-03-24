
# Addition calculator




## How is it used?
You can do simple addition calculations.



# Ai
//Html file
<html>
<head>
    <title>Kokonaisluku</title>
    <form method="get"action="Luvut.php"> 
        Luku1:<input type="text" name="arvo1" ><br>
        Luku2:<input type="text" name="arvo2" ><br>
        Luku3:<input type="text" name="arvo3" ><br>
        Luku4:<input type="text" name="arvo4" ><br>
        Luku5:<input type="text" name="arvo5" ><br>
        <input type="submit" value="Calculate">
        
    </form>
</head>
<body>
    
</body>
</html>


//Php file
<?php 
$luku1=$_GET["arvo1"];
$luku2=$_GET["arvo2"];
$luku3=$_GET["arvo3"];
$luku4=$_GET["arvo4"];
$luku5=$_GET["arvo5"];
$luku1>=0;
$luku2>=0;
$luku3>=0;
$luku4>=0;
$luku5>=0;


$summa=$luku1 + $luku2 + $luku3 + $luku4 + $luku5;
print "Summa on:";
print ($summa);

?>
