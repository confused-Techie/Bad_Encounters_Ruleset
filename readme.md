# Bad Encounters Ruleset

This is a simple custom ruleset for use with Suricata specifically targeting OpnSense Installations.

The Ruleset is based off malicious actors in my personal experience to help protect any network from them.

## Installation

These following instructions are for installation within OpnSense. Simply connect to your OpnSense installation and run the following.

```
cd /user/local/opnsense/scripts/suricata/metadata/rules/

curl https://raw.githubusercontent.com/confused-Techie/Bad_Encounters_Ruleset/main/Bad_Encounters_Ruleset.xml -o bad-encounters.xml

```

* Then go to the OpnSense Dahsboard and reload the Suricata Service.

* Once reloaded: Services > Intrusion Detection > Administration > Download

* Here you can enable Bad_Encounters/bad_ips and of course start the download by hitting "Download and Update Rules"

* Keep in mind that by default these will only alert and do nothing to block. Blocking should be enabling by creating a Policy that applies to this ruleset.


## Contributing

Feel free to add anything that has affecting your personal network. Just ensure to also add to the reasoning file.
