### Build command using Scala 2.11 

```
./dev/change-version-to-2.11.sh
./make-distribution.sh --name NPI -Dscala-2.11 -Phadoop-2.6 -Pflume-provided -Phadoop-provided -Pparquet-provided -Phbase-provided -Phive-provided
```


