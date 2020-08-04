

### HOW THE SCRIPT WORKS? 

The script (installReactDependencies) receives a parameter what is a folder name, this avoid some errors when the command is running.

First, we have to intall the bash script, and we have to clone the current repository, I suggest you intall in home:

* cd ~
* git clone repository  
* nano ~/.bash_profile ( in my case this is my main profile, maybe .bashrc, .zshrc, .kshrc ... )  
* Append to end of file `source ~/.react`  
* You have to typing this command `source ~/.bash_profile`   
* Finally run the command as the below example  
Example :  

```
installReactDependencies myCurrentFolder
``` 