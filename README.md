# git ssh

```
ls -al ~/.ssh
clip < ~/.ssh/id_ed25519.pub

ssh-keygen -t ed25519 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
ssh-keygen -t ed25519-sk -C "your_email@example.com"
```

refrence: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys