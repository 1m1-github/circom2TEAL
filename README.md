# circom2TEAL
create TEAL smart contracts from circom circuits to zero-knowledge-prove any quadratic statement

circom -> TEAL
create the equivalent of snarkjs for another, non-EVM chain. this would be a very simple version with only the most basic functionality  

mainly, create verification smart contracts and generate witness data in the correct format. the chain of choice would be Algorand, which runs the so-called AVM  

the benefit of this tool would be that devs could start using circom to create zk proofs on Algorand  

the main obstacles will be making sure the TEAL code is 100% correct (unit tests + logic) for the algebra and creating a nice frontend  
 
otherwise, the tool will use snarkjs to export the`verification key` and import that into a Algorand smart contract that can go elliptic curve algebra
