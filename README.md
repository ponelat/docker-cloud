### docker-cloud
# A bunch of silly utilities to work with cloud.docker.com

## fzf
Install this. Its a fuzzy-completer for the terminal, used by a couple of the utilities...
https://github.com/junegunn/fzf#installation


## Environment variables
```sh
# This could be your .bashrc
export DOCKERCLOUD_USER='ponelat'
export DOCKERCLOUD_NAMESPACE='some-clever-bear'
export DOCKERCLOUD_APIKEY="secretsecret"
```
These are used by the utilities for access control
> PS: The DOCKERCLOUD_NAMESPACE is used if you want access to your organization's docker cloud.


### To get an API key
if ponelat were your name...
To get an API key... go to https://cloud.docker.com and under Settings, you'll see a section on API keys in the left pane. Create a key, there aren't any scope it'll give you full access.


### That said, you should be able to run the tools. They'll spit out help files or do something magical 
Happy figuring-out-what-they did!
