cifaz.ansible-generate-ssh-key
==============================
快速生成sshkey, 需要单独在一台机器生成

### 安装
```
ansible-galaxy install cifaz.generate-ssh-key
```

### 变量
[变量, 目录和名称](vars/main.yml "目录和生成文件名称")


### 示例
```
- hosts: local
  roles:
    - cifaz.generate-ssh-key
```


License
-------

MIT

Author Information
------------------

ccz <hanlin2531@163.com>