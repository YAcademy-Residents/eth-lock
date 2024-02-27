## ETH Lock Contract

Design for fellows to stake ETH during a yAcademy fellow block. After the block ends, `newLock()` is called by the yAcademy admin to set a merkle root and the proofs are sent to each fellow individually to allow them to redeem their staked ETH.

If you are trying to run the tests are getting an error, try using `forge install OpenZeppelin/openzeppelin-contracts@v5.0.1` before running the tests.