# Privacy Policy
## 1. Introduction

This Privacy Policy explains what data the Sentinel Discord bot ("the Bot") and its public leaderboards website ("the Leaderboards") collect, why it is collected, how it is stored, and your rights regarding that data.

The Bot is operated by **ItsMias** and is active in the **Beyond The Horizon Discord server**. By being a member of the discord server or by directly interacting with the Bot, your data may be processed as described below.

## 2. Data We Collect

When you send a message or use a voice channel in the server, the following is recorded automatically:
- **Discord User ID**
- **Discord Guild ID** 
- **Message count** 
- **XP & Total XP** 
- **Level** 
- **Rank** (Leaderboard position)
- **Last reward role** 
- **XP earned each day** (from messages, voice and XP drops)
- **Time spent in voice channels**
- **Activity streaks** (current and best)

**Message content is never stored.** Only the fact that a message was sent is counted.

For the Leaderboards, your **name in the server** and a **link to your avatar** are fetched from Discord about every 30 minutes. They are removed at the next update if you leave the server or use `/no xp`.

When someone views the Leaderboards, the web server logs their **IP address**, the page they opened and their browser details. These logs are deleted after about two weeks.

If you choose to link your Minecraft account to your Discord account, the following is stored permanently:
- **Discord User ID**
- **Minecraft UUID**
- **Minecraft Username** 

When a users joins the `link.itsmias.com` Minecraft server, a temporary 6-digit code is generated and stored alongside your Minecraft UUID and username. Data is deleted after 5 minutes if the link is unsuccessful.

Your Minecraft username may be automatically updated in our records if it has changed since you last linked. To verify usernames, the Bot queries the **Mojang Session Server API** using your Minecraft UUID. No additional data beyond your username is retrieved from this API.

If an error occurs while you are using the Bot, the following may be captured:
- **Discord User ID**
- **Discord Guild ID** 
- **Interaction ID** 
- **Error details** 
This data will be deleted by **ItsMias** once your bug has been dealt with.

## 3. What We Do Not Collect
- **Message content**
- **IP addresses**, except in the Leaderboards web server logs described in Section 2
- **Command arguments**

## 4. Why We Collect This Data
- **Leveling data**, to run the leveling system and the Leaderboards.
- **Names and avatars**, to show who is who on the Leaderboards.
- **Web server logs**, to find problems with the Leaderboards.
- **Minecraft linking data**, to associate your Discord and Minecraft for role synchronization.
- **Error logs**, to identify and fix bugs in the Bot.

## 5. How Long We Keep Your Data
All data that is stored, is kept indefinitely unless otherwise stated.
  

## 6. Who Has Access to Your Data
- **ItsMias** - is the only person who can access the database and the server it runs on, for maintenance and administration. Sentinel is hosted on a private server, which The Horizon and Aalchemy no longer have access to.
- **Bot administrators (ItsMias and The Horizon)** - can use Bot commands to look up which Minecraft account is linked to which Discord account, read error details, and change or delete stored data.
- **Members with certain roles** - can look up and remove linked accounts with Bot commands, or see account links posted in a private staff channel.
- **Staff and Contestant Portal admins** - can see the Minecraft accounts linked by staff and contestants.
- **Other users** - can view your data through commands like `/rank`, `/leaderboard` & `/xpchart`.
- **Anyone on the internet** - can view your name, avatar, level, XP (including XP per day), message count, voice time, streaks and XP drops on the [Leaderboards](https://leaderboards.itsmias.com/1051717586313826314), without a Discord account. You are not listed if you have left the server or use `/no xp`. Linked Minecraft accounts are not shown.
- **Third parties** - your data is **never sold or shared** with any third party, unless stated otherwise.

## 7. Third-Party Services

The Bot interacts with the following external services:
- **Discord** - the platform the Bot operates on. Discord's own [Privacy Policy](https://discord.com/privacy) applies to your use of Discord. The Leaderboards load avatars from Discord, so Discord receives the IP address of anyone viewing them.
- **Mojang Session Server** (`sessionserver.mojang.com`) - triggered to look up Minecraft usernames by UUID. 

## 8. Your Rights (GDPR)
If you are located in the European Economic Area (EEA) or United Kingdom, you have certain rights under the General Data Protection Regulation (GDPR). To exercise any of these rights, please contact us using the details in Section 11.

## 9. Data Security
Your data is stored in a local SQLite database on a private server. Only ItsMias can access the server and the database directly.

## 10. Limitation of Liability  
While we take reasonable steps to protect your data, we cannot guarantee absolute security. In the event of a data breach or unauthorised access, we accept no liability for any resulting damages, losses, or harm. By using the Beyond The Horizon Discord server and interacting with the Bot, you acknowledge and accept this risk. 

## 11. Contact
If you have questions about this policy, wish to exercise your data rights, or want to request deletion of your data, please contact us:
- **Discord:** Open a ticket in the support channel.
- **Email:** Send an email to `sentinel@beyondthehorizon.xyz`

## 12. Changes to This Policy
We may update this policy at any time. The "Last updated" at the bottom of this website shows when the latest changes were made. Continued use of the server after changes are made constitutes acceptance of the updated policy.
