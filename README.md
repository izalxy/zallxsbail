# Modified Whatsapp-API
<p align='center'>
  <img src="https://files.catbox.moe/hor8kz.jpg" width="350">
</p>

--- 

## Usage
```json
"depencies": {
  "@whiskeysockets/baileys": "github: izalxy/zallxsbail"
}
```
## Import
```javascript
const {
  default:makeWASocket, 
} = require('@whiskeysockets/baileys');
```

```javascript
await zal.relayMessage(m.chat, {
  productMessage {
    title: "Izalnotdev",
    description: "Xhsut Engine",
    thumbnail: { url: "./zalThumb" },
    url: "https://t.me/Izalnotdev",
    body: "Buy Access",
    footer: "Footer",
    buttons: [
      {
        name: "cta_url",
        buttonParamsJson: "{\"display_text\":\"zal.index\",\"url\":\"https://t.me/Izalnotdev\"}"
      }
    ],
    priceAmount1000: 120.000,
    currencyCode: "IDR"
  }
})
```
