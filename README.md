### Whatsapp Birthday congratulator script

I usually forget to congratulate people on their birthday so decided to make a tiny script for it. 

Uses a Google Sheets csv to track birthday and sends an api request that should open your local Whatsapp app. You still need to press send (reduces moral guilt). I run the script on startup.

#### Default CSV example

| Name  | Birthday   | Number   | Language |
| ----- | ---------- | -------- | -------- |
| John  | 02/01/2023 | 49xxxxxx | EN       |
| Maria | 09/02/2023 | 34xxxxx  | ES       |

#### Google Sheets csv setup

1. Open sheet
2. Click on share
3. Allow anyone with the link
4. Copy link, replace `edit?usp=sharing`with `export?gid=0&format=csv`
5. Paste link where URL

#### Languages supported

- English (EN)

- Spanish (ES)