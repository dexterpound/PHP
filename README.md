# PHP
/* My PHP lessons on "Fundamental PHP"*/
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html>
<head>
<title>Floating Point Numbers</title>

</head>

<body>
          <?php echo $float = 3.14; ?><br />
          <?php echo $float + 7; ?><br />
          <?php echo 4/3; ?><br />
<br />
Round: 		<?php echo round($float, 1); ?><br />
Cealing: 	<?php echo ceil($float); ?><br />
Floor: 		<?php echo floor($float); ?><br />
<br />
          <?php $integer = 3; ?>
<br />
          <?php echo "Is {$integer} interger? " . is_int($integer); ?><br  />
          <?php echo "Is {$float} interger? " . is_int($float); ?><br />

          <?php echo "Is {$integer} float? " . is_float($integer); ?><br  />
          <?php echo "Is {$float} float? " . is_float($float); ?><br />


          <?php echo "Is {$integer} numeric? " . is_numeric($integer); ?><br  />
          <?php echo "Is {$float} numeric? " . is_numeric($float); ?><br />
</body>
</html>
