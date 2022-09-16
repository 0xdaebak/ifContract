# ifContract

Contract Address : 0xaBE2cEFCcB2d0D4911dF3dbb3D409ad6ba67F8d0

It is a smart contract on bsc. You can check if address is smart contract or not.


## Key Function

```javascript
function isContract(address addr) public view returns (bool) {
  uint size;
  assembly { size := extcodesize(addr) }
  return size > 0;
}

```
 
## Authors

- [@0xdaebak](https://www.github.com/0xdaebak)



## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
