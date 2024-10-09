
# Mcoins Swap Widget Integration Guide

## Introduction

This guide provides a step-by-step process to seamlessly embed the Mcoins Swap Widget into your website. By following the instructions below, you can offer a smooth swap experience for your users.

## Step 1: Copy the iFrame Code

The first step involves copying the iFrame code snippet provided below:

```html
<iframe 
    src="https://app.mcoins.xyz/swap-widget?token0=0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56&token1=TOKEN1_ADDRESS&chainid=CHAIN_ID" 
    width="400" 
    height="500" 
    style="border-radius: 15px;">
</iframe>
```

### Important:
- Replace `TOKEN1_ADDRESS` with the contract address of your desired token.
- Set `CHAIN_ID` to the appropriate blockchain identifier:
  - Use `56` for BSC (Binance Smart Chain).
  - Use `137` for Polygon.
  - Use `8453` for Base Chain (ETH)
  - Use `369` for Pulsechain

## Step 2: Embed the Code into Your Website

Once you have customized the iFrame code with your token address and chain ID, paste it into the HTML of your website at the desired location. The swap widget will automatically appear, offering a user-friendly interface for token swapping.

## Conclusion

By following these steps, you have successfully integrated the Mcoins Swap Widget into your website. We are continuously working on enhancing our features, including the ability to select token pairs and lock tokens directly within the swap widget.

If you require further assistance, please do not hesitate to contact our support team.

