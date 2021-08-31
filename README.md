# bash_profile-in-zsh
How to use your aliases etc in .bash_profile in .zsh *on macOS*

`cd ~/`
Now that you're in the root folder..
`vi .zprofile`
Insert (press `i` to get in insert mode): `source ~/.bash_profile`
Congrats, new instances will now have your bash_profile shortcuts accessible in zsh.

You can also make a env file that's more accessible and for environment variables `vi .zshenv`.

Notes on the differences in the latter here, though the example is for linux not macOS: 
https://scriptingosx.com/2019/06/moving-to-zsh-part-2-configuration-files/

Of note: 
https://stackoverflow.com/questions/18428374/commands-not-found-on-zsh
