<html>
	<head>
		<title>Calendar</title>
	</head>
	<body>
		<?php 
			$months = array(0,'January', 'February',  'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December');
		 ?>
		<select id = "years">
			<?php 
				for($i = 2014; $i >= 1990; $i--)
					echo "<option value='" . $i . "'>" . $i . "</option>";
			?>
		</select>
		<select id = "months">
			<?php 
				foreach($i = 1; $i <= 12; $i++)
					echo "<option value='". $i . "'>" . $months[$i] . "</option>";
			?>
		</select>
		<select id = "days">
			<?php 
				for($i = 1; $i <= 31; $i++)
					echo "<option value='" . $i . "'>" . $i . "</option>";
			?>
		</select>
		<script type="text/javascript" src = "jquery.1.10.2.js"></script>
		<script type="text/javascript" src = "ajax.js"></script>
	</body>
</html>
