# BannerEverywhere
BannerEverywhere is a powerful Discord bot extension that automatically adds a custom banner image to embeds sent in designated channels. This is perfect for creating a consistent visual brand across your server's announcement or media channels.
> 💡 **Built for the Zygnal Ecosystem — to download and use this extension, you must be part of the Zygnal Ecosystem.**  
> This extension (cog) is part of the **Zygnal Ecosystem** and is only available through its supported platforms.  
> You can use it with:  
> - The **[Discord Bot Framework](https://github.com/TheHolyOneZ/discord-bot-framework)** — ideal for developers who want full control and flexibility *(includes an integrated extension marketplace)*, or  
> - The **[ZygnalBot](https://zygnalbot.de)** — a prebuilt, plug-and-play Discord bot *(also includes an integrated extension marketplace)*.  
>
> Browse and install extensions at [zygnalbot.com/extension](https://zygnalbot.com/extension).  
> For help or community discussions, join us on Discord: [discord.gg/sgZnXca5ts](https://discord.gg/sgZnXca5ts)
# BannerEverywhere

BannerEverywhere is a powerful Discord bot extension that automatically adds a custom banner image to embeds sent in designated channels. This is perfect for creating a consistent visual brand across your server's announcement or media channels.

---

### Key Features

* **Custom Banners:** Attach a specific image or GIF to embeds in chosen channels.
* **Multi-Channel Support:** Configure different banners for different channels within the same server.
* **Easy Setup:** A simple, interactive panel lets you configure channels without needing to remember complex commands.
* **Persistence:** Your configurations are saved, so you don't need to set them up again if the bot restarts.

---

### Commands

This extension primarily uses an interactive panel to manage settings.

* `/banners` or `!banners`
    * **Description:** Opens the main configuration panel.
    * **Usage:** Use this command to access a menu with buttons for adding, removing, and viewing your banner configurations.
    * **Permissions:** Requires **Administrator** permissions.

---

### How to Use the Panel

1.  Use the `/banners` or `!banners` command to open the panel.
2.  Click the **"Add Channels"** button. The bot will ask you to send a message with the channels and banner URLs you want to add.
    * **Format:** `#channel_name:your_banner_url`
    * **Example:** `#announcements:https://example.com/banner.gif, #events:https://example.com/other-banner.png`
3.  Click the **"Remove Channels"** button. The bot will ask you to send a message with the channel names you want to remove.
    * **Format:** `#channel_name`
    * **Example:** `#announcements, #old-channel`
4.  Click the **"Status"** button to see a list of all channels currently configured with a banner.
