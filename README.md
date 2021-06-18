<div style="display: flex;justify-content:space-between;margin-bottom:50px;">
<img src="jobsamuel.svg" width="100px" style="flex-basis:auto;align-self:center" />
<div style="flex-basis:auto;align-self:center;margin-left:50px;font-family:monospace;">
TheDoor_eyJuYW1lIjoiSm9ic2FtdWVsIE51bmV6IiwiYmlydGhkYXRlIjoiMTk5MC0wMS0wOFQwNDowMDowMC4wMDBaIiwiY291bnRyeSI6IlZlbmV6dWVsYSDwn4e78J+HqiIsImF2YWlsYWJsZV9mb3JfaGlyZSI6dHJ1ZSwibGFuZ3VhZ2VzIjpbIkphdmFTY3JpcHQiLCJFbmdsaXNoIiwiU3BhbmlzaCJdLCJ0ZWNoX3N0YWNrIjpbIkZpcmViYXNlIiwiTm9kZS5qcyIsIlZlcmNlbCIsIk5leHQuanMiLCJSZWFjdCJdfQ==
</div>
</div>

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
