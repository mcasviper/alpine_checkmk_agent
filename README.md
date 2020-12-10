# alpine_checkmk_agent
all files needed to create a service to run CheckMK agent on Alpine Linux

## playbook
to run the playbook you have to replace the following strings:

$YOUR_ALPINE_IP = the IP of your Alpine Linux host

$YOUR_CHECKMK_HOSTNAME = hostname of your CheckMK server needed to create the download url for agent file

$YOUR_SITE_NAME = Name of your CheckMK site

$YOUR_CHECKMK_SERVER_IP = this is only needed if you want to limit the requests to the port only to the CheckMK Server. This will only be used if uncommented!

