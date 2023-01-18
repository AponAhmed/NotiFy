# NotiFy
 Simple Notification for web, there three types of Notification - success,warning,error

## Installation
    `npm i @aponahmed/notify`

## Uses
```javascript
import Notification from "@aponahmed/notify";

new Notification({
    type:"success",
    message: "This is a success message via Notification",
    timeout:3000 // Default timeout 6 second or 6000ms, if not `success` notification then it will multiply by 2
});

```



