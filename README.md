<h1 align="center">Formula 1 - Dwains Dashboard Add-on (more_page)</h1>

<p align="center">
  <a href="https://dwainscheeren.github.io/dwains-lovelace-dashboard/">
    <img src="https://img.shields.io/badge/Dwains%20Dashboard-Default-299ec2.svg" />
  </a>
  <a href="https://github.com/LRvdLinden/LRvdLinden/f1_dd_addon">
    <img src="https://img.shields.io/github/v/release/LRvdLinden/f1_dd_addon" />
  </a>
      <a href="https://github.com/LRvdLinden/f1_dd_addon/commits">
    <img src="https://img.shields.io/github/last-commit/LRvdLinden/f1_dd_addon.svg?style=plasticr" />
  </a>
    <a href="https://github.com/LRvdLinden/">
    <img src="https://img.shields.io/github/followers/LRvdLinden?style=social" />
    </a>
    <a href="https://discord.gg/7yt64uX">
    <img src="https://img.shields.io/discord/688401603811999885" />
</a>
</p>

<p align="center">Formula 1 scheduls, driver standings and more.</p>

<p align="center">Created by <a href="https://github.com/LRvdLinden">Léon van der Linden</a>
</p> 


![simple-ipad-pro-mockup-23619 (15)](https://user-images.githubusercontent.com/77990847/118716342-00b38d80-b825-11eb-9cac-6075115a547e.png)



## Prerequisite
---
- Make sure you have the [Google Calendar Event](https://www.home-assistant.io/integrations/calendar.google/) integration
```yaml
     # Example configuration.yaml entry
     google:
       client_id: YOUR_CLIENT_ID
       client_secret: YOUR_CLIENT_SECRET
```
- Subscribe to [the official Formula1 calendar](https://calendar.google.com/calendar/r?cid=http://www.formula1.com/calendar/Formula_1_Official_Calendar.ics) and the [Track Image calendar](https://calendar.google.com/calendar/ical/vj31lmvf0g2inn2r5494imm3dc%40group.calendar.google.com/public/basic.ics) to your [Google Calendar](https://marksie1988.github.io/atomic-calendar-revive/options/main-options.html) and sync the calendar with Home Assistant
- Make sure you have installed [atomic-calendar-revive](https://marksie1988.github.io/atomic-calendar-revive/options/main-options.html). This can be done manually or directly via hacs.


## Create sensors 🔧
---
- Copy and place the `f1.yaml`file from the folder `sensor` in to your `/config/sensor` directory or `configuration.yaml`
- Reboot Home Assistant


## Installation Add-on ⚙️
---
- Copy the `formula1` folder in to the `dwains-dashboard/addons/more_page` directory.
- Open your `more_page.yaml` file in `dwains-dashboard/configs` and add the following;
 ```yaml
     - name: F1
       main_menu: 'true' #Show this addon in the main navigation bar!
       icon: mdi:keyboard-f1
       path: 'dwains-dashboard/addons/more_page/formula1/page.yaml'
```
- Reload the theme configuration via Theme Settings


## Configuration ⚙️
---
`atomic-calendar-revive` is highly customizable. See Github [atomic-calendar-revive](https://marksie1988.github.io/atomic-calendar-revive/options/main-options.html) for all the options

## Result
---
![mockup-of-two-iphones-12-pro-max-with-a-plain-background-5014-el1 (1)](https://user-images.githubusercontent.com/77990847/118715870-6fdcb200-b824-11eb-8adb-fe7755e16f04.png)
![mockup-of-two-iphones-12-pro-max-with-a-plain-background-5014-el1 kopie](https://user-images.githubusercontent.com/77990847/118715872-723f0c00-b824-11eb-8e1c-a5bc75639339.png)
![mockup-of-two-iphones-12-pro-max-with-a-plain-background-5014-el1 (2)](https://user-images.githubusercontent.com/77990847/118715848-68b5a400-b824-11eb-8542-fbe7389f8e22.png)

![simple-ipad-pro-mockup-23619](https://user-images.githubusercontent.com/77990847/118716338-ff826080-b824-11eb-962e-c68c619d0177.png)
![simple-ipad-pro-mockup-23619 (1)](https://user-images.githubusercontent.com/77990847/118716342-00b38d80-b825-11eb-9cac-6075115a547e.png)





---
Enjoy my card? Help me out for a couple of :beers: or a :coffee:!

[![coffee](https://www.buymeacoffee.com/assets/img/custom_images/black_img.png)](https://www.buymeacoffee.com/LRvdLinden)
