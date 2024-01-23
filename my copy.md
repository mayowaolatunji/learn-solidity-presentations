# Smart Contracts: A Blockchain Program

A smart contract is blockchain-deployed code. For example:

```js
contract Agreement {
  address recipient;
  bool conditionIsMet;

  function payout() external {
    if(conditionIsMet) {
      sendValue(recipient);
    }
  }

  // ......
}
```

---