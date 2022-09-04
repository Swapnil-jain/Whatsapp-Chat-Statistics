# WhatsApp Chat Analysis
Upload your WhatsApp chats and the tool analyses them for you. Works for both group chats and individual chats. None of the chats are stored, and your data is 100% secured.

It is live at: https://whatsapp-message-analysis.herokuapp.com/

## What it shows ?
1. Top statistics including total messages, total links shared, total words etc.
2. Monthly and Daily Timeline graphs.
3. Monthly and Daily Activity map including Heat map.
4. Wordcloud and top word count.
5. Emoji analysis and pie chart.

<img width="1436" alt="Screenshot 2022-09-04 at 11 41 54 AM" src="https://user-images.githubusercontent.com/36638309/188300165-a73e6304-fad8-413d-8e95-716f8824c2ec.png">
<img width="1437" alt="Screenshot 2022-09-04 at 11 42 19 AM" src="https://user-images.githubusercontent.com/36638309/188300172-a72b1010-cc72-42b0-a4f7-9dc672014831.png">
<img width="1436" alt="Screenshot 2022-09-04 at 11 42 00 AM" src="https://user-images.githubusercontent.com/36638309/188300175-6ee856c0-0e93-4562-a86d-c1836cc77a05.png">
<img width="1432" alt="Screenshot 2022-09-04 at 11 42 11 AM" src="https://user-images.githubusercontent.com/36638309/188300183-0a859975-b66d-45fd-9685-8a1059637463.png">



## How to use?
1. Change your phone time to 24 hours. Close Whatsapp and open it again.
2. On any WhatAapp chat, click "Export chat".
3. Select "Without Media".
4. Upload the text file generated in the website.
5. Choose either Overall Analysis or any particular user.

## Known issues:
1. Works only for 24 hours time format for now. Will soon make it work for any format.
2. Emojis are sometimes not visible in the pie-chart, due to incompatible support from matplotlib for those emojis.

### Tech stack used:
Python, Streamlit, Heroku, Lottie and data analysis libraries like numpy, pandas, matplotlib etc.
