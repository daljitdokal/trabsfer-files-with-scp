# Transfer files with SCP (Local to remote and Remote to local)

### Local to remote

```bash
$user="xxxxx"
$remoteMachine="xxxxxxxx"

scp -r .\path\ $user@$remoteMachine:~/
```

### Remote to local

```bash
$user="xxxxx"
$remoteMachine="xxxxxxxx"

scp $user@$remoteMachine:~/filename  ./path
``` 
