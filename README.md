# zabbix-proxy-mysql-no-fping6
Zabbix proxy avoiding problems without ipv6.

This is almost identical to zabbix/zabbix-proxy-mysql:ubuntu-latest - but has fping6 renamed to fping6.hide to make in invisible to zabbix. So zabbix won't try ipv6. - Without this patch I got some problems with ping-checks (e.g. wrong paket loss values).
