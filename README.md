# Messaging Services Comparison

This is a backup of a [google drive based comparison of messaging services and communications protocols](https://docs.google.com/spreadsheets/d/1-UlA4-tslROBDS9IqHalWVztqZo7uxlCeKPQ-8uoFOU/edit#gid=0), but you know, not hosted by google on their properietary spreadsheets. This is on both [github](https://github.com/dessalines/Messaging-Services-Comparison) and [gitlab](https://gitlab.com/dessalines/Messaging-Services-Comparison)

This will be updated with new services as they come out.

| | Security | | | | | | | | | | | | Compatibility | | | | | | | | | Features | | | | | | Sustainability | | | |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | [**Active**][active] | **TLS** | **Open Client** | **Open Server** | **On Premise** | [**Anonymous**][anonymous] | **E2E Private** | **E2E Group** | [**E2E Default**][e2e_default] | [**E2E Audit**][e2e_audit] | **FIDO1 / U2F** | **Desktop Web** | **Mobile Web** | **Android** | **Apple iOS** | [**AOSP**][aosp] | **Win** | **macOS** | **Linux** | **BSD** | **Terminal** | [**MDM**][mdm] | [**Offline Messages**][offline_messages] | **File Share** | **Audio Call** | **Video Call** | [**Phoneless**][phoneless] | [**Decentralized or Federated**][decentralized] | **Open Spec** | [**IETF**][ietf] | **Introduced** |
| [Riot/Matrix](https://matrix.org/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | [✗](https://github.com/vector-im/riot-web/issues/6779) | [✓](https://www.nccgroup.trust/us/our-research/matrix-olm-cryptographic-review/) | [✗](https://github.com/vector-im/riot-web/issues/2772) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | [½](https://github.com/torhve/weechat-matrix-protocol-script/issues/124) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | [✗](https://matrix.org/docs/guides/faq.html#why-aren't-you-doing-this-through-the-ietf%3F-or-w3c%3F-or-3gpp%3F) | 2014 |
| [XMPP](https://xmpp.org/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ½ | [✓](http://conversations.im/omemo/audit.pdf) | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | 1999 |
| Email | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | 1960s |
| [NextCloud Talk](https://nextcloud.com/talk/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | 2018 |
| [Wire](https://wire.com/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | [✓](https://medium.com/@wireapp/wires-independent-security-review-61f37a1762a8) | [✗](https://github.com/wireapp/wire/issues/85) | ✓ | ✗ | ✓ | ✓ | [✗](https://github.com/wireapp/wire-android#what-is-included-in-the-open-source-client) | ✓ | ✓ | ✓ | ✓ | [½](https://github.com/wireapp/coax) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | 2014 |
| [Briar](https://briarproject.org/) | ✓ | ✓ | ✓ |  |  | ✓ | ✓ | ✓ | ✓ | [✓](https://briarproject.org/raw/BRP-01-report.pdf) |  | ✗ | ✗ | ✓ | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | 2016 |
| [Tox](https://tox.chat/) | ✓ | ✓ | ✓ |  |  | ✓ | ✓ | ✓ | ✓ | [✗](https://github.com/TokTok/c-toxcore/issues/426) |  | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ½ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | 2013 |
| [Kontalk](https://kontalk.org/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ½ | 2014 |
| [DeltaChat](https://delta.chat/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✗ | ✗ | ½ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | [½](https://github.com/deltachat/deltachat-android/blob/master/standards.md#standards-used-in-delta-chat) | 2017 |
| [Ring](https://ring.cx/) | ✓ | ✓ | ✓ |  |  | ✓ | ✓ | ✓ | ✓ | ✗ |  | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ½ | ✗ | 2016 |
| [BitMessage](https://bitmessage.org/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | [✓](https://github.com/Bitmessage/PyBMAndroidQt) | ✗ | ✗ | ✓ | [✓](https://github.com/VoluntaryLabs/Bitpost) | ✓ | ✓ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | 2014 |
| [Ricochet](https://ricochet.im/) | ✓ | ✓ | ✓ |  |  | ✓ | ✓ | ✓ | ✓ | ✗ |  | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | [✗](https://github.com/ricochet-im/ricochet/issues/405) | ✗ | ✗ | ✗ | ✓ | ✓ | [✓](https://github.com/ricochet-im/ricochet/blob/master/doc/protocol.md) | ✗ | 2016 |
| [PSYC-2](https://about.psyc.eu/PSYC2) | ✓ | ✓ | ✓ |  |  | ✓ | ✓ | ✓ | ✓ | ✗ |  | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | 2013 |
| [Status.im](http://status.im/) | ✓ | ✓ | ✓ |  |  | ✓ | ✓ | ✓ | ✓ | ✗ |  | ✗ | ✗ | [✓](https://play.google.com/store/apps/details?id=im.status.ethereum) | ✓ |   | ✗ | ✓ | ✓ | ✗ |   |   | ½ |   |   |   | ✓ | ✓ |   | ✗ | 2016 |
| [Rocket](https://rocket.chat/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✗ | 2015 |
| IRC | ✓ | ½ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | 1988 |
| [Mattermost](https://mattermost.com/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✗ | 2016 |
| [Zulip](https://zulipchat.com/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | [✗](https://github.com/zulip/zulip/issues/6096) | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | [✗](https://github.com/zulip/zulip/issues/356) | ✗ | ✗ | 2014 |
| [Orbit](https://github.com/orbitdb/orbit) | ✓ | ½ | ✓ |  |  | ✓ | ✗ | ✗ | ✗ | ✗ |  | [✓](https://orbit.chat/) | [✓](https://orbit.chat/) | ✗ | ✗ | ✗ | ✗ | [✓](https://github.com/orbitdb/orbit-electron) | [✓](https://github.com/orbitdb/orbit-electron) | ✗ | [✓](https://github.com/orbitdb/orbit-textui) | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | 2015 |
| [Mumble](https://wiki.mumble.info/wiki/Main_Page) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✗ | ✗ | ✓ | ✗ | ✓ | ✗ | ✓ | ✗ | 2005 |
| [Spectrum](https://spectrum.chat/) | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | [✗](https://github.com/withspectrum/spectrum/issues/549) | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | 2011 |
| [Signal](https://www.signal.org/) | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | [✓](https://eprint.iacr.org/2016/1013.pdf) | ✗ | ✓ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | 2014 |
| Semaphor | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | 2016 |
| [Keybase](https://keybase.io/) | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✗ | [✗](https://github.com/keybase/keybase-issues/issues/808) | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | 2017 |
| [Surespot](https://www.surespot.me/) | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ |   |
| [Silence](https://silence.im/) | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ |   |
| [Telegram](https://telegram.org/) | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ½ | ✗ | ✗ | ✗ | ✗ | [✓](https://web.telegram.org/) | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | [✓](https://core.telegram.org/mtproto) | ✗ |   |
| SMS/MMS | ✓ | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ½ |   |
| [IMS/RCS](https://en.wikipedia.org/wiki/Rich_Communication_Services) | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✗ |   |
| [Discord](https://discordapp.com/) | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| Gitter | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✗ |   |
| [Duo](https://duo.google.com/) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ! | ! | ✗ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| [Keeperchat](https://keeperchat.com/) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ! | ! | ✗ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | 2017 |
| [Wickr](https://wickr.com/) | ✓ | ! | ✗ | ✗ | ✓ | ✗ | ! | ! | ! | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| [Threema](https://threema.ch/) | ✓ | ! | ✗ | ✗ | ✗ | ✓ | ! | ! | ! | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✗ | ✗ | ✗ |   |
| Whatsapp | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ! | ! | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✗ | [✓](https://blog.whatsapp.com/10000621/Introducing-WhatsApps-desktop-app) | [✓](https://blog.whatsapp.com/10000621/Introducing-WhatsApps-desktop-app) | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ |   |
| iMessage | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ! | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ |   |
| MS Teams | ✓ | ! | ✗ | ✗ | ✓ | ✓ | ! | ! | ! | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| [Facetime](https://www.apple.com/ios/facetime) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ! | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| [Line](https://line.me/en/) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ! | ! | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| Viber | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ! | ! | ✗ | ✗ |   |   | ✓ | ✓ |   | ✓ | ✓ |   |   | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ |   |
| [Allo](https://allo.google.com/) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ! | ✗ | ✗ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ |   |
| Facebook | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ! | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| Skype | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ! | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| [Kakaotalk](https://www.kakaocorp.com/service/KakaoTalk?lang=en) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | [!](https://techcrunch.com/2014/12/07/chat-app-kakao-talk-begins-offering-opt-in-encryption-following-recent-privacy-storm/) | ✗ | ✗ | ✗ | ✗ |   |   | ✓ | ✓ |   | ✓ | ✓ |   |   | ✗ | ✓ | ✓ | ✓ | ✓ |   |   | ✗ | ✗ | ✗ |   |
| Hangouts | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | [✓](https://github.com/tdryer/hangups) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| Reddit Chat | ✓ | ! | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | ✗ |   |
| Twitch | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✗ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✗ |   |
| [Zoom](https://zoom.us/) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| [Slack](https://slack.com/) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ |   |
| Instagram | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ |   |
| Snapchat | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ |   |
| [Steam](https://steampowered.com/) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | [✓](https://steamcommunity.com/chat/) |   | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |   | ✗ | ✓ | ✓ | ✗ | ✓ | ✗ | ✓ | ✗ | ✗ | ✗ |   |
| WeChat | ✓ |   | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ |   | ✓ | ✓ |   | ✓ | ✓ | [✓](https://github.com/geeeeeeeeek/electronic-wechat) |   |   | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | 2011 |
| Kik | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ |   |   | ✓ |   |   |   |   |   |   | ✗ | ✓ | ✓ | ✓ |   |   |   | ✗ | ✗ | ✗ |   |
| BBM | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ |   |   |   |   |   |   |   |   |   | ✗ | ✓ | ✓ |   |   |   |   | ✗ | ✗ | ✗ |   |
| [IMO](https://www.imo.im/) | ✓ | ! | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✓ | ✓ |   |   |   |   | ✗ | ✗ | ✗ |   |
| [QQ](http://www.qq.com/) | ✓ |   | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ |   | ✓ | ✓ |   | ✓ | ✓ | ✗ |   | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | 1999 |
| [Zalo](https://zalo.me/) | ✓ | ! | ✗ | ✗ |   |   |   |   |   | ✗ | ✗ | ✓ |   | ✓ | ✓ |   |   |   |   |   | ✗ | ✓ |   |   | ✓ | ✓ |   |   |   | ✗ |   |
| [Tango](https://www.tango.me/) | ✓ |   | ✗ | ✗ | ✗ |   |   |   |   | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ |   | ✓ | ✓ | ✓ |   |   |   |   |   |
| [Tuenti](https://www.tuenti.com/epp) | ✓ |   | ✗ | ✗ | ✗ |   |   |   |   | ✗ | ✗ | [✓](http://www.tuenti.com/login) |   | ✓ | ✓ |   |   |   |   |   | ✗ | ✓ |   |   | ✓ |   |   | ✗ | ✗ | ✗ |   |
| ICQ | ✓ | ! |   |   |   |   |   |   |   | ✗ | ✗ |   |   |   |   |   | ✓ |   |   |   | ✓ | ✓ |   |   |   |   |   | ✗ |   | ✗ |   |
| [Gadu Gadu](https://www.gadu-gadu.pl/) | ✓ | ! | ✗ | ✗ | ✗ |   |   |   |   | ✗ | ✗ |   |   | ✓ | ✓ |   | ✓ | ✓ | ✓ |   | ✗ | ✓ | ✓ | ✓ | ✓ |   |   | ✗ | ✗ | ✗ |   |
| [stealthy.im](http://stealthy.im/) | ✓ |   |   |   |   |   |   |   |   |   |   |   |   | ✓ | ✓ |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| [Pond](https://github.com/agl/pond) | ✗ |   | ✓ | ✓ | ✗ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ |   |   | ✗ | ✗ | ✗ |   | ✗ | ✓ | ✗ |   |
| [SILC](http://www.silcnet.org/) | ✗ |   | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ | ✓ |   | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ |   |
| PSYC-1 | ✗ |   | ✓ | ✓ | ✓ | ✓ | ✗ | ✗ | ✗ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |   | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✗ | 2000 |
| [Zephyr](https://github.com/zephyr-im) | ✗ |   | ✓ |   |   |   |   |   |   | ✗ | ✗ |   |   |   |   |   |   |   |   |   | ✗ |   |   |   |   |   |   |   |   |   |   |
| AIM | ✗ | ! |   | ✗ |   |   | ✗ | ✗ | ✗ | ✗ | ✗ |   |   |   |   |   | ✓ |   |   |   | ✓ |   |   |   |   |   |   | ✗ |   | ✗ |   |
| MSN | ✗ | ✗ | ✗ | ✗ | ✗ |   | ✗ | ✗ | ✗ | ✗ | ✗ |   |   |   |   |   | ✓ |   |   |   | ✓ |   |   |   |   |   | ✓ | ✗ |   | ✗ |   |
| Yahoo | ✗ | ✗ | ✗ | ✗ | ✗ |   | ✗ | ✗ | ✗ | ✗ | ✗ |   |   |   |   |   |   |   |   |   | ✓ |   |   |   |   |   | ✓ | ✗ |   | ✗ |   |
| [ooVoo](http://www.oovoo.com/) | ✗ |   |   |   |   |   |   |   |   | ✗ | ✗ |   |   |   |   |   |   |   |   |   | ✗ |   |   |   |   |   |   |   |   |   |   |
| Echo | ✗ |   |   |   |   | ✓ |   |   |   | ✗ | ✗ |   |   |   |   |   |   |   |   |   | ✗ |   |   |   |   |   | ✓ | ✓ |   |   |   |
| [cfc.io](http://cfc.io/) |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| vero |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| tinode |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| [Dust](https://www.usedust.com/) |   |   |   |   |   |   |   |   |   |   |   |   |   | ✓ | ✓ |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |


## Symbols

- ✗ = no or false
- ½ = partial support
- ! = claimed

<!-- Footnotes -->

[active]: https://duckduckgo.com/?q=!w+active "The creators of the app/protocol are continuing development/support of it.
For Open Source projects: has had a commit in the last year."
[anonymous]: https://duckduckgo.com/?q=!w+anonymous "If a phone number or other permanent-ish identifier is required for using the platform"
[e2e_default]: https://duckduckgo.com/?q=!w+e2ee "Are all chats end-to-end encrypted by default?"
[e2e_audit]: https://duckduckgo.com/?q=!w+e2ee "Has there been a third party audit on the overall end to end encryption protocol by a well known security research firm or academic institution."
[aosp]: https://duckduckgo.com/?q=!w+aosp "This means there is an open source signed package available to a package manager that works on phones without Google Play. E.G. a reproducible F-Droid release."
[mdm]: https://duckduckgo.com/?q=!w+messaging "Multi-device messaging: More than one device can be directly connected to a given account at the same time"
[offline_messages]: https://duckduckgo.com/?q=!w+offline+messages "If the receiving party does not have the client open; can you send them a message?"
[phoneless]: https://duckduckgo.com/?q=!w+phoneless "Do you need an actual phone to use the software? e.g. do you need to receive an SMS to sign up?"
[decentralized]: https://duckduckgo.com/?q=!w+decentralized "Multiple people can run their own servers and communicate between them. E-mail is an example of a federated network where gmail users can communicate with fastmail users"
[ietf]: https://duckduckgo.com/?q=!w+ietf "Is the protocol documented in a published IETF or other international standards body document?
Usually this column is: Does an RFC exist for the protocol"
