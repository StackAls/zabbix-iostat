# zabbix-iostat

```
sudo nano /etc/zabbix/zabbix_agentd.d/iostat_json.conf

UserParameter=iostat.json, iostat -yxdtc -o JSON

sudo systemctl restart zabbix-agent.service
