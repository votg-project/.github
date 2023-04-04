**VoTG** - Voice over Telegram

**Work-in-progress** project (in very early stages) to leverage [VoWiFi](https://en.wikipedia.org/wiki/Voice_over_WLAN) to make cellular call and SMS (via your own SIM card) accessible via Telegram - anywhere in the world, no GSM coverage needed - only a gateway (e.g. Raspberry Pi) with a smart card reader with SIM card in it and Internet access.

Current architecture: _(subject to change at any time)_
1. SIM card connector (closed-source PoC available), which handles all communications with a SIM.
2. Slightly modified [StrongSwan](https://github.com/votg-project/strongswan) to connect to mobile operator's ePDG.
3. TBD

I did succesfully established a tunnel with a ePDG server of MTS (Russia) back in Summer 2020 and in November 2022, but currently did not made progress any further. Also, at this time I am unable to establish tunnel with some other domestic major mobile operators which I had SIM cards of.

**Unfortunately, the development pacing is very slow due to author's lack of knowledge, and very little easy-to-follow information availability on the internet.** The development of this project is the only learning opportunity for me regarding EPC and IMS internals. If you want to help - please, contact me!

In development by [leenr](https://github.com/leenr).
