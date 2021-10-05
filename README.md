<p align="center">
  <img src="jobsamuel.svg" width="60px" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original-wordmark.svg" alt="nextjs" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="react" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="25" height="25" />
  <img src="https://docs.soliditylang.org/en/v0.8.7/_images/logo.svg" alt="solidity" width="25" height="25" />
  <img src="https://assets.vercel.com/image/upload/q_auto/front/favicon/vercel/57x57.png" alt="vercel" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-plain.svg" alt="firebase" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-plain.svg" alt="nodejs" width="25" height="25" />
  <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/gatsby/gatsby-plain.svg" alt="gatsby" width="25" height="25" />
</p>

<h1> Hola 👋 I'm Jobs.</h1>

>DOOR_eyJuYW1lIjoiSm9ic2FtdWVsIE51bmV6IiwiZGVzY3JpcHRpb24iOiJBbiBlbmdpbmVlciB3aG8gbG92ZSB0byBjcmVhdGUgc2ltcGxlIGFuZCBwb3dlcmZ1bCBzb2x1dGlvbnMgdXNpbmcgSW50ZXJuZXQuIiwiZW1haWwiOiJob2xhQGpvYnNhLmNvIiwiYmlydGhkYXRlIjoiMTk5MC0wMS0wOFQwNDowMDowMC4wMDBaIiwiY291bnRyeSI6IlZlbmV6dWVsYSDwn4e78J+HqiIsImF2YWlsYWJsZV9mb3JfaGlyZSI6dHJ1ZSwiaG91cmx5X3JhdGVfaW5fdXNkIjo1MCwiYWNjZXB0X2J0Y19hc19wYXltZW50Ijp0cnVlLCJsYW5ndWFnZXMiOlsiSmF2YVNjcmlwdCIsIkVuZ2xpc2giLCJTcGFuaXNoIl0sImZhdm9yaXRlX3RlY2hfc3RhY2siOlt7Im5hbWUiOiJGaXJlYmFzZSIsImV4cGVyaWVuY2UiOiJzaW5jZSBpdHMgQkVUQSBsYXVuY2guIPCflKUifSx7Im5hbWUiOiJOb2RlLmpzIiwiZXhwZXJpZW5jZSI6IkR1cmluZyBteSBlbnRpcmUgY2FyZWVyLCBldmVyeSBhcHAgSSd2ZSBjcmVhdGVkIGhhdmUgYmVlbiBwb3dlcmVkIGJ5IE5vZGUuIPCfpJgifSx7Im5hbWUiOiJSZWFjdCIsImV4cGVyaWVuY2UiOiJTaW5jZSAyMDE4LCBJIGp1c3QgbG92ZSB0byBjcmVhdGUgVUlzIHdpdGggUmVhY3QuIPCfpKkifV0sImZhdm9yaXRlX29mZmxpbmVfYWN0aXZpdGllcyI6WyJjeWNsaW5nIiwicnVubmluZyIsInBob3RvZ3JhcGh5Il0sImludGVyZXN0cyI6WyJjcnlwdG8iLCJtYWNoaW5lIGxlYXJuaW5nIiwiZGF0YSBwcm9jZXNzaW5nIiwibWFwcyIsImVjb21tZXJjZSIsImJvdHMiLCJBUElzIl19


```js
// KEY.
function decodeData(token) {
  const encoded = token.split('_')[1]
  const json = Buffer.from(encoded, 'base64').toString()
  const data = JSON.parse(json)

  return data   
}

// ✨ hint: use Node.js to open the door. ✨
```

<!--
🎉🎉🎉
Here is the decoded data because you are the one who "work smarter, not harder."

```json
{
  "name": "Jobsamuel Nunez",
  "description": "An engineer who love to create simple and powerful solutions using Internet.",
  "email": "hola@jobsa.co",
  "birthdate": "1990-01-08T04:00:00.000Z",
  "country": "Venezuela 🇻🇪",
  "available_for_hire": true,
  "hourly_rate_in_usd": 50,
  "accept_btc_as_payment": true,
  "languages": [
    "JavaScript",
    "English",
    "Spanish"
  ],
  "favorite_tech_stack": [
    {
      "name": "Firebase",
      "experience": "since its BETA launch. 🔥"
    },
    {
      "name": "Node.js",
      "experience": "During my entire career, every app I've created have been powered by Node. 🤘"
    },
    {
      "name": "React",
      "experience": "Since 2018, I just love to create UIs with React. 🤩"
    }
  ],
  "favorite_offline_activities": [
    "cycling",
    "running",
    "photography"
  ],
  "interests": [
    "crypto",
    "machine learning",
    "data processing",
    "maps",
    "ecommerce",
    "bots",
    "APIs"
  ]
}
```

And this is the script used to hide at plain sight.
```js
function encodeData(prefix, data) {
  const json = JSON.stringify(data)
  const encoded = Buffer.from(json).toString('base64')
  const token = [prefix, encoded].join('_')

  return token
}
```
-->
