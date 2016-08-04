# javascript megalogger client

##Installation:
**add script below into header tag in your project**
```
 <script language="JavaScript" type="text/javascript" src="src/jwt-lib.min.js"></script>
 <script language="JavaScript" type="text/javascript" src="src/megalogger-client.js"></script>
```


##Usage:
**Add the code below into your function**

```javascript
 var apiInfo = 'asefas_efjhj-afsd64sf_megaToken';
 var dataLog = [{data: "Message test"}];
 var level = 'info';
 _MEGALOGGER.clientLib._pushLog(apiInfo, dataLog, level, 'test_log');
 
```



