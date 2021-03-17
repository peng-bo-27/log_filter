

how to use
like   
./log_filter  /var/log/syslog  /home/root/log  /home/root/file
syslog--->file(how to filter)--->log


file style:
like
"dhcp4 (ens33): option" : "reason"

log output:
like
reason 5 Mar 17 00:09:34 ubuntu NetworkManager[765]: <info>  [1615910974.7159] dhcp4 (ens33): option dhcp_lease_time      => '1800'

