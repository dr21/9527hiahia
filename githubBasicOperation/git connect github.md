## github

### 1 <img src="../images/github/github_index_newRepository.png"/>

### 2 <img src="../images/github/github_index_newRepository.png"/>

## git

```
$ git config --global user.name 'dongrui23' 
$ git config --global user.email '1339450327@qq.com' 
$ ssh-keygen -t rsa -C "1339450327@qq.com"
PS：Enter your github password
$ cat id_rsa.pub
PS: cat + (id_rsa.pub)文件的目录地址，如：$ cat /c/Users/13394/.ssh/id_rsa

copy(-----BEGIN OPENSSH PRIVATE KEY-----
)和(-----END OPENSSH PRIVATE KEY-----
)之间的密钥
```

## github

### 3 <img src="../images/github/github_index_newRepository.png"/>

### 3 <img src="../images/github/github_index_newRepository.png"/>


## git

```
push、pull时可能提示要密码：
$ ssh-agent bash
$ ssh-add -k ~/.ssh/id_rsa
```