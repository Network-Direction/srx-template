# srx-template
Push template config to SRX firewalls

"""
Connects to an SRX and pushes template config

Usage:
    Take a single SRX, or a list of SRXs (CSV) to connect to
    Take a JSON file (accessible over HTTP) of config to apply
    Options:
        -v, --verbose: Show the config that's being applied
        -c, --commit: Commit the changes (otherwise the changes will be rolled back)

Authentication:
    Supports username and password for login to NETCONF over SSH
    Junos supports RSA keys, but this script currently does not

Restrictions:
    Requires JunosPyEZ to be installed
    Requres a username/password to connect
    Asynchronous processing is not supported

To Do:
    - None

Author:
    Luke Robertson - September 2022
"""



