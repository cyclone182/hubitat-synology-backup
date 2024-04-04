# hubitat-synology-backup
A script to download the Hubitat backup file to Synology NAS. This will be configured as a repeating, scheduled task.
<p>Instructions:</p>
<p>1. In your Synology NAS, under Control Panel, open Task Scheduler.</p>
<p>2. Create Scheduled Task -> User Defined Script.</p>
<p>3. Edit the Schedule settings as required.</p>
<p>4. Under Task Settings, add the code from this repository under the User-defined script box.</p>
<p>5. Edit the following variables for your setup:</p>
 <p> &nbsp &nbsp &nbsp he_login (the Hubitat login username)</p>
 <p> &nbsp &nbsp &nbsp he_password (the Hubitat user's password)</p>
 <p> &nbsp &nbsp &nbsp he_ipaddr (the IP address of the Hubitat)</p>
 <p> &nbsp &nbsp &nbsp backupdir (the location to store the backup file on your Synology NAS)</p>
<p>6. Now click OK. Test the script by right-clicking the task and click Run.</p>
