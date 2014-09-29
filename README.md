# CIE Calculator

[![Build Status](https://travis-ci.org/slopezm-adquira/cie-calculator.svg)](https://travis-ci.org/slopezm-adquira/cie-calculator)
[![Dependency Status](https://gemnasium.com/slopezm-adquira/cie-calculator.svg)](https://gemnasium.com/slopezm-adquira/cie-calculator)
[![GitHub version](https://badge.fury.io/gh/slopezm-adquira%2Fcie-calculator.svg)](http://badge.fury.io/gh/slopezm-adquira%2Fcie-calculator)

---

> Easily generate CIE References for BBVA Bancomer

## Minimal Usage

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title></title>
  <script src="../dist/ciecalculator.js" type="text/javascript"></script>
</head>
<body>
  <script type="text/javascript" charset="utf-8">
    console.log(CIECalculator({alg: '35', reference: '12346342'}));
  </script>
</body>
</html>

```

## Supported Algorithms

* 00
* 02
* 03
* 04
* 06
* 10
* 35
* 36
* 37


## Changelog

`0.0.1` : Initial release

## Contribute


### Dev

```
npm run watch
```

### Test

```
npm test
```

### Build

```
npm run build-debug
npm run build
```



