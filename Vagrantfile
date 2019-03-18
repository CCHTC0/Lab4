#!/bin/bash;
while [ true ]  ;do
	used=`free -m  | awk  'NR==3  {print $4}'`
if [  $used  -lt  1500  ]   &&   [  $used  -gt  800  ]; then
	echo "Free memory is below 1500MB. Possible memory leak!!

fi

done.
