# Namescheap_SSL_Activation
Step 1:
* go to your namescheap panel and login or directly visit this URL https://ap.www.namecheap.com/ProductList/SslCertificates
* download your ssl certificate by clicking download button on the right side of browser window
* now its time to connect the SSL certificate to Educationhost.com, goto your educationhost control panel by visiting this URL --> https://svr.educationhost.cloud:2222/ then login.
* inside Account Manager--> SSL Certificat

Step 2:
Before you begin  with the SSL activation, you'll first need to have a CSR code generated on your server by your hosting provider. 
--Login to your hosting CPANEL--https://svr.educationhost.cloud/
--In the top side *Account Manager* click on *SSL Certificate*.
--Click on create *Create a Certificate Request* --- Fill your details like country,state,city,domain(your website name)  (company--type your company name OR your website name)
Hit *Generate*.
--From next page you see your CSR fill generated. *Copy (Copy to Clipboard) the -Encoded Certificate Signing Request-*
BEFORE ADDING CSR FILE TO YOUR CPANEL CREATE ONE EMAIL FROM YOUR DOMAIN BECAUSE IN THE PROCESS OF GENERATING SSL/CSR CERTIFICATE WE WILL RECEIVE SOME VARIFICATION EMAIL TO THAT EMAIL ADDRESS AND SSL CERIFICATES DIRECTLY SENT TO YOUR HOSTING CONTROL PANEL EMAIL ADDRESS LINK admin@mywebsite.com.
1) In our case we can issue one email id from educationhost.com
--visit again https://svr.educationhost.cloud:2222/
--inside *Email Manager* click to email account in here click on *CREATE ACCOUNT* (in github education pack we can create only 2 account (1 is already created))
2) After clicking on generate cerificate you will receive the varification email in which you have to verify your website name/domain name.
3) In the email click to *verify* one browser tab will open and you need to insert *varification code* from the email. and NEXT ---if varification code match your verifiation done.  
**4) After 10-15 min later you will receive 2 more emails from COMODO Authority(ssl certificate issueing authority). when email received from COMODO find attachment along with email and download the cerificate zip file. and extract it. 

Step 3: 
Again goto CPANEL of your Educationhost.com --> Account Manager --> SSL Cerificate
--Refer this ----> https://www.educationhost.co.uk/whmcs/index.php?rp=/knowledgebase/4075/How-to-install-an-SSL-certificate-in-DirectAdmin.html



