# A user-friendly, security hardened, Nextcloud setup script.
This scripts assumes:
- You ran it as the root user
- It's running on a fresh installation of Debian 11 bullseye
- You only use this VPS/Computer for hosting Nextcloud
If you do not meet these requirements, you should not run the script.
## Installation
1. Add the needed DNS records for your domain
2. SSH into your fresh install of Debian 11
3. `bash -c $(curl https://gitlab.com/mr.r/nextcloud-setup/-/raw/main/setup.sh)`
4. You will be asked for your email and the domain name.
6. **DONE.** Now open your browser, and type your domain.
## TODO
- [ ] Make a backup system
- [ ] Check if domain is pointing to this VPS, if yes, start nextcloud
- [ ] Automatic nextcloud updates
####  Licensed Under AGPL v3 
