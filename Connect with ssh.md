## GIT bash commands


### Check for existing KEYS
#### ls -al ~/.ssh


### Generate new KEY
#### $ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"


### Start ssh-agent before adding the key
#### $ eval $(ssh-agent -s)


### Add the key
#### $ ssh-add ~/.ssh/id_rsa


### Test connection
#### $ ssh -T \<git@githost\>

