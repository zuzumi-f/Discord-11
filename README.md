## Discord 11

### [Version 2.2.2!!!](https://github.com/zuzumi-f/Discord-11/releases)

A theme based in windows 11 new UI

Theme by [zuzumi](https://github.com/zuzumi-f)

* [Requirements](#requirements)
* [Preview](#preview)
* [Message Style (Not working)](#message-style)
    * [Default Style](#left-message-bubble)
    * [Right (No Autor)](#default-message-bubble)
    * [Right (Autor)](#new-message-bubble)
* [Customization](#customization)
* [Compatibility](#compatibility)
    * [Compatibility HSL](#horizontalserverlist)
    * [Compatibility DSC](#displayserversaschannels)
* [Addons](#addons)

## Preview

### Dark Mode
![image](https://user-images.githubusercontent.com/79029257/192063455-1880f1c3-435a-4836-b952-23ac73637cc9.png)
![image](https://user-images.githubusercontent.com/79029257/192063481-44bb679c-0db9-4a5f-9461-136f22c0ebec.png)

### Light Mode + Glass Effect
![image](https://user-images.githubusercontent.com/79029257/192063611-3f965167-715a-4c5d-8d03-ae7789feb8ba.png)
![image](https://user-images.githubusercontent.com/79029257/192063652-83518755-beb8-4527-a1ef-51b0ab3a2e7a.png)

## Message Style

(Messages in RightSide are not working at the moment sorry)

### Left Message bubble
![image](https://user-images.githubusercontent.com/79029257/183246736-7c229bb6-c064-4870-a6eb-744d4bd8d951.png)

### Default Message bubble
![image](https://user-images.githubusercontent.com/79029257/183246763-c3824133-3e38-4ec1-a7a2-ae415670eff7.png)

### New Message bubble

(Not work with Compact Mode)

![image](https://user-images.githubusercontent.com/79029257/183246798-c534587b-37f6-403e-9547-fb46dced9f25.png)

## Customization

For better customization please use [ThemeSettings](https://betterdiscord.app/plugin/ThemeSettings)

![image](https://user-images.githubusercontent.com/79029257/183246831-7820dbef-89a6-439e-a640-56d50a9e3019.png)

## Addons
* Discolored by **[Nyri4](https://github.com/NYRI4/Discolored)**

* Fluent Icons by **[Stickfab](https://github.com/stickfab/pc-fluenticons)**

* Emoji Replace by **[DevilBro](https://github.com/mwittrien/BetterDiscordAddons/blob/master/Themes/EmojiReplace/EmojiReplace.theme.css)**

* FriendGrid by **[CorellanStoma](https://github.com/CreArts-Community/Friends-Grid)**

* BearableInbox by **[Disease](https://github.com/maenDisease/BetterDiscordStuff/blob/main/css/bearableInbox.css)**

## Requirements
* [ThemeSettings](https://betterdiscord.app/plugin/ThemeSettings)

## Compatibility

Copy and paste the code at the bottom of the file

![image](https://user-images.githubusercontent.com/79029257/185492619-98009f68-31c4-4a59-a8dc-e515d22b4363.png)

### HorizontalServerList

```css

#app-mount .standardSidebarView-E9Pc3j {
    border-radius: 0;
    border-left: none;
    width: 100%;
    left: 0;
    height: calc(100% - 60px);
    top: unset;
    bottom: 0;
}
```

### DisplayServersAsChannels

```css

:root {
    --server-display-as-channels-width: 240px;
}
.styledGuildsAsChannels-DNHtg_ .wrapper-1_HaEi .scroller-3X7KbA::before {
    width: var(--server-display-as-channels-width) !important;
}
.standardSidebarView-E9Pc3j {
    left: var(--server-display-as-channels-width) !important;
    width: calc(100% - var(--server-display-as-channels-width)) !important;
}
.styledGuildsAsChannels-DNHtg_ .wrapper-1_HaEi .wrapper-38slSD {
    margin-right: 8px;
}
```
