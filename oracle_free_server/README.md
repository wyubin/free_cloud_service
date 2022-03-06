[Ref](https://www.minextuts.com/free-vps-install-ubuntu-remote-desktop-rdp-vnc-server/)
[Youtube](https://www.youtube.com/watch?v=8UFDVwR0rXU)
# 建立一個 vm
要玩一個雲端服務，最簡單的方向就是直接建一個 vm 來玩
- 選 create vm instance
- oracle 在免費額度的狀況下，可以選 arm 系統最大 4核心++24G
- 可以提供的作業系統不多，最好還是選 ubuntu 20
- 網路可以先用預設，重要是產生 ssh key 來access
```shell
ssh-keygen -t ecdsa
ssh-add ~/.ssh/ecdsa_oracle
```
