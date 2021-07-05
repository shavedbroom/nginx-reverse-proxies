# nginx-reverse-proxies
NGINX Reverse Proxies i use for my plex-seedboxes ALL ARE RUNNING SWIZZIN https://swizzin.ltd/
If you are not running swizzin then your setup will differ from mine.
Requirements are you have a domain name you own, doesnt matter if its .com .net. org .eu just has to be one you own and managed by cloudflare which i also use (its FREE).
SSL Certs are created using sudo box install letsencrypt and following the on screen wizard all you will need is your cloudflare API key and the mail used on your cloudflare account and the letsencrypt cloudflare script will talk with the API and do all the hardstuff.
Subdomains are intended for seperate subdomains before the domain.ltd like plex.domain.ltd are to be stored in nginx/sites-enabled folder
Subfolders are reverse proxies that trail behind a domain name and are intended to be stored in nginx/apps folder inside nginx
