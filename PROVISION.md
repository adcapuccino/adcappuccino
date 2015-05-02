# Provisioning AMI

```
# install docker (do we need it?)
sudo yum update
sudo yum -y install docker
service docker start

# install jenkins
sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat-stable/jenkins.repo
sudo rpm --import http://pkg.jenkins-ci.org/redhat-stable/jenkins-ci.org.key
sudo yum install jenkins
sudo service jenkins start
chkconfig jenkins on
```
