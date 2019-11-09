# Where are the fireworks?

In Australia the sale and use of fireworks are heavily restricted. From what I've seen it costs thousands of
dollars and requires criminal checks to become a licensed pyrotechnician - something out of reach of not only
the lazy and infirm, but just about everybody else too.

Anyway, I've got kids and and therefore a need to know where and when public fireworks will be on. Luckily
the Queensland Government publish event data via a REST interface - hence this project. As you can see, it's
easier to <a href="https://wherearethefireworks.com">consume the information via Google Maps</a> rather than
<a href="https://www.dnrm.qld.gov.au/qld/emergency/safety/explosive-fireworks/upcoming-fireworks-display-dates">
tabular form on the Goverment website</a>.

## Roadmap

* Cache firework event data in cookies (TTL ~4hrs)
* Cache Google Places data in cookies (TTL much longer)
* Filter by date, suburb, etc
* Filter by distance from your location

## Contributing

See above :kiss:

## DISCLAIMER:

I'm not a professional front-end developer and I haven't done too much work in Javascript - pls don't judge me too harshly :)
