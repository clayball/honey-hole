# Honey-Hole

The Honey-Hole project is being created for the purpose of managing data collected from
honey pots deployed throughout an organization.


## Required software

The following software is required.

- iptables
- SSH (key auth, fetch honeypot logs from honeyhole)
- PHP


## Setup

### PHP

TODO:

### IPtables

TODO:


## Honey-Hole Project Planning

What are we going to do?

- collect data from all honeypots (OSSEC reports)
- create datasets from our data
- create a report generation tool

How are we going to do it?

- very carefully
- with thoughtful execution
- using as few requirements as possible


### Data Collection

We could configure our honey pots to send data to a location in the Honey-Hole root directory.

    /opt/honey-hole/data/honey-pot-x
    /opt/honey-hole/data/honey-pot-y
    /opt/honey-hole/data/honey-pot-z

We can use a config file to set metadata for each honey pot.

