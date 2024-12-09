# SHAKA BASE
### HOW CAN YOU INTEGRATE YOUR SESSION ID?:
## 1. visit <a href= "https://github.com/IRON-M4N/pair-example">PAIR EXAMPLE BY IRON M4N</a></b>
fork the repo and change prefix and deploy but stuff in config onlyy, then head to index.js and ./lib/session.js and change the prefix to the one you set in the pair example you deployed, pair abd put session id
### plugin creation below
```
command(
  {
    pattern: "ssweb ?(.*)",
    fromMe: true,
    desc: "screenshots a site",
    type: "misc",
  },
  async (message, match) => {
    })
  }
);
```
### Image url with thumbnail

```
const imageUrl = "https://files.catbox.moe/flinnf.jpg"; // Developer image
        const thumbnailUrl = "https://files.catbox.moe/cuu1aa.jpg"; // Thumbnail image

        await message.client.sendMessage(message.jid, {
            image: { url: imageUrl },
            caption: devInfo,
            contextInfo: {
                externalAdReply: {
                    title: "𝞖𝞓𝞙𝞘 𝙎𝞢𝞒 - Developer Info",
                    body: "About haki",
                    sourceUrl: "https://haki.us.kg", // Link to website
                    mediaUrl: "https://haki.us.kg",
                    mediaType: 4,
                    showAdAttribution: true,
                    renderLargerThumbnail: false,
                    thumbnailUrl: thumbnailUrl,
                },
            },
        });
    }
);
```

### only image 
```
const imageUrl = "https://files.catbox.moe/etg6fk.jpg"; // Replace with your image URL

        await message.client.sendMessage(message.jid, {
            image: { url: imageUrl },
            caption: devInfo,
        });
    }
);
```


## Credits:
👉 <a href = "https://haki.us.kg">H4KI SER</a></br>
👉 <a href = "#">STAR KING</a></br>
👉 <a href = "#">IRON M4N</a></br>
👉 <a href = "#">PARADOXICAL</a></br>

## all rights reserved, made with so much ❤️ by haki🍀
