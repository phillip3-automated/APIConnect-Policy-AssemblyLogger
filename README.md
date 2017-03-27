# Assembly Logger policy ![alt text](https://api.travis-ci.org/ChrisPhillips-cminion/APIConnect-Policy-AssemblyLogger.svg?branch=master "status")

When you design and develop custom integration policies, you need to be alerted to any problems with your policies. By defining a custom logging policy to log the values of context variables, you can be quickly alerted to where policies might be malfunctioning so that you can correct any errors.

This tutorial describes a user-defined policy to assist with logging and error diagnosis in the API Connect assembly tool. In this policy, custom strings or context variables can be written directly to IBM® DataPower® logs at any point when running an API. By defining such policy, messages can be written at any priority level. And, when you combine API Connect with the capability of DataPower to selectively listen at different priorities, you get straightforward yet powerful logging and diagnosis when designing an API.

Read More - [Developer Works Link](https://www.ibm.com/developerworks/library/mw-1610-phillips-trs/index.html?ca=drs-)

## Build
To build this policy Run
```
sh build.sh . writeToDatapowerLog
```

This will generate the zip file in the out directory.
