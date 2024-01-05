# burp-installation

### source
```
https://portswigger.net/burp/communitydownload
```
it will dowload .sh file
Now, Run the .sh file then burp will intall 
To run the .sh file 
```
sh <filename.sh>
```
After Installation
### Proxy Setup in burp suite
Go to Proxy setting> proxxy listeners>
click on add > select specific addess and port 
ex: 192.168.138.126:4444

#### proxy setup in browser 
Note: works in firefox

Go to Settings > network settings > select manual proxy
give details here ip and port , check box https

Now access from browser 
```
http://burp/
```
or 
```
http://<ipaddress>:<port>
```
now Install CA certificate 
Go to settings > options > privacy & seccurity > view certificate > import > selevct file 
check boxes then OK 



