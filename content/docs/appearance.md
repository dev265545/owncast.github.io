---
title: Customizing appearance
description: "Customize the appearance of your Owncast instance."
menu:
  docs:
    parent: "guides"
---

{{<versionsupport feature="Appearance customization" version="0.1.0">}}

{{< alert icon="💡" text="TODO: Share some examples of setting appearance via CSS and the admin." >}}

## CSS Selectors

- `header`
- `footer`
- `#global-header-text` The text in the header.
- `#offline-banner` The banner that appears when the stream is offline.
- `#custom-page-content` The custom content of the page.
- `#notify-button` Button to display the notify modal.
- `#follow-button` Button to display the follow modal.
- `#followers-collection` The collection of followers.
- `#modal-container` The container for the modals.
- `#chat-container` The container for the chat.
- `.chat-message_user` A user-sent chat message.
- `.chat-message_system` A system-sent chat message.
- `.chat-message_social` A social message from the Fediverse.
- `.followers-follower` A single Follower in the followers collection.

## CSS Variables

You can override the values assigned to CSS variables manually by setting them in the CSS editor in the admin.
You can find a list of [variable names](https://owncast.online/components/?path=%2Fdocs%2Fowncast-styles-colors--default-theme) you can override.

For example, if you'd like to make all action items (links, buttons) red, button borders green, and change the body font to a `serif` font, you can set the following CSS variables as follows:

```css
:root {
  --theme-color-action: red;
  --theme-color-components-primary-button-border: green;
  --theme-text-body-font-family: serif;
}
```
