#Plug-Badges
A way to get plug's chat badge easily.

#How to use

Assuming `badgeName` is valid (you can check examples in [/img](img), we can do this :
```javascript
var badgeURL = 'https://cdn.rawgit.com/WiBla/Plug-Badges/master/img/'+badgeName;
// There are 4 gif badges
if (badgeName === 'beachb-e01' ||
    badgeName === 'beachb-e02' ||
    badgeName === 'nycb-e01' ||
    badgeName === 'nycb-e02') {
    badgeURL += '.gif';
} else {
    badgeURL += '.png';
}
```

##Disclaimer
All images listed here are property of Plug Technologies, Inc.
