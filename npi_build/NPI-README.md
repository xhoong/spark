### Build command using Scala 2.11 

```
./dev/change-version-to-2.11.sh
./make-distribution.sh --name NPI --tgz -Dscala-2.11 -Dhadoop.version=2.7.1 -Phadoop-2.6 -Pyarn -Pflume-provided -Phadoop-provided -Pparquet-provided -Phbase-provided -Phive-provided
```
Alternatively build with everything:
```
./make-distribution.sh --name NPI --tgz -Dscala-2.11 -Dhadoop.version=2.7.1 -Phive -Phive-thriftserver -Phadoop-2.6 -Pyarn -Pflume-provided -Phadoop-provided
```

