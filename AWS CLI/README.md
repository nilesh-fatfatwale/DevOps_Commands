# List of usefull commands for aws cli

**Installation**
```
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
sudo apt-get install unzip
unzip -q awscliv2.zip
sudo ./aws/install --bin-dir /usr/local/bin --install-dir /usr/local/aws-cli --update   
```

- Start the Stoped Instance 
```
aws ec2 start-instances --instance-ids i-04db9a25b2e85f374
```
- Stop the Instance 
```
aws ec2 stop-instances --instance-ids i-04db9a25b2e85f374
```
- Terminate the Instance 
```
aws ec2 terminate-instances --instance-ids i-04db9a25b2e85f374
```
