# ticketting NFT smart contract

# Umut Yorulmaz - 101410083

# SUMMARY:

PROBLEM STATEMENT: Currently ticketting for travel and events such as; concerts, sports, gatherings, is handled by a central authority which is prone to hacks and security issues. The recent happening in USA, FAA (federal aviation administration) system outage caused thousands of flight cancellations on 11th of January 2023 across US, showed us the importance of the decentralization.

GOALS: There are two 2 goals of the project:
1- To assure the security of sensitive data:
When consumers buy a ticket the issuer collects all the consumer information like; credit card and ID details. In case of a hack or malicious issuer can steal this data. By issueing tickets as a NFT, consumers does not need to provide all their sensitive data.

2- Non-stop operation. As mentioned above failure of the issuer's system can halt all the operation. However, if a decentralized system is used instead, failures can be tolerated.

# USER'S OF THE SMART CONTRACT:

Consumers; can be an airline passenger, a spectator for a sports or a music event.

Organizer; can be an airline company or events company organizing the music or sports event.

# SCENARIO:

In this implementation, lets consider an NFT for airlines operations. Passengers would be able to choose their flight according to their travel needs from a marketplace like opensea but specifically designed for the airline industry. They would interact with the smart contract to make their payment in the form of crypto to book their flight and get the ticket in the form of an NFT, which would contain their flight details plus pasenger information, by connecting their web3 wallet such as; Metamask, Trustwallet, Keplr etc. When the day comes they would do online or inperson checkin by connecting their wallet and providing their public key. If it is a valid ticket (NFT) their NFT would be burned and the ticket would be printed and given to the customer to provide to airport visa officers and airline workers.

# ACTIONS:

As mentioned in the above scenario part, passengers would interact with the smart contract to transfer funds and get the ticket in the form of an NFT. They would keep that NFT in their wallet until their travel date. And when they need it they would go to checkin counter and would provide it by using a QR code, which triggers a transfer function. And NFT would be transferred to the smart contract back to be burned and it would be checked if it is valid and in case of a valid NFT boarding pass would be issued by the airline company and passenger can move to the plane.
