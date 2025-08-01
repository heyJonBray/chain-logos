# Blockchain Network Logos

A collection of normalized blockchain logos.

## Install

```
npm install @heyjonbray/chain-logos
```

## Name Normalization

The naming convention for logos is the chain name in lowercase with no spaces.

**Example:** _Polygon ZKEVM -> polygonzkevm_

### PNG

- **Ratio:** 1:1
- **Size:** 400x400px

All logos in `png` directory are strictly 400x400px as I use them in Farcaster
Frames where large images drastically slow down page load times.

Icons > 400x400px should be placed in `png/large` dir.

### SVG

SVG files have minimal metadata.

### BASE64

Icons in base64 contain only the necessary code. After retrieving the data, it must be placed into the
format below depending on your required useage:

#### For use in `<img>` elements

`data:image/png;base64;<logo code>`

#### For use as CSS background

`url('data:image/png;base64,<logo code>')`

---

If you have any questions, you can find me on [Warpcast](https://warpcast.com/jonbray.eth) 🫡
