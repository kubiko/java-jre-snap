# java run time snap

Java 8 run time snap, this snap is intented to be used by other snaps, providing java run time environment using content interface.
Once snap is installed, connect jre slot of this snap with plug from host snap. Host snap  needs to set JAVA_HOME and update PATH.
Example how to lift values from connected jre snap can be find here:
https://github.com/kubiko/openhab-snap/blob/without-jre/snap/src/openhab-control#L35

