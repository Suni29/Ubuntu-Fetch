# Ubuntu-Fetch
A fake, customizeable neofetch in a bash script!

# Source code
### If you dont want to download the bash script.

```
###################
#                 #
# FAKE NEOFETCH   #
#                 #
# made by Suni29  #
#                 #
###################

##################
# Basic Settings #
##################

# Username
username="root" # root

# PC / Laptop Name
desktopname="neofetch" # neofetch

#######################
# Perfomance Settings #
#######################

# Virtualization (Yes / No)
virt="Yes" # Yes

# GPU
gpu="Intel Xeon (4) @ 2.299GHz" # Intel Xeon (4) @ 2.299GHz

# Memory / RAM
mem="1013MiB" # 1013MiB

# Installed Memory / RAM
maxmem="26068MiB" # 26068MiB

####################
# Desktop Settings #
####################

# Ubuntu Version
ver="20.04" # 20.04

# LTS (leave it blank if not LTS version)
lts="LTS" # LTS

# Architecture
arch="x86_64" # x86_64

# Host
host="HP" # HP

# Kernel version
kernel="None" # None

# Window Manager
wmgr="None" # None

#####################
# Optional Settings #
#####################

# Uptime
uptime="0 sec" # 0 sec

# Packages
pkgs="1383" # 1383

# Resolution
res="0000x0000" # 0000x0000

##################
# Color Settings #
##################

# Yellow color
normal="\e[33m" # \e[33m

# White color
white="\e[97m" # \e[97m

############
#          #
# Neofetch #
#          #
############

##########################################
#                                        #
#       #                                #
#      ###                               #
#     ## ##     WARNING!                 #
#    ### ###    Do NOT change this code! #
#   #########                            #
#  ##### #####                           #
# #############                          #
#                                        #
##########################################

echo " "
echo " "
echo ""
echo -e "${normal}            .-/+oossssoo+/-."
echo -e "         :+ssssssssssssssssss+:"
echo -e "       -+ssssssssssssssssssyyssss+-"
echo -e "     .ossssssssssssssssss${white}dMMMNy${normal}sssso."
echo -e "    /sssssssssss${white}hdmmNNmmyNMMMMh${normal}ssssss/                   ${normal}${username}${white}@${normal}${desktopname} "
echo -e "   +sssssssss${white}hm${normal}yd${white}MMMMMMMNddddy${normal}ssssssss+                  ${white}-------------------${normal} "
echo -e "  /ssssssss${white}hNMMM${normal}yh${white}hyyyyhmNMMMNh${normal}ssssssss/                 ${normal}OS: ${white}Ubuntu ${ver} ${lts} ${arch}${normal}"
echo -e " .ssssssss${white}dMMMNh${normal}ssssssssss${white}hNMMMd${normal}ssssssss.                ${normal}Host: ${white}${host}${normal}"
echo -e " +ssss${white}hhhyNMMNy${normal}ssssssssssss${white}yNMMMy${normal}sssssss+                ${normal}Kernel: ${white}${kernel}${normal}"
echo -e " oss${white}yNMMMNyMMh${normal}ssssssssssssss${white}hmmmh${normal}ssssssso                ${normal}Uptime: ${white}${uptime}${normal}"
echo -e " oss${white}yNMMMNyMMh${normal}sssssssssssssshmmmh${normal}ssssssso                ${normal}Packages: ${white}${pkgs} (apt)${normal}"
echo -e " +ssss${white}hhhyNMMNy${normal}ssssssssssss${white}yNMMMy${normal}sssssss+                ${normal}Shell: ${white}bash 4.4.20${normal}"
echo -e " .ssssssss${white}dMMMNh${normal}ssssssssss${white}hNMMMd${normal}ssssssss.                ${normal}Resolution: ${white}${res}${normal}"
echo -e "  /ssssssss${white}hNMMM${normal}yh${white}hyyyyhdNMMMNh${normal}ssssssss/                 ${normal}Window Manager: ${white}${wmgr}${normal} "
echo -e "   +sssssssss${white}dm${normal}yd${white}MMMMMMMMddddy${normal}ssssssss+                  ${normal}Virtualization: ${white}${virt}${normal} "
echo -e "    /sssssssssss${white}hdmNNNNmyNMMMMh${normal}ssssss/                   ${normal}CPU: ${white}${gpu}${normal} "
echo -e "     .ossssssssssssssssss${white}dMMMNy${normal}sssso.                    ${normal}Memory: ${white}${mem} ${normal}/ ${white}${maxmem}${normal} "
echo -e "       -+sssssssssssssssss${white}yyy${normal}ssss+-                   "
echo -e "         :+ssssssssssssssssss+:"
echo -e "             .-/+oossssoo+/-."
echo " "
echo " "
echo " "```
