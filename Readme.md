Git 学习教程

1. 生成ssh Key并添加到GitHub的个人账号中；

    参考两篇文章：
[Generating a new SSH key and adding it to the ssh-agent](https://help.github.com/en/enterprise/2.15/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent);

[Adding a new SSH key to your GitHub account](https://help.github.com/en/enterprise/2.15/user/articles/adding-a-new-ssh-key-to-your-github-account);

2. 在GitHub新建一个repository；
3. 把GitHub内容clone下来；

    方法有两种：
    git clone [repository_url];
    或者：
    git@github.com:githubUser/repo_name.git
    
4. 把本地和GitHub进行关联；

    比如：
    $ git remote add origin git@github.com:michaelliao/learngit.git
    如果报错：fatal: remote origin already exists.
    则输入：
    git remote set-url origin git@github.com:michaelliao/learngit.git
5. Git 把本地上传到GitHub
    $ git push -u origin master

    


