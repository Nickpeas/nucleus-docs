---
title: Create icons
description: Creating icons guidelines.
---

## Icon principles

1. Make sure that a similar icon is not already in use.
2. Think about the icon you want to create and which category it fits in.
3. Use the icon grid to ensure consistency with existing icons.
4. Make sure icon works across different sizes.
5. Remember to create both solid and outline versions of your icon (Use solid over outline, unless icon is interactive).
6. Use a consistent stroke thickness based on sizes (Use at least 2px for stroke to avoid odd resizing issues or using fills with strokes).
7. Design clean and simple forms using our shapes.
8. Use flat shapes over 3d forms.
9. Rounded corners should make an icon feel friendly, not childish.
10. An icon should be one topic, therefore don't overlay or intersect an icon with another icon.
11. Don't add text to an icon as this will break accessibility.
12. Icons are only one colour, but they can be any of our colours. Make sure that the icons work with different colours.

## The icon grid

We use a grid for icon creation to give consistency across our icons. You should also be considering where your paths sit, to be as close to pixel perfect as possible. Here are examples of the grid and basic shapes to show it's usage:

| Grid | Grid - Vertical | Grid - Horizontal | Grid - Circle |
| :--- | :--- | :--- | :--- |
| ![Grid for creating icons](https://user-images.githubusercontent.com/43471890/62045505-66bcc400-b1fd-11e9-949e-572e2dc40bf8.jpg) | ![Grid with vertical highlight for creating icons](https://user-images.githubusercontent.com/43471890/62050044-6b3aaa00-b208-11e9-8adb-3df5d4c240dd.jpg) | ![Grid with horizontal highlight for creating icons](https://user-images.githubusercontent.com/43471890/62050140-a5a44700-b208-11e9-8bf8-555ec87242a8.jpg) | ![Grid with circle highlight for creating icons](https://user-images.githubusercontent.com/43471890/62050739-c91bc180-b209-11e9-8561-134bd845fb4b.jpg) |

### Sizing

Icons are created using illustrator with a 32px x 32px art-board. This allows scaling both up and down of the icon’s size. It is important to check your icons across different sizes during creation. The Nucleus Design System scales across different screen sizes meaning elements, including the icon’s scale to retain their visual proportions. We recommend checking your icon works between 16px and 72px.


### Exporting

Once you’re icons are completed (and signed off!) they need to be made ready for development. Follow these steps to a happy developer:

1. Make sure your icon is set to black.
2. Select the icon and choose Object &gt; Expand appearance.
3. Then using the top menu select File &gt; Export &gt; Export for Screens and export the icon to .svg file type.

![Exporting icons from illustrator](https://user-images.githubusercontent.com/43471890/62050909-2283f080-b20a-11e9-8c05-fa13100c5222.jpg)


## Best practices

* When designing the icons, use only paths not shapes.
* Make sure all unnecessary attributes in the SVG document have been removed including;
   * `<title>` element.
   * Any `id=””` attributes.
   * All `data-name=””` attributes if they exist.
   * All colour information e.g. `fill="#000000"`.
   * `<style>` and any `classes`.
   * Nested and empty `<g>` (groups).
* The position of each icon within the artboard must be consistent. This is very important when creating different states of the same icon.
* Make sure the paths align to the pixel grid.
* When creating a corner, ensure it has only 2 points. Too many points per shape will overcomplicate the icon and increase file size.



