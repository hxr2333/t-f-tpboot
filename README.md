# tftpboot
tftpboot for DRBL
download it and unzip
then run docker run --name drbl-final -d --privileged=true --network=host -v /home/partimag/:/home/partimag/ -v /tftpboot:/tftpboot huangxiangru/drbl-final /sbin/init
you will have a drblserver with docker
