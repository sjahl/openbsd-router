# openbsd-router

This is the config for my router, which is running openbsd, and sets up my network to have almost no inbound access except for what is required to get native ipv6 working on Comcast.

This config is largely based off of the openbsd FAQ at https://www.openbsd.org/faq/pf/example1.html, with some extras added for comcast/ipv6, and my apu2d4 hardware.

Software that's actually running:

- PF
- dhcpd
- dhcp6c (not in base, required for getting ipv6 addresses from comcast)
- unbound
- rad
