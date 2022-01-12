# Windows Exporter
###### tags: `Monitor` `Windows`
## Install Windows Exporter

* Windows
```
msiexec /i windows_exporter-0.16.0-amd64.msi ENABLED_COLLECTORS=cache,cpu_info,cpu,cs,logical_disk,logon,memory,net,os,process,remote_fx,service,system,tcp,textfile,vmware
```
* AD
```
msiexec /i windows_exporter-0.16.0-amd64.msi ENABLED_COLLECTORS=cache,cpu_info,cpu,cs,logical_disk,logon,memory,net,os,process,remote_fx,service,system,tcp,textfile,vmware,ad,adfs,dns
```
* RDS
```
msiexec /i windows_exporter-0.16.0-amd64.msi ENABLED_COLLECTORS=cache,cpu_info,cpu,cs,logical_disk,logon,memory,net,os,process,remote_fx,service,system,tcp,textfile,vmware,terminal_services,iis
```
* DHCP
```
msiexec /i windows_exporter-0.16.0-amd64.msi ENABLED_COLLECTORS=cache,cpu_info,cpu,cs,logical_disk,logon,memory,net,os,process,remote_fx,service,system,tcp,textfile,vmware,dhcp
```
* .Net
```
msiexec /i windows_exporter-0.16.0-amd64.msi ENABLED_COLLECTORS=cache,cpu_info,cpu,cs,logical_disk,logon,memory,net,os,process,remote_fx,service,system,tcp,textfile,vmware,netframework_clrexceptions,netframework_clrinterop,netframework_clrjit,netframework_clrloading,netframework_clrlocksandthreads,netframework_clrmemory,netframework_clrremoting,netframework_clrsecurity
```
* ProGet
```
msiexec /i windows_exporter-0.16.0-amd64.msi ENABLED_COLLECTORS=cache,cpu_info,cpu,cs,logical_disk,logon,memory,net,os,process,remote_fx,service,system,tcp,textfile,vmware,iis
```
