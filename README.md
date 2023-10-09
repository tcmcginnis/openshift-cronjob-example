# openshift-cronjob-example
Example configuration to run scripts under Kubernetes cron.

This configuration will place a demo script and cronjob in a project named "demo".

<table border="0" cellspacing="0" cellpadding="0">
        <tbody>
                <tr>
                        <td width="200">
                                <b>file</b>
                        </td>
                        <td>
                                <b>Description</b>
                        </td>
                </tr>

<tr><td> demo-cronjob.yaml    </td>-<td></td> Cronjob definition                                </td></tr>
<tr><td> demo-datafile.yaml   </td>-<td> Example datafile to map to the cronjob                 </td></tr>
<tr><td> demo-options.yaml    </td>-<td> Example environment variables to expose to the cronjob </td></tr>
<tr><td> demo-script.yaml     </td>-<td> The script being mounted and run from the cronjob      </td></tr>
<tr><td> svc-demo-crontab.yaml</td>-<td> Service Account definition for running OC CLI commands </td></tr>
<tr><td> svc-demo-role.yaml   </td>-<td> Role binding for the service account.                  </td></tr>
</table>

