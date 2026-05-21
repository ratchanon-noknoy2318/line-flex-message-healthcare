<p align="left">
  <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779241423/%E0%B8%AA%E0%B8%81%E0%B8%A3%E0%B8%B5%E0%B8%99%E0%B8%8A%E0%B9%87%E0%B8%AD%E0%B8%95_2026-05-20_084327_qaqnhc.png" width="300"/>
  <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779241693/%E0%B8%AA%E0%B8%81%E0%B8%A3%E0%B8%B5%E0%B8%99%E0%B8%8A%E0%B9%87%E0%B8%AD%E0%B8%95_2026-05-20_084806_arsa4m.png" width="300"/>
  <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779250510/%E0%B8%AA%E0%B8%81%E0%B8%A3%E0%B8%B5%E0%B8%99%E0%B8%8A%E0%B9%87%E0%B8%AD%E0%B8%95_2026-05-20_111446_j3ghrt.png" width="300"/>
   <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779241747/%E0%B8%AA%E0%B8%81%E0%B8%A3%E0%B8%B5%E0%B8%99%E0%B8%8A%E0%B9%87%E0%B8%AD%E0%B8%95_2026-05-20_084858_se4vfw.png" width="300"/>
  <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779250660/%E0%B8%AA%E0%B8%81%E0%B8%A3%E0%B8%B5%E0%B8%99%E0%B8%8A%E0%B9%87%E0%B8%AD%E0%B8%95_2026-05-20_111715_u4eku2.png" width="300"/>
   <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779250757/%E0%B8%AA%E0%B8%81%E0%B8%A3%E0%B8%B5%E0%B8%99%E0%B8%8A%E0%B9%87%E0%B8%AD%E0%B8%95_2026-05-20_111906_nw7dq3.png" width="200"/>
</p>


## Example Flex Message (JSON)

Below is an example of a Flex Message used in this system for healthcare communication via LINE Messaging API.

```json
{
  "type": "bubble",
  "hero": {
    "type": "image",
    "url": "https://developers-resource.landpress.line.me/fx/img/01_1_cafe.png",
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
        "type": "box",
        "layout": "baseline",
        "margin": "md",
        "contents": [
          {
            "type": "text",
            "size": "sm",
            "color": "#999999",
            "margin": "md",
            "flex": 0,
            "text": "บริการปรึกษาแพทย์ทางไกล"
          }
        ]
      },
      {
        "type": "box",
        "layout": "vertical",
        "margin": "lg",
        "spacing": "sm",
        "contents": [
          {
            "type": "box",
            "layout": "baseline",
            "spacing": "sm",
            "contents": [
              {
                "type": "text",
                "text": "Place",
                "color": "#aaaaaa",
                "size": "sm",
                "flex": 1
              },
              {
                "type": "text",
                "text": "Kamphaeng Phet",
                "wrap": true,
                "color": "#666666",
                "size": "sm",
                "flex": 5
              }
            ]
          },
          {
            "type": "box",
            "layout": "baseline",
            "spacing": "sm",
            "contents": [
              {
                "type": "text",
                "text": "Time",
                "color": "#aaaaaa",
                "size": "sm",
                "flex": 1
              },
              {
                "type": "text",
                "text": "10:00 - 23:00",
                "wrap": true,
                "color": "#666666",
                "size": "sm",
                "flex": 5
              }
            ]
          }
        ]
      }
    ]
  },
  "footer": {
    "type": "box",
    "layout": "vertical",
    "spacing": "sm",
    "contents": [
      {
        "type": "button",
        "style": "link",
        "height": "sm",
        "action": {
          "type": "uri",
          "uri": "https://kppmch-register.vercel.app/PatientRegister",
          "label": "ลงทะเบียน"
        }
      },
      {
        "type": "button",
        "style": "link",
        "height": "sm",
        "action": {
          "type": "uri",
          "label": "ค้นหาวันนัด",
          "uri": "https://telemedscheduler.vercel.app/"
        }
      },
      {
        "type": "box",
        "layout": "vertical",
        "contents": [],
        "margin": "sm"
      }
    ],
    "flex": 0
  }
}
```

## Project Reference

LinkedIn:
https://www.linkedin.com/posts/ratchanon-noknoy_softwareengineering-backendengineering-systemsthinking-share-7437740581310648320-BKiJ
