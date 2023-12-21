server-reboot pm2 not restart itself:
follow the following commands

pm2 start start.js
pm2 save
pm2 startup centos
pm2 unstartup centos

