# Digispark payloads 

## All the payloads for digispark board  
![alt text](https://images-na.ssl-images-amazon.com/images/I/61iDcLA1%2BXL._AC_SX425_.jpg "digispark")

# Setup the server to send all the payloads 
```
php -S 0.0.0.0:80 -T /Users/Name/Dir
```

# For the reverse shell 

### Listen all the tcp connexion on port 1234
```
ncat -nvlp [PORT]
```

# Shell spawner
**Using python**

    python -c 'import pty; pty.spawn("/bin/sh")'

**Echo**

    echo 'os.system('/bin/bash')'

**sh**

    /bin/sh -i

**bash**

    /bin/bash -i

**Perl**

    perl -e 'exec "/bin/sh";'

**From within VI**

    :!bash
