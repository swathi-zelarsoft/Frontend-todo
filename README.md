## FRONTEND
```
# apt update
# apt install nginx-y
# systemctl enable nginx 
# systemctl start nginx 
# apt install npm
# cd /var/www/html
# git clone https://github.com/zelar-soft-todoapp/frontend.git
# cd frontend
# npm install
# npm run build

Update Login and todo Ip address.

# cd /var/www/html/frontend
# cd config
# vi index.js

Now change the root in /etc/nginx/sites-available/default   /var/www/html/frontend/dist

# systemctl restart nginx
```

![image](https://user-images.githubusercontent.com/82637337/116817881-2e8ea600-ab86-11eb-8344-f759f7a3add4.png)
