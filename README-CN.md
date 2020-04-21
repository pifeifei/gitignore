# 使用说明

> 更多 .gitignore 文件：[github/gitignore](https://github.com/github/gitignore) 



1. 复制 `*.ginignore` ([github/gitignore](https://github.com/github/gitignore)) 文件到目录: `~/.gitignore_global`，或使用 ln、mklink 做软连接

   ```shell
   git clone https://github.com/pifeifei/gitignore
   cd gitignore
   # git checkout self origin/self
   
   # linux & mac OS
   ln -s `pwd`/.gitignore_global ~/.gitignore_global
   # windows
   mklink /j  %HOMEDRIVE%%HOMEPATH%\.gitignore_global  .gitignore_global
   ```



2. 运行以下命令：

    ```shell
    # Global Git ignore
    git config --global core.excludesfile ~/.gitignore

    # linux
    sh sh/.gitignore-create.sh

    # window 
    ./.gitignore-create.bat
    ```

3. 完成