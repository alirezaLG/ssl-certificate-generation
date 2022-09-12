# ssl-certificate-generation
to generate ssl certificate

#video channel to check
https://www.youtube.com/watch?v=XxMbLr4ytCM&ab_channel=WPHowKnow


1. install acme.sh
curl https://get.acme.sh | sh

2. install certificate
.acme.sh/acme.sh --issue -d domain.com -d www.domaim.com  -w /home/_director_/public_html/  --server letsencrypt

3. deploy certificate
go to ssl/tsl -> manage SSL -> copy and past manually cer and private key from folder .acme.sh/domain.com  


#to check ssl 
https://wphowknow.com/ssl-checker/


more infor on medium 
https://medium.com/@jonathanobise/how-to-setup-free-lets-encrypt-ssl-on-namecheap-using-acme-sh-in-cpanel-5a3d408071ba
dont forget to replace -- 


