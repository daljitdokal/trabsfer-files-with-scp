# Transfer files with SCP
### Local to remote

```bash
$user="xxxxx"
$remoteMachine="xxxxxxxx"

# Single file
scp ./path/filename $user@$remoteMachine:~/path/

# Full directory
scp -r ./path/ $user@$remoteMachine:~/path/

```

### Remote to local

```bash
$user="xxxxx"
$remoteMachine="xxxxxxxx"

# Single file
scp $user@$remoteMachine:~/path/filename ./path

# Full directory
scp -r $user@$remoteMachine:~/path/ ./path
``` 
