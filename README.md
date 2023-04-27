# soon_landing
Coming soon!

server {
       listen 80;
       listen [::]:80;

       server_name prolab.kg www.rolab.kg;

       root /var/www/soon_landing
       index index.html;

       location / {
               try_files $uri $uri/ =404;
       }
}
