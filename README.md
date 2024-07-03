Follow command below:
curl -L -o CentOS-Base.repo https://raw.githubusercontent.com/KloxoNGCommunity/kloxong/master/rpm/CentOS-Base.repo
curl -L -o CentOS-Vault.repo https://raw.githubusercontent.com/KloxoNGCommunity/kloxong/master/rpm/CentOS-Vault.repo
yum clean all && yum update -y
