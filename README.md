# git-greetings
Simple script that greets user when terminal loads. Download hidden file in same directory as your .bash_profile.

# dependencies
Install *Fortune*:

For Mac (Homebrew): 
```bash
  brew install fortune
```

On Linux machines:
```bash
  sudo apt install fortune
```

# source to your .bash_profile
Once you've installed Fortune and have a copy of .bash_greetings, enter into your terminal:

```bash
  echo 'source ~/.bash_greetings' >>~/.bash_profile
```

Then source your bash_profile:

```bash
  source ~/.bash_profile
```
