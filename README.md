# use



1. Copy the `*.ginignore` file in [github/gitignore](https://github.com/github/gitignore) and put it in the directory: `~/.gitignore_global`

   ```shell
   git clone https://github.com/pifeifei/gitignore
   cd gitignore
   # git checkout self origin/self
   
   # linux & mac OS
   ln -s `pwd`/.gitignore_global ~/.gitignore_global
   # windows
   mklink /j  %HOMEDRIVE%%HOMEPATH%\.gitignore_global  .gitignore_global
   ```

   

2. Run the following command:

    ```shell
    # Global Git ignore
    git config --global core.excludesfile ~/.gitignore

    # linux
    sh sh/.gitignore-create.sh

    # window 
    ./.gitignore-create.bat
    ```

3. done