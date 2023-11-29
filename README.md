# CentOS
linux commands &amp; issues

### yum on Centos stuck at "loaded plugins: fastestmirror
```
nano /etc/yum/pluginconf.d/fastestmirror.conf
```
Change enabled=1 to enabled=0 to disable the fastestmorror plugin.
