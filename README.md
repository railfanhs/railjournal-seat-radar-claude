# RailJournal Seat Radar for Claude

Claude plugin that finds Indian Railways trains with a seat between two stations, using the [RailJournal](https://railjournal.in/find-seats.php) MCP server (`https://railjournal.in/chatgpt/mcp.php`, no authentication). It does not book tickets.

## Install

```
/plugin marketplace add <owner>/<repo>
/plugin install railjournal-seat-radar@railjournal
```

Then run `/mcp` to confirm `railjournal-seat-radar` is connected, and try: "Find a 3A seat from NDLS to MMCT tomorrow."

## Notes

- A scan checks at most 8 trains because the server allows six uncached calls per minute.
- Availability changes quickly; confirm on IRCTC or the Indian Railways app.

Privacy: https://railjournal.in/chatgpt/privacy.html · Terms: https://railjournal.in/terms.php · Support: railjournalindia@gmail.com
