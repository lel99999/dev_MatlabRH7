# dev_MatlabRH7
Matlab development/update for RHEL 7.x

#### Add Specific User License Info
ADD following lines right before INCREMENT:
SERVER <hostname> <hostid> 27000 <br/>
DAEMON MLM {$MATLAB}/<path>/MLM <br/>

#### Test License Mgr and License File with Log Output
{$MATLAB}/etc/glnxa64/lmgrd -c "/<path>/license.lic" -l "/<path>/logfile.log"
 
