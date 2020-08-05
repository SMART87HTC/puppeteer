<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Input](./puppeteer.protocol.input.md) &gt; [DispatchKeyEventRequest](./puppeteer.protocol.input.dispatchkeyeventrequest.md) &gt; [commands](./puppeteer.protocol.input.dispatchkeyeventrequest.commands.md)

## Protocol.Input.DispatchKeyEventRequest.commands property

Editing commands to send with the key event (e.g., 'selectAll') (default: \[\]). These are related to but not equal the command names used in `document.execCommand` and NSStandardKeyBindingResponding. See https://source.chromium.org/chromium/chromium/src/+/master:third\_party/blink/renderer/core/editing/commands/editor\_command\_names.h for valid command names.

<b>Signature:</b>

```typescript
commands?: string[];
```