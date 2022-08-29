# Huff Challenge

### contract code

```js
0x60003560e01c806364c4ef1a1461002157806364d98f6e146100295760006000fd5b602435600435555b595459525b602060026000518060ff169060081c60005260011b61009701603e3951565b6108001460005260206000f35b0161002e565b0261002e565b0361002e565b0461002e565b6000518060ff169060081c60005261002e565b1461002e565b1b61002e565b1c61002e56004d005a00600066006c00720085008b0091
```

### interface
```js
interface IHuffChallenge {
	function isSolved() external returns (bool);
	function set(uint256, bytes32) external;
}

```

deployed at [0xbFd9Bed7Cf6ebd303465314Ca00a6DFC853085c8](https://mumbai.polygonscan.com/address/0xbFd9Bed7Cf6ebd303465314Ca00a6DFC853085c8#code)

### [code](src/HuffChallenge.huff) 
![](HuffChallengeImg.png)