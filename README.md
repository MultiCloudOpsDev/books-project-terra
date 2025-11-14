# books-project-terra ---nodejs project
*****Installation of frontend****
if u make any update in file always copy code /var/www/html and restart -->
npm run build
sudo cp -r build/* /var/www/html
systemctl restart httpd
******Installation of backend******
sudo dnf install -y nodejs
npm install
npm install -g pm2
pm2 start index.js --name backend
pm2 startup
pm2 save
