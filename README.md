

mkdir ~/sshQuic
cd ~/sshQuic
dirpath=`pwd`
git clone https://github.com/l0veshe/sshCopyAutoSH.git
sudo -c "echo \"export PATH=$PATH:$dirpath\" >> /etc/profile"
source /etc/profile

重新登陆命令行
sshCopyAuto 
