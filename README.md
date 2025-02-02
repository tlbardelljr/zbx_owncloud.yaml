# zbx_owncloud.yaml
zbx_owncloud.yaml

App Owncloud Monitoring API

Overview
Owncloud Monitoring API integration for Zabbix 6.4

Needs curl to be installed on the Nextcloud server.

You need to set the macros according to your environment.

You also need to allow the execution of the script in Zabbix Agent configuration file For example, AllowKey=system.run["curl *"]

Fully compatible with Owncloud version 10.10.0.

Shows different operating values of your Nextcloud server:
<br>
Owncloud: Edition<br>
Owncloud: Hostname<br>
Owncloud: Maintenance<br>
Owncloud: Needs Db Upgrade<br>
Owncloud: Product<br>
Owncloud: Status<br>
Owncloud: Statuscode<br>
Owncloud: Webdav-root<br>
<br>
# Macros used<br>
{$OWNCLOUD.IP}<br>
{$OWNCLOUD.PASS}<br>
{$OWNCLOUD.USER}<br>
{$OWNCLOUD.WEB}<br>

Template links
There are no template links in this template.

Discovery rules
There are no discovery rules in this template.

Triggers
Owncloud: Maintenance Enabled
Owncloud: Status not ok
