# DOMAIN-based Rules for Surge 4 & Quantumult X

These rule sets include domain-based rules for Surge & Quantumult X, exclusively provide logical rules (AND, NOT) for Surge 4.

## Fix Apple-System-Apps Installation Error

Enabling [iOS OTA update blocker](https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/DOMAINs/AppleOTA.list) will also blocks the installations of some Apple-Apps such as Weather, Home, Mail. To fix the problem, you should add the rule ```USER-AGENT,MobileAsset*,DIRECT``` on top of **AppleOTA.list** on your Surge Module or configuration. This method is yet to be tested and may not work on Quantumult X due to rules loading priority ([V2EX Discussion #62](https://www.v2ex.com/t/642077)).
