# AWS-webserver
AWS webserver simple


Step 1 :  create EC2 instance 
Step 2 :  Launch EC2 instance using SSH
Step 3 :  run sudo apt update 
step 4 :  install apache server using CMD sudo apt install apache2
Step 5 :  sudo service apache2 start
step 6 :  sudo systemctl status apache2
step 7 :  run both step 5 and 6 to make sure the apache server is ruinning 
step 8 :  copy the test.html file to /var/www/html folder   or you can crete you own html file and save to the folder 
step   : enable the inbond rule got o EC@ instance security add new rule http to any ip (note thisis not secure so please delet the rule after the testing )
step 10 : accesss the EC2 IP publically 
