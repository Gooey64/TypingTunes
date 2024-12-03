# TypingTunes

Web Programming final project

## How it works

1. User searches for a song

   ```{json}
   {
       "title": "chandelier",
       "artist": "sia"
   }
   ```

2. We query the lyrics API

   ```{json}
   GET https://lyrist.vercel.app/api/chandelier/sia
   ```

   ```{json}
   {
       "lyrics": "[Verse 1]\nParty girls don't get hurt\n...",
       "title": "Chandelier",
       "artist": "Sia",
       "image": "https://images.genius.com/0503a01c6f9a632167d3de01ca687976.1000x1000x1.png"
   }
   ```

3. Start up the typing!
