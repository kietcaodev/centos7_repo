Follow command below:

mv /etc/yum.repos.d/CentOS-Base.repo /etc/yum.repos.d/CentOS-Base.repo.bk

mv /etc/yum.repos.d/CentOS-Vault.repo /etc/yum.repos.d/CentOS-Vault.repo.bk

curl -L -o /etc/yum.repos.d/CentOS-Base.repo https://raw.githubusercontent.com/kietcaodev/centos7_repo/main/CentOS-Base.repo

curl -L -o /etc/yum.repos.d/CentOS-Vault.repo https://raw.githubusercontent.com/kietcaodev/centos7_repo/main/CentOS-Vault.repo

yum clean all && yum update -y
