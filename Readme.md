mkdir ~/.npm-global

npm config set prefix '~/.npm-global'

<!-- export PATH=~/.npm-global/bin:\$PATH -->

export PATH=\$PATH:~/.npm-global/bin

source ~/.profile

<!-- source ~/.bash_profile -->

npm install -g expo-cli

full command:
mkdir ~/.npm-global && npm config set prefix '~/.npm-global' && export PATH=\$PATH:~/.npm-global/bin && source ~/.profile && npm install -g expo-cli

---

expo -V

expo login

---

expo start

---

expo init

echo \$PATH
