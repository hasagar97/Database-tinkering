# Phase 1 instructions

## makefile fixing

```bash
grep -rl '/p/course/cs784-raghu/minibase_share/' . | xargs sed -i 's|/p/course/cs784-raghu/minibase_share/|/home/hrishi/phase/|g'
grep -rl '/usr/java/jdk1.3.1_02' . | xargs sed -i 's|/usr/java/jdk1.3.1_02|/usr/lib/jvm/java-1.11.0-openjdk-amd64|g'
grep -rl '/s/java' . | xargs sed -i 's|/s/java|/usr/lib/jvm/java-1.11.0-openjdk-amd64|g'

```

## generating typescript
Run the following make commands and then do some tests
- make sure you run the script command in the src foldert otherwise the output won't be stored in the typescript file
``` bash
make db
script
make test
```

### Cleaning

When done with the changes or want to make edits to the file run make clean
```bash
make clean
```