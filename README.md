# Integration AppScan Enterprise (DAST) and Gitlab
<br>
Gitlab YAML file to integrate AppScan Enterprise (DAST feature) and Gitlab Pipeline enabling send DAST scans requests to AppScan Enterprise and keep result reports in Gitlab.
Gitlab will start scan, generate report, publish results in AppScan Enterprise and check for Security Gate.<br>
<br>
Requirements:<br>
1 - AppScan Enterprise and AppScan Dynamic Analysis tool.<br>
2 - Gitlab Runner for Linux, because this YAML will run in Linux Environment.<br>
<br>

```yaml
