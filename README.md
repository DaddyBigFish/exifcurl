<img src="https://github.com/user-attachments/assets/3b663b88-c131-40b5-b811-39696521d017" alt="image-removebg-preview (7)" width="300"/>     

# Description
The tool 𝗲𝘅𝗶𝗳𝗰𝘂𝗿𝗹 was developed to solve the issue of downloading images in order to enumerate exiftool information. Essentially the tool will scrape all images into /tmp/exif and then it will run exiftool on them all, allowing the user to grep and search automatically.
# Usage
```
exifcurl absolute.htb | grep -oP '^Author\s*:\s*\K.*'
James Roberts
Michael Chaffrey
Donald Klay
Sarah Osvald
Jeffer Robinson
Nicole Smith
```
# Installation
`sudo wget https://github.com/DaddyBigFish/exifcurl/raw/refs/heads/main/exifcurl -O /usr/local/bin/exifcurl`     
`sudo chmod +x /usr/local/bin/exifcurl`
