---
sidebar_position: 3
title: Debugging
---

> this follows the previous part [Build your first project](../getting-started/build-first-project)

> Please make sure you're already familiar with [debugging JavaScript using Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/javascript).

Now, let's debug a hypothetical situation. For some reason, your grid is not rendering, and all you get is a strange looking white plane, like this:

📷 A strange looking white plane, Aka, the 🐞:

![getting-started-strange-plane](/img/misc/getting-started-strange-plane.png ':class=screenshot')

### Step 1

Open the DevTools Sources panel and locate the index.js file:

![getting-started-sources-panel](/img/misc/getting-started-sources-panel.png ':class=screenshot')

### Step 2

Pause the code with a breakpoint:

![getting-started-breakpoint-start](/img/misc/getting-started-breakpoint-start.png ':class=screenshot')

### Step 3

Step through the code until the end of the file:

![getting-started-breakpoint-end](/img/misc/getting-started-breakpoint-end.png ':class=screenshot')

Aha! Looks like we're so thrilled about learning the Zea Engine ways, that we accidentally left an extra line at the end. It turns out the strange looking white plane is actually a very crammed grid, with 10000 subdivisions in each direction.

### Step 4

Remove or comment the problematic line. Your grid should render again:

![getting-started-commented-line](/img/misc/getting-started-commented-line.png ':class=screenshot')

![getting-started-working-grid](/img/misc/getting-started-working-grid.png ':class=screenshot')

## Next steps

> Use the [Basic Setup Template](../../Tutorials/basic-template.md) and follow a few [Tutorials](../../Tutorials/tutorials.md).

> Learn how to [load assets](../../Tutorials/load-an-asset.md) into your Zea Engine App; when you're done with that, view the [Zea CAD](https://docs.zea.live/zea-cad/#/getting-started/get-started-with-zea-cad) docs for more advanced use cases.
