# README #

This is an installation mirror for xtream ui software.

### How do I install? ###

update your ubuntu first, then install panel  
  
* sudo apt-get update && sudo apt-get upgrade -y; 
* sudo apt-get install libxslt1-dev libcurl3 libgeoip-dev python -y ; 
* wget https://bitbucket.org/emre1393/xtreamui_mirror/downloads/install.py; 
* sudo python install.py  
  
If you want a whole NEW installation, choose MAIN and then ADMIN.  
If you want ONLY the admin part, select ADMIN only.  
If you want to install load balance on additional servers,  
add a server to panel in manage servers page, then run script and proceed with LB option.

### tutorials are here;###
https://www.youtube.com/playlist?list=PLJB51brdC_w7dTDxi1MPqiuk3JH5U2ekn

### Files Hashes ###
* admin_xtreamcodes_reborn.tar
* sha1: "2D36AEF6E3EF2DBB8943AF2D6F4F73D7EEFB6ECB"

* main_xtreamcodes_reborn.tar
* sha1: "532B63EA0FEA4E6433FC47C3B8E65D8A90D5A4E9"

* sub_xtreamcodes_reborn.tar
* sha1: "5F8A7643A9E7692108E8B40D0297A7A5E4423870"

### note,
original install.py is from https://xtream-ui.com/install/install.py  
btw, developer removed admin part from original install.py at begining of this year.  
you can compare my install.py with original one.