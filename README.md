# README

sudo nine-manage-vhosts virtual-host create virgin.access4all.ch --template=reverseproxy_puma --webroot=/home/www-data/virgin.access4all.ch/rails/current/public --template-variable MODSEC=Off --template-variable PROXYPORT=3000

sudo nine-manage-databases database create nmd_virgin
