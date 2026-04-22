# StoreAddress.sol
StoreAddress.sol
pragma solidity ^0.8.20;
contract StoreAddress {
    address public addr;

    function set(address _a) public {
        addr = _a;
    }
}
