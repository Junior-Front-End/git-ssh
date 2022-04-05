# git SSH
2022.April.05 - [refrence](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys)

```bash
// list of existing SSH Keys 
ls -al ~/.ssh

// copy the SSH Key to clipboard
clip < ~/.ssh/id_ed25519.pub

// create a new SSH Key
ssh-keygen -t ed25519 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
ssh-keygen -t ed25519-sk -C "your_email@example.com"
```
