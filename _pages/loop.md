---
layout: defaultBlank
title: Loop Demo
permalink: /loop
---

<h2>Loop Example</h2>

```javascript
var objects = [
        {
            type: 'RDC', 
            data: { 
                RiskScore: 34 
                }
        },
                {
            type: 'RDC', 
            data: { 
                RiskScore: 32 
                }
        }
    ];
var rules = [
        {
            dataType: 'number', 
            expectedValue: 34
        },
        {
            dataType: 'number', 
            expectedValue: 344
        },
    ];
```



<script>
var obj = [
        {
            type: 'RDC', 
            data: { 
                RiskScore: 34 
                }
        },
                {
            type: 'RDC', 
            data: { 
                RiskScore: 32 
                }
        }
    ];
var rls = [
        {
            dataType: 'number', 
            expectedValue: 34
        },
        {
            dataType: 'number', 
            expectedValue: 344
        },
    ];

let loopProps = function(obj, rules) {
        for(const property in obj) {
            document.write(`${property}: ${obj[property]}, typeof: ${typeof obj[property]} <br />`);
            check(obj[property], rules);
        }
}
let loopArr = function(objRes, rules) { 
    for (var i = 0; i < objRes.length; i++) {
        var obj = objRes[i];
        document.write(` <br /> <br />looping array item: ${JSON.stringify(obj)} <br />`)
        loopProps(obj, rules);
    }
}
let loopRules = function(property, rules) {
    for (var y = 0; y < rules.length; y++) {
        var rule = rules[y];
        document.write(`Checking Rule: ${JSON.stringify(rule)} <br />`)
        var propType = typeof property
        if (propType === rule.dataType) {
            document.write(`${propType} == ${rule.dataType} <br />`);
            document.write(`Check Value: ${property} == Rule Expected Value: ${rule.expectedValue} <br />`);
        }
    }
}
let check = function(objRes, rules) {
    let objResType = typeof objRes;
    switch (objResType) {
        case 'object':
            if (Array.isArray(objRes)) {
                loopArr(objRes, rules);
            } else {
                loopProps(objRes, rules);
            }
            break;
        case 'string': 
            loopRules(objRes, rules);
            break;
        case 'number': 
            loopRules(objRes, rules);
            break;
    }
}

check(obj, rls)

</script>
<br />
<br />
<br />
<br />
```javascript 
    /// check the incoming data
    let check = function(objRes, rules) {
        let objResType = typeof objRes;
        switch (objResType) {
            case 'object':
                if (Array.isArray(objRes)) {
                    document.write('looping array <br />')
                    loopArr(objRes, rules);
                } else {
                    loopProps(objRes, rules);
                }
                break;
            case 'string': 
                loopRules(objRes, rules);
                break;
            case 'number': 
                loopRules(objRes, rules);
                break;
        }
    }
```

```javascript
    // setup each of the loops
    let loopProps = function(obj, rules) {
        for(const property in obj) {
            document.write(`${property}: ${obj[property]}, typeof: ${typeof obj[property]} <br />`);
            check(obj[property], rules);
            }
    }
    let loopArr = function(objRes, rules) { 
        for (var i = 0; i < objRes.length; i++) {
            var obj = objRes[i];
            document.write(`looping array item: ${JSON.stringify(obj)} <br />`)
            loopProps(obj, rules);
        }
    }
    let loopRules = function(property, rules) {
        for (var y = 0; y < rules.length; y++) {
            var rule = rules[y];
            document.write(`Checking Rule: ${JSON.stringify(rule)} <br />`)
            var propType = typeof property
            if (propType === rule.dataType) {
                document.write(`${propType} == ${rule.dataType} <br />`);
                document.write(`Check Value: ${property} == Rule Expected Value: ${rule.expectedValue} <br />`);
            }
        }
    }
```