# Пароли от программы
http://192.168.10.25:8080
admin HelloDevOps@12

192.168.10.25:22 (SSH to SRV5-ubuntu-22-04)
sysadmin PrognoseLife@20220721
sysadmin 5000

192.168.10.26:22 (SSH to SRV6-ubuntu-22-04)
sysadmin 6000

cat /etc/passwd -n

jenkins@srv5-ubuntu-22-04:~$ ssh-keygen 
Generating public/private rsa key pair.
Enter file in which to save the key (/var/lib/jenkins/.ssh/id_rsa): 
Created directory '/var/lib/jenkins/.ssh'.
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /var/lib/jenkins/.ssh/id_rsa
Your public key has been saved in /var/lib/jenkins/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:Wl7oyjhVkXL8b0g49NrkLlXYcRgOENaeM8Ul5ftSs/8 jenkins@srv5-ubuntu-22-04
The key's randomart image is:
+---[RSA 3072]----+
|       .+=..o=o  |
|      ..* .o=o.  |
|       + * =.o.  |
|        +.@ o  . |
|       .SB.*  ...|
|      .=..= o  oo|
|     .. oo .  ...|
|    .o .. .    ..|
|    ..o  .      E|
+----[SHA256]-----+
jenkins@srv5-ubuntu-22-04:~$ cat .ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCg0Ld0X8orQ4enfA604e48J9fZqgHfGUfGk9XtflLeyE2Zj9HGrNWhSBU1GkKNwuf2d40WM59mjiiMedT8pckqCQO6B8wUm5MCgUIf/zRCWa9nobDyBNd00G+eZ9NX9IhiHNyO15D/DYGzZdUpmz5qxYk177+zYQ7x07BQO3Fb44d/R8cY2nPv75/49xYnVnDFD/9yW0gkgoljfa/eMmqXXGk7GCK/ANd0MdBUeCF8k1VmxhaAXMt+kv34H1zMP1yWe3A3WKru0aXuBsXdrYhzT8caw92/xT0WOiX2QDH8loNvc5HscmGUvF04CVwJt2g9GNvLGN+JOehT55Mkihl0dgOczKdv0JRBT7Fo/yxR/MJOYSFL+40rQz56YASJ7vcvyewB5J/1V/XN7xj+x79EoMdzsdRQ+ICmfD7lLeZiSnmwxMNJKVG9P/5fXGv/+73DoP5KLmw9OQDDEBY2FIvEpJbjN9w7Qay8mj6Htrq0priW5tTi5C7ag3To2HWMZWk= jenkins@srv5-ubuntu-22-04

# тут создал ключ на Ub2 для sysadmin
sysadmin@srv6-ubuntu-22-04:~$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/home/sysadmin/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/sysadmin/.ssh/id_rsa
Your public key has been saved in /home/sysadmin/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:nCwsG+gbmRuiLslkV7sfVsuLgPz6DVS1vfDlL6ttAH8 sysadmin@srv6-ubuntu-22-04
The key's randomart image is:
+---[RSA 3072]----+
|         .       |
|        . o      |
|       . o . .   |
|   . o.o oo +    |
|  . +.+ S.oo .   |
| +.+o= .o .o E.  |
|=.Bo.o.o o  o. . |
|+o =..= o . ..o  |
|+.o.oo.+ . .oo   |
+----[SHA256]-----+
sysadmin@srv6-ubuntu-22-04:~$ cat .ssh/id_rsa.pub 
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDLBTxgCDX0LlsFjCNE+KP7bsPP2zVOkqQn6aXHsjjdgwg4EE4KRO85A2bBludZC7nkUXzistef3NcDVCT+QPOLpSRuGUR6yJLPefcRBuKYlYt68g86IE+cA6+LsDlL8m0AfEHzb/Kkuh1WI4LAdwXxTXPn7+UEUcSKS/c3U38I4fDeUjMLcwSVJ3unuVWY8lkpgCfZ9h0uGGKLmyZyUQRD78ePIHd0TK9dLNfderAnZDmKliDUaMX2jAg7DH/M3JjoN/cz52lCt4NsOnTD0+iujj15GJ/wa2+WFBAaqg8G90Z7wScUXvHVZ4dhZQkyqEZhJNHAgcTg/2srG01henxb7y7725unRw+JcJApKCiNOvIxD0/8w8bYNPiQ+CL03fgWcs7+t9USu1QeSQQ3qgyOfz0iPjmY6yDZVPVf7ColrHscXPM7526oYGVzTFzp8roqG2Col4eO0vdNo5hmjfowAxHfmEm4tykrnRwHomiQx8rwHBS5fgHUWYO+GdaokpU= sysadmin@srv6-ubuntu-22-04

-----BEGIN OPENSSH PRIVATE KEY-----
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
-----END OPENSSH PRIVATE KEY-----