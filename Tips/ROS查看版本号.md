第一个终端: `roscore`  

第二个终端: `rosparam list`, 然后就可以看到参数列表了．　　

```
-> rosparam list
/rosdistro
/roslaunch/uris/host_trunk__42271
/rosversion
/run_id

-> rosparam get /rosversion
'1.12.13

  '

-> rosparam get /rosdistro
'kinetic

  '
```

