<?php 
	$year = $_GET['year'];
	$month = $_GET['month'];
	$is_leap_year = (($year % 4) == 0) ? true : false;

	switch($month){
		case 1:
		case 3:
		case 5:
		case 7:
		case 8:
		case 10:
		case 12:
			echo json_encode(
				array('result'=> 'success', 'day' => 31)
				);
			break;
		case 4:
		case 6:
		case 9:
		case 11:
			echo json_encode(
				array('result'=> 'success', 'day'=> 30)
				);
			break;
		case 2:
			if($is_leap_year){
				echo json_encode(
					array('result'=> 'success', 'day'=> 29)
					);
			}else{
				echo json_encode(
					array('result'=> 'success', 'day'=> 28)
					);
			}
			break;
		default:
			echo json_encode(
				array('result'=> 'failed', 'month'=> $month, 'year'=> $year)
				);
	}
	
 ?>
