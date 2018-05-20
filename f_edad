<?php
//titulo
 echo "<title>Script 1 # JC WebMaster</title>";

//función mi edad
function m_edad($fecha_nac){
	//Dia Mes y Año
	$dia=date("j");
	$mes=date("n");
	$anno=date("Y");
	//descomponer fecha de nacimiento
	$a_nac=substr($fecha_nac, 0, 4);
	$m_nac=substr($fecha_nac, 5, 2);
	$d_nac=substr($fecha_nac, 8, 2);
	//
	if($m_nac>$mes){
		$c_edad= $anno-$a_nac-1;
	}else{
		if($mes==$m_nac AND $d_nac>$dia){
			$c_edad= $anno-$a_nac-1;  
		}else{
			$c_edad= $anno-$a_nac;
		}
	}
	return $c_edad;
}

	print "Actualmente tengo ".m_edad("1992-06-06")." años";

?>
