---
description: Atom | Tab component.
---

import { StorybookStory } from '../../includes/storybook-story.js'
import { ComponentPlacement } from '../../includes/component-placement.js'
import { PageFooter } from '../../includes/page-footer.js'

## Introduction

> The singular tab that dictates what the area is about.

The tab is the button that can be clicked to change the content in the `ns-tabs`. It shows the user what content there is with a heading and an optional icon.

## Content guidance

Please see [ns-tabs](components/ns-tabs.md) for full content guidance.

## Best practice

| 💚 Do's | 💔 Don'ts |
| :--- | :--- |
| Always add heading text | Add an icon to one tab and not to the other tabs |
|  | Add more than 2 words to the heading |
|  | Add different types of icons (solid, outline, functional) |

### Considerations of best practice

* Only use inside `ns-tabs` as a slot of `tab`.

## Usage

<StorybookStory story="components-ns-tab--tab"></StorybookStory>

## Component placement

<ComponentPlacement component="ns-tab" parentComponents="ns-tabs"></ComponentPlacement>

## Specification

| Attribute | Type | Default | Options | Description |
| :--- | :--- | :--- | :--- | :--- |
| `icon`    | `string` |  | Please see the [documentation for ns-icon](../components/ns-icon) | Optional icon to add to the tab. |
| `selected` | `boolean` | `false` |`true`, `false`| Pre-selected tab |

| Event | Description |
| :--- | :--- |
| `tabselected` | Sends a event when tab is selected. |

| Slots | Type |
| :--- | :--- |
| `anonymous` | `textNode` |

## Feedback

* Do you have insights or concerns to share? You can raise an issue via [Github bugs](https://github.com/ConnectedHomes/nucleus/issues/new?assignees=&labels=Bug&template=a--bug-report.md&title=[bug]%20[ns-tab]).
* See all the issues already raised via [Github issues](https://github.com/connectedHomes/nucleus/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3ABug+[ns-tab]).

<PageFooter></PageFooter>
