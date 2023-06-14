# Azure-demos 

1.	git clone https://github.com/ramar92/Azure-demos.git
2.	git config --global user.email "ramarexplorer@gmail.com"
3.	git config --global user.name "Ramar Bose"
4.	use -cd and go that your file 
5.	git init
6.	git add .
7.	git commit -m "Edunet"
8.	az webapp deployment source config-local-git --name ccdemo02 --resource-group RAMAR-AI 
9.	az webapp deployment list-publishing-credentials --name ccdemo02 --resource-group RAMAR-AI
10.	git remote add azure 'https://$ccdemo02:aD57kevSxlv9s30Laj9N6NT8xwGNE9eXDxAKfCRxohZAiCasXW61gfeJHD7D@ccdemo02.scm.azurewebsites.net'
11.	git push azure master
