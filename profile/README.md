:hotel: :hospital: :bank: :house_with_garden: :convenience_store: :post_office: :factory:

<!--
see : https://gist.github.com/rxaviers/7360908
**Here are some ideas to get you started:**
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

open building management is about data management solutions for buildings and houses

a solution is emoncms, a timeseries which is like influxdb and which exposes an HTTP API. You can use the **emoncms standalone docker** which can also acts as a home assistant addon. It is surely the easiest way to start with emoncms. In a few seconds, you will have all the tools available without the need to go into the configuration details.

See :
- [emoncms-docker](https://emoncms-docker.github.io) for an introduction
- [advanced tips and use cases](https://github.com/Open-Building-Management/emoncms/discussions)

I've also crafted a minimal [emontx sniffer addon](https://github.com/Open-Building-Management/emontx_sniffer) for home assistant which I originally thought to be used in combination with the emoncms addon.

It can act as a standalone tool, storing datas in the home assistant database only. see https://github.com/Open-Building-Management/emontx_sniffer/issues/1

I am also discovering grafana...
