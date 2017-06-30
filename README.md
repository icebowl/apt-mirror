
############# config ##################
#
# set base_path    /var/spool/apt-mirror
#
# set mirror_path  $base_path/mirror
# set skel_path    $base_path/skel
# set var_path     $base_path/var
# set cleanscript $var_path/clean.sh
# set defaultarch  <running host architecture>
# set postmirror_script $var_path/postmirror.sh
# set run_postmirror 0
set nthreads     24
set _tilde 0
#
############# end config ##############

deb-amd64 http://ftp.us.debian.org/debian stretch main contrib non-free
deb-amd64 http://ftp.us.debian.org/debian stretch-backports main contrib non-free
deb-amd64 http://ftp.us.debian.org/debian stretch-updates main contrib non-free
deb-amd64 http://ftp.us.debian.org/debian stretch-proposed-updates main contrib non-free

#deb-i386 http://ftp.us.debian.org/debian stretch main contrib non-free
#deb-i386 http://ftp.us.debian.org/debian stretch-backports main contrib non-free
#deb-i386 http://ftp.us.debian.org/debian stretch-updates main contrib non-free
#deb-i386 http://ftp.us.debian.org/debian stretch-proposed-updates main contrib non-free

clean http://ftp.us.debian.org/debian

# apt-mirror


default location is: /var/spool/apt-mirror/mirror

apt-mirror
