# Debug Systemd problems

## List jobs
```
systemctl list-jobs
```
To identify slow boot and look for the jobs that are "running" those jobs are the ones where boot waits for
completion on and the ones that listed as "waiting" will be executed only after those which are "running" are completed. 



## List Units


```
systemctl list-units -t service --all
```

To show all active services 

```
systemctl list-units -t service
```

To examine the current runtime status of a service. (In the above example the ssh service) 

```
systemctl list-units -t target --all
```
To show all available targets. 


```
systemctl list-units -t target
```
To show all active targets. 