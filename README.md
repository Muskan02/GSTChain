# GSTChain - no more tax evasion

In a report of Financial Express it is found that the central GST authorities have detected evasion of Rs 70,206 crore between July 1, 2017 launch of GST and January, 2020. So our project aims to solve this problem using a decentralised blockchain system.

# How to setup and run the Dapp
<ol>
<li> Copy the code from contracts/gst-system.sol and paste it on Remix IDE and compile using version <b> 0.4.22 </b> compiler</li>
<li> Use the Injected Web3 for deploying locally to setup a ethereum test server.</li>
<li> In Metamask, select the account as Matic Mumbai Testnet. All the transactions will be done from here.</li>
<li> Deploy the contract by providing correct parameter for the constructor </li>
<li> After deployment, Copy and paste the Contract address in <b>scripts/cred.js</b></li>
<li> After that, run the application at deployed [site](https://gstchain.web.app).</li>
</ol>

# Functions provided
1. Various Businesses can register themselves using GST Number.
2. Business can generate bills for customers using customer's Aadhar Number.
3. Business can see the previous transaction details and total GST paid.
4. Business can search for a particular bill using Bill Number.
5. Government can see the details of all businesses registered and keep an eye on the GST paid by them.

## Team Members
- [Muskan Maheshwari](https://github.com/Muskan02)
- [Priyanshu Ranjan](https://github.com/ranjanistic)
- [Rajat Shrivastava](https://github.com/rajathandsom)
