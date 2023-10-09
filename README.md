# openshift-cronjob-example
Example configuration to run scripts under Kubernetes cron.

This configuration will place a demo script and cronjob in a project named "demo".


demo-cronjob.yaml	- Cronjob definition

demo-datafile.yaml	- Example datafile to map to the cronjob

demo-options.yaml	- Example environment variables to expose to the cronjob

demo-script.yaml	- The script being mounted and run from the cronjob

svc-demo-crontab.yaml	- Service Account definition for running OC CLI commands

svc-demo-role.yaml	- Role binding for the service account.

