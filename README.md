# Discord Reopen DM

```js
const TOKEN = "";
const RECIPIENT_USER_ID = "";

fetch("https://discord.com/api/v9/users/@me/channels", {
  headers: {
    authorization: TOKEN,
    "content-type": "application/json",
  },
  body: `{"recipients":[${RECIPIENT_USER_ID}]}`,
  method: "POST",
});
```
