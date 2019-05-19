# plotmappy

Asset Transfer Sample for Azure Blockchain Workbench

The asset transfer smart contract covers the scenario for buying and selling high value assets, which require an inspector and appraiser. Sellers can list their assets by instantiating an asset transfer smart contract. Buyers can make offers by taking an action on the smart contract, and other parties can take actions to inspect or appraise the asset. Once the asset is marked both inspected and appraised, the buyer and seller will confirm the sale again before the contract is set to complete. At each point in the process, all participants have visibility into the state of the contract as it is updated. 

There are four personas in this demo contract – the seller as the initiator, and the other three personas (buyer, appraiser, and inspector) as participants. As indicated in the visual above, at certain stages in the contract, there are various actions which participants can take. The logic written in the smart contract will modify the state accordingly based on which actions are taken. 

Application Roles 
------------------
Name 	      Description
-------     ------------
Seller  	  A person who owns an asset and wants to sell the asset. (developed so far)
Buyer  	    A person who intends to buy the asset being sold by the seller. (developed so far)
Inspector  	A person who is chosen by the buyer to be the inspector of the asset being considered for buying.(yet to be developed)
Appraiser  	A person who is chosen by the buyer to be the appraiser for the asset being considered for buying.(yet to be developed) 
