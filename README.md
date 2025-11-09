# Instagram Follower Comparison

A browser-based tool that helps you see who is not following you back on Instagram using the data archive you can request from Instagram.

## How to use the tool

1. Log in to Instagram on a computer.
2. Request your data by following the official guide: [Access and download your information on Instagram](https://help.instagram.com/181231772500920).
3. Choose **JSON** as the format and **All time** as the date range when generating the archive.
4. After downloading the archive you have two options:
   - **Upload the ZIP archive** directly. The app reads the required `following.json` and all `followers_*.json` files automatically.
   - **Upload the JSON files manually.** Extract the archive, navigate to `connections/followers_and_following`, then select `following.json` and every `followers_*.json` file.
5. Click **Check** to compare the lists. The result shows every account you follow that does not follow you back.

> Processing happens entirely in your browser. No data is uploaded to a server.

## Live demo
https://phumix.com/tools/Instagram-Follower-Comparison/
