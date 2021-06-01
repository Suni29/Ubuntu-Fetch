# Ubuntu-Fetch
A fake, customizeable neofetch in a bash script!

# Source code
###If you dont want to download the bash script.

```###################
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
c2="\e[97m" # \e[97m

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
echo " "
echo -e "${normal}            .-/+oossssoo+/-."
echo -e "         :+ssssssssssssssssss+:"
echo -e "       -+ssssssssssssssssssyyssss+-"
echo -e "     .ossssssssssssssssss${c2}dMMMNy${normal}sssso."
echo -e "    /sssssssssss${c2}hdmmNNmmyNMMMMh${normal}ssssss/                   ${normal}${username}${c2}@${normal}${desktopname} "
echo -e "   +sssssssss${c2}hm${normal}yd${c2}MMMMMMMNddddy${normal}ssssssss+                  ${c2}-------------------${normal} "
echo -e "  /ssssssss${c2}hNMMM${normal}yh${c2}hyyyyhmNMMMNh${normal}ssssssss/                 ${normal}OS: ${c2}Ubuntu ${ver} ${lts} ${arch}${normal}"
echo -e " .ssssssss${c2}dMMMNh${normal}ssssssssss${c2}hNMMMd${normal}ssssssss.                ${normal}Host: ${c2}${host}${normal}"
echo -e " +ssss${c2}hhhyNMMNy${normal}ssssssssssss${c2}yNMMMy${normal}sssssss+                ${normal}Kernel: ${c2}${kernel}${normal}"
echo -e " oss${c2}yNMMMNyMMh${normal}ssssssssssssss${c2}hmmmh${normal}ssssssso                ${normal}Uptime: ${c2}${uptime}${normal}"
echo -e " oss${c2}yNMMMNyMMh${normal}sssssssssssssshmmmh${normal}ssssssso                ${normal}Packages: ${c2}${pkgs} (apt)${normal}"
echo -e " +ssss${c2}hhhyNMMNy${normal}ssssssssssss${c2}yNMMMy${normal}sssssss+                ${normal}Shell: ${c2}bash 4.4.20${normal}"
echo -e " .ssssssss${c2}dMMMNh${normal}ssssssssss${c2}hNMMMd${normal}ssssssss.                ${normal}Resolution: ${c2}${res}${normal}"
echo -e "  /ssssssss${c2}hNMMM${normal}yh${c2}hyyyyhdNMMMNh${normal}ssssssss/                 ${normal}Window Manager: ${c2}${wmgr}${normal} "
echo -e "   +sssssssss${c2}dm${normal}yd${c2}MMMMMMMMddddy${normal}ssssssss+                  ${normal}Virtualization: ${c2}${virt}${normal} "
echo -e "    /sssssssssss${c2}hdmNNNNmyNMMMMh${normal}ssssss/                   ${normal}CPU: ${c2}${gpu}${normal} "
echo -e "     .ossssssssssssssssss${c2}dMMMNy${normal}sssso.                    ${normal}Memory: ${c2}${mem} ${normal}/ ${c2}${maxmem}${normal} "
echo -e "       -+sssssssssssssssss${c2}yyy${normal}ssss+-                   "
echo -e "         :+ssssssssssssssssss+:"
echo -e "             .-/+oossssoo+/-."
echo " "
echo " "
echo " "```
