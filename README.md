Follow command below:
curl -L -o CentOS-Base.repo https://raw.githubusercontent.com/kietcaodev/centos7_repo/main/CentOS-Base.repo
curl -L -o CentOS-Vault.repo https://raw.githubusercontent.com/kietcaodev/centos7_repo/main/CentOS-Vault.repo
yum clean all && yum update -y
