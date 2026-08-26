# Computa-o-em-nuvem---Anhanguera

root@ubuntu:~$ whoami
root
root@ubuntu:~$ hostname
ubuntu
root@ubuntu:~$ uname -a
Linux ubuntu 6.8.0-138-generic #138-Ubuntu SMP PREEMPT_DYNAMIC Fri Jul 31 22:41:49 UTC 2026 x86_64 x86_64 x86_64 GNU/Linux
root@ubuntu:~$ cat /etc/os-release
PRETTY_NAME="Ubuntu 24.04.4 LTS"
NAME="Ubuntu"
VERSION_ID="24.04"
VERSION="24.04.4 LTS (Noble Numbat)"
VERSION_CODENAME=noble
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=noble
LOGO=ubuntu-logo
root@ubuntu:~$ pwd
/root
root@ubuntu:~$ ls
filesystem
root@ubuntu:~$ mkdir computacao-nuvem
root@ubuntu:~$ cd computacao-nuvem
root@ubuntu:~/computacao-nuvem$ pwd
/root/computacao-nuvem
root@ubuntu:~/computacao-nuvem$ echo "Minha primeira atividade de computacao em nuvem" <mensagem.txt>
bash: syntax error near unexpected token `newline'
root@ubuntu:~/computacao-nuvem$ echo "Minha primeira atividade de computacao em nuvem" > mensagem.txt 
root@ubuntu:~/computacao-nuvem$ ls
mensagem.txt
root@ubuntu:~/computacao-nuvem$ cat mensagem.txt
Minha primeira atividade de computacao em nuvem
root@ubuntu:~/computacao-nuvem$ echo "Estou utilizando um ambiente Linux remoto" >> mensagem.txt
root@ubuntu:~/computacao-nuvem$ echo "O acesso esta sendo realizado pelo navegador" >> mensagem.txt
root@ubuntu:~/computacao-nuvem$ cat mensagem.txt
Minha primeira atividade de computacao em nuvem
Estou utilizando um ambiente Linux remoto
O acesso esta sendo realizado pelo navegador
root@ubuntu:~/computacao-nuvem$ hostname
ubuntu
root@ubuntu:~/computacao-nuvem$ nproc
1
root@ubuntu:~/computacao-nuvem$ free -h
               total        used        free      shared  buff/cache   available
Mem:           1.9Gi       457Mi       794Mi       1.1Mi       820Mi       1.4Gi
Swap:          1.0Gi          0B       1.0Gi
root@ubuntu:~/computacao-nuvem$ df -h
Filesystem      Size  Used Avail Use% Mounted on
tmpfs           191M  996K  190M   1% /run
/dev/vda1        19G  5.4G   13G  30% /
tmpfs           952M   84K  952M   1% /dev/shm
tmpfs           5.0M     0  5.0M   0% /run/lock
/dev/vda16      881M  117M  703M  15% /boot
/dev/vda15      105M  6.2M   99M   6% /boot/efi
root@ubuntu:~/computacao-nuvem$ mkdir atividad-nuvem
root@ubuntu:~/computacao-nuvem$ cd atividad-nuvem
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Nome dos integrantes: " > grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Rafael Felipe Zambeli" >> grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Elywelton Ferreira Nunes" >> grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Disciplina: Computacao em nuvem" >> Grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Ambiente utilizado: Killer Coda" >> Grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Sistema Operacional: Ubuntu" >> Grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Hostname: ubuntu" >> Grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ cat grupo.txt
Nome dos integrantes: 
Rafael Felipe Zambeli
Elywelton Ferreira Nunes
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Disciplina: Computacao em nuvem" >> grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Ambiente utilizado: Killer Coda" >> grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Sistema Operacional: Ubuntu" >> grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ echo "Hostname: ubuntu" >> grupo.txt
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ cat grupo.txt
Nome dos integrantes: 
Rafael Felipe Zambeli
Elywelton Ferreira Nunes
Disciplina: Computacao em nuvem
Ambiente utilizado: Killer Coda
Sistema Operacional: Ubuntu
Hostname: ubuntu
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ ^C
root@ubuntu:~/computacao-nuvem/atividad-nuvem$ 
