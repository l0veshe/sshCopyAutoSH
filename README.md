
```bash
mkdir ~/sshQuic
cd ~/sshQuic
dirpath=`pwd`
wget https://raw.githubusercontent.com/l0veshe/sshCopyAutoSH/master/sshCopyAuto
sed 's/installDir/$dirpath/' ./sshCopyAuto  
chmod a+x ./sshCopyAuto
sudo -c "echo \"export PATH=$PATH:$dirpath\" >> /etc/profile"
source /etc/profile
```

重新登陆命令行
sshCopyAuto 
