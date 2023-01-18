# Run-Taiko-Node
simple taiko node


<h1 align="center"> Taiko </h1> 

  

 ![image](https://user-images.githubusercontent.com/101149671/212496781-33a8eb3a-0ba2-497a-9f87-6185de6c1b2a.png) 

 
 ## Requirements: 

 ``` 

 2 - 4 CPU 

 4GB RAM 

 50 GB SSD 

 ``` 

  

 ## Setup: 

 * Enter commands one by one

  

 ``` 

 sudo apt update  

 ``` 

 ``` 

 sudo apt upgrade 

 ``` 

 ``` 

 apt install docker-compose 

 ``` 

 ``` 

 sudo apt-get update && sudo apt install jq && sudo apt install apt-transport-https ca-certificates curl software-properties-common -y && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin && sudo apt-get install docker-compose-plugin 

 ``` 

  

 ## Clone the repository

 ``` 

 git clone https://github.com/taikoxyz/simple-taiko-node.git 

 cd simple-taiko-node 

 ``` 

 ## Run it on a separate screen: 

 ``` 

 screen -S rues 

 ``` 

  

 ## Go in and make adjustments.: 

 ``` 

 cp .env.sample .env 

 nano .env 

 ``` 

 ## Before continuing with this part, create a metamask from scratch and get a token: [link](https://twitter.com/Ruesandora0/status/1607802177036091393?s=20&t=0OJOlVuEJIoSQRYLo2x5Sw)
  

 ## The screen that will open when you enter the above commands is as in the image.

 * After opening, we come to the bottom with the arrow keys. 

 * Make ENABLE_PROPOSER  'true '

 * `L1_PROPOSER_PRIVATE_KEY=` kısmına metamasktan private key alıyoruz (2. görsele bakın) 

 * `L2_SUGGESTED_FEE_RECIPIENT=`bu kısımda `Metamask 0x Cüzdan Adresi` olacak 

 * sonra CTRL + X + Y ile çıkıyoruz. 

  

 ![image](https://user-images.githubusercontent.com/76253089/212540636-32564971-d531-41f2-b2a6-ffc5ef21582c.png) 

  

 * Metamasktan 3 noktaya tıklayınca hesap bilgileri kısmında olacak burası: 

 ![image](https://user-images.githubusercontent.com/101149671/212497188-e5480587-9872-4c0f-abf0-4f6b24839396.png) 

  

 ## Node'u çalıştırın: 

 ``` 

 docker compose up 

 ``` 

 ## Node'unuz çalışıyor kolay gelsin: 

  

 ![image](https://user-images.githubusercontent.com/101149671/212497350-4cebdcc6-edeb-4949-b18b-a38a83e1a53c.png) 

  

 ## Taiko yatırımını açıklamamış projelerden birisidir. 

  

  

 
