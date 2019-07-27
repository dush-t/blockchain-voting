# Idea for Codefundo++

## Voter Registration

An adult citizen of India will have to make a digital signature before voting. The digital signature will have lifetime validity. The user will give the hash of the first half of his/her digital signature. The user will need to visit the government office, get his/her credentials verified and receive the "unhashed" version of the second half of the digital signature generated by government servers. The unhashed first and second halves will make the whole signature. Once the second half is added, the complete SHA256 hash is stored in a blockchain along with the user's data. After the user gets it made, he or she can use it to vote remotely, too. The bigger blockchain containing digital signature hashes will not be stored on every node. It will be on government servers. There will be no consensuse protocol. Biometric verification will be used in its place- eyes, fingerprints and face. 

## A Week Before Voting

The user will generate a vote request signed by his/her digital signature. The vote request will be sent to a verifying organisation, in this case the Election Commission (EC) or a similar government organisation. The organisation will find the block with the given hash in the master blockchain where all user data is stored. The extracted user data will be matched with the data provided in the vote request. If they match, a voting key will be generated which will be sent to the user via electronic means. The SHA256 hash value of the voting key, along with the user ID, will now be stored in a separate blockchain. If the data does not match, the vote request will be rejected and the user will be notified.

## During Voting

The user will use the voting key issued to him/her to vote for a candidate of his/her choice.


## Vote Storage

There will be state-wise blockchains, with each blockchain hosted on every server in a P2P format.









The given flowchart provides an outline of our idea. Please start reading from "The USER" in either direction.

![flowchart](https://raw.githubusercontent.com/dush-t/blockchain-voting/master/flowchart.jpeg?token=AKJFV2ITYPMXVGTSPK4APPK5HXDSY) 
