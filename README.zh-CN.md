��������(cocker)
===================

<!-- TOC -->

- [1. ����](#1-����)
    - [1.1. cocker��ʲô��](#11-cocker��ʲô)
    - [1.2. ϵͳ�ܹ�](#12-ϵͳ�ܹ�)
        - [1.2.1. ״̬Ǩ��ͼ](#121-״̬Ǩ��ͼ)
        - [1.2.2. ����ļ�ϵͳ](#122-����ļ�ϵͳ)
        - [1.2.3. ����](#123-����)
        - [1.2.4. ϵͳ��Դ����](#124-ϵͳ��Դ����)
        - [1.2.5. α�ն�](#125-α�ն�)
    - [1.3. ����ʹ��](#13-����ʹ��)
- [2. ��װ](#2-��װ)
    - [2.1. LinuxԴ�����](#21-linuxԴ�����)
        - [2.1.1. ȷ���������Ѱ�װ](#211-ȷ���������Ѱ�װ)
        - [2.1.2. ȷ���ں�ת�������ѿ���](#212-ȷ���ں�ת�������ѿ���)
        - [2.1.3. ׼��cockerԴ��](#213-׼��cockerԴ��)
        - [2.1.4. ���밲װ](#214-���밲װ)
- [3. ʹ�ý̳�](#3-ʹ�ý̳�)
    - [3.1. cockerָ��](#31-cockerָ��)
        - [3.1.1. ���⸽��ѡ��](#311-���⸽��ѡ��)
        - [3.1.2. ��ѯ�����б�](#312-��ѯ�����б�)
        - [3.1.3. �ɾ��񴴽�����](#3.1.�ɾ��񴴽�����)
        - [3.1.4. ��ѯ�����б�](#3.2.��ѯ�����б�)
        - [3.1.5. ��������](#315-��������)
        - [3.1.6. ��������](#316-��������)
        - [3.1.7. ֹͣ����](#317-ֹͣ����)
        - [3.1.8. ɱ������](#318-ɱ������)
        - [3.1.9. ��������](#319-��������)
        - [3.1.10. �޸ľ�������](#3110-�޸ľ�������)
            - [3.1.10.1. �޸İ汾��](#31101-�޸İ汾��)
        - [3.1.11. �޸���������](#3111-�޸���������)
            - [3.1.11.1. �޸�VIP](#31111-�޸�vip)
            - [3.1.11.2. �޸������˿�ӳ��](#31112-�޸������˿�ӳ��)
            - [3.1.11.3. �޸���Ҿ�ӳ��](#31113-�޸���Ҿ�ӳ��)
        - [3.1.12. ����ת��Ϊ����](#3112-����ת��Ϊ����)
        - [3.1.13. ����ת��Ϊ����](#31.1.����ת��Ϊ����)
        - [3.1.14. ���ƾ���](#31.2.���ƾ���)
        - [3.1.15. ɾ������](#3115-ɾ������)
        - [3.1.16. ��������](#3116-��������)
        - [3.1.17. ���뾵��](#3117-���뾵��)
        - [3.1.18. �ϴ�����ssh�����](#3118-�ϴ�����ssh�����)
        - [3.1.19. ��ssh��������ؾ���](#3119-��ssh��������ؾ���)
        - [3.1.20. �ϴ�����cocker���о����](#3120-�ϴ�����cocker���о����)
        - [3.1.21. ��cocker���о�������ؾ���](#3121-��cocker���о�������ؾ���)
        - [3.1.22. ��������ִ������������](#3122-��������ִ������������)
        - [3.1.23. �滻�������ļ�����](#3123-�滻�������ļ�����)
        - [3.1.24. �����������ļ���Ŀ¼��������](#3124-�����������ļ���Ŀ¼��������)
        - [3.1.25. �����������ļ���Ŀ¼��������](#3125-�����������ļ���Ŀ¼��������)
        - [3.1.26. �õ�������Ŀ¼��������·��](#3126-�õ�������Ŀ¼��������·��)
    - [3.2. �ű�](#32-�ű�)
        - [3.2.1. �������Ծ�����ļ�ϵͳ�ű�](#321-�������Ծ�����ļ�ϵͳ�ű�)
        - [3.2.2. ��������ϵͳ��������ű�](#322-��������ϵͳ��������ű�)
        - [3.2.3. ����sshd����ű�](#323-����sshd����ű�)
        - [3.2.4. ����gcc����ű�](#324-����gcc����ű�)
        - [3.2.5. ����������Ŀ¼��������](#325-����������Ŀ¼��������)
    - [3.3. ����ʾ��](#33-����ʾ��)
        - [3.3.1. ����ʽ����yum����](#331-����ʽ����yum����)
        - [3.3.2. ����ʽ����sshd����](#332-����ʽ����sshd����)
        - [3.3.3. ����ʽ����G6����](#333-����ʽ����G6����)
        - [3.3.4. ��������ʵ��������������](#334-��������ʵ��������������)
        - [3.3.5. ��������������](#335-��������������)
- [4. ���](#4-���)
    - [4.1. ����cocker](#41-����cocker)
    - [4.2. ��������](#42-��������)

<!-- /TOC -->

# 1. ����

## 1.1. cocker��ʲô

`cocker`���Ҹ�����C������ȫ���е��������棨�Ա�`Docker`��`����Pouch`������Ҫ������¹��������е�ʹ�㣺

* ԭ��֧�ֶ���̼ܹ�������ʹ��ģʽ��������������������
* ������������ʽ��������������ʽ��������д������Dockerfile���˶����ʹ����
* �����汾�������
* ������...��

`cocker`ʹ�õ�������Linux�ײ㼼����`LXC`��`cgroup`��`overlayfs`��`iptables`��`ptms`�ȡ�

## 1.2. ϵͳ�ܹ�

![images/cocker_architecture.png](images/cocker_architecture.png)

��LXC�У�����ֻ���ں������ռ����ĸ������Լ��ӽ����������������������֡����̿ռ䡢���ļ�ϵͳ��IPC������ȡ�`cocker`������ʵ�����������и������������������������������������ʽ��Ҳ֧������`Docker`�ĵ����̷�ʽ��

`cocker`�Դ������������̣�����ͨ��α�ն˷�ʽ�Ž��������⣬�����Ǳ���ͨ��`ssh`��

`cgroup`����������ϵͳ��Դ�ܿأ�����CPU���ڴ�ȡ�

### 1.2.1. ״̬Ǩ��ͼ

![images/cocker_state_transition_diagram.png](images/cocker_state_transition_diagram.png)

`cocker`������Ա��ع�����Ӿ�����ϴ����أ������Ŀǰֻ֧��`ssh`����ˣ������汾�л����`cocker`ԭ����������

`cocker`��������ͬ�汾���棬��������ʱ����ָ������汾������Ĭ�����°档������Ը��ƺ�ɾ����Ҳ�����޸İ汾�š�

`cocker`������������������������رպ����١��޸���������������IP���˿�ӳ��;�ӳ������������ر�״̬�½��С�

`cocker`�������ת��Ϊ`cocker`�������ڽ���ʽ�޸ģ�Ȼ����ת��������

### 1.2.2. ����ļ�ϵͳ

![images/cocker_overlayfs.png](images/cocker_overlayfs.png)

����ļ�ϵͳ�Ƕྵ�������Ĵ洢������cocker����overlayfs��Ϊ�����ļ�ϵͳ���棬���Ե��Ӽ������޵ľ���㡣

`cocker`�ľ���������ȶ�����ڻ�������`COCKER_HOME`ָ�����Ŀ¼�У����Թ滮��������ʹ��ǰ����Ҫ���ǵ����⡣���û�����û�������`COCKER_HOME`����Ĭ��ָ��`/var/cocker`��

`COCKER_HOME`��Ŀ¼���о�����Ŀ¼`images`��������Ŀ¼`containers`��`ssh`����ֿ�`srepo`���Լ���־�ļ�`cocker.log`��

### 1.2.3. ����

![images/cocker_network.png](images/cocker_network.png)

`cocker`֧����������ģ�ͣ�HOST��CUSTOM��BRIDGE��

| ����ģ�� | ˵�� |
|---------|------|
| HOST | ��Ԥ�����绷�� |
| CUSTOM | ����Ԥ�����������ռ䣬�������������������ȣ�����ȫ���û������� |
| BRIDGE | Ԥ����NAT��ʽ����������������������ͨ��ʽ���Զ������ָ���˿�ӳ��ת������������������������ͨ��ʽ |

�״�ִ��`cocker`�ᴴ�������豸`cocker0`������Ϊ`166.88.0.x`��

### 1.2.4. ϵͳ��Դ����

![images/cocker_cgroup.png](images/cocker_cgroup.png)

`cocker`Ŀǰֻʵ����CPU�˷��䡢ʱ��Ƭռ�ðٷֱȷ��䡢�ڴ���䣬����ϵͳ��Դ�ں����汾�л������ơ�

### 1.2.5. α�ն�

![images/cocker_pty.png](images/cocker_pty.png)

�Դ����������̽��ܿͻ���`cocker`���Ӻ�ᴴ��α�ն˻Ự�������¼�����������������һ��������ʹ��`ssh`��

## 1.3. ����ʹ��

ʹ�����ع���cocker���ٴ���һ��С�Ͳ��Ծ�������������Դ��ű�`cocker_install_test.sh`�������ļ�ϵͳ��

Ȼ��ʹ��ָ��`-a boot`���ڸոմ����ľ���`test`����һ������`test`������ֱ�Ӵ�һ���Ự���ӵ������е�α�ն�...�˳�α�ն˺�ʹ��ָ��`-a shutdown`�ر����������ʹ��ָ��`-a destroy`����������

```
# cocker -a install_test
OK
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
test                           _          2018-11-10T09:21:12 24 MB
# cocker -a create -m test -c test
OK
# cocker -a boot -c test -t   
connect to container ok
--- Welcome to cocker contrainer ---

[root@test /root] exit
logout
# cocker -a shutdown -c test
OK
# cocker -a destroy -c test
OK
```

# 2. ��װ

## 2.1. LinuxԴ�����

### 2.1.1. ȷ���������Ѱ�װ

```
yum install -y telnet
yum install -y nmap-ncat
yum install -y bridge-utils
yum install -y man-pages
yum install -y supermin5
```

### 2.1.2. ȷ���ں�ת�������ѿ���

��ʱ����

```
# echo "1" >/proc/sys/net/ipv4/ip_forward
```

�����ÿ���

```
# echo "net.ipv4.ip_forward=1" >>/etc/sysctl.conf
# sysctl -p
```

### 2.1.3. ׼��cockerԴ��

����cockerԴ������⿪������

```
# tar xvzf cocker-X.X.X.tar.gz
# cd cocker-X.X.X
```

���¡cockerԴ��⣬����

```
# git clone https://gitee.com/calvinwilliams/cocker
# cd cocker
```

or

```
# git clone https://github.com/calvinwilliams/cocker
# cd cocker
```

### 2.1.4. ���밲װ

ע�⣺������ڷ�root�û�����Դ�룬ȷ��`sudo`�����������롣

�����м��ļ�

```
# make -f makefile.Linux clean
make[1]: ����Ŀ¼��/home/calvin/src/cocker/shbin��
make[1]: �뿪Ŀ¼��/home/calvin/src/cocker/shbin��
make[1]: ����Ŀ¼��/home/calvin/src/cocker/src��
make[2]: ����Ŀ¼��/home/calvin/src/cocker/src/util��
rm -f list.o
rm -f LOGC.o
rm -f version.o
rm -f file.o
rm -f string.o
rm -f socket.o
rm -f pts.o
rm -f libcocker_util.so
make[2]: �뿪Ŀ¼��/home/calvin/src/cocker/src/util��
make[2]: ����Ŀ¼��/home/calvin/src/cocker/src/cocker��
rm -f util.o
rm -f main.o
rm -f env.o
rm -f show_images.o
rm -f show_containers.o
rm -f action_create.o
rm -f action_destroy.o
rm -f action_boot.o
rm -f action_shutdown.o
rm -f action_version.o
rm -f action_vip.o
rm -f action_port_mapping.o
rm -f action_volume.o
rm -f action_attach.o
rm -f action_install_test.o
rm -f action_to_container.o
rm -f action_to_image.o
rm -f action_copy_image.o
rm -f action_del_image.o
rm -f action_export.o
rm -f action_import.o
rm -f show_ssearch.o
rm -f action_spush.o
rm -f action_spull.o
rm -f cocker
make[2]: �뿪Ŀ¼��/home/calvin/src/cocker/src/cocker��
make[2]: ����Ŀ¼��/home/calvin/src/cocker/src/cockerinit��
rm -f main.o
rm -f server.o
rm -f pty.o
rm -f pts_and_tcp_bridge.o
rm -f cockerinit
make[2]: �뿪Ŀ¼��/home/calvin/src/cocker/src/cockerinit��
make[1]: �뿪Ŀ¼��/home/calvin/src/cocker/src��
```

���벢��װ��ϵͳĿ¼��

ע�⣺������ڷ�root�û�����Դ�룬ǰ�����`sudo -E`��

```
# make -f makefile.Linux install
make[1]: ����Ŀ¼��/home/calvin/src/cocker/src��
make[2]: ����Ŀ¼��/home/calvin/src/cocker/src/util��
rm -f list.o
rm -f LOGC.o
rm -f version.o
rm -f file.o
rm -f string.o
rm -f socket.o
rm -f pts.o
rm -f libcocker_util.so
make[2]: �뿪Ŀ¼��/home/calvin/src/cocker/src/util��
make[2]: ����Ŀ¼��/home/calvin/src/cocker/src/cocker��
rm -f util.o
rm -f main.o
rm -f env.o
rm -f show_images.o
rm -f show_containers.o
rm -f action_create.o
rm -f action_destroy.o
rm -f action_boot.o
rm -f action_shutdown.o
rm -f action_version.o
rm -f action_vip.o
rm -f action_port_mapping.o
rm -f action_volume.o
rm -f action_attach.o
rm -f action_install_test.o
rm -f action_to_container.o
rm -f action_to_image.o
rm -f action_copy_image.o
rm -f action_del_image.o
rm -f action_export.o
rm -f action_import.o
rm -f show_ssearch.o
rm -f action_spush.o
rm -f action_spull.o
rm -f cocker
make[2]: �뿪Ŀ¼��/home/calvin/src/cocker/src/cocker��
make[2]: ����Ŀ¼��/home/calvin/src/cocker/src/cockerinit��
rm -f main.o
rm -f server.o
rm -f pty.o
rm -f pts_and_tcp_bridge.o
rm -f cockerinit
make[2]: �뿪Ŀ¼��/home/calvin/src/cocker/src/cockerinit��
make[1]: �뿪Ŀ¼��/home/calvin/src/cocker/src��
make[1]: ����Ŀ¼��/home/calvin/src/cocker/shbin��
make[1]: �뿪Ŀ¼��/home/calvin/src/cocker/shbin��
make[1]: ����Ŀ¼��/home/calvin/src/cocker/src��
make[2]: ����Ŀ¼��/home/calvin/src/cocker/src/util��
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99  -c list.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99  -c LOGC.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99  -c version.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99  -c file.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99  -c string.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99  -c socket.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99  -c pts.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -o libcocker_util.so list.o LOGC.o version.o file.o string.o socket.o pts.o -shared -L. -L/lib64 -L/usr/lib64 -L/usr/lib 
rm -f /lib64/libcocker_util.so
cp -rf libcocker_util.so /lib64/
rm -f /usr/include/cocker_in/list.h
cp -rf list.h /usr/include/cocker_in/
rm -f /usr/include/cocker_in/LOGC.h
cp -rf LOGC.h /usr/include/cocker_in/
rm -f /usr/include/cocker_in/cocker_util.h
cp -rf cocker_util.h /usr/include/cocker_in/
make[2]: �뿪Ŀ¼��/home/calvin/src/cocker/src/util��
make[2]: ����Ŀ¼��/home/calvin/src/cocker/src/cocker��
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c util.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c main.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c env.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c show_images.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c show_containers.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_create.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_destroy.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_boot.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_shutdown.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_version.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_vip.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_port_mapping.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_volume.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_attach.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_install_test.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_to_container.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_to_image.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_copy_image.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_del_image.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_export.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_import.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c show_ssearch.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_spush.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c action_spull.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -o cocker util.o main.o env.o show_images.o show_containers.o action_create.o action_destroy.o action_boot.o action_shutdown.o action_version.o action_vip.o action_port_mapping.o action_volume.o action_attach.o action_install_test.o action_to_container.o action_to_image.o action_copy_image.o action_del_image.o action_export.o action_import.o show_ssearch.o action_spush.o action_spull.o -L. -L/lib64 -L/usr/lib64 -L/usr/lib -L/lib64 -lcocker_util -lcrypto 
rm -f /bin/cocker
cp -rf cocker /bin/
make[2]: �뿪Ŀ¼��/home/calvin/src/cocker/src/cocker��
make[2]: ����Ŀ¼��/home/calvin/src/cocker/src/cockerinit��
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c main.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c server.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c pty.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -I. -I/usr/include -I/usr/include -std=gnu99 -I/usr/include/cocker_in  -c pts_and_tcp_bridge.c
gcc -g -fPIC -O2 -Wall -Werror -fno-strict-aliasing -o cockerinit main.o server.o pty.o pts_and_tcp_bridge.o -L. -L/lib64 -L/usr/lib64 -L/usr/lib -L/lib64 -lcocker_util -lcrypto 
rm -f /bin/cockerinit
cp -rf cockerinit /bin/
make[2]: �뿪Ŀ¼��/home/calvin/src/cocker/src/cockerinit��
make[1]: �뿪Ŀ¼��/home/calvin/src/cocker/src��
make[1]: ����Ŀ¼��/home/calvin/src/cocker/shbin��
rm -f /bin/cocker_ldd_and_cp_lib64.sh
cp -rf cocker_ldd_and_cp_lib64.sh /bin/
rm -f /bin/cocker_profile_template.sh
cp -rf cocker_profile_template.sh /bin/
rm -f /bin/cocker_etc_profile_template.sh
cp -rf cocker_etc_profile_template.sh /bin/
rm -f /bin/cocker_install_test.sh
cp -rf cocker_install_test.sh /bin/
rm -f /bin/cocker_create_image_rhel-7.4-x86_64.sh
cp -rf cocker_create_image_rhel-7.4-x86_64.sh /bin/
rm -f /bin/cocker_create_image_rhel-7.4-gcc-x86_64.sh
cp -rf cocker_create_image_rhel-7.4-gcc-x86_64.sh /bin/
make[1]: �뿪Ŀ¼��/home/calvin/src/cocker/shbin��
```

���û�з���������������밲װ�ɹ��������������л�֪��

* �����������ڲ�ʹ��ͷ�ļ�`src/cocker/*.h`��װ��`/usr/include/cocker_in`�����ļ�`libcocker_util.so`��װ��`/lib64`�������ڲ��ļ������ڱ��롣
* ��������ִ���ļ�`cocker`��`cockerinit`��װ��`/bin`��
* �Դ��ű�`shbin/*.sh`��װ��`/bin`��

# 3. ʹ�ý̳�

## 3.1. cockerָ��

����ѡ��ִ��`cocker`���õ�����ָ���ѡ���б�

```
# cocker
USAGE : cocker -v
               -s images
               -s containers
               -a create (-m|--image) (image[:version])[,(image[:version])]... [ create options ] [ (-c|--container) (container) ] [ (-b|--boot) [ cgroup options ] [ (-t|--attach) | (-e|--exec) (cmd|"program para1 ...") ] ]
               -a boot (-c|--container) (container) [ cgroup options ] [ (-t|--attach) | (-e|--exec) (cmd|"program para1 ...") ]
               -a attach (-c|--container) (container)
               -a shutdown (-c|--container) (container) [ (-f|--forcely) ]
               -a kill (-c|--container) (container) [ (-f|--forcely) ]
               -a destroy (-c|--container) (container) [ (-f|--forcely) ] [ (-h|--shutdown) ]
               -a version (-m|--image) (image[:version]) [ --version (version) ]
               -a vip (-c|--container) (container) --vip (ip)
               -a port_mapping (-c|--container) (container) --port-mapping (src_port:dst_port)
               -a volume (-c|--container) (container) --volume (host_path[:container_path])[ ...]
               -a to_image --from-container (container) [ --verion (verion) ] --to-image (image)
               -a to_container --from-image (image[:version]) (-m|--image) (image[:version])[,(image[:version])]... [ create options ] --to-container (container)
               -a copy_image --from-image (image[:version]) --to-image (image[:version])
               -a del_image (-m|--image) (image[:version])
               -a import --image-file (file)
               -a export (-m|--image) (image[:version])
               -s ssearch --srepo (user@host)
               -a install_test
create options : [ --volume (host_path:container_path) ][ --volume ... ] [ --host (hostname) ] [ --net (BRIDGE|HOST|CUSTOM) ] [ --host-eth (eth) ] [ --vip (ip) ] [ --port-mapping (src_port:dst_port) ]
cgroup options : [ --cpus [(cpu_num,...)|(cpu_num-cpu_num2)] ] [ --cpu-quota (percent%) ] [ --mem-limit (num|numM) ]
  enable debug : [ (-d|--debug) ]
```

ע�⣺�״�ִ��`cocker`���Զ�����������Ŀ¼`images`��������Ŀ¼`containers`��

### 3.1.1. ���⸽��ѡ��

`cocker`ѡ��`-d`�������ִ��ʱ������Ϣ�������������е�����Ϣ�����������Ļ�ϣ�ĳЩ�����������Ļ����Ϣ���¼����־�ļ���`cocker.log`���������Ļ�ϵ���ϢҲ�Ḵ��һ�ݵ���־�ļ��С�

`cocker`ѡ��`-f`����ǿ��ִ�ж�����һЩ��������һЩָ���к����á�

### 3.1.2. ��ѯ�����б�

ʹ��`cocker`ָ��`-s images`��ѯ������Ŀ¼������о���

```
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
test                           _          2018-11-10T09:21:12 24 MB
```

����Ŀ¼���Ϊ`������/�汾��/����Ŀ¼�ļ�����`�����û�а汾�ţ��汾��Ŀ¼��Ϊ`_`��

��������ʽ�Ƽ�`(����������֯��)=(�����)-(����汾��)`���汾�Ÿ�ʽ�Ƽ�`x.y.z`��

���ǿ���ʹ��ָ��`-a install_test`������ͬ�汾�Ĳ��Ծ��񣬶�汾�������

```
# cocker -a install_test --version "1.0.0"
OK
# cocker -a install_test --version "1.1.0"   
OK
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
test                           _          2018-11-10T09:21:12 24 MB
test                           1.0.0      2018-11-14T07:20:06 24 MB
test                           1.1.0      2018-11-14T07:20:17 24 MB
```

### 3.1.3. �ɾ��񴴽�����

ʹ��`cocker`ָ��`-a create`��һ������������Ӵ���������

```
# cocker -a create -m test --host test --net BRIDGE --vip 166.88.0.2 --port-mapping 19527:9527 -c test
OK
```

`-m (�����б�)`:ָ�������б�������������`(������)(:�汾��)`��ʽָ���汾�ţ���ָ��������ָ���汾�ţ�`cocker`���Զ���ѡһ�����汾�ŵľ��񡣶������֮����`,`�ָ���

`--host (������)`:���������ڵ���������

`--net (����ģ��)`:������������ģ�ͣ���ǰ������ģ���½ڡ�

`--vip (ip)`:�������ģ��Ϊ`BRIDGE`�����������ڵ�����IP��

`--port-mapping (����˿�ӳ���б�)`:�������ģ��Ϊ`BRIDGE`�������ⲿ����������������������˿�ӳ���б��˿�ӳ���ʽΪ`(�������˿�):(�����˿�)`������˿�ӳ��֮����`,`�ָ���

`-c (������)`:ָ��������������ָ�����뾵��ͬ��������ָ����

��������ʾ�����õ���ѡ�����Ϊ������ѡѡ�

`--host-eth (������)`:ָ�����������������������ڶ���������ʱʹ�á�

`--volume (���̾�ӳ���б�)`:���̾�ӳ������������������֮��Ŀ¼�������ø�ʽΪ`(������Ŀ¼:����Ŀ¼)`��������̾�ӳ��ʹ�ø��Ե�ѡ���ǰ׺`--volume`��

`-b`:��������������������������׷��������������ѡ�

### 3.1.4. ��ѯ�����б�

ʹ��`cocker`ָ��`-s containers`��ѯ������Ŀ¼�е����������Լ�״̬��

```
# cocker -s containers
container_id         image                hostname   net        netns            size       status
-----------------------------------------------------------------------------------------------------------
test                 test                 test       BRIDGE     nns098F6BCD46    0 B        STOPED
```

����`test`״̬Ϊֹͣ��

### 3.1.5. ��������

ʹ��`cocker`ָ��`-a boot`��ѯ������Ŀ¼�е����������Լ�״̬��

```
# cocker -a boot -c test
OK
```

��������ʾ�����õ���ѡ�����Ϊ������ѡѡ�

`--cpus (CPU���б�)`:�������Ƶ�CPU���б������һ��CPU��`0`������ǰ����CPU��`0,1`,����ڶ���CPU�˵���ʮ��CPU��`1-9`��

`--cpu-quota (num%)`:�������Ƶ�CPU�����ʣ�������ȫ����`100%`������ֻ�������ķ�֮һ`25%`��

`--mem-limit (numM)`:�������Ƶ��ڴ�����������`100M`��

`-t`:�����������������ӡ�

`-e (cmd)`:ָ�����������̣�Ĭ��ʹ��`cocker`�Դ���`cockerinit`��

�������ٲ鿴����״̬

```
# cocker -s containers  
container_id         image                hostname   net        netns            size       status
-----------------------------------------------------------------------------------------------------------
test                 test                 test       BRIDGE     nns098F6BCD46    0 B        RUNNING(89698)
```

ע�⣺Ĭ�����������ĸ�����Ϊ`cockerinit`���ɼ򵥴���ϵͳ`init`���̻��չ¶����̡�����α�ն˵ȹ��ܡ�

### 3.1.6. ��������

���ʹ��`cockerinit`��Ϊ����������������ʹ��`cocker`ָ��`-a attch`������������`cockerinit`��һ���Ự���ӵ������е�α�նˡ�Ҳ�ɵ���ssh����������������ssh������������ssh������������

```
# cocker -a attach -c test   
connect to container ok
--- Welcome to cocker contrainer ---

[root@test /root] 
```

ע�⣺�����þ���`test`�Ѱ����˾�������ر����߰������������С�

��α�ն�������`exit`�ӻس��ɹرջỰ��

```
[root@test /root] exit
logout
#
```

### 3.1.7. ֹͣ����

ʹ��`cocker`ָ��`-a shutdown`ֹͣ������

```
# cocker -a shutdown -c test   
OK
```

```
# cocker -s containers          
container_id         image                hostname   net        netns            size       status
-----------------------------------------------------------------------------------------------------------
test                 test                 test       BRIDGE     nns098F6BCD46    0 B        STOPED
```

### 3.1.8. ɱ������

ʹ��`cocker`ָ��`-a kill`ǿɱ������

### 3.1.9. ��������

ʹ��`cocker`ָ��`-a destroy`����������

ע�⣺���������������������޸Ľ���ʧ��

```
# cocker -a destroy -c test
OK
```

��������ʾ�����õ���ѡ�����Ϊ������ѡѡ�

`-h`:��ֹͣ����Ȼ����������������

`-f`:�������������к��Դ���Ĭ�ϻ��ж����ٹ��̡�

### 3.1.10. �޸ľ�������

#### 3.1.10.1. �޸İ汾��

ʹ��`cocker`ָ��`-a version`�޸ľ���汾�š�

```
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
test                           _          2018-11-10T09:21:12 24 MB
# cocker -a version -m test --version "1.0.1"
OK
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
test                           1.0.1      2018-11-10T09:21:12 24 MB
# cocker -a version -d -m "test:1.0.1" --version "1.0.2"
OK
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
test                           1.0.2      2018-11-10T09:21:12 24 MB
# cocker -a version -d -m "test:1.0.2"
OK
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
test                           _          2018-11-10T09:21:12 24 MB
```

### 3.1.11. �޸���������

#### 3.1.11.1. �޸�VIP

ʹ��`cocker`ָ��`-a vip`�޸�����������IP��

ע�⣺��������ֹͣ������޸ġ�

```
# cocker -a vip --vip 166.88.0.3 -c test
OK
```

#### 3.1.11.2. �޸������˿�ӳ��

ʹ��`cocker`ָ��`-a port_mapping`�޸���������˿�ӳ�䡣

ע�⣺��������ֹͣ������޸ġ�

```
# cocker -a port_mapping --port-mapping 19528:9528 -c test
OK
```

#### 3.1.11.3. �޸���Ҿ�ӳ��

ʹ��`cocker`ָ��`-a volume`�޸��������̾�ӳ�䡣

ע�⣺��������ֹͣ������޸ġ�

```
# cocker -a volume --volume "/tmp:/tmp" --volume "/mnt/cdrom:/mnt/cdrom" -c test
OK
```

### 3.1.12. ����ת��Ϊ����

����Ҫ�޸ľ������ļ�ʱ���ȰѾ���ת��Ϊ�������޸����ת���ؾ���

ʹ��`cocker`ָ��`-a to_container`ת��ָ������Ϊ������

```
# cocker -a to_container --from-image test --host test --net BRIDGE --vip 166.88.0.2 --port-mapping 19527:9527 --to-container test
OK
```

ע�⣺������ʹ������ָ��`-a create`��ѡ�

### 3.1.13. ����ת��Ϊ����

�����ĳһ��������ɾ��񣬿�ʹ�ô�ָ�

ʹ��`cocker`ָ��`-a to_image`ת��ָ������Ϊ����

ע�⣺ת��������������ֹͣ�ġ�

```
# cocker -a to_image --from-container test --to-image test
OK
```

### 3.1.14. ���ƾ���

ʹ��`cocker`ָ��`-a copy_image`�ɸ��ƾ���

```
# cocker -a copy_image --from-image test --to-image "test2:1.0.0"
OK
```

### 3.1.15. ɾ������

ʹ��`cocker`ָ��`-a del_image`��ɾ������

```
# cocker -a del_image -m "test2:1.0.0"   
OK
```

### 3.1.16. ��������

ʹ��`cocker`ָ��`-a export`�ɵ�������Ϊ�������ļ���

```
# cocker -a export -m "test:1.1.0"   
OK
```

### 3.1.17. ���뾵��

ʹ��`cocker`ָ��`-a import`�ɴӾ������ļ����뾵��⡣

ע�⣺�������ļ�����չ��������`.cockerimage`��

```
# cocker -a del_image -m "test:1.1.0"
OK
# cocker -a import --image-file "test:1.1.0.cockerimage"   
OK
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
test                           1.1.0      2018-11-14T08:53:13 24 MB
```

### 3.1.18. �ϴ�����ssh�����

ssh�����������ssh�������������⡣���Ȱ�װssh������������������û����ӿͻ��˲�����Կ�ļ��ַ���������Է������ܵ�¼��

```
# ssh-keygen -t rsa
...
# ssh-copy-id -i ~/.ssh/id_rsa.pub cockerimages@192.168.6.74
```

ʹ��`cocker`ָ��`-s ssearch`�ɲ鿴ssh�������ľ����б�

```
# cocker -s ssearch --srepo "cockerimages@192.168.6.74"
OK
```

ע�⣺`cocker`����ssh������ַ����`cockerimages@192.168.6.74`��

���ܼ����Ӵ�ͨ��ѡ��`--match`��

```
# cocker -s ssearch --match test
```

ʹ��`cocker`ָ��`-a spush`�ϴ�����ssh����⡣

```
# cocker -a spush -m "test:1.0.0"
OK
# cocker -s ssearch --match test
cocker -s ssearch   
image_id                                      modify_datetime     size      
----------------------------------------------------------------------
test:1.0.0                                    2018-11-14T9:05:48  11 MB
```

### 3.1.19. ��ssh��������ؾ���

ʹ��`cocker`ָ��`-a spull`��ssh��������ؾ���

```
# 
cocker -a del_image -m "test:1.0.0"
OK
# cocker -a spull -m "test:1.0.0"
OK
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
test                           1.0.0      2018-11-14T09:09:04 24 MB
```

### 3.1.20. �ϴ�����cocker���о����

�����з���

### 3.1.21. ��cocker���о�������ؾ���

�����з���

### 3.1.22. ��������ִ������������

ʹ��`cocker`ָ��`-a run`��������ִ������������

```
# cocker -a run -c test --cmd "hostname"
test
#
```

ע�⣺�����Ǳ���������״̬��

### 3.1.23. �滻�������ļ�����

ʹ��`cocker`ָ��`-a rplfile`�滻�������ļ�����

```
# cocker -a rplfile -c test --template-file "/root/tpl.txt" --mapping-file "map.txt" --instance-file "/root/ins.txt"
OK
#
```

`--template-file`��`--instance-file`�ֱ�Ϊģ���ļ���ʵ�����ļ�����������·����ʡ��`--instance-file`���滻`--template-file`�Լ���

`--mapping-file`Ϊ�滻���ã���������·����һ������Ϊһ�У�
```
(KEY) (VALUE)\n
(KEY) (VAL UE)\n
...\n
```

�滻ʾ����

`tpl.txt`
```
{ "leaf":"${LEAF}" }
```

`map.txt`
```
${LEAF} �ҵ���Ҷ
```

�滻���`ins.txt`
```
{ "leaf":"�ҵ���Ҷ" }
```

���滻���ܱ��㷺����ʵ����������Ӧ�������ļ���

ע�⣺�����Ǳ���������״̬��

### 3.1.24. �����������ļ���Ŀ¼��������

ʹ��`cocker`ָ��`-a putfile`�����������ļ���Ŀ¼��������

```
# cocker -a putfile -c test --src-file "map.txt" --dst-file "/root/"
OK
#
```

ע�⣺Ҳ��ͨ��ssh�ȷ����ơ�

### 3.1.25. �����������ļ���Ŀ¼��������

ʹ��`cocker`ָ��`-a getfile`�����������ļ���Ŀ¼��������

```
# cocker -a getfile -c test --src-file "/root/map.txt" --dst-file "./"
OK
#
```

ע�⣺Ҳ��ͨ��ssh�ȷ����ơ�

### 3.1.26. �õ�������Ŀ¼��������·��

ʹ��`cocker`ָ��`-s container_root`�õ�������Ŀ¼��������·��

```
# cocker -s container_root -c test
/var/cocker/containers/test/merged
#
```

ע�⣺��¶������Ŀ¼���ܲ�̫���ʡ�

## 3.2. �ű�

### 3.2.1. �������Ծ�����ļ�ϵͳ�ű�

```
# cocker_install_test.sh
```

ע�⣺Ӧ��`cocker`ָ��`-a install_test`���ʹ�á�

### 3.2.2. ��������ϵͳ��������ű�

ע�⣺���������ʹ��yumΪǰ�ᡣ
ע�⣺������ɾ������޸�`supermin5 -v --prepare`�������б�

```
# cocker_create_image_rhel-7.4-x86_64.sh
...
# ls -l calvin=rhel-7.4-x86_64:1.0.0.cockerimage
-rw-r--r--  1 root root 91781857 Nov 25 09:03 calvin=rhel-7.4-x86_64:1.0.0.cockerimage
```

ִ�к��������ֺͰ汾�ţ��Զ����ɿɵ���ľ������ļ����ļ�����ʽΪ`(����)=(rhel-7.4-x86_64):(�汾��).cockerimage`

```
# cocker -a import --image-file calvin=rhel-7.4-x86_64:1.0.0.cockerimage
OK
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
calvin=rhel-7.4-x86_64         1.0.0      2018-11-25T09:03:48 228 MB
```

### 3.2.3. ����sshd����ű�

��Ϊ����sshd����㾵�����ļ���

```
# cocker_create_image_rhel-7.4-sshd-x86_64.sh
```

ע�⣺�����½�ͨ������ʽ�����ɴﵽ��С���ɾ��ľ���

### 3.2.4. ����gcc����ű�

��Ϊ����gcc����㾵�����ļ���

```
# cocker_create_image_rhel-7.4-gcc-x86_64.sh
```

ע�⣺�����½�ͨ������ʽ�����ɴﵽ��С���ɾ��ľ���

### 3.2.5. ����������Ŀ¼��������

```
# . cocker_container_root.sh test
$ echo $COCKER_CONTAINER_ROOT
/var/cocker/containers/test/merged
# ls -l $COCKER_CONTAINER_ROOT
total 20
drwxr-xr-x.   2 root root 4096 Nov 22 08:26 bin
-rwxr-xr-x.   1 root root 2634 Nov 22 08:43 cocker.log
-rwxr-xr-x.   1 root root 4848 Nov 22 08:46 cockerinit.log
drwxr-xr-x.   1 root root   25 Nov 22 08:43 dev
drwxr-xr-x.   1 root root    6 Nov 22 08:26 etc
drwxr-xr-x.   2 root root    6 Nov 22 08:26 lib
drwxr-xr-x.   2 root root 4096 Nov 22 08:26 lib64
drwxr-xr-x.   3 root root   19 Nov 22 08:26 mnt
dr-xr-xr-x. 197 root root    0 Nov 22 08:43 proc
drwxr-xr-x.   1 root root   42 Nov 22 08:46 root
drwxr-xr-x.   2 root root   61 Nov 22 08:26 sbin
drwxr-xr-x.   2 root root    6 Nov 22 08:26 tmp
drwxr-xr-x.   3 root root   19 Nov 22 08:26 usr
drwxr-xr-x.   2 root root    6 Nov 22 08:26 var
```

ע�⣺�˽ű�������ָ��`-s container_root`��
ע�⣺��¶������Ŀ¼���ܲ�̫���ʡ�

## 3.3. ����ʾ��

### 3.3.1. ����ʽ����yum����

���˲���ϵͳ�����������Խ���ʽ�����������񡣴��¹���Ϊ�û������񴴽������������������ڽ���ʽ��װ�Ͳ���Ȼ��ֹͣ���������ת������Ϊ�¾���

```
# cocker -a create -m "calvin=rhel-7.4-x86_64" --host yum --volume "/mnt/cdrom:/mnt/cdrom" -c "calvin=yum"
OK
# cocker -a boot -c "calvin=yum" -t
[root@yum /root] 
```

�����������ú�yum�����ҵĻ�������������

```
[root@yum /root] mkdir -p /etc/yum.repos.d
[root@yum /root] vi /etc/yum.repos.d/cdrom.repo
[cdrom]
name=cdrom
baseurl=file:///mnt/cdrom
gpgcheck=0
enable=1
```

```
[root@yum /root] yum search sshd
cdrom                                                                                                                                                                                                                 | 4.1 kB  00:00:00     
(1/2): cdrom/group_gz                                                                                                                                                                                                 | 137 kB  00:00:00     
(2/2): cdrom/primary_db                                                                                                                                                                                               | 4.0 MB  00:00:00     
=============================================================================================================== Matched: sshd ===============================================================================================================
openssh-server.x86_64 : An open source SSH server daemon
```

ת������Ϊyum����

```
[root@yum /etc/yum.repos.d] exit
logout
# cocker -a shutdown -c "calvin=yum"
OK
# cocker -s containers
container_id         image                hostname   net        netns            size       status
-----------------------------------------------------------------------------------------------------------
calvin=yum           calvin=rhel-7.4-x86_64 yum        HOST                        24 MB      STOPED
# cocker -a to_image --from-container "calvin=yum" --version "1.0.0" --to-image "calvin=yum"
OK
# cocker -s containers
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
calvin=rhel-7.4-x86_64         1.0.0      2018-11-25T09:55:25 271 MB
calvin=yum                     1.0.0      2018-11-25T10:16:59 24 MB
```

### 3.3.2. ����ʽ����sshd����

ע�⣺����ʽ����sshd����yum��

```
# cocker -a create -m "calvin=rhel-7.4-x86_64,calvin=yum" --host sshd --volume "/mnt/cdrom:/mnt/cdrom" --net BRIDGE --vip 166.88.0.2 --port-mapping "2222:22" -c "calvin=sshd"
OK
# cocker -a boot -c "calvin=sshd" -t
[root@sshd /root] 
```

�����������ú�sshd�����ҵĻ�������������

```
[root@sshd /root] yum install -y openssh-server
...
[root@sshd /root] ssh-keygen -t rsa -f /etc/ssh/ssh_host_rsa_key
...��һ��ȫֱ�Ӱ��س���
[root@sshd /root] ssh-keygen -t rsa -f /etc/ssh/ssh_host_ecdsa_key
...��һ��ȫֱ�Ӱ��س���
[root@sshd /root] echo "root:root" | chpasswd
...�����п�ס����Ctrl+C������
[root@sshd /root] nohup /usr/sbin/sshd -D &
```

���⿪һ������sshd����

```
# ssh root@166.88.0.2 -p 2222
The authenticity of host '[166.88.0.2]:2222 ([166.88.0.2]:2222)' can't be established.
RSA key fingerprint is SHA256:kSX5DU3MiwEy8dArBoAk00kbB7hBtRXl/Pm4n9jWjBY.
RSA key fingerprint is MD5:27:5d:b6:5a:5a:b1:bc:eb:b9:82:98:58:40:7e:eb:45.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added '[166.88.0.2]:2222' (RSA) to the list of known hosts.
root@166.88.0.2's password: ��root����ǰ�汻���ó�root�ˣ�
Last login: Mon Nov 26 13:28:07 2018 from 192.168.6.7
-bash-4.2# 
```

ת������Ϊsshd����

```
[root@sshd /root] exit
logout
# cocker -a shutdown -c "calvin=sshd"
OK
# cocker -s containers
container_id         image                hostname   net        netns            size       status
-----------------------------------------------------------------------------------------------------------
calvin=yum           calvin=rhel-7.4-x86_64 yum        HOST                        24 MB      STOPED
# cocker -a to_image --from-container "calvin=sshd" --version "1.0.0" --to-image "calvin=sshd"
OK
# cocker -s containers
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
calvin=rhel-7.4-x86_64         1.0.0      2018-11-25T09:55:25 271 MB
calvin=yum                     1.0.0      2018-11-25T10:16:59 24 MB
calvin=sshd                    1.0.0      2018-11-26T09:16:59 335 MB
```

### 3.3.3. ����ʽ����G6����

`G6`�Ǳ�����ǰ�������еĸ��ؾ�������Դ���йܵ�ַ : [��Դ�й�](https://gitee.com/calvinwilliams/G6)��[github](https://github.com/calvinwilliams/G6)�������ٹ�˾��ʹ�ã�������ܽ���ʽ����G6����

```
# cocker -a create -m "calvin=rhel-7.4-x86_64,calvin=yum,calvin=sshd" --host G6 --volume "/mnt/cdrom:/mnt/cdrom" --net BRIDGE --vip 166.88.0.2 --port-mapping "8600:8600,2222:222" -c "calvin=G6"
OK
# cocker -a boot -c "calvin=G6" -t
[root@G6 /root] 
```

�����������ú�G6�����ҵĻ�������������

```
[root@G6 /root] yum install -y git
[root@G6 /root] yum install -y make
[root@G6 /root] yum install -y gcc
...�����������ʾ�����԰�git��gcc����װ��һ���ˣ�
[root@G6 /root] mkdir src && cd src
[root@G6 /root/src] git clone https://gitee.com/calvinwillisms/G6 && cd G6
[root@G6 /root/src/G6] cd src
[root@G6 /root/src/G6/src] make -f makefile.Linux install
...
[root@G6 /root/src/G6/src] mkdir ~/etc/ && vi ~/etc/G6.conf
admin_rule_id G 127.0.0.1:* - 127.0.0.1:8600 ;
my_rule RR *:* - 0.0.0.0:222 > 166.88.0.2:22 ;
[root@G6 /root/src/G6/src] cd ~
[root@G6 /root] nohup /usr/sbin/sshd -D &
[root@G6 /root] G6
G6 v1.0.6 build Nov 26 2018 14:28:18
TCP Bridge && Load-Balance Dispenser
Copyright by calvin 2016
USAGE : G6 -f (config_pathfilename) [ -t (forward_thread_size) ] [ -s (forward_session_size) ] [ --log-level (DEBUG|INFO|WARN|ERROR|FATAL) ] [ --log-filename (logfilename) ] [ --close-log ] [ --no-daemon ] [ --set-cpu-affinity ]
[root@G6 /root] G6 -f ~/etc/G6.conf
```

���⿪һ������G6����

```
# ssh root@166.88.0.2 -p 2222
root@166.88.0.2's password: ��root����ǰ�汻���ó�root�ˣ�
Last login: Mon Nov 26 13:28:07 2018 from 192.168.6.7
-bash-4.2# 
```

ת������ΪG6����

```
[root@G6 /root] ps -ef
...
[root@G6 /root] ps -ef | grep -v grep | grep "G6 -f" | awk '{if($3==1)print $2}' | xargs kill
[root@G6 /root] ps -ef | grep -v grep | grep -w sshd | awk '{print $2}' | xargs kill
[root@G6 /root] exit
logout
# cocker -a shutdown -c "calvin=G6"
OK
# cocker -s containers
container_id         image                hostname   net        netns            size       status
-----------------------------------------------------------------------------------------------------------
calvin=G6            calvin=rhel-7.4-x86_64,calvin=yum,calvin=sshd G6         BRIDGE     nns2513F44178    373 MB     STOPED
# cocker -a to_image --from-container "calvin=G6" --version "1.0.0" --to-image "calvin=G6"
OK
# cocker -s containers
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
calvin=rhel-7.4-x86_64         1.0.0      2018-11-25T09:55:25 271 MB
calvin=yum                     1.0.0      2018-11-25T10:16:59 24 MB
calvin=sshd                    1.0.0      2018-11-26T09:16:59 335 MB
calvin=G6                      1.0.0      2018-11-26T10:01:48 373 MB
```

### 3.3.4. ��������ʵ��������������

�����ñ��˵�`G6`�����ӣ��Ѿ���`calvin=G6`ת��Ϊ�������������ļ��ĳ�ģ�����ת���ؾ���

```
# cocker -a to_container --from-image "calvin=G6" -m "calvin=rhel-7.4-x86_64" --host G6 --to-container "calvin=G6"
OK
# cocker -a boot -c "calvin=G6" -t
[root@G6 /root] cd etc
[root@G6 /root/etc] mv G6.conf G6.conf.tpl
[root@G6 /root/etc] vi G6.conf.tpl
admin_rule G 127.0.0.1:* - 127.0.0.1:${ADMIN_PORT} ;
my_rule RR *:* - 0.0.0.0:${FORWARD_PORT} > ${DEST_IP}:${DEST_PORT} ;
[root@G6 /root/etc] vi ../bin/sshd.start
nohup /usr/sbin/sshd -D &
[root@G6 /root/etc] chmod +x ../bin/sshd.start
[root@G6 /root/etc] exit
logout
# cocker -a shutdown -c "calvin=G6"
OK
# cocker -a to_image --from-container "calvin=G6" --version "1.1.0" --to-image "calvin=G6"
OK
# cocker -s images
image_id                       version    modify_datetime     size      
--------------------------------------------------------------------
calvin=rhel-7.4-x86_64         1.0.0      2018-11-27T08:00:07 273 MB
calvin=yum                     1.0.0      2018-11-26T09:10:43 24 MB
calvin=sshd                    1.0.0      2018-11-26T09:17:12 335 MB
calvin=G6                      1.1.0      2018-11-27T08:03:33 373 MB
```

����þ��񴴽�����������ʵ��������������

```
# cocker -a create -m "calvin=rhel-7.4-x86_64,calvin=sshd,calvin=G6" --host G6 --net BRIDGE --vip 166.88.0.2 --port-mapping "8600:8600,2222:222" -c "G6"
OK
# cocker -a boot -c "G6"
OK
# vi G6.conf.map
${ADMIN_PORT}   8600
${FORWARD_PORT} 222
${DEST_IP}      166.88.0.2
${DEST_PORT}    22
# cocker -a rplfile -c "G6" --template-file "/root/etc/G6.conf.tpl" --mapping-file "G6.conf.map" --instance-file "/root/etc/G6.conf"
OK
# cocker -a run -c "G6" --cmd "cat /root/etc/G6.conf"
admin_rule G 127.0.0.1:* - 127.0.0.1:8600 ;
my_rule RR *:* - 0.0.0.0:222 > 166.88.0.2:22 ;
# cocker -a run -c "G6" --cmd "nohup /usr/sbin/sshd -D"
nohup: ignoring input and appending output to 'nohup.out'
# cocker -a run -c "G6" --cmd "G6 -f /root/etc/G6.conf"
OK
```

���⿪һ������G6����

```
# ssh root@166.88.0.2 -p 2222
root@166.88.0.2's password: ��root����ǰ�汻���ó�root�ˣ�
Last login: Mon Nov 26 13:28:07 2018 from 192.168.6.7
-bash-4.2# exit
```

�����رշ������ֹͣ����������

```
# cocker -a run -c "G6" --cmd "ps -ef | grep -v grep | grep 'G6 -f' | awk '{if($3==1)print $2}' | xargs kill"
# cocker -a run -c "G6" --cmd "ps -ef | grep -v grep | grep -w sshd | awk '{print $2}' | xargs kill"
# cocker -a shutdown -c G6
```

### 3.3.5. ��������������

��ǰ���`G6`��������ʾ��`Docker`������������������

```
# cocker -a create -m "calvin=rhel-7.4-x86_64,calvin=sshd,calvin=G6" --host G6 --net BRIDGE --vip 166.88.0.2 --port-mapping "8600:8600,2222:222" -c "G6" -b -e "/root/bin/G6 -f /root/etc/G6.conf --no-daemon" -d
OK
```

�����ֹͣ����������

```
# cocker -a destroy -c G6 -h
OK
```

# 4. ���

## 4.1. ����cocker

��ӭʹ��cocker�������ʹ��������������������ң�лл ^_^

Դ���йܵ�ַ : [��Դ�й�](https://gitee.com/calvinwilliams/cocker)��[github](https://github.com/calvinwilliams/cocker)

## 4.2. ��������

����������C��д��С������׿Խ�����ݵ���־�⡢HTTP����������־�ɼ����ȣ��󵽽���ƽ̨/�м���ȣ��ֲ�ʽϵͳʵ���ߣ��������������ߣ�Ŀǰ��ĳ�����и�������ܹ���

ͨ��������ϵ�� : [����](mailto:calvinwilliams@163.com)��[Gmail](mailto:calvinwilliams.c@gmail.com)
