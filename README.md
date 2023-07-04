### Hi there 👋

<!--
**momonalyza1/momonalyza1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->apt install clang gcc libssl-dev pkg-config
sudo apt update && sudo apt upgrade -y

apt install ufw -y 
ufw allow ssh 
ufw allow https 
ufw allow http 
ufw allow 30333
ufw allow 8078
ufw enable

sudo mkdir -p /etc/apt/keyrings
curl -fsSL repo.chainflip.io/keys/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/chainflip.gpg
