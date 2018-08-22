![Shadowrun Logo](/shadowrunlogo.png) <br/>
<br/>
# Roller

This probject aims to be an easy to use tool to roll dice pools for Shadowrun. Select the DP (Dicepool) number from the drop down menu and the system will show how many hits and how many glitches.
```html
<button id="button">Roll</button>
```
```javascript
var dice = {
  sides: 6,
  roll: function () {
    var randomnumber = Math.floor(Math.random() * this.sides) + 1;
    return randomnumber;
    }
}
```

