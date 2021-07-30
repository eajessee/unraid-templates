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


###############################
##         CLOUDFLARE        ##
###############################

    {
      "provider": "cloudflare",
      "zone_identifier": "some id",
      "domain": "domain.com",
      "host": "@",
      "ttl": 600,
      "token": "yourtoken",
      "ip_version": "ipv4"
    }
###############################
##         DD24        ##
###############################
	{
      "provider": "dd24",
      "domain": "domain.com",
      "host": "@",
      "password": "password",
      "ip_version": "ipv4"
    }
###############################
##         DDNS        ##
###############################
	{
      "provider": "ddnss",
      "provider_ip": true,
      "domain": "domain.com",
      "host": "@",
      "username": "user",
      "password": "password",
      "ip_version": "ipv4"
    }
###############################
##         DigitalOcean        ##
###############################
	{
      "provider": "digitalocean",
      "domain": "domain.com",
      "host": "@",
      "token": "yourtoken",
      "ip_version": "ipv4"
    }
###############################
##         DNSOMATIC        ##
###############################
	{
      "provider": "dnsomatic",
      "domain": "domain.com",
      "host": "@",
      "token": "yourtoken",
      "ip_version": "ipv4"
    }
###############################
##         DNSPOD        ##
###############################
	{
      "provider": "dnspod",
      "domain": "domain.com",
      "host": "@",
      "token": "yourtoken",
      "ip_version": "ipv4"
    }
###############################
##         DONDOMINO        ##
###############################
	{
      "provider": "dondominio",
      "domain": "domain.com",
      "name": "something",
      "username": "username",
      "password": "password",
      "ip_version": "ipv4"
    }
###############################
##         DREAMHOST        ##
###############################
	{
      "provider": "dreamhost",
      "domain": "domain.com",
      "key": "key",
      "ip_version": "ipv4"
    }
###############################
##         DUCKDNS        ##
###############################
	{
      "provider": "duckdns",
      "host": "host",
      "token": "token",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         DYN        ##
###############################
	{
      "provider": "dyn",
      "domain": "domain.com",
      "host": "@",
      "username": "username",
      "password": "password",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         DYNV6        ##
###############################
	{
      "provider": "dynv6",
      "domain": "domain.com",
      "host": "@",
      "token": "token",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         FreeDNS        ##
###############################
	{
      "provider": "freedns",
      "domain": "domain.com",
      "host": "host",
      "token": "token",
      "ip_version": "ipv4"
    }
###############################
##         GANDI        ##
###############################
	{
      "provider": "gandi",
      "domain": "domain.com",
      "host": "@",
      "key": "key",
      "ttl": 3600,
      "ip_version": "ipv4",
    }
###############################
##         GoDaddy        ##
###############################
	{
      "provider": "godaddy",
      "domain": "domain.com",
      "host": "@",
      "key": "key",
      "secret": "secret",
      "ip_version": "ipv4"
    }
###############################
##         GOOGLE        ##
###############################
	{
      "provider": "google",
      "domain": "domain.com",
      "host": "@",
      "username": "username",
      "password": "password",
      "ip_version": "ipv4"
    }
###############################
##         HE        ##
###############################
	{
      "provider": "he",
      "domain": "domain.com",
      "host": "@",
      "password": "password",
      "ip_version": "ipv4"
    }
###############################
##         INFOMANIAK        ##
###############################
	{
      "provider": "infomaniak",
      "domain": "domain.com",
      "host": "@",
      "password": "password",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         LINODE        ##
###############################
	{
      "provider": "linode",
      "domain": "domain.com",
      "host": "@",
      "token": "token",
      "ip_version": "ipv4"
    }
###############################
##         LuaDNS        ##
###############################
	{
      "provider": "luadns",
      "domain": "domain.com",
      "host": "@",
      "email": "email",
      "token": "token",
      "ip_version": "ipv4"
    }
###############################
##         NameCheap        ##
###############################
	{
      "provider": "namecheap",
      "domain": "domain.com",
      "host": "@",
      "password": "password",
      "provider_ip": true
    }
###############################
##         NJALLA        ##
###############################
	{
      "provider": "njalla",
      "domain": "domain.com",
      "host": "@",
      "key": "key",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         NoIP        ##
###############################
	{
      "provider": "noip",
      "domain": "domain.com",
      "host": "@",
      "password": "password",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         DYN        ##
###############################
	{
      "provider": "dyn",
      "domain": "domain.com",
      "host": "@",
      "username": "username",
      "password": "password",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         OVH        ##
###############################
	{
      "provider": "ovh",
      "domain": "domain.com",
      "host": "@",
      "username": "username",
      "password": "password",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         SelfHost.de        ##
###############################
	{
      "provider": "selfhost.de",
      "domain": "domain.com",
      "host": "@",
      "username": "username",
      "password": "password",
      "ip_version": "ipv4"
    }
###############################
##         SPDYN        ##
###############################
	{
      "provider": "spdyn",
      "domain": "domain.com",
      "host": "@",
      "user": "user",
      "password": "password",
      "token": "token",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         STRATO        ##
###############################
	{
      "provider": "strato",
      "domain": "domain.com",
      "host": "@",
      "password": "password",
      "ip_version": "ipv4",
      "provider_ip": true
    }
###############################
##         VarioMedia        ##
###############################
	{
      "provider": "variomedia",
      "domain": "domain.com",
      "host": "@",
      "email": "email@domain.com",
      "password": "password",
      "ip_version": "ipv4",
      "provider_ip": true
    }