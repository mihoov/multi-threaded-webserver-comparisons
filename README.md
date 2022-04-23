# multi-threaded-webserver-comparisons

- install apache bench (apache lounge, includes bench, for windows dl link: [link](https://www.apachelounge.com/download/VS16/binaries/httpd-2.4.53-win64-VS16.zip))
- extract zip; run executable `Apache24/bin/ab` 
- specific command I use, for the go code:  
```shell
.\ab -n 5000 -c 500 localhost/
```