## Discord 11

### [Version 2.3.0!!!](https://github.com/zuzumi-f/Discord-11/releases)

A theme based in windows 11 new UI

Theme by [zuzumi](https://github.com/zuzumi-f)

* [Preview](#preview)
* [Message Style (Not working)](#message-style)
    * [Default Style](#left-message-bubble)
    * [Right (No Autor)](#default-message-bubble)
    * [Right (Autor)](#new-message-bubble)
* [Customization](#customization)
* [Compatibility](#compatibility)
    * [Horizontal Server List](#hsl)
* [Addons](#addons)

## Preview

### Dark Mode
![Discord_nv3jrt8L82](https://user-images.githubusercontent.com/79029257/197858304-c3c77148-603b-4ed2-88b3-7821efcc1e3f.png)
![Discord_P0hhYwfz8r](https://user-images.githubusercontent.com/79029257/197858332-522f1da4-6349-4081-a471-635910cdc6c3.png)

### Light Mode + Glass Effect
![Discord_1KWD7oM0T0](https://user-images.githubusercontent.com/79029257/197858375-bf1e7ff4-f586-43ca-8c96-187660c4c7af.png)
![Discord_u7DFNFaSOp](https://user-images.githubusercontent.com/79029257/197858393-2fe8acfb-86ca-456d-a53e-5af5a80de481.png)

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

For customization follow the next steps

![image](https://user-images.githubusercontent.com/79029257/196771736-bf0421c8-1d16-490e-8003-6c04086224e9.png)

![image](https://user-images.githubusercontent.com/79029257/196772831-6f14281e-2731-47ee-b02e-90eef7e656e1.png)

You can write any other code at the bottom of the file

![image](https://user-images.githubusercontent.com/79029257/185492619-98009f68-31c4-4a59-a8dc-e515d22b4363.png)

## Compatibility

### HSL

```css

#app-mount .guilds-2JjMmN [class*=expandedFolderBackground] {
    border-radius: var(--winrad2) !important;
    left: calc(var(--server-size)/2) !important;
}
#app-mount .guilds-2JjMmN .wrapper-z5ab_q {
    height: auto !important;
    width: 0px !important;
    top: calc(-50% + 1px) !important;
    margin-left: 0px !important;
}
#app-mount .guilds-2JjMmN [class*=pill] span {
    border-radius: 1.5px !important;
}
#app-mount .listItem-3SmSlK {
    width: fit-content !important;
    margin: 0 12px 6px !important;
}
.tutorialContainer-2jwoiB + .listItem-3SmSlK {
    position: fixed !important;
}
#app-mount .base-2jDfDU {
    border-left: none;
    border-top-left-radius: 0px;
}
```

## Addons
* Discolored by **[Nyri4](https://github.com/NYRI4/Discolored)**

* Fluent Icons by **[Stickfab](https://github.com/stickfab/pc-fluenticons)**

* Emoji Replace by **[DevilBro](https://github.com/mwittrien/BetterDiscordAddons/blob/master/Themes/EmojiReplace/EmojiReplace.theme.css)**

* FriendGrid by **[CorellanStoma](https://github.com/CreArts-Community/Friends-Grid)**

* BearableInbox by **[Disease](https://github.com/maenDisease/BetterDiscordStuff/blob/main/css/bearableInbox.css)**
