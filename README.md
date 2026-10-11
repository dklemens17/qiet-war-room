# QIET War Room

Copper Conquest planner for alliance **[QIET]** (Last War, Evernight Isle).

Live site: https://dklemens17.github.io/qiet-war-room/

- **War Room** – next round at a glance: our group, defense outlook, best declaration, tank check
- **Alliances** – every alliance's attack and defense record, and the ranks of the alliances they beat
- **Declare** – win chances and expected copper for each target, likely attackers, group plans
- **Warzone** – best target or defense outlook for every alliance from one warzone (default #1600), with split-the-targets plans where they share a group
- **Final Rankings** – simulates the rest of the season to project every alliance's final copper rank, its chance of each season reward tier, and which faction wins the faction reward
- **Tanking & 2v2** – lose-on-purpose scenarios, value of each rank band, solo vs paired declarations
- **Data** – battle record, rankings, assumptions

The EN / PT button in the header switches the whole interface between English and Brazilian Portuguese; each viewer's choice is remembered.

## Updating

All shared data lives in `data.json`. Replace it to update the site (GitHub Pages republishes in a minute or two).
The "Copy JSON" button on the Data tab produces a file in exactly this format.

Edits made on the website itself (adding battles, locking declarations, changing settings) are saved in that
viewer's browser only, until someone updates `data.json`.
