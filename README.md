--------------------------------------------------------------------------------
```

            ('-.      .-') _                   _  .-')    ('-.    _ (`-.                               ('-.              ('-. .-.  ('-.   
           ( OO ).-. (  OO) )                 ( \( -O ) _(  OO)  ( (OO  )                             ( OO ).-.         ( OO )  /_(  OO)  
 ,--.      / . --. ,(_)----. ,--.   ,--.       ,------.(,------._.`     \.-'),-----.          .-----. / . --. /  .-----.,--. ,--(,------.
 |  |.-')  | \-.  \|       |  \  `.'  /        |   /`. '|  .---(__...--'( OO'  .-.  '        '  .--./ | \-.  \  '  .--./|  | |  ||  .---'
 |  | OO .-'-'  |  '--.   / .-')     /         |  /  | ||  |    |  /  | /   |  | |  |        |  |('-.-'-'  |  | |  |('-.|   .|  ||  |     
 |  |`-' |\| |_.'  (_/   / (OO  \   /          |  |_.' (|  '--. |  |_.' \_) |  |\|  |       /_) |OO  \| |_.'  |/_) |OO  |       (|  '--.  
(|  '---.' |  .-.  |/   /___|   /  /\_         |  .  '.'|  .--' |  .___.' \ |  | |  |       ||  |`-'| |  .-.  |||  |`-'||  .-.  ||  .--'  
 |      |  |  | |  |        `-./  /.__)        |  |\  \ |  `---.|  |       `'  '-'  '      (_'  '--'\ |  | |  (_'  '--'\|  | |  ||  `---.
 `------'  `--' `--`--------' `--'             `--' '--'`------'`--'         `-----'          `-----' `--' `--'  `-----'`--' `--'`------'
```
Ascii art from [here](http://patorjk.com/software/taag/#p=display&f=Doom&t=KP%20Kickstart)  
--------------------------------------------------------------------------------

# Welcome to the Lazy Repo Caching Proxy Service
If you have a dev project that installs anything from a package repo,
you are going to want to install this!

# Usage
./run-repo-cache.bsh
* starts a caching proxy docker container, named "kp-yum-repo-cache"
./view-cache-logs.bsh
* tail and follows the caching proxy logs.  ctrl-c to exit.

# Directory Guide

* `cache`
  * This is where the local cache files get dumped.

# ToDos
Add example showing how to connect dev projects to the caching service.
