## Installation

cd /usr/local/opnsense/scripts/suricata/metadata/rules/

curl https://raw.githubusercontent.com/confused-Techie/Bad_Encounters_Ruleset/main/Bad_Encounters_Ruleset.xml -o bad-encounters.xml

Go to the OpnSense Dashboard and reload Suricata Service

Now you can go to Services > Intrustion Detection > Administration > Download

Then enable Bad_Encounters/bad_ips then "Download and Update Rules"

Then you are good to go
