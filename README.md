<p align="center">
  <img src="jobsamuel.svg" width="60px" />
</p>

<h1> Hola 👋 I'm Jobs.</h1>

>TheDoor_eyJuYW1lIjoiSm9ic2FtdWVsIE51bmV6IiwiYmlydGhkYXRlIjoiMTk5MC0wMS0wOFQwNDowMDowMC4wMDBaIiwiY291bnRyeSI6IlZlbmV6dWVsYSDwn4e78J+HqiIsImF2YWlsYWJsZV9mb3JfaGlyZSI6dHJ1ZSwibGFuZ3VhZ2VzIjpbIkphdmFTY3JpcHQiLCJFbmdsaXNoIiwiU3BhbmlzaCJdLCJ0ZWNoX3N0YWNrIjpbIkZpcmViYXNlIiwiTm9kZS5qcyIsIlZlcmNlbCIsIk5leHQuanMiLCJSZWFjdCJdfQ==

```js
// The key.
function decodeData(token) { 
  const encoded = token.split('_')[1]
  const json = Buffer.from(encoded, 'base64').toString()
  const data = JSON.parse(json)
  
  return data   
}

// ✨ hint: use Node.js to open the door. ✨
```

<!--
```json
{
  "name": "Jobsamuel Nunez",
  "birthdate": "1990-01-08T04:00:00.000Z",
  "country": "Venezuela 🇻🇪",
  "available_for_hire": true,
  "languages": [
    "JavaScript",
    "English",
    "Spanish",
  ],
  "tech_stack": [
    "Firebase",
    "Node.js",
    "Vercel",
    "Next.js",
    "React",
  ]
}
```
-->
