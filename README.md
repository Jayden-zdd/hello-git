# hello-git
git clone特别慢是因为github.global.ssl.fastly.net域名被限制了

resolved：
1.change hosts file
* WindowsC:\Windows\System32\drivers\etc\hosts
* Linux: sudo vim /etc/hosts
add below info:
199.232.69.194 github.global-ssl.fastly.net
140.82.114.3 github.com

2.save and refresh the DNS  
* Winodws: CMD=>ipconfig /flushdns
* Linux: sudo /etc/init.d/networking restart
