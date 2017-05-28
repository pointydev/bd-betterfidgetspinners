# BetterFidgetSpinners™
The first fidget spinner theme with photorealistic design and animation for Discord, you wont need a real fidget spinner after this!

## Previews
Dark Theme

![Dark Theme](http://i.imgur.com/nA1TIaE.gif)

Light Theme

![Light Theme](http://i.imgur.com/AvnDffh.gif)

## How to install
Please install [BetterDiscord](http://betterdiscord.net) and refer to [this guide](https://github.com/Jiiks/BetterDiscordApp/wiki/Themes#how-to-add-a-theme).

## Options
### Removing the "kill yourself" text on hover
Open up the theme file and remove this code from it ([L26-39](https://github.com/PointyDev/bd-betterfidgetspinners/blob/master/BetterFidgetSpinners.theme.css#L26-L39))
```css
.header-toolbar:hover::after {
    content: "kill yourself";
    right: 505px!important;
    background-color: #303030!important;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.2)!important;
    padding: 6px 10px;
    border-radius: 3px;
    font-size: 13px;
    z-index: 3000000;
    display: block;
    position:absolute;
    color:#fff;
    text-align: center;
}
```

> Made by [Pointy](https://github.com/PointyDev) with help from [BeardDesign](https://github.com/BeardDesign1)

> [Ebrima](https://www.microsoft.com/typography/fonts/font.aspx?FMID=2114) font made by Microsoft
