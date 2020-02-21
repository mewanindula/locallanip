# What is this?

Get client's local LAN IPv4 IP Address

# Installation

`npm i locallanip --save`

Then...

```
import {locallanip} from 'locallanip'

locallanip((ip) => {
    console.log("My Local LAN IPv4 IP Address : " + ip);
});

```

# Special Thanks

Mr. Suranga Upul