/usr/local/openjdk-11/bin/java -Dfile.encoding=UTF-8 -Xverify:none -Xms3584m -Xmx3584m -XX:NewSize=896m -XX:MaxNewSize=2390m -XX:+DisableExplicitGC -XX:+UseConcMarkSweepGC -XX:+ParallelRefProcEnabled -XX:TargetSurvivorRatio=90 -XX:+UseCompressedOops -XX:ParallelGCThreads=5 -XX:ConcGCThreads=2 -XX:+HeapDumpOnOutOfMemoryError -XX:HeapDumpPath=$DUMP_PATH
