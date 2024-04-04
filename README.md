# hubitat-synology-backup
A script to download the Hubitat backup file to Synology NAS. This will be configured as a repeating, scheduled task.
<p><b>Instructions:</b></p>
<p>1. In your Synology NAS, under Control Panel, open Task Scheduler.</p>
<p>2. Create Scheduled Task -> User Defined Script.</p>
<p>3. Edit the Schedule settings as required.</p>
<p>4. Under Task Settings, add the code from <b>user-defined script</b> from this repository under the User-defined script box.</p>
<p>5. Edit the following variables for your setup:</p>
 <p> &nbsp &nbsp &nbsp he_login <i>(the Hubitat login username)</i></p>
 <p> &nbsp &nbsp &nbsp he_password <i>(the Hubitat user's password)</i></p>
 <p> &nbsp &nbsp &nbsp he_ipaddr <i>(the IP address of the Hubitat)</i></p>
 <p> &nbsp &nbsp &nbsp backupdir <i>(the location to store the backup file on your Synology NAS)</i></p>
<p>6. Now click OK. Test the script by right-clicking the task and click Run.</p>
