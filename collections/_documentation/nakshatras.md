---
layout: post
date: 2024-07-16 12:00:00 +1000
modified: 2024-07-16 12:00:00 +1000
order: 1
title: The Nakshatras (lunar mansions)
description: Track the nakshatras (lunar mansions) of the Moon and other planets of astrological chart using a Home Screen widget and an app extension.
comments: true
# Extra info for structured data
schema:
  images:
    alt: Moon phase and cycle widget
  image:
    url: /images/og/og-time-nomad-doc-nakshatra-widget.jpg
    width: 1200
    height: 630    
  image_1x1:
    url: /images/schema/time-nomad-docs-nakshatra-widget-1x1.jpg
    width: 760
    height: 760
---

The nakshatras (or lunar mansions) are 27 divisions of the sidereal Zodiac. Each mansion (or nakshatra) corresponds to a particular asterism — prominent group of stars.

As the Moon travels across the Zodiac it picks up energies of prominent groups of stars (the nakshatras) and that in turn influences qualities of current time segment.

The Nakshatras tool is comprised of several components:

* a **Home Screen widget** tracking current Moon nakshatra in real time
* a **Dashboard** component with detailed information about current Moon nakshatra
* a **Chart Details** component that accompanies every chart and lists all nakshatras and planets within them
* a **Numeric Chart Details** popup entry for current Moon nakshatra

## Moon Nakshatra widget

The Home Screen widget tracks the Moon‘s current nakshatra.

<div class="container post-pullout-box">
  <div class="row">
    <div class="col-6">
      <div class="row">
		<img loading="lazy" src="/images/docs/nakshatra-widgets-01.png" srcset="/images/docs/nakshatra-widgets-01.png 1x, /images/docs/nakshatra-widgets-01@2x.png 2x" alt="Current Moon nakshatra widgets for the Home Screen.">
      </div>
    </div>
    <div class="col-6">
      <div class="row text-photo-caption-serif">
		The widget comes in two sizes.
      </div>
    </div>
  </div>
</div>
<div class="float-clear"></div>

Both widget sizes show current nakshatra, one of its visual symbols and its ruling planet. The countdown is decreasing towards the Moon‘s crossing into the next nakshatra.

The medium size widget offers additional details such as:

* Short description
* Current asterism of the Moon: stars of constellation(s)
* Tropical and/or sidereal zodiac boundaries of the nakshatra. Sidereal boundaries are marked with ✦ (star symbol)

The widget can be configured (to certain extent) by long-tapping and selecting “Edit Widget”.

As with any widgets, more than one instance of the widget can be added to any Home Screen.

# On the Dashboard

The **Lunar Mansion (Nakshatras)** Dashboard component displays the Moon’s progress through the nakshatras.

<img loading="lazy" src="/images/docs/nakshatra-dashboard-01.jpg" srcset="/images/docs/nakshatra-dashboard-01.jpg 1x, /images/docs/nakshatra-dashboard-01@2x.jpg 2x" alt="The nakshatra lunar mansion component for the Dashboard.">

The component displays current nakshatra, its number and pada (quarter). The dates and duration describe the timing of nakshatra.

Tap on the component to get a brief description of the nakshatra and a detailed listing of all events of the timeline.

Long-tap on the component (or tap and then tap on “Chart”) to bring up the **Chart Event Explorer** add-on that allows to quickly preview charts that correspond to the nakshatra start and end dates.

## In Charts Details

The nakshatra information is displayed in “Chart for Now” and “Natal Chart” reports as well as corresponding “Chart Details”.

<img loading="lazy" src="/images/docs/nakshatra-chart-details-01.jpg" srcset="/images/docs/nakshatra-chart-details-01.jpg 1x, /images/docs/nakshatra-chart-details-01@2x.jpg 2x" alt="The nakshatra lunar mansion component in the Chart Details report.">

The details report can also be invoked as a popup by tapping on the chart.

Long-tap on the component (or tap and then tap on “Chart”) to bring up the **Chart Event Explorer** add-on that allows to quickly preview charts that correspond to the nakshatra start and end dates.


The drop down menu of the **Chart Event Explorer** allows to quickly jump to the moment when the planet crosses nakshatra cusps.

## Numeric Chart Details

Tapping on the date at the top of pretty much every screen brings up the **Numeric Chart Details** popup that contains current Moon nakshatra for that date within the “Summary” category.

<img loading="lazy" src="/images/docs/nakshatra-numeric-chart-details-01.jpg" srcset="/images/docs/nakshatra-numeric-chart-details-01.jpg 1x, /images/docs/nakshatra-numeric-chart-details-01@2x.jpg 2x" alt="Current Moon nakshatra listing in the Chart Numeric Details report.">

The “Summary” section includes current Moon nakshatra.
