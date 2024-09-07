# iredmail configration readme

Iredmail is the mail server used by cyber evangelists company. Ired using ldap for authentication mechanisms and mysql on  local port 3306.
Here is brief configurations.

## Dns Record configurations
DNS record for mail.cyberevangelists.com (on which mail server configured) are configurated on godaddy.com

## Nginx configuration file 
  Configuration file which is handeling iredmail requests is located at `/etc/nginx/sites-enabled/00-default-ssl.conf` .


### Services using by iredmail
iredmail using `postfix, dovecot and mysl` services to mail managemnt 

## Complete Installation guide
[Here](https://www.linode.com/docs/guides/how-to-install-and-configure-iredmail/) is the Complete installtion guide for iredmail



## What is "Oops...something went wrong!" error?
 Well if you got `Oops...something went wrong!` error its mean your mysql service got downed you need to restart it by something like this command `service mysql restart`. 

## Can;t login if you still trying same login passwords?
 Your ldap service got down, restart it your problem got resolved....
