# AutoReply AI 🤖 (Smart Memory Version)

Kisi bhi messaging app (Toki, WhatsApp, Telegram...) pe aaye message ka
**context samajhkar** automatic human-style reply.

## Kaise kaam karta hai

1. Notification aata hai → app chat khud khol deta hai
2. Accessibility **poori visible chat padh leta hai** (kya baat ho chuki hai)
3. AI ko bhejta hai: chat history + naya message + tumhara persona
4. AI reply likhta hai jo **pichli baat ko continue karta hai** — random "Hi" nahi
5. Reply save hota hai history mein — har baar context aur strong hota hai

Smart mode mein TOKI TEAM / [Match] jaise system messages ka auto-reply nahi hota.

## APK kaise banaye (Android Studio nahi chahiye)

1. github.com pe free account banao
2. New repository: `AutoReplyAI` (Public, README tick mat karo)
3. ZIP extract karke saari files/folders wahi structure mein upload karo
4. Actions tab → enable → "Run workflow" → 4-5 min →
   Artifacts mein `app-debug.apk` download karo

## Phone setup

1. APK install karo → "unknown apps" allow karo
2. App kholo:
   - Notification Access ON → Accessibility ON (donon buttons app mein hain)
3. Custom package mein apna app add karo (Settings → Apps → package name)
4. **API key dalo** (platform.openai.com → API keys, thoda paid credit chahiye)
   aur **Persona** likho (jaise: "22 saal ka ladka, casual Hinglish, thoda funny")
5. Smart memory switch ON rakho
6. Test button se pehle check kar lo ✓

## ⚠️ Warning

Testing/personal use ke liye. Apps automation detect kar sakte hain aur account
restrict kar sakte hain. Human-like delay ON rakho, zyada spam mat karo.
API key sirf apne phone pe rakho, kisi ko mat dena.
