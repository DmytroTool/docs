# Events

To trigger [Events](https://github.com/blynkkk/blynkkk.github.io/tree/1b828d2e6ad5add190596bc1bfad64e2d6aa0832/en/product/product-template-settings/events/README.md) creation from hardware \(or other sources\) and render them on Timeline in Device profile pages on the web and in the mobile apps, use this API call:

```text
/external/api/logEvent?token={token}&code={event_name}
```

`event_name` should be taken from [Product Template Settings](https://github.com/blynkkk/blynkkk.github.io/tree/1b828d2e6ad5add190596bc1bfad64e2d6aa0832/en/product/product-template-settings/README.md) &gt; [Events](https://github.com/blynkkk/blynkkk.github.io/tree/1b828d2e6ad5add190596bc1bfad64e2d6aa0832/en/product/product-template-settings/events/README.md)

\*\*\*\*

**Options:**

To render custom description of the event on the Timeline, use `event_description` parameter

`/external/api/logEvent?token={token}&code={event_name}&description={event_desciption}`

&gt;&gt;IMAGE OF TIMELINE WITH EVENT DESCRIPTION \(MOBILE AND WEB\)

