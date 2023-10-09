# openshift-cronjob-example
Example configuration to run scripts under Kubernetes cron.

This configuration will place a demo script and cronjob in a project named "demo".

<table border="0" cellspacing="0" cellpadding="0">
        <tbody>
                <tr>
                        <td width="60"> &nbsp; </td>
                        <td width="70">
                                <b>file</b>
                        </td>
                        <td width="240">
                                <b>Description</b>
                        </td>

<tr><td></td> demo-cronjob.yaml</td>- Cronjob definition</tr>
<tr><td></td> demo-datafile.yaml   </td>-<td> Example datafile to map to the cronjob</tr>
<tr><td></td> demo-options.yaml    </td>-<td> Example environment variables to expose to the cronjob</tr>
<tr><td></td> demo-script.yaml     </td>-<td> The script being mounted and run from the cronjob</tr>
<tr><td></td> svc-demo-crontab.yaml</td>-<td> Service Account definition for running OC CLI commands</tr>
<tr><td></td> svc-demo-role.yaml   </td>-<td> Role binding for the service account.</tr>
</table>

