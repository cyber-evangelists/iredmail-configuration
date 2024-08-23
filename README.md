# iredmail configration readme

Iredmail is the mail server used by cyber evangelists company.
Here is brief configurations.

## Dns Record configurations
DNS record for mail.cyberevangelists.com (on which mail server configured) are configurated on godaddy.com

## Nginx configuration file 
  Configuration file which is handeling iredmail requests is located at `/etc/nginx/sites-enabled/00-default-ssl.conf` .


### Services using by iredmail
iredmail using `postfix, dovecot and mysl` services to mail managemnt 

## Complete Installation guide
[Here](https://www.linode.com/docs/guides/how-to-install-and-configure-iredmail/) is the Complete installtion guide for iredmail




