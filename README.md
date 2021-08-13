# freebox-monitoring

![](https://raw.githubusercontent.com/tuxtof/freebox-monitoring/master/screenshot.png)

Test done on Freebox Delta S,

### Quickly launch with Docker

Just run

```
$ docker-compose up
```

Go To http://<your docker host ip>:3000/dashboard/file/freebox-grafana.json, wait 1 minute, and you should see your data :).

### Dependency:
- telegraf
- influxdb
- grafana

### List of important files for manual install:
- fbx-info.py : script for retrieve freebox info to put in /etc/telegraf/
- freebox-grafana.json : freebox dashboard sample to import in grafana
- freebox.conf: telegraf sample conf to put in /etc/telegraf/telegraf.d/
