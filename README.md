# TPOT-Honeypot-TA
A Splunk Technical Add-on To Collect and Parse T-Mobile's TPOT Honeypot data

Welcome to the Technical Add-on for T-Mobile's TPOT Honeypot. The T-Pot Honeypot is a virtual machine with multiple Honeypots created by T-Mobile, combining existing honeypots (glastopf, kippo, honeytrap and dionaea) with the network IDS/IPS suricata, and T-Mobile's own data submission ewsposter which now also supports hpfeeds honeypot data sharing. For more information on T-Pot please see http://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html.

This Technical Add-on adds props.conf, transform.conf and example inputs.conf and indexes.conf file to help you collect and parse T-Pot log data. All log data on the T-Pot Honeypot resides in the /data folder of the virtual machine.

To install this TA, install this package on your indexers, create the tpot index (or equivalent) using the example indexes.conf or your own method, and push the inputs.conf to your T-Pot Splunk Universal Forwarder. You will have to enable the inputs.conf stanaz when you push it to your SUF.

For any question or comments please E-Mail me at david@wellsconsulting.ca if you have any questions.
