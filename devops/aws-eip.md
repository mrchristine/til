# Assigning Elastic IPs
EC2 instances allow you to assign Elastic IP Addresses (EIP) to instances. This has an additional cost, and removes the public ip address associated with the instance.  
Amazon's DNS will continue to resolve the hostname to the old public address. You would need to configure your own DNS to resolve this for the internal instances.  
EIPs are beneficial to ensure restarts of EC2 instances do not change the IP address. 
