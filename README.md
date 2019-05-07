# ![LOGO](logo.png) NHL v3 Projections **flow**ground Connector

## Description

A generated **flow**ground connector for the NHL v3 Projections API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/nhl-v3-projections/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:38+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### DFS Slates by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-DEC-01</code>, <code>2018-FEB-15</code>.

### Projected Player Game Stats by Date (w/ Injuries, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
 <br>Examples: <code>2018-JAN-31</code>, <code>2017-OCT-01</code>.
 

### Projected Player Game Stats by Player (w/ Injuries, DFS Salaries)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
 <br>Examples: <code>2018-JAN-31</code>, <code>2017-OCT-01</code>.
 
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>30000378</code>.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-nhl-v-3-projections-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
