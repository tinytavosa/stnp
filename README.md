# stnp
smartthings-nodeproxy

config.json and SMARTAPP info follows

--------

{
  "port": 8080,
  "authCode": "secret-key",
  "dash": {
    "buttons": [
      "yo:ur:MA:C#:he:re"
    ]
  },
  "notify": {
    "address": "192.168.1.3",
    "port": "39500"
  }
}

--------

	("address" is SmartThings Hub IP address)
	(change "40:b4:cd:ca:6f:e4" to CORRESPONDING MAC ADDRESS)
	("port" seems to stay the same)
	(be sure to change "dashX" to 
	
	
	(push control+O to save)
	(push ENTER to confirm WRITE/save)
	(push control+X to exit)

	(Install Smart App and configure)

	("Proxy Address" in SMART APP is for the Raspberry Pi)

	("address" in config.json is for SMARTTHINGS HUB)

	(in the end config.json contains - starts line 48, ends  line 60)
