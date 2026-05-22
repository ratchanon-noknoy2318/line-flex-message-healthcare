![Messaging](https://img.shields.io/badge/Built_with-LINE_OA_Flex_Message-green)
![Package](https://img.shields.io/badge/Package-Free_Tier-blue)

<p align="left">
  <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779326376/%E0%B8%94%E0%B8%B5%E0%B9%84%E0%B8%8B%E0%B8%99%E0%B9%8C%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%B1%E0%B8%87%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B9%84%E0%B8%94%E0%B9%89%E0%B8%95%E0%B8%B1%E0%B9%89%E0%B8%87%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD_14_kguenq.png" width="400"/>
  <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779326489/%E0%B8%94%E0%B8%B5%E0%B9%84%E0%B8%8B%E0%B8%99%E0%B9%8C%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%B1%E0%B8%87%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B9%84%E0%B8%94%E0%B9%89%E0%B8%95%E0%B8%B1%E0%B9%89%E0%B8%87%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD_15_mae4gm.png" width="400"/>
</p>


## Example Flex Message (JSON)

Below is an example of a Flex Message used in this system for healthcare communication via LINE Messaging API.

```json
{
  "type": "bubble",
  "hero": {
    "type": "image",
    "url": "https://res.cloudinary.com/ds6xq6wbm/image/upload/v1756009686/%E0%B8%84%E0%B8%B7%E0%B8%AD%E0%B8%AD%E0%B8%B0%E0%B9%84%E0%B8%A3.png",
    "size": "full",
    "aspectRatio": "20:13",
    "aspectMode": "cover",
    "action": {
      "type": "uri",
      "uri": "https://line.me/"
    }
  },
  "body": {
    "type": "box",
    "layout": "vertical",
    "contents": [
      {
        "type": "text",
        "text": "Telemedicine",
        "weight": "bold",
        "size": "xl"
      },
      {
        "type": "text",
        "text": "บริการแพทย์ทางไกล",
        "weight": "regular",
        "size": "xl"
      }
    ]
  }
}
```

## LINE Flex Message Simulator

https://developers.line.biz/flex-simulator 
