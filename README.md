# Discord 11

### [Version 3 is out!](https://github.com/zuzumi-f/Discord-11/blob/main/Discord11.theme.css)

A theme based on Windows 11's UI - by [zuzumi](https://github.com/zuzumi-f)

- [Discord 11](#discord-11)
    - [Windows 11 UI](#design)
    - [Install](#install)
        - Third party Discord clients
        - UserStyle (Stylus, Stylish etc.)
    - [Screenshots](#screenshots)
        - [Dark mode](#dark-mode-details)
        - [Light mode + glass effect](#light-mode-glass-details)
        - [Message styles](#message-styles)
            - [Left message bubble](#left-message-bubble)
            - [Default message bubble](#default-message-bubble)
            - [New message bubble](#new-message-bubble)
    - [Customization](#customization)
        - [Third party Discord clients](#customization-third-party)
        - [UserStyle (Stylus)](#customization-userstyle-stylus)
    - [Used Addons](#used-addons)

## Design

You can find all the values of Windows 11's UI [here](https://www.figma.com/community/file/1159947337437047524)

[![image](https://user-images.githubusercontent.com/79029257/198903356-9c6463b9-dc84-420e-a932-98f647408000.png)](https://www.figma.com/community/file/1159947337437047524)

## Install

### Third party Discord clients

- BandagedBD
    - Install from https://betterdiscord.app/theme/Discord%2011
- Goosemod, Powercord, Replugged
    - Go to Settings > Plugins > Custom CSS
    - Copy [Discord11.theme.css](Discord11.theme.css) contents and paste into the input box

### UserStyle (Stylus, Stylish etc.)

- Open https://github.com/zuzumi-f/Discord-11/raw/main/Discord11.user.css
- Customize for your needs and click install
> Note: You need to enable CSP patching from your extension's settings, and make sure you don't have anohter extension that patches CSP. Otherwise theme won't work.

## Screenshots

<details id="dark-mode-details">
    <summary>Dark mode</summary>

![Dark mode screenshot](https://github.com/zuzumi-f/Discord-11/assets/79029257/5a00561f-db3a-4614-a7eb-1a90ab200035)
![Dark mode screenshot 2](https://github.com/zuzumi-f/Discord-11/assets/79029257/64cd1323-c353-4e0a-b74f-34de8895a501)

</details>

<details id="light-mode-glass-details">
    <summary>Light mode + glass effect</summary>

![Light mode + glass effect screenshot](https://user-images.githubusercontent.com/79029257/197858375-bf1e7ff4-f586-43ca-8c96-187660c4c7af.png)
![Light mode + glass effect screenshot 2](https://user-images.githubusercontent.com/79029257/197858393-2fe8acfb-86ca-456d-a53e-5af5a80de481.png)
</details>

### Message styles

> Note: Self Messages in Right side are not working at the moment

<details id="left-message-bubble">
    <summary>Left message buble</summary>

![Left message bubble style](https://user-images.githubusercontent.com/79029257/183246736-7c229bb6-c064-4870-a6eb-744d4bd8d951.png)

</details>

<details id="default-message-bubble">
    <summary>Default message bubble</summary>

![Default message buble style](https://user-images.githubusercontent.com/79029257/183246763-c3824133-3e38-4ec1-a7a2-ae415670eff7.png)
</details>

<details id="new-message-bubble">
    <summary>New message bubble</summary>

> Note: Doesn't work with compact mode

![New message bubble style](https://user-images.githubusercontent.com/79029257/183246798-c534587b-37f6-403e-9547-fb46dced9f25.png)
</details>

## Customization

<details id="customization-third-party">
    <summary>Third party Discord clients</summary>

![Customize theme step 1](https://user-images.githubusercontent.com/79029257/196771736-bf0421c8-1d16-490e-8003-6c04086224e9.png)
![Customize theme step 2](https://user-images.githubusercontent.com/79029257/196772831-6f14281e-2731-47ee-b02e-90eef7e656e1.png)

You can write any other code at the bottom of the file

![Customize theme step 3](https://user-images.githubusercontent.com/79029257/185492619-98009f68-31c4-4a59-a8dc-e515d22b4363.png)
</details>

<details id="customization-userstyle-stylus">
    <summary>UserStyle (Stylus)</summary>

![Customize theme step 1](https://i.imgur.com/G88mLLd.png)
</details>

## Compatibility

### [Horizontial Server List](https://betterdiscord.app/theme/Horizontal%20Server%20List)

You need to add the following CSS to the theme's CSS for it to work. [Check here for how customize the CSS](#customization).

```css
/* HSL on Top */
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


## Used Addons

- Fluent Icons by **[Stickfab](https://github.com/stickfab/pc-fluenticons)**

- Emoji Replace by **[DevilBro](https://github.com/mwittrien/BetterDiscordAddons/blob/master/Themes/EmojiReplace/EmojiReplace.theme.css)**

- FriendsGrid by **[CorellanStoma](https://github.com/CreArts-Community/Friends-Grid)**

- BearableInbox by **[Disease](https://github.com/maenDisease/BetterDiscordStuff/blob/main/css/bearableInbox.css)**
