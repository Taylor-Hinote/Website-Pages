# Want to know something that grinds my gears?

When your trying to simply log into your work machine and windows decides to run an update. During this update unknown to you, your place of work had a power outage last night. So now when you boot the machine your windows install is now corrupt and you can't log in. So you have to boot into a live USB and try to fix the issue. With this being my last straw on all the recent personal problems I've had with MS recently I've decided my work machine will be moved over to Ubuntu. Why? Well since it has a simple enough GUI for normal use incase anyone else needs to use this machine, it uses significantly less resources than windows, and it's free. 

## A few things I've ran into so far with this migration.

I had a few issues getting update NodeJS installed on the machine. I had to use the following commands to get it installed.

```bash
    sudo apt-get update
    sudo apt-get install curl
    curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
    sudo apt-get install nodejs
```

At first the same commands kept failing with an unsigned key error. I decided to delete the key and try again. This time it worked. I'm not sure why it failed the first time.


## Final Thoughts

I'm still not 100% sure why windows crashed but for my work machine Ubuntu is a better fit. I am certain I won't be moving my personal machine over to Linux due to the fact it's not having any problems in Windows 11.