# Note

## SSH port 변경
```
sudo nano /etc/ssh/sshd_config
#port 24  < = 원하는 번호로 변경
sudo service sshd restart
sudo ufw allow 포트번호
```
계정 만들기 참고

https://www.nemonein.xyz/2019/10/2611/
