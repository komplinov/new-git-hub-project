# Пароли от программы
http://192.168.21.25:8080
admin HelloDevOps@12

192.168.21.25:22 (SSH to SRV5-ubuntu-22-04)
sysadmin PrognoseLife@20220721
sysadmin 5000

192.168.21.26:22 (SSH to SRV6-ubuntu-22-04)
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