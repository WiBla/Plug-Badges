# Plug-Badges
A way to get plug's chat badge easily.

# How to use

Assuming `badgeName` is valid (you can check examples in [/img](img)), we can do this :
```javascript
const baseURL = 'https://raw.githubusercontent.com/WiBla/Plug-Badges/master/img/';
// There are 4 gif badges
const isGif = ['beachb-e01', 'beachb-e02', 'nycb-e01', 'nycb-e02'].indexOf(badgeName) > -1;
const url = baseURL + badgeName + (isGif ? '.gif' : '.png');
console.log(`Your image url for badge ${badgeName} is: ${url}`);
```

## Disclaimer
All images listed here are property of Plug Technologies, Inc.
