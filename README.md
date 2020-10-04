# GSTChain - no more tax evasion

In a report of Financial Express it is found that the central GST authorities have detected evasion of Rs 70,206 crore between July 1, 2017 launch of GST and January, 2020. So our project aims to solve this problem using a decentralised blockchain system.

### Checkout the deployed site [here](https://gstchain.web.app/).

### Youtube video of the working is [available here](https://youtu.be/WkeIelvqu0A).

# How this works
This system works between government and business.
## For government
- The government official receives GST every time a bill is generated by a registered business.
- Businesses cannot evade taxes, as data of each bill is stored in the blockchain, as soon as it is generated.
- Government officials can login and check every billing and business details through portal.
## For businesses
- Business officials can register, and login using their unique GST numbers.
- The bills they generate will automatically contribute towards GST generation.
- Every business is registered in blockchain.

# How to setup and run the Dapp
<ol>
<li> Copy the code from <b>contracts/gst-system.sol</b> and paste it on Remix IDE and compile using version <b> 0.4.22 </b> compiler</li>
<li> Use the Injected Web3 for deploying and select Matic Mumbai Test server.</li>
<li> Copy the contract address from <b> scripts/cred.js </b> and deploy the contract using that address. </li>
<li> After that, run the application at deployed [site](https://gstchain.web.app).</li>
<li> At first load meta mask pop Up will come and it will connect the site with the meta mask extension. Press the accept button </li>
<li> Before doing any work make sure that your account have sufficient balance to pay fees </li>
<li> To login as government user username - "admin " and password = "123456"</li>
 <li> You can create any number of business and generate any number of bill </li>
 <li> At the time of business creation or bill generation an meta mask confirmation notification will come. </li>
 <li> Press confirm at that pop up to accept the transaction </li>
 
</ol>



# Functions provided
1. Various Businesses can register themselves using GST Number.
2. Business can generate bills for customers using customer's Aadhar Number.
3. Business can see the previous transaction details and total GST paid.
4. Business can search for a particular bill using Bill Number.
5. Government can see the details of all businesses registered and keep an eye on the GST paid by them.

# Technologies Used
<ol>
<li> Ethereum Blockchain
<li> Solidity
<li> Matic Mumbai Test Network
<li> HTML
 <li> CSS
 <li> JavaScript
 <li> Web3.js
 <li> Progressive Web App
 </ol>

## Team Members
- [Muskan Maheshwari](https://github.com/Muskan02)
- [Priyanshu Ranjan](https://github.com/ranjanistic)
- [Rajat Shrivastava](https://github.com/rajathandsom)
