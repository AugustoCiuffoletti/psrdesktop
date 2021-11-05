### README

# developer

$ sudo docker build -t psrdesktop:latest .

$ sudo docker run -it --rm psrdesktop:latest /bin/bash

# user

$ sudo docker run -d psrdesktop:latest

# access

$ rdesktop -g 1600x900 172.17.0.2:3389
