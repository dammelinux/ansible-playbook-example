# Build by KAI VO 

# Install Ansible 
yum update -y
yum -y install epel-release 
yum --enablerepo=epel -y install ansible openssh-clients 

# create file ssh key public && copy for another server
# Reference modules on pages Ansible https://docs.ansible.com/ansible/latest/modules/modules_by_category.html


# Create key ssh on server Ansible and copy key pub on server webserver and database
# Test ssh from server Ansible => webserver and database

# Play-book 1
# Install package apache httpd and start service

# Play-book 2
# Install package apache httpd and start service && open port 80 on firewalld

# Play-book 3
# Sample example Play-book 2 and open multi port 80 & 8080

# Play-book 4
# Install list packages tree, wget, curl, unzip

# Play-book 5
# Copy file with owner and permissions

# Play-book 6
# Copy file with owner and permissions && run file scripts

