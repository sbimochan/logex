# logex
Bash script to log and organize git-logs by date & repository, inspired from [logit](https://github.com/bhattaraib58/logit) by [@bhattaraib58](https://github.com/bhattaraib58).

#### Install:
```shell
sudo curl -L https://raw.githubusercontent.com/kritish-dhaubanjar/logex/main/logex.sh -o /usr/local/bin/logex && sudo chmod +x /usr/local/bin/logex
```

Depends on:
- `git config user.name`

#### Uninstall:
```shell
sudo rm /usr/local/bin/logex
```

#### Usage:
```
$ logex --help
Usage: logex [OPTION]... [FILE]
logex - Bash script to log and organize git-logs by date & repository.

Options:
  -d, --days       set number of days to log
  -a, --author     set commit author to log (git config user.name)
  -h, --help       display this help and exit
```

#### Preview:

![logex-colors](https://user-images.githubusercontent.com/25634165/199158501-f86241f2-a988-41e2-a397-7a9df95fc618.png)
