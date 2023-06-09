# Auto LAMP Stack Setup

LAMP stack installation script. The script also automates the process of the creation of virtual hosts on Apache and generation of SSL certificates for the added vhosts.

## ✨ _Usage_

### Connect to your server via SSH

```sh
ssh root@server.ip.address
```

### Copy and pase the following

```sh
curl -s https://raw.githubusercontent.com/sanjeetsagar/auto-LAMP/main/auto_lamp_setup.sh | bash
```

You will be asked to enter website URL(s) and a few other configuration questions.

That's it, after the script is done, open your newly created website(s) in the browser to test if all works. If you have generated an SSL certificate for your website(s), make sure to test over HTTPS as well.

**Note:** Don't forget to change MySQL root user password as soon as possible. The default password for **root** is **root**.

## Subsequent Use

If you need to add more websites to your web server later, run the script as you would normally and type your new website(s) domain(s) when prompted.
