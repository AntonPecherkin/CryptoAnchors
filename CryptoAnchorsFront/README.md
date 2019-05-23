#Info

The application allows you to create a tracking operation for a any product. And track the path of this product / lot on the map.
There is a miniature device(cryptoAnchor) that stores a digital signature inside it on the selected product is . 
This device can be verified with the help of a special android application. In case of successful verification, 
the label with the coordinates and description of the goods is transmitted to the WEB service to display the goods path.

For this purpose, a smart contract is created for each selected product in the blockchain network.
When checking some special device (cryptoAnchor), the mobile application checks the digital signatures and in case of successful verification 
the label with the coordinates and description of the goods is transmitted to the WEB service to display the goods path.
To store the smallest amount of data inside the smart contract, a system of Naviaddress is used. This solution allows only 7 digits to store coordinates, 
description and accompanying files for the goods, for example, customs documents.
WEB interface allows you to track the track track of all products added to the system.

This application is designed to introduce transparency in the supply chain and is guaranteed to exclude the presence of counterfeit goods.

#Installing

1. Download this directory
2. Paste it to some host (this is really important, since if you run locally, you can not interact with quarckChain blockChain)
3. Install MetaMask Plagin
4. Create account in MetaMask
5. Select rinkeby testNet
6. put some ether to your wallet (Now we use etherium blockChain)
7.  Save your changes on host
8. Congrate! your can run yuor host (check than your host is http://, but not https://)

#Use
1. click 'Add Product' button
2. In input field add 'Chateau Margaux 2004' (sory, now we have fixe number of product, but it may be changes really simple)
3. click 'Add to AnchorChain' button
4. MetaMask popUp will be shown. Click to approve button
5. Wait (don't leave the page)
6. click 'Add Product' button
7. In input field add 'Prednisolone' (sory, now we have fixe number of product, but it may be changes really simple)
8. click 'Add to AnchorChain' button
9. MetaMask popUp will be shown. Click to approve button
10. Wait (don't leave the page)
11. In selecte field selecte one of this product
12. click to 'Check Track' button
13. But nothing will happen, cause android app don't check created cryptoAnchors.
14. If android app will check created cryptoAnchors, on map new Marcker with description will appear
