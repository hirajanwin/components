# Muil Components

Easily develop emails with email-ready components.

Read More [Muil Docs - Components.](https://docs.muil.io/docs/components/intro/)

## Installation

`npm install @muil/components`

or

`yarn add @muil/components`

## Components

-  [Charts](https://docs.muil.io/docs/components/charts)
-  [Style](https://docs.muil.io/docs/components/style)
-  [Alignment](https://docs.muil.io/docs/components/alignment)
-  [Button](https://docs.muil.io/docs/components/button)
-  [Callout](https://docs.muil.io/docs/components/callout)
-  [Grid](https://docs.muil.io/docs/components/grid)
-  [Menu](https://docs.muil.io/docs/components/menu)
-  [Spacer](https://docs.muil.io/docs/components/spacer)
-  [Wrapper](https://docs.muil.io/docs/components/wrapper)
-  [Typography](https://docs.muil.io/docs/components/typography)

## Basic Example

```jsx
import { StyleProvider, Button } from "@muil/components";

<StyleProvider>
  <Button href="#">Button</Button>
  <Button href="#" tiny>Tiny Button</Button>
  <Button href="#" small>Small Button</Button>
  <Button href="#">Default Button</Button>
  <Button href="#" large>Large Button</Button>
</StyleProvider>;
```

![Buttons](media/buttons.png)

## More Components

![Bar Chart](media/bar-chart.png)
![Multiple Bar Chart](media/multiple-bar-chart.png)
![Multiple Bar Chart](media/multiple-hor-bar-chart.png)
![Calendar](media/calendar.png)
![Heat map](media/heat-map.png)
