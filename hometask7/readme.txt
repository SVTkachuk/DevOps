3022,3122,3222,....5422,5522
14822

ssh -D8899 -p 4822 root@yoko.ukrtux.com
Jnf5kh76Bv+ou6

ssh-keygen
/home/st/.ssh/id_rsa
abc
/home/st/.ssh/id_rsa.pub
ssh-keygen -t rsa

ssh-copy-id -i /home/st/.ssh/id_rsa.pub -p 4822 root@yoko.ukrtux.com

ssh -p 4822 root@yoko.ukrtux.com


python3 -m http.server 1337

#not working
ssh -R 14822:localhost:1337 -p 4822 root@yoko.ukrtux.com