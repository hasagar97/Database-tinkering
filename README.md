# Phase 1 instructions

## makefile fixing

```bash
grep -rl '/p/course/cs784-raghu/minibase_share/' . | xargs sed -i 's|/p/course/cs784-raghu/minibase_share/|/home/hrishi/phase/|g'
grep -rl '/usr/java/jdk1.3.1_02' . | xargs sed -i 's|/usr/java/jdk1.3.1_02|/usr/lib/jvm/java-1.11.0-openjdk-amd64|g'
grep -rl '/s/java' . | xargs sed -i 's|/s/java|/usr/lib/jvm/java-1.11.0-openjdk-amd64|g'

 ```

 ## generating typescript
Run the following make commands and then do some tests

 ``` bash
 make db
 make test
 ```