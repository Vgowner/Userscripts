# [Flightradar24] Bypass timeout

Bypasses the 15-min timeout

## Debugging

If the script is broken, you can check out the [bundle.js](https://github.com/Hakorr/Userscripts/blob/main/Flightradar24/BypassTimeout/bundle.js) to figure out what to block. Search for strings like 

`exit_map()` `blackoutMapForTimeout` `ctaPromoBtn` `.session-timeout-modal .cta-group .trial` `value: '/timeout-overlay'`