# ssl site checker

This is a script that will check whether a site has a cert or not.

Currently its a demo for a freelance project proposal - so currently its a hardcoded list of urls to be checked and the results are written to std out.

Running the current script ou will to install :

cryptography==2.9
idna==2.9
pyOpenSSL==2.20

pip install cryptography
pip install idna
pip install pyOpenSSL

running python ssl-check.py outputs :

 jrj.com.cn has no SSL certificate
 gmw.cn has no SSL certificate
» urbangraphicstudio.com « … ('69.163.160.45', 443)
    	commonName: urbangraphicstudio.com
    	SAN: ['urbangraphicstudio.com', 'www.urbangraphicstudio.com']
    	issuer: Let's Encrypt Authority X3
    	notBefore: 2020-03-09 11:54:46
    	notAfter:  2020-06-07 11:54:46
    
livedoor.com has no SSL certificate

in the console
