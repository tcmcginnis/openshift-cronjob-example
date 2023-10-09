# openshift-cronjob-example
Example configuration to run scripts under Kubernetes cron.

This configuration will place a demo script and cronjob in a project named "demo".


demo-cronjob.yaml	\t- Cronjob definition<br>
demo-datafile.yaml	\t- Example datafile to map to the cronjob<br>
demo-options.yaml	- Example environment variables to expose to the cronjob<br>
demo-script.yaml	- The script being mounted and run from the cronjob<br>
svc-demo-crontab.yaml	- Service Account definition for running OC CLI commands<br>
svc-demo-role.yaml	- Role binding for the service account.<br>

