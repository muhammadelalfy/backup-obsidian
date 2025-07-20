new short password 

sudo usermod --password $(openssl passwd -1 NEWPASS) muhamad

Example: 
`sudo usermod --password $(openssl passwd -1 1234) muhamad`
