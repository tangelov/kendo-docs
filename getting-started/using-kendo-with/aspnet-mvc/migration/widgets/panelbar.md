---
title: PanelBar
slug: panelbar
publish: true
---

# Server-Side API

### Animations

#### Old

    Html.Telerik().PanelBar().Name("SamplePanelBar").Effects(effects => effects.Slide())

#### New

    Html.Kendo().PanelBar().Name("SamplePanelBar").Animation(animation => animation.Open(open => open.FadeIn(FadeDirection.Down))

# Client-Side API

## Events

### KendoUI Complete for ASP.NET MVC does not support action syntax i.e. “() => {}”

### All Widgets No Longer Have The OnLoad Event. Please Use **$(document).ready()** Instead.

#### Old

    Html.Telerik().PanelBar().Name("SamplePanelBar").ClientEvents(events => events.OnChange(“change”))

#### New

    Html.Kendo().PanelBar().Name("SamplePanelBar").Events(events => events.Change(“change”))