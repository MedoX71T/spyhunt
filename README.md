
# INSTALLATION

```bash

git clone https://github.com/gotr00t0day/spyhunt.git

cd spyhunt

sudo python3 install.py

```

# USAGE 

```
sudo python3 spyhunt.py -h

usage: spyhunt.py [-h] [-sv] [-s domain.com] [-j domain.com] [-d domain.com] [-p domains.txt]  
                   [-a domains.txt] [-r domains.txt] [-e https://site/file.js]                  
                                                                                                
optional arguments:                                                                             
  -h, --help            show this help message and exit                                         
  -sv, --save           save output to file                                                     
  -s domain.com         scan for subdomains                                                     
  -j domain.com         find javascript files                                                   
  -d domain.com, --dns domain.com                                                               
                        scan for dns records                                                    
  -p domains.txt, --probe domains.txt                                                           
                        probe domains.                                                          
  -a domains.txt, --aquatone domains.txt                                                        
                        take screenshots of domains.                                            
  -r domains.txt, --redirects domains.txt                                                       
                        links getting redirected                                                
  -e https://site/file.js, --endpoints https://site/file.js                                     
                        extract endpoints from js files 

```

# EXAMPLE

Scan for subdomains and save the output to a file.
```
sudo python3 spyhunt.py -s yahoo.com --save 
```
Scan for javascript files 
```
sudo python3 spyhunt -j yahoo.com
```

