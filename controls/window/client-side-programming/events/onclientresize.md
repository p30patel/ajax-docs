---
title: OnClientResize
page_title: OnClientResize | UI for ASP.NET AJAX Documentation
description: OnClientResize
slug: window/client-side-programming/events/onclientresize
tags: onclientresize
published: True
position: 11
---

# OnClientResize



## 

The __OnClientResize__ event of the __RadWindow__ fires while the user is resizing the popup.

The event handler receives the following arguments:

1. The [RadWindow]({%slug window/client-side-programming/radwindow-object%}) object that fired the event.

1. An event arguments object that does not expose any methods and properties.

You can use this event to get the current dimensions of the dialog by calling the `getWindowBounds()` methodfrom the [RadWindow client-side API]({%slug window/client-side-programming/radwindow-object%}).

# See Also

 * [Overview]({%slug window/client-side-programming/events/overview%})

 * [RadWindow Object]({%slug window/client-side-programming/radwindow-object%})