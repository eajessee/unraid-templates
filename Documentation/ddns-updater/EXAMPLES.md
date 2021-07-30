###################################
###################################
####                           ####
#### UNRAID SETUP INSTRUCTIONS ####
####                           ####
###################################
###################################
1. Fill out template and apply (Do not start container after install)
2. Create config.json in the AppData folder (e.g. /mnt/user/appdata/ddns-updater)

#############################
## SINGLE PROVIDER EXAMPLE ##
#############################
{
    "settings": [
        {
			"provider": "namecheap",
			"domain": "example.com",
			"host": "@",
			"password": "e5322165c1d74692bfa6d807100c0310"
        }
    ]
}
###############################
## MULTIPLE PROVIDER EXAMPLE ##
###############################
{
    "settings": [
        {
			"provider": "namecheap",
			"domain": "example.com",
			"host": "@",
			"password": "e5322165c1d74692bfa6d807100c0310"
        },
        {
			"provider": "namecheap",
			"domain": "example.com",
			"host": "@",
			"password": "e5322165c1d74692bfa6d807100c0310"
        }
    ]
}

3. Start the ddns-updater container

##################################
##################################
####                          ####
####     PROVIDER EXAMPLES    ####
####                          ####
##################################
##################################

Examples for each supported provider can be found here:
https://github.com/qdm12/ddns-updater/tree/master/docs

A detailed doc on all features and settings can be found here:
https://github.com/qdm12/ddns-updater/blob/master/README.md

