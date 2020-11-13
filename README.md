# PIA Servers
This repository contains an automatically updated list of all Private Internet Access servers

![Servers](https://img.shields.io/badge/servers-6908-brightgreen) ![Last update](https://img.shields.io/badge/last%20update-2020--11--13%2010%3A00-brightgreen) 

<a href="https://www.buymeacoffee.com/Lars-" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-orange.png" alt="Buy Me A Coffee" height="60" style="height: 60px !important;width: 217px !important;" ></a>

## Why?
Private Internet Access was unable to send a list of IPs and just said that I should "reconfigure my device", whatever that means.
On some forums I read that they don't share it, because Hulu could then block all of them. Yes, this could be true, but NordVPN also publishes their list of VPNs and they don't seem to have any problems.

## How does it work?
PIA rotates their IPs via DNS. When you open one of their provided OVPN files, you will see something like:
`remote au-melbourne.privateinternetaccess.com 1198`. When you check the A record of au-melbourne.privateinternetaccess.com, you will find one or more IPs (but never all), these are the server IPs.
You could check every 120s if there is a new IP available, or you could let me do it.

This repository is automatically updated with all the IPs that have been seen in the past 14 days. That means that if PIA disables a server, it will take approximately 14 days for it to dissapear here.
The repository is updated every hour if something has changed.

## The full list
Private Internet Access provides two types, the normal servers and the "nextgen servers" which should be faster. This repository will provide both.

Region | Normal | Nextgen | Combined
------ | ------ | ------- | --------
AU Melbourne | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/AU%20Melbourne) | [70 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/AU%20Melbourne) | [90 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/AU%20Melbourne)
AU Perth | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/AU%20Perth) | [31 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/AU%20Perth) | [35 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/AU%20Perth)
AU Sydney | [27 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/AU%20Sydney) | [66 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/AU%20Sydney) | [93 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/AU%20Sydney)
Albania | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Albania) | No servers | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Albania)
Argentina | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Argentina) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Argentina) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Argentina)
Austria | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Austria) | [78 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Austria) | [80 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Austria)
Belgium | [9 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Belgium) | [71 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Belgium) | [80 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Belgium)
Bosnia and Herzegovina | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Bosnia%20and%20Herzegovina) | No servers | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Bosnia%20and%20Herzegovina)
Bulgaria | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Bulgaria) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Bulgaria) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Bulgaria)
CA Montreal | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/CA%20Montreal) | [180 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/CA%20Montreal) | [182 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/CA%20Montreal)
CA Ontario | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/CA%20Ontario) | No servers | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/CA%20Ontario)
CA Toronto | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/CA%20Toronto) | [228 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/CA%20Toronto) | [233 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/CA%20Toronto)
CA Vancouver | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/CA%20Vancouver) | No servers | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/CA%20Vancouver)
Czech Republic | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Czech%20Republic) | [100 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Czech%20Republic) | [101 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Czech%20Republic)
DE Berlin | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/DE%20Berlin) | [141 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/DE%20Berlin) | [147 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/DE%20Berlin)
DE Frankfurt | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/DE%20Frankfurt) | [128 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/DE%20Frankfurt) | [134 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/DE%20Frankfurt)
Denmark | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Denmark) | [46 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Denmark) | [47 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Denmark)
Estonia | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Estonia) | No servers | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Estonia)
Finland | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Finland) | [49 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Finland) | [51 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Finland)
France | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/France) | [144 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/France) | [146 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/France)
Greece | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Greece) | No servers | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Greece)
Hungary | [8 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Hungary) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Hungary) | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Hungary)
Iceland | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Iceland) | [30 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Iceland) | [32 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Iceland)
India | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/India) | [30 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/India) | [32 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/India)
Ireland | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Ireland) | [59 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Ireland) | [62 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Ireland)
Israel | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Israel) | [23 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Israel) | [27 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Israel)
Italy | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Italy) | [82 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Italy) | [84 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Italy)
Japan | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Japan) | [102 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Japan) | [104 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Japan)
Latvia | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Latvia) | No servers | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Latvia)
Lithuania | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Lithuania) | No servers | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Lithuania)
Luxembourg | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Luxembourg) | [30 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Luxembourg) | [36 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Luxembourg)
Moldova | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Moldova) | [11 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Moldova) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Moldova)
Netherlands | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Netherlands) | [170 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Netherlands) | [175 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Netherlands)
New Zealand | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/New%20Zealand) | [23 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/New%20Zealand) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/New%20Zealand)
North Macedonia | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/North%20Macedonia) | No servers | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/North%20Macedonia)
Norway | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Norway) | [59 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Norway) | [61 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Norway)
Poland | [8 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Poland) | [33 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Poland) | [41 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Poland)
Portugal | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Portugal) | No servers | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Portugal)
Romania | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Romania) | [93 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Romania) | [113 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Romania)
Serbia | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Serbia) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Serbia) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Serbia)
Singapore | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Singapore) | [87 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Singapore) | [91 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Singapore)
Slovakia | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Slovakia) | No servers | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Slovakia)
South Africa | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/South%20Africa) | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/South%20Africa) | [28 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/South%20Africa)
Spain | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Spain) | [80 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Spain) | [82 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Spain)
Sweden | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Sweden) | [83 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Sweden) | [85 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Sweden)
Switzerland | [7 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Switzerland) | [167 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Switzerland) | [174 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Switzerland)
Turkey | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Turkey) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Turkey) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Turkey)
UAE | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/UAE) | No servers | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/UAE)
UK London | [7 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/UK%20London) | [198 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/UK%20London) | [205 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/UK%20London)
UK Manchester | [12 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/UK%20Manchester) | [126 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/UK%20Manchester) | [138 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/UK%20Manchester)
UK Southampton | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/UK%20Southampton) | No servers | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/UK%20Southampton)
US Atlanta | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Atlanta) | [169 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Atlanta) | [173 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Atlanta)
US California | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20California) | [323 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20California) | [324 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20California)
US Chicago | [8 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Chicago) | [234 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Chicago) | [242 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Chicago)
US Dallas | [9 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Dallas) | No servers | [9 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Dallas)
US Denver | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Denver) | [171 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Denver) | [172 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Denver)
US East | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20East) | No servers | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20East)
US Florida | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Florida) | [241 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Florida) | [261 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Florida)
US Houston | [41 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Houston) | [106 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Houston) | [147 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Houston)
US Las Vegas | [40 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Las%20Vegas) | No servers | [40 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Las%20Vegas)
US New York City | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20New%20York%20City) | No servers | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20New%20York%20City)
US Seattle | [7 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Seattle) | [153 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Seattle) | [160 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Seattle)
US Silicon Valley | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Silicon%20Valley) | [195 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Silicon%20Valley) | [209 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Silicon%20Valley)
US Washington DC | [61 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Washington%20DC) | [256 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Washington%20DC) | [317 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Washington%20DC)
US West | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20West) | [196 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20West) | [200 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20West)
Ukraine | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Ukraine) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Ukraine) | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Ukraine)
Algeria | No servers | [37 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Algeria) | [37 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Algeria)
Andorra | No servers | [43 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Andorra) | [43 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Andorra)
Armenia | No servers | [33 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Armenia) | [33 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Armenia)
Bahamas | No servers | [34 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Bahamas) | [34 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Bahamas)
Bangladesh | No servers | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Bangladesh) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Bangladesh)
Cambodia | No servers | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Cambodia) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Cambodia)
China | No servers | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/China) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/China)
Cyprus | No servers | [31 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Cyprus) | [31 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Cyprus)
Egypt | No servers | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Egypt) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Egypt)
Georgia | No servers | [31 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Georgia) | [31 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Georgia)
Greenland | No servers | [33 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Greenland) | [33 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Greenland)
Iran | No servers | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Iran) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Iran)
Isle of Man | No servers | [29 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Isle%20of%20Man) | [29 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Isle%20of%20Man)
Kazakhstan | No servers | [32 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Kazakhstan) | [32 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Kazakhstan)
Liechtenstein | No servers | [35 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Liechtenstein) | [35 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Liechtenstein)
Macao | No servers | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Macao) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Macao)
Malta | No servers | [31 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Malta) | [31 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Malta)
Mexico | No servers | [48 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Mexico) | [48 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Mexico)
Monaco | No servers | [34 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Monaco) | [34 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Monaco)
Mongolia | No servers | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Mongolia) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Mongolia)
Montenegro | No servers | [33 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Montenegro) | [33 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Montenegro)
Morocco | No servers | [29 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Morocco) | [29 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Morocco)
Nigeria | No servers | [39 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Nigeria) | [39 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Nigeria)
Panama | No servers | [34 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Panama) | [34 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Panama)
Philippines | No servers | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Philippines) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Philippines)
Qatar | No servers | [31 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Qatar) | [31 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Qatar)
Saudi Arabia | No servers | [32 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Saudi%20Arabia) | [32 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Saudi%20Arabia)
Sri Lanka | No servers | [34 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Sri%20Lanka) | [34 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Sri%20Lanka)
Taiwan | No servers | [23 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Taiwan) | [23 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Taiwan)
US New Jersey | No servers | [131 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20New%20Jersey) | [131 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20New%20Jersey)
US New York | No servers | [192 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20New%20York) | [192 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20New%20York)
US Texas | No servers | [218 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Texas) | [218 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Texas)
United Arab Emirates | No servers | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/United%20Arab%20Emirates) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/United%20Arab%20Emirates)
Venezuela | No servers | [38 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Venezuela) | [38 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Venezuela)
Vietnam | No servers | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Vietnam) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Vietnam)


## Disclaimer
I am not affiliated with PIA and therefore do not include any affiliate links in this repository. 
All actions could have been done by anyone. This is in no way considered or meant as hacking. 
If servers or OVPN files don't work, it is not the fault of this repository. If you don't need anything special, just use the files provided by PIA themselves.

## Ideas or contributions
Do you have an idea for this to be better/faster/more useful, please leave me a message. Also consider buying me a coffee using the button above if it helped you.
