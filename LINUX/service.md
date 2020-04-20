##Service on startup

```
$ sudo nano /etc/systemd/system/my-docker-service.service
```
```shell script
[Unit]
Description=My Docker container
Requires=docker.service
After=docker.service

[Service]
Restart=always
ExecStart=/usr/bin/docker start -a my-container-name
ExecStop=/usr/bin/docker stop -t 10 my-container-name

[Install]
WantedBy=default.target

```
