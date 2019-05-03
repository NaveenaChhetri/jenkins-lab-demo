# jenkins-lab-demo

$ cp -r $HOME/.ssh /var/lib/jenkins/

$ chown -R jenkins /var/lib/jenkins/.ssh

$ ssh-copy-id -i $HOME/.ssh/id_rsa.pub student@targetmachineip

\## Create jenkins job for httpd-install and deploy package using ansible plugin
