Ejercicios
==========
<?php
$arreglo[0][0]="a";
  $arreglo[0][1]="b";
  $arreglo[0][2]="c";
  $arreglo[1][0]="d";
  $arreglo[1][1]="e";
  $arreglo[1][2]="f";
  $arreglo[2][0]="g";
  $arreglo[2][1]="h";
  $arreglo[2][2]="i";
   
		
                $resulta=$arreglo[0][0].$arreglo[0][1];
                $resulta=$resulta.$arreglo[0][2];
                $resulta=$resulta.$arreglo[1][2];
                $resulta=$resulta.$arreglo[2][2];
                $resulta=$resulta.$arreglo[2][1];
                $resulta=$resulta.$arreglo[2][0];
                $resulta=$resulta.$arreglo[1][0];
                $resulta=$resulta.$arreglo[1][1];
                
                echo "el resultado es ".$resulta;

