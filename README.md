# 🚀 11+ LINE Flex Message Templates

**Stop hand-coding complex nested JSON.** This is a curated collection of 11 LINE Flex Message templates (Free Tier), designed for easy use without manual JSON coding. Optimized for high conversion and consistent rendering across both iOS and Android devices.

---

## 📸 Preview Gallery
*Captured from [Flex simulator](https://developers.line.biz/flex-simulator/).*

| Telemedicine Start | Telemedicine More Info | About Us | Health Tip |
| :---: | :---: | :---: | :---: |
| <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581774/%E0%B8%94%E0%B8%B5%E0%B9%84%E0%B8%8B%E0%B8%99%E0%B9%8C%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%B1%E0%B8%87%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B9%84%E0%B8%94%E0%B9%89%E0%B8%95%E0%B8%B1%E0%B9%89%E0%B8%87%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD_h4iu7b.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581739/11_rg53qf.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581741/9_qzcm7o.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581740/10_eclrzt.png" width="200"> |
| [JSON](./TelemedicineStartFlexmessage.json) | [JSON](./TelemedicineMoreInfoFlexmessage.json) | [JSON](./AboutUsFlexmessage.json) | [JSON](./HealthTipsFlexmessage.json) |

## ⚙️ Developer Integration
Directly load JSON files and pass the content to the LINE Messaging API SDK. Environment variables (.env) are used to securely store the LINE Channel Access Token and Channel Secret.

**Node.js Example:**
```javascript
const getTelemedSession = require('./TelemedicineStartFlexmessage.json');

// Send via LINE Messaging API SDK
// Load environment variables
const config = {
  channelAccessToken: process.env.CHANNEL_ACCESS_TOKEN,
  channelSecret: process.env.CHANNEL_SECRET,
};

// LINE SDK client
import { Client } from "@line/bot-sdk";

const client = new Client(config);

// Import Flex Message JSON
import flexMessage from "./TelemedicineStartFlexmessage.json" with { type: "json" };

// Send message example
await client.pushMessage(USER_ID, flexMessage);
```
