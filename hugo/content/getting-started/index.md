---
title: "Getting started"
date: 2018-01-22T15:46:08+09:00
draft: false
---

## Quick start

included html
```$xslt
<link rel="stylesheet" href="css/crypto-currency-icon.css">
```

**Install with [npm](https://www.npmjs.com):**
```$xslt
$ npm install crypto-currency-icon
```

**SCSS**
```$xslt
@import "/node_modules/crypto-currency-icon/dist/crypto-currency-icon.css";
```


**HTML**

Bitcoin

```$xslt
<p class="icon cryptoCoin btc"></p>
```

![bitCoin](/images/bitcoin_30.png)


Ripple
```$xslt
<p class="icon cryptoCoin xrp"></p>
```

![Ripple](/images/ripple_30.png)


add Size Variation.
```$xslt
<p class="icon cryptoCoin xrp small"></p>
```


![Ripple](/images/ripple_20.png)

## Icon Size

| size (px)     | css className |  images  |
|:-------------:|:-------------:|:--------:|
| 14px × 14px   | mini          | <p class="icon cryptoCoin btc mini"></p> |
| 20px × 20px   | small         | <p class="icon cryptoCoin btc small"></p>  |
| 30px × 30px   | medium        | <p class="icon cryptoCoin btc"></p> |
| 50px × 50px   | large         | <p class="icon cryptoCoin btc large"></p> |
| 100px × 100px | big           | <p class="icon cryptoCoin btc big"></p> |


**Clone the repo:**

```$xslt
$ git clone git@github.com:webcyou/crypto-currency-icon.git
```


## Start Develop

```$xslt
npm install
```

If necessary, install Hugo and other Go.

```$xslt
brew install hugo
```


```$xslt
npm run start
```

Open `http://localhost:1313` in your browser.