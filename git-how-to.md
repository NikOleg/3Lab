## Create ssh-key
- `ssh-keygen -t ed25519 -C "name.surname@phystech.edu"` in ~/.ssh --> make ssh keys
- `cat ~/.ssh/id_ed25519.pub` - show pub key
- `eval "$(ssh-agent -s)"` - client SSH use our key
- `ssh-add ~/.ssh/id_ed25519` - add our key
## Clone repository
- in github.com go to settings -> SSH and GPG keys -> new SSH key
- `git clone 'git@github.com:username/repository.git'` --> successCreate

