[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://stand-with-ukraine.pp.ua)

:hotel: :hospital: :bank: :house_with_garden: :convenience_store: :post_office: :factory: :hotel: :hotel: :hotel: :hospital: :hotel: :bank: :house_with_garden: :convenience_store: :convenience_store: :post_office: :factory: :house_with_garden: :house_with_garden: :hotel: :house_with_garden: :house_with_garden: :house_with_garden: :house_with_garden: :house_with_garden: :factory: :factory: :factory: :factory: :factory: 

<!--
see : https://gist.github.com/rxaviers/7360908
**Here are some ideas to get you started:**
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

open building management is about **long term** data management solutions for buildings and houses

a SIMPLE solution is emoncms, a timeseries which is like influxdb and which exposes an HTTP API. You can use the **emoncms standalone docker** which can also acts as a home assistant addon. It is surely the easiest way to start with emoncms. In a few seconds, you will have all the tools available without the need to go into the configuration details.

See :
- [emoncms-docker](https://emoncms-docker.github.io) for an introduction
- [advanced tips and use cases](https://github.com/Open-Building-Management/emoncms/discussions)

The minimal [emontx sniffer addon](https://github.com/Open-Building-Management/emontx_sniffer) for home assistant was originally thought to be used in combination with the emoncms addon. Anyway, it can store directly datas in the home assistant database. see https://github.com/Open-Building-Management/emontx_sniffer/issues/1

[EnergyGym](https://github.com/Open-Building-Management/EnergyGym) is an experience using reinforcement learning to create an energy building model
