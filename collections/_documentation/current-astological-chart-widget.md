---
layout: post
date: 2021-08-21 12:00:00 +1000
modified: 2021-08-21 12:00:00 +1000
order: 1
title: Astrological chart widget for your Home Screen
description: The “Chart for Now” widget can be added to any screen on iPhone or iPad. The widget presents an astrological chart for the current time at your location.
comments: true
# Extra info for structured data
schema:
  images:
    alt: Astrological chart widget
  image:
    url: /images/og/og-time-nomad-doc-chart-widget.jpg
    width: 1200
    height: 630    
  image_1x1:
    url: /images/schema/time-nomad-docs-chart-widget-1x1.jpg
    width: 760
    height: 760
---

“Chart for Now” is a Home Screen widget that offers a fully configurable astrological wheel chart for current date & time. Multiple instances of the widget can be conveniently stacked or added across several screens.

<div class="container post-pullout-box">
  <div class="row">
    <div class="col-6">
      <div class="row">
		<img loading="lazy" src="/images/docs/widget-astro-chart-stack.gif" alt="Multiple astrological chart widgets stacked on the home screen">
      </div>
    </div>
    <div class="col-6">
      <div class="row text-photo-caption-serif">
      	Since the widget can be configured to show different kinds of chart data, <b>multiple instances</b> of the widget can be either <b>stacked on top of each other</b> or placed on different screens.
      </div>
    </div>
  </div>
</div>
<div class="float-clear"></div>

## How to add the widget

{% include video-youtube.html id="yu1fjUYQy84" %}

Follow these steps to add the widgets to your device home screen:

* Long tap anywhere on the screen.
* Once the icons began to shake tap on the “**+**” icon in one of top corners of the screen to bring up the widget selector.
* In the widget selector scroll down to “Time Nomad”.
* Add a widget and repeat the steps to add another widget…

<div class="container post-pullout-box">
  <div class="row">
    <div class="col-6">
      <div class="row">
		<img loading="lazy" src="/images/docs/widget-astro-chart-adding.jpg" alt="Adding astrological chart widget to home screen">
      </div>
    </div>
    <div class="col-6">
      <div class="row text-photo-caption-serif">
      	Adding the widget to your Home Screen.
      </div>
    </div>
  </div>
</div>
<div class="float-clear"></div>

Before the widgets can display useful information **they need to be configured**. When first installed, the widgets aren’t aware of your device **geographic location**. Scroll down to “How to configure the widget” section of this page that explains the process.

## Required widget configuration 

Once the widget “knows” your geographic location, it needs to know your preferred colour scheme. 

<div class="container post-pullout-box">
  <div class="row">
    <div class="col-6">
      <div class="row">
		<img loading="lazy" src="/images/docs/widget-astro-chart-color-scheme-prompt.jpg" alt="Astrological chart widget requesting color scheme selection">
      </div>
    </div>
    <div class="col-6">
      <div class="row text-photo-caption-serif">
      	The colour scheme selection is <b>required once</b> for each widget instance. <b>Long tap</b> on the widget and select the “Edit Widget” option.
      </div>
    </div>
  </div>
</div>
<div class="float-clear"></div>

The three supported colour schemes are:

* Light
* Dark
* Auto Day/Night — the widget will adjust its colour scheme at sunset & sunrise moments at your nominated geographic location.

## How often is the widget updated?

Widgets on iOS don’t update themselves in real-time, instead they are allowed to update their information at specified time intervals, that’s provided the device decides to go ahead with the widget update (each device behaves differently depending on available resources and other priorities).

Setting the update interval gives a suggestion to the device as to how often you’d like the widget to update itself. The default value is 5 minutes that seems to work quite reliably. We’ve tried 1 minute but didn’t produce reliable results. Thus the minimal update interval is 3 minutes.

**How to force the chart to update?** That’s an important question! Although rarely, widgets can get “stuck in time” as the device decides to skip their update for some reason. The workaround is simple — **tap on the widget**, the app will open and the widget will become instantly updated.

In super rare situations when any of the widgets seems to be completely stuck, **simply restart your device**. This is a proven way out of tricky situations.

## How to spot retrograde and stationary planets?

Retrograde planets have a **solid line** outside of their coordinate (or outside of the icon if coordinates aren’t shown).

Stationary planets indicated by a **two-segment line** with one segment darker and another lighter thus hinting that the planet is about to change its perceived direction and is barely moving when seen from the Earth’s point of view.

<div class="container post-pullout-box">
  <div class="row">
    <div class="col-6">
      <div class="row">
		<img loading="lazy" src="/images/docs/widget-astro-chart-retrograde-and-stationary-planets.jpg" alt="Astrological chart widget showing retrograde and stationary planets">
      </div>
    </div>
    <div class="col-6">
      <div class="row text-photo-caption-serif">
      	In this example the <b>retrograde planets</b> are: Pluto, Saturn, Jupiter and Neptune.<br>
		The chart also shows one <b>stationary planet</b>: Uranus.
      </div>
    </div>
  </div>
</div>
<div class="float-clear"></div>

## Fine tuning widget configuration

Each instance of the chart widget can be configured to show a different view of the chart. 

### Locality

Select “Local” or “World” option. The local chart will be based on your geographic location and aligned to the Ascendant. Local chart allows to easily see what planets are above and below the horizon. Since the local chart rotates following the hours of the day, it may not be an ideal chart to observe long-term astrological phenomena like aspects.

The world chart doesn’t rotate and is better suited to observe aspects and planetary positions within the Zodiac.

A good practice is to have both local and world widgets.

### Zodiac

The choice of the Zodiac type supports both Tropical and Sidereal models as well as no Zodiac ring or both Zodiac rings displayed.

### Zodiac color

The Zodiac sign sectors can be coloured based on their Element or Quadruplicity. This will also define to colour of coordinates.

### Houses

The widgets supports several most popular house systems: Placidus, Koch, Campanus, Regiomontanus, Porphyry, Equal House and Whole Sign Houses.

The houses wheel can also be turned off.

### Coordinates

The Zodiac positions of planets and chart points can be reported in degrees or degrees-minutes, for example 23º or 23º17.

The coordinates can also be turned off.

### Visible planets & points

Configures which planets and points should be displayed on the chart.

### Aspects

Having too many aspects makes the chart busy and hinders perception. A good alternative is have several widgets showing different kinds of aspects. For example, one widget with major aspects and another with minor aspects.

### Filter aspects

Suppose you only wanted to show the Moon’s aspects with certain planets. Activate the “Filter aspects” option and selects which planets’ or points’ aspects need to be drawn by the widget.

<div class="container post-pullout-box">
  <div class="row">
    <div class="col-6">
      <div class="row">
		<img loading="lazy" src="/images/docs/widget-astro-chart-aspects-of-planet.jpg" alt="Astrological chart widget showing current aspects of some planet">
      </div>
    </div>
    <div class="col-6">
      <div class="row text-photo-caption-serif">
      	This is a great tool to create <b>snapshots to share</b> on social media.<br>
      	For example, if you wanted to talk about current Uranus aspects simply hide all other planets’ aspects.
      </div>
    </div>
  </div>
</div>
<div class="float-clear"></div>


### Widget appearance 

The visual presentation of the chart is further configurable by selecting:

- The **colour of coordinates** can be set to “Color” or “Mono”. The colour corresponds to the “Zodiac Color” option previously selected.
- The **colour of the chart’s planets and points** can be set to “Color” or “Mono”.
- Setting the “Icon Size” allows to override default **sizing of the planets** with your preferred value.
- “Icons” sets the **visual weight of icons** used for planets and points. Three weights are available: Light, Regular and Bold.

### Adding chart descriptors

How to differentiate between several instances of the widget? Use _“Your text 1”_ and _“Your text 2”_ to enter short annotaions that will be displayed in the top right and bottom right corners of the widget.

<div class="container post-pullout-box">
  <div class="row">
    <div class="col-6">
      <div class="row">
		<img loading="lazy" src="/images/docs/widget-astro-chart-annotated.jpg" alt="Astrological chart widget showing aspects of minor planets">
      </div>
    </div>
    <div class="col-6">
      <div class="row text-photo-caption-serif">
      	Chart descriptors added to clarify that this chart is showing major aspects of minor planets.
      </div>
    </div>
  </div>
</div>
<div class="float-clear"></div>

## How to configure the widget – geographic location

Most chart calculations depend on the **knowledge of current geographic location**, specifically its coordinate expressed as latitude and longitude. The widget needs to obtain **user permissions** to access that information.

Widget configuration can be accessed through the **Time Nomad application**. 

<img loading="lazy" class="border-gray" src="/images/docs/widgets-configuration-menu.png" alt="Widgets configuration menu">

In the app’s right side menu tap on the **“Activate widgets”** (if present) or alternatively tap on the **“Widgets”** under the announcements menu (top right corner) as illustrated above.

<img loading="lazy" class="border-gray" src="/images/docs/widget-configuration-location.png" alt="Planetary hour widget configuration of geographic location">

The app offer two methods of obtaining current geographic location:

* automatic
* manual

**Automatic is the easiest** “set and forget” method. When user permissions are prompted, choose to allow Time Nomad access to the device geographic location by using the “When in Use” option. There will also be the second prompt on the home screen that will request similar permission for the Time Nomad widgets. Allow it as well.

And if for some reason a mistake has been made or permissions need to be adjusted, **simply go to the Settings app**, scroll down to Time Nomad and change **“Location”** permission. For a smooth widget operation recommended location setting is **“While Using the App or Widgets”**.

The **manual configuration** is great for situations when the device can’t access its current location or that is not desirable due to the user privacy concerns.

If that’s the case, set manual location by **entering its name and picking the most relevant matching result**. Note that Maps access is required for the search to work.
