# Nessus_Scans_Parser
Nessus_Scans_Parser

Nessus Profesional Version: 8.7.1 (#212) LINUX

This Python script is able to download the Scans with CSV format.

In order to execute the script correctly is nedded to modify the next variables: nessusBaseURL, nessusUsername, nessusPassword

Example:

nessusBaseURL= "https://192.168.191.132:8834" 

nessusUsername= "Rodrigo.Varas"

nessusPassword= "Westcon,.-3218"


Output:

Starting  Popcorn
Plugin ID,CVE,CVSS,Risk,Host,Protocol,Port
"33850","","10.0","Critical","10.10.10.6","tcp","0"

Completed Popcorn
-----------------------------------------------
Starting  Prueba1
Plugin ID,CVE,CVSS,Risk,Host,Protocol,Port
"32314","CVE-2008-0166","10.0","Critical","10.10.10.3","tcp","22"

Completed Prueba1
-----------------------------------------------
Starting  CTF_Devel
Plugin ID,CVE,CVSS,Risk,Host,Protocol,Port

Completed CTF_Devel
-----------------------------------------------
Starting  CTF_Legacy
Plugin ID,CVE,CVSS,Risk,Host,Protocol,Port
"34477","CVE-2008-4250","10.0","Critical","10.10.10.4","tcp","445"
"35362","CVE-2008-4114","10.0","Critical","10.10.10.4","tcp","445"
"35362","CVE-2008-4834","10.0","Critical","10.10.10.4","tcp","445"
"35362","CVE-2008-4835","10.0","Critical","10.10.10.4","tcp","445"
"73182","","10.0","Critical","10.10.10.4","tcp","0"
"97833","CVE-2017-0143","10.0","Critical","10.10.10.4","tcp","445"
"97833","CVE-2017-0144","10.0","Critical","10.10.10.4","tcp","445"
"97833","CVE-2017-0145","10.0","Critical","10.10.10.4","tcp","445"
"97833","CVE-2017-0146","10.0","Critical","10.10.10.4","tcp","445"
"97833","CVE-2017-0147","10.0","Critical","10.10.10.4","tcp","445"
"97833","CVE-2017-0148","10.0","Critical","10.10.10.4","tcp","445"
"108797","","10.0","Critical","10.10.10.4","tcp","0"

Completed CTF_Legacy
-----------------------------------------------
Starting  CTF_Lame
Plugin ID,CVE,CVSS,Risk,Host,Protocol,Port
"32314","CVE-2008-0166","10.0","Critical","10.10.10.3","tcp","22"

Completed CTF_Lame
-----------------------------------------------
Starting  prueba_2
Plugin ID,CVE,CVSS,Risk,Host,Protocol,Port

Completed prueba_2
