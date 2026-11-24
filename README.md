# msukdev.github.io

<https://msukdev.github.io/>

## Events

Edit [events.json](events.json) to update the event listings. Entries follow
[events.schema.json](events.schema.json). Use `"type": "online-lab"` for events
displayed in the **On-line Labs** section, after **Virtual events**.

Each entry must include its calendar `year` (for example, `"year": 2026`),
`month` and `day`. The year is used only for filtering and is not displayed.
The page checks today's date in the UK (`Europe/London`)
when it loads and hides events whose dates have passed. Events for today
remain visible all day. Multi-day entries such as `"day": "25<br />26"`
remain visible through the last listed day; all days must be within the
same month and year. Past entries can stay in the JSON file.
