
- Create a Administrator user and a dev user and their groups with proper permissions
https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html

- Set up ssh keygen locally

- Start a ec2 instance with the dev user account and import the public key
https://us-east-2.console.aws.amazon.com/ec2/v2/home?region=us-east-2#Instances:

- Install VSCode locally with "Remote - SSH" extension

- In VSCode, "Control + Shift + p" to get the command bar and search for "Remote-ssh: Connect to host"
https://code.visualstudio.com/docs/remote/ssh

- Create ~/.ssh/config
```
Host ec2
    HostName "ip address"
    User ubuntu
    Port 22
```

- "Forward a port" in VScode