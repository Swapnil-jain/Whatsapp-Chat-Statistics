# WhatsApp Chat Analysis
Upload the chats and analyse common statistics about the chat. Works for both group chats and individual chats.

It is live at: https://whatsapp-message-analysis.herokuapp.com/

How to use?
1. Change your phone time to 24 hours. Close Whatsapp and open it again.
2. On any whatsapp chat, click "Export chat".
3. Select "Without Media".
4. Upload the text file generated in the website.
5. You now have data about ur chats.

Known issues:
1. Works only for 24 hours format for now. Will soon make it work for any format.
2. Emojis are sometimes not visible in the pie-chart, due to incompatible support from matplotlib for those emojis.

Tech stack used:
Python, Streamlit, Heroku and other common data analysis libraries like numpy, pandas etc.
