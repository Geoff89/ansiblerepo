ansible-playbook runsetup.yml --syntax-check
ansible-playbook runsetup.yml

--login to client node
--confirm whehter httpd is running and access the web page
sudo systemctl status httpd
cat /etc/httpd/conf/httpd.conf