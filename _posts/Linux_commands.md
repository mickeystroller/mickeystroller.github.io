### Decompress

```
tar -zxvf backup.tar.gz 
```

### Compress
```
tar -cxvf file.txt
```

### Alias
```
$ vim ~/.bash_profile
add one line: alias l='ls -lah'
$ source ~/.bash_profile
```

### PDFcrop
```
pdfcrop --margins '5 10 20 30' input.pdf output.pdf
```
* the left, top, right, bottom order.


### Tmux
```
tmux new -s myname # create new session
tmux ls # list all existing seesion
tmux a -t myname # attach to existing session

ctrl+b then "d" # detach
ctrl+b then "[" # to scroll 

```
[tmux cheatsheet](https://gist.github.com/MohamedAlaa/2961058)

### Swith modules on Server
```
module avail # see all available modules
module load # load module
```

### Download git repo with username
```
git clone https://username@github.com/username/repository.git
```

### Remote link
```
ssh -L 8000:127.0.0.1:5000 netID@dmserv4.cs.illinois.edu
```

### Random Sample Files
```
gshuf -n 1000 input.txt > output.txt (on Mac)
shuf -n 1000 input.txt > output.txt (on Linux)
```

### Grep
```
grep -nr 'phrase_to_find' input.txt -m 5 (find first 5 lines that include phrase_to_find)
```

### Grep with Regex
```
grep -P "^.*\t300" input.txt -m 10
```

### Kill any process that occupies a port on **MAC**
```
lsof -ti:target_port | xargs kill -9 (kill target_port process)
```

### Start tensorflow
```
source ~/tensorflow/bin/activate # start
deactivate # end
```

### Config SSH



### Show IP address on Ubuntu
```
$ ifconfig -a
```

### Print results on terminal and save to file
```
python test.py | tee test_tee.txt
```

### Check cpu/
