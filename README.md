Hello,
I am not a programmer but I can read and understand the logic behind a code. In order to track my portfolio's performance, I used a script I found online that allows me to get updated prices automatically. I adapted the script to my requirements: I didn't need the dashboard and the margin email notifications. Additionally, I added a time-based trigger that automatically refreshes the file and the figures every 5 minutes.

My dashboard (https://i.stack.imgur.com/S2Bs5.png)

However, for some reason the file is not updating automatically every 5 minutes and is not returning the message: "Rates were last updated at TIME".

Also, by comparing my sheet with the original one (link below), I noticed that this could be due to the following:

1. I removed BTC from where it was positioned.
2. I removed the contents in column A, Rows 2 and 3 which contained the formulas: =MATCH("BTC", B:B,0) / =MATCH("ETH", B:B,0)
3. I removed this formula from Column D, Row 27: =INDIRECT(ADDRESS(A2+1,9))

Original sheet and script: https://docs.google.com/spreadsheets/d/1t3tX22qEIK0HmgXgwiI0kxCLkBWFSSfusGGvxULWO1I/edit

Any help is appreciated :)
