# 签名交易
---
>*可在特定网站对插件请求签名（类似metamask）*

```javascript
window.VbWallet.request('signTransaction', {
    params: {
        from: "0xfB4ae1......6a44",
        to: '0xdd3d9A503A......4De4b076',
        value: 1000000000000000,
        gasLimit: 300000,
        maxPriorityFeePerGas: 1e9,
        maxFeePerGas: 10e9,
        data: '',
        nonce: 4,
        type: 2,
        chainId: 5
    }
})
    .then(res => console.log(res))
```