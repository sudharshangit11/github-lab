# this is the readme file for github lab practice 
https://github.com/NikitasGithub/DevOpsClassCodes.git


#sonarqube code git 

https://github.com/akshu20791/addressbook-cicd-project

#kubernetes master install

wget raw.githubusercontent.com/NikitasGithub/Deployment-script/main/k8s-master.sh

#kubernetes node install 

wget raw.githubusercontent.com/NikitasGithub/Deployment-script/main/k8s-nodes.sh

sudo modprobe br_netfilter
sudo sh -c 'echo 1 > /proc/sys/net/bridge/bridge-nf-call-iptables'
sudo sh -c 'echo 1 > /proc/sys/net/ipv4/ip_forward'

cat <<EOF | sudo tee /etc/sysctl.d/k8s.conf
net.bridge.bridge-nf-call-iptables = 1
net.ipv4.ip_forward = 1
EOF

sudo sysctl --system


#jenkins install

wget https://raw.githubusercontent.com/akshu20791/Deployment-script/refs/heads/main/jenkins.sh

#tomcat install

wget https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.115/bin/apache-tomcat-9.0.115.zip

#sonarqube install

https://medium.com/@deshdeepakdhobi/how-to-install-and-configure-sonarqube-on-aws-ec2-ubuntu-22-04-c89a3f1c2447


