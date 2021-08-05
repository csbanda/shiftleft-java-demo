# GETTING SOURCE CODE TO LOCAL MACHINE

### Generating your ssh key
#### Generate an SSH key on your local computer. To run the command to generate your keys, you need to have ssh activated on your windows machine
> C:\Users\user>ssh-keygen
>
> Enter file in which to save the key (/home/ylo/.ssh/id_rsa):
>
> Enter passphrase (empty for no passphrase):
>
> Enter same passphrase again:
> 
> Your identification has been saved in <home directory>\<filename>:
> 
> Your public key has been saved in <home directory>\<filename>.pub:
> 
> The key fingerprint is:
> 
> *algorithm-fingerprint*
> 
> The key's randomart image is:
> +---[RSA 2048]----+
> 
> |                 |
> 
> |                 |
> 
> |+ o . .          |
> 
> |.O +.o . .       |
> 
> |o.Oo= o S        |
> 
> | ..Bo= o E .     |
> 
> |  ..=+o...B      |
> 
> |   oo+=+.=.      |
> 
> |   .o+B*=+.      |
> 
> +----[SHA256]-----+:

* Your ssh key will be generated and saved in your user directory
* The passphrase you enter will be used later therefore, keeping it secure and saved is greatly recommemded

### Adding SSH key to your gitlab account
#### Log into the repository using your user credentials
* Click your user icon in the top left corner of your account page
* Select the settings menu
* On the right navigation panel, select the SSH Keys option
* Open the public key that was generated in the ssh key generation process (*file should be called <filename\>.pub*) in your text editor of choice (*e.g. notepad++*)
* Copy the entire content of your public key and paste it into the textarea on the SSH Keys page on GitLab
* Click the <b>Add Key</b> button to save your SSH key

The ssh keys should now configured on your GitLab account

### Cloning your project
#### You may now clone the repository using the git client of your choice
* The cloning links are:

> git@172.17.2.89:cms-backend/cms-portal.git
> 
> or
> 
> http://172.17.2.89/cms-backend/cms-portal.git


A full tutorial can be found <a href='http://172.17.2.89/help/ssh/README#review-existing-ssh-keys'>HERE</a>

