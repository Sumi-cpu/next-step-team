# Next Step

Sunday roster planner for the NextStep Team and Salvation Team at Christian City Church. The people directory is the existing team pool; the app is centered on placing those people on the rosters for each Sunday, not recruiting new volunteers.

## Run

Open `index.html` in a modern browser. No build or dependencies are required.

## Build the Sunday roster

The app opens to **Sunday roster** with two cards: **NextStep Team** and **Salvation Team**. The month planner shows every Sunday in the selected month—four or five, depending on the calendar. Select a Sunday to edit that week's rosters and use the clearly labeled **Team leaders for [Sunday]** section below the planner to add or remove leaders for that date. The overall team coaches list is managed separately below it. Each team has five places, and each person can be rostered on one team per Sunday. Rosters and Sunday leader names are stored separately by date in browser local storage.

Use **Event rosters → Add event** to create a separate event and date. Each event has independent **NextStep Team**, **Salvation Team**, and **Team leaders** lists, with no five-person limit. Add people from the shared directory; an individual can only be assigned to one group per event, but can serve in multiple events. Removing an event does not change Sunday rosters.

Use **All team members → Import people** to paste CSV rows in `name,email,role` format (email and role are optional), or add individual existing team members. Everyone appears in one shared team-member list. Add a team member once, then select them from either roster dropdown for each Sunday they serve.

For each rostered person, select **Send request** to share a message through the device's share sheet (such as WhatsApp or Messages). If sharing is unavailable, copy the prepared message and send it yourself. The response column tracks **Not sent**, **Awaiting reply**, **Yes**, or **No**; update it when you hear back. Replies are entered by the team leader and are saved with that person's roster for the selected Sunday.

## Salvation care

Use **Salvation care** to record a salvation decision and its follow-up status: New, Contacted, Connected, or Ongoing. Keep conversations confidential.

## Data

People, salvation follow-ups, Sunday rosters, event rosters, Sunday leader names, team coaches, and roster replies are stored in the current browser profile only. Requests are shared through your messaging app; replies are recorded by the team leader. There is no server or cross-device sync in this first pass. Use a shared backend before relying on multiple coordinators or devices.
