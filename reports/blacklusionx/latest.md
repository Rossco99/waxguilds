![Blacklusion Logo](https://blacklusion.com/resources/blacklusion_logo_192.png)

### <ins>General</ins>

|  |                                         |
| --- |-----------------------------------------|
| Website | https://blacklusion.io                  |
| Contact | hello@blacklusion.com                   |
| bp.json (mainnet) | https://blacklusion.io/wax.json         |
| bp.json (testnet) | https://blacklusion.io/wax-testnet.json |
| producer (mainnet) | blacklusionx                            |
| producer (testnet) | blacklusionx                            |
| Guild Jurisdiction | Munich, Germany                         |

### <ins>Noteworthy</ins>

Check the contributions section

### <ins>API Services</ins>
We updated our server infrastructure and the api versions

| History (partial) | History (full) | History (testnet) | AA API | Light-API | IPFS      |
|-------------------|--------|-------------------|-------|-----------|-----------|
| [ ]               | [ ] | [x]               | [x] | [ ]       | [x]       |
| -                 | - | not tracked       | 1.5mio req | -         | not tracked |


### <ins>Contributions</ins>

### Validationcore

**URLs**: https://validationcore.io

**List of SCs**: -

**Update**: 
- We have pruned the validationcore database to contain data only back to 2023-01-01. This has reduced the database size by 50% and increased the query speed. This also improves other aspects such as the time machine and the filters are easier to use and specify with the smaller available range.
- We have deployed changes to the accepted server versions as discussed in the telegram chat. This ensures our lists of apis are up-to-date. Old api versions were deprecated and removed.


**Metrics**

Period: -

Stats: Not tracked, but it is save to say the validationcore is an essential part of the OIG evaluations itself :)

---

### illusive GG

**URLs**: https://illusive.gg

**List of SCs**: illusiveauth

**Update**:
- We have quietly pushed our Token pages into production as a beta feature. Users can now track token prices via the overview page and look at historical data on the detail page https://www.illusive.gg/tokens/. Currently, this only supports tokens listed on coingecko. We are planning to expand this to wax-based tokens as well, but testing the overall functionality with the current live version
- We have published our community pages that were part of the gHubs grant. Users can now see all games that integrate the same NFT collection and see the aggregated player stats: e.g. https://www.illusive.gg/communities/alien-worlds/ For Battlefleet Armageddon we are also testing to inject web2 stats from the Unity Cloud 
- We have listed 3 new games on illusive this month: Avalon, Mission Control, and Battlefleet Armageddon
- On our rankings page we have fixed a bug, that caused the percentage changes to not show. We also have changed the behavior of the ranking table to behave better responsive performance: https://www.illusive.gg/rankings/
- We have ported over 100 pieces of existing content to illusive: https://www.illusive.gg/feed/
- We have launched our AI search: The ported content is used to inject custom context into a chatGPT-based AI search via a Vectorstore. Users can now ask questions about the games and the AI will try to answer with parts from the content. You can try it yourself by clicking on the searchbar. Keep in mind, that currently Alien Worlds has the most content and hence responses will be most accurate
- We have added a couple of improvements to the Content Creator and Content Viewer: Design Changes, Responsive improvements, added a sidebar showing an overview of all sections of the content and how far the user has already read the content

**Metrics**

Period: 15. March 2024 - 15 April 2024

Stats: 127 unique users, 3 new games

---

### OneApi

**URLs**: https://wax.oneapi.dev/v1/chain/get_info

**List of SCs**: -

**Update**:
- Upkeep

**Metrics**


Period: 15. March 2024 - 15 April 2024

Stats: 41.35k unique visitors | 5.64M total requests (based on cloudflare stats)

---

### Prometheus Exporter

**URLs**: https://github.com/Blacklusion/eosio-prometheus-exporter

**List of SCs**: -

**Update**: -

**Metrics**

Period: -

Stats: Other guilds are using our exporters. We do not have exact numbers, since it is an open-source repo and not a hosted service

---

### Blacklusion Pager
**URLs**: https://t.me/WaxPagerBot

**Update**: Operational

**Metrics**

Period: 15. March 2024 - 11 April 2024

Stats: 8 subscribers. The number by itself, does not sound impressive, but keep in mind that this tool is targeted towards guild operators. Taking this into account, a decent percentage of all guilds use the bot to monitor their infrastructure.


---


### <ins>Marketing</ins>

none

### <ins>Backups </ins>
URL: -

| Snapshot | Blocks Log | State History | Elastic Search | AA API |
|----------|------------|---------------|--------|--------|
| [ ]      | [ ]        | [ ]           | [ ] | [ ] |


### <ins>Feedback to OIG</ins>

There are a lot of calls happening recently and the timelines for the periods are sometimes tricky to find. Make a calendar we can subscribe to ✨ 

----

