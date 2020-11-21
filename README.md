# dev_MatlabRH7
Matlab development/update for RHEL 7.x

#### Add Specific User License Info
ADD following lines right before INCREMENT: <br/>
```
SERVER <hostname> <hostid> 27000
DAEMON MLM {$MATLAB}/<path>/MLM 
```
#### Test License Mgr and License File with Log Output
```
{$MATLAB}/etc/glnxa64/lmgrd -c "/<path>/license.lic" -l "/<path>/logfile.log"
``` 

#### Add Lic Mgr
Download and add to <MATLAB_Install_Dir>/etc/glnxa64 <br/>
