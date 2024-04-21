# Chain Logos

A collection of normalized blockchain logos.

## Requirements

The naming convention for logos is `<chain>Logo.png` where the chain name is
lowercase and contains no spaces.

**Example:** _Polygon ZKEVM -> polygonzkevm_

### PNG

- **Ratio:** 1:1
- **Size:** 400x400px

All logos in `png` directory are strictly 400x400px as I use them in Farcaster
Frames where large images drastically slow down page load times.

Larger icons are in `png-large`.

### SVG

SVG files have minimal metadata.

### BASE64

Icons in base64 contain only the necessary code. Place the code into the
formatting below depending on your required useage.

#### For use in <img> elements

`data:image/png;base64;<logo code>`

#### For use as CSS background

`url('data:image/png;base64,<logo code>')`

---

If you have any questions, you can find me on [Warpcast](https://warpcast.com/jonbray.eth) 🫡
