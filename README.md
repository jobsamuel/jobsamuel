<p align="center">
  <img src="jobsamuel.svg" width="60px" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original-wordmark.svg" alt="nextjs" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="react" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-plain.svg" alt="firebase" width="25" height="25" />
  <img src="https://assets.vercel.com/image/upload/q_auto/front/favicon/vercel/57x57.png" alt="vercel" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-plain.svg" alt="nodejs" width="25" height="25" />
  <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/gatsby/gatsby-plain.svg" alt="gatsby" width="25" height="25" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ubuntu/ubuntu-plain.svg" alt="ubuntu" width="25" height="25" />
</p>

<h1> Hola 👋 I'm Jobs.</h1>

>DOOR_eyJuYW1lIjoiSm9ic2FtdWVsIE51bmV6IiwiZGVzY3JpcHRpb24iOiJBbiBlbmdpbmVlciB3aG8gbG92ZSB0byBjcmVhdGUgc2ltcGxlIGFuZCBwb3dlcmZ1bCBzb2x1dGlvbnMgd2l0aCBKYXZhc2NyaXB0LiIsImVtYWlsIjoiaG9sYUBqb2JzYS5jbyIsImJpcnRoZGF0ZSI6IjE5OTAtMDEtMDhUMDQ6MDA6MDAuMDAwWiIsImNvdW50cnkiOiJWZW5lenVlbGEg8J+Hu/Cfh6oiLCJhdmFpbGFibGVfZm9yX2hpcmUiOnRydWUsImhvdXJseV9yYXRlX2luX3VzZCI6NTAsImFjY2VwdF9idGNfYXNfcGF5bWVudCI6dHJ1ZSwibGFuZ3VhZ2VzIjpbIkphdmFTY3JpcHQiLCJFbmdsaXNoIiwiU3BhbmlzaCJdLCJmYXZvcml0ZV90ZWNoX3N0YWNrIjpbeyJuYW1lIjoiRmlyZWJhc2UiLCJleHBlcmllbmNlIjoic2luY2UgaXRzIEJFVEEgbGF1bmNoLiDwn5SlIn0seyJuYW1lIjoiTm9kZS5qcyIsImV4cGVyaWVuY2UiOiJEdXJpbmcgbXkgZW50aXJlIGNhcmVlciwgZXZlcnkgYXBwIEkndmUgY3JlYXRlZCBoYXZlIGJlZW4gcG93ZXJlZCBieSBOb2RlLiDwn6SYIn0seyJuYW1lIjoiUmVhY3QiLCJleHBlcmllbmNlIjoiU2luY2UgMjAxOCwgSSBqdXN0IGxvdmUgdG8gY3JlYXRlIFVJcyB3aXRoIFJlYWN0LiDwn6SpIn1dLCJmYXZvcml0ZV9vZmZsaW5lX2FjdGl2aXRpZXMiOlsiY3ljbGluZyIsInJ1bm5pbmciLCJwaG90b2dyYXBoeSJdLCJpbnRlcmVzdHMiOlsiY3J5cHRvIiwibWFjaGluZSBsZWFybmluZyIsImRhdGEgcHJvY2Vzc2luZyIsIm1hcHMiLCJlY29tbWVyY2UiLCJib3RzIiwiQVBJcyJdfQ==


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
  "description": "An engineer who love to create simple and powerful solutions with Javascript.",
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
