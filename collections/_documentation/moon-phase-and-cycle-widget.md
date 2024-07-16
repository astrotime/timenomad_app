---
layout: post
date: 2024-07-15 12:00:00 +1000
modified: 2024-07-15 12:00:00 +1000
order: 1
title: Current Moon phase and cycle widget for your Lock Screen and Home Screen
description: The “Moon Cycle” widget can be added to any screen on iPhone or iPad, including Lock Screen. The widget presents current Moon phase within its overall lunation cycle.
comments: true
# Extra info for structured data
schema:
  images:
    alt: Moon phase and cycle widget
  image:
    url: /images/og/og-time-nomad-doc-moon-cycle-widget.jpg
    width: 1200
    height: 630    
  image_1x1:
    url: /images/schema/time-nomad-docs-moon-cycle-widget-1x1.jpg
    width: 760
    height: 760
---

This Lock Screen and Home Screen family of widgets covers current lunation, Moon phase, zodiac sign and other parameters, including eclipses, transit through constellations and conjunctions with both fixed stars and planets.

<div class="container post-pullout-box">
  <div class="row">
    <div class="col-6">
      <div class="row">
        <img loading="lazy" src="/images/docs/moon-cycle-widgets-01.png" srcset="/images/docs/moon-cycle-widgets-01.png 1x, /images/docs/moon-cycle-widgets-01@2x.png 2x" alt="Moon phase and lunation cycle family of widgets for Lock Screen and Home Screen.">
      </div>
    </div>
    <div class="col-6">
      <div class="row text-photo-caption-serif">
        The widget family consists of two Lock screen widgets and several sizes of Home Screen widgets. Both dark and light schemes are supported. The widgets shown illustrate upcoming partial lunar eclipse.
      </div>
    </div>
  </div>
</div>
<div class="float-clear"></div>

## Lock Screen widgets 

The Lock Screen widgets are always visible, just tap the screen. The widgets offer the following information in a concise visual format:

* Moon phase
* Moon lunation timeline
* any solar and lunar eclipses that may take place during lunation, including eclipse types
* Moon applying and separating conjunctions with planets and points of a chart
* future and past conjunctions with planets
* Moon transit through constellations
* Moon conjunctions with fixed stars in the vicinity of the ecliptic

<img loading="lazy" src="/images/docs/moon-cycle-widget-lock-screen-01.png" srcset="/images/docs/moon-cycle-widget-lock-screen-01.png 1x, /images/docs/moon-cycle-widget-lock-screen-01@2x.png 2x" alt="Moon phase and lunation widgets for the Lock Screen.">

Lock Screen with both widgets added. Peruse [Apple online guide](https://support.apple.com/en-us/118610) on how to add widgets to the Lock Screen.

<img loading="lazy" src="/images/docs/moon-cycle-widget-lock-screen-02.png" srcset="/images/docs/moon-cycle-widget-lock-screen-02.png 1x, /images/docs/moon-cycle-widget-lock-screen-02@2x.png 2x" alt="Moon phase  widget displaying partial lunar eclipse and total solar eclipse.">

Moon phase widget displaying partial lunar eclipse and total solar eclipse.

The widget highlights current intermediary phase and shows the countdown to the next phase.

Solar and lunar eclipses are indicated by corresponding icons and a short legend. Scroll to the bottom of this guide for the full explanation of eclipses.

<img loading="lazy" src="/images/docs/moon-cycle-widget-lock-screen-03.png" srcset="/images/docs/moon-cycle-widget-lock-screen-03.png 1x, /images/docs/moon-cycle-widget-lock-screen-03@2x.png 2x" alt="Widget displaying conjunctions of the Moon with planets, fixed stars and Moon constellation transit.">

Moon phase widget displaying current planetary conjunctions, separating fixed star conjunction and current constellation traversed by the Moon.

The top row shows planets with which the Moon is currently conjuncts. Dimmed planets indicate future/past conjunctions accompanied by the day count. 

The bottom row is about constellations traversed by the Moon and fixed stars that the Moon is passing by. Constellation passages are based on visual observations, meaning how the observer perceives the segments of the night sky and their boundaries. Hence Scorpius is used as a complete visual segment and not subdivided into Ophiuchus that is barely visible to the observer. That’s an invitation to the user to spend some nights observing the constellations of the Zodiac.

## Home Screen widgets

Several sizes of widgets present different amount of visual information, the user is welcome to add the one (or several) that suit the taste and screen estate.

<img loading="lazy" src="/images/docs/moon-cycle-widgets-home-screen-01.png" srcset="/images/docs/moon-cycle-widgets-home-screen-01.png 1x, /images/docs/moon-cycle-widgets-home-screen-01@2x.png 2x" alt="Large, medium and small size Home Screen Widget displaying Moon phase along with additional parameters.">

All widgets can be configured with a long-tap followed by the “Edit widget” (or similar) menu item. Configuration offers a choice between tropical and sidereal zodiac coordinates, or both for medium and large size widgets. Sidereal zodiac coordinate is indicated by the star symbol ✦ that also is used throughout the app to indicate the sidereal zodiac model.

Solar and lunar eclipses are indicated by corresponding icons and a short legend underneath. Scroll to the bottom of this guide for the full explanation of eclipses.

<img loading="lazy" src="/images/docs/moon-cycle-widget-home-screen-01.png" srcset="/images/docs/moon-cycle-widget-home-screen-01.png 1x, /images/docs/moon-cycle-widget-home-screen-01@2x.png 2x" alt="Small size Home Screen Widget displaying Moon phase along with additional parameters.">

Small size widget packs a lot of information in a concise format.

<img loading="lazy" src="/images/docs/moon-cycle-widget-home-screen-02.png" srcset="/images/docs/moon-cycle-widget-home-screen-02.png 1x, /images/docs/moon-cycle-widget-home-screen-02@2x.png 2x" alt="Medium size Home Screen Widget displaying Moon phase along with additional parameters.">

Medium size widget.

<img loading="lazy" src="/images/docs/moon-cycle-widget-home-screen-03.png" srcset="/images/docs/moon-cycle-widget-home-screen-03.png 1x, /images/docs/moon-cycle-widget-home-screen-03@2x.png 2x" alt="Large size Home Screen Widget displaying Moon phase along with additional parameters.">

Large size widget is the most informative. Additional information includes:

* the Moon’s distance from the Earth. **Perigee** (P) is the closest while **apogee** (A) is the furthest
* the Moon’s passages over the **ascending** and **descending** lunar nodes, aka the North Node and the South Node
* the Moon’s **rise, transit and set** which may happen on the current or following day(s) in the current user geographic location

### Enabling geographic location

Moon rise, transit and set times require the knowledge of user geographic location coordinates. Detailed information on how to enable either automatic or manual geo location can be found in the [Chart Widget guide](/documentation/current-astological-chart-widget.html).

## Eclipses

Solar eclipse can only happen during New Moon when the Moon is positioned in front of the Sun. The three types of solar eclipse:

* **Partial** (P) — the Sun is partially covered by the Moon
* **Annular** (A) — the ring like eclipse when the Moon is too small to cover the whole of the Sun
* **Total** (T) — the Sun is fully obscured by the Moon

Lunar eclipse can only happen during Full Moon when the Earth is positioned between the Sun and the Moon. The three types of lunar eclipses:

* **Penumbral** (PU) — the Moon is in the weaker part of the Earth’s shadow (penumbra)
* **Partial** (P) — the Moon is partially covered by the Earth’s shadow (umbra)
* **Total** (T) — the Moon is fully within Earth’s shadow (umbra)






