# Messaging Services Comparison

This is a backup of a [google drive based comparison of messaging services and communications protocols](https://docs.google.com/spreadsheets/d/1-UlA4-tslROBDS9IqHalWVztqZo7uxlCeKPQ-8uoFOU/edit#gid=0), but you know, not actually hosted on a centralized service.

This will be updated with new services as they come out, and sorted by a user poll at some point. 

|   | Active | TLS | Open Client | Open Server | On Premise | Anonymous | E2E Private | E2E Group | E2E Default | E2E Audit | FIDO1 / U2F | Desktop Web | Mobile Web | Android | Apple iOS | AOSP | Win | macOS | Linux | \*BSD | Terminal | MDM | Offline Messages | File Share | Audio Call | Video Call | Phoneless | Decentralized or Federated | Open Spec | IETF | Introduced |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Riot/Matrix](https://matrix.org/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | [FALSE](https://github.com/vector-im/riot-web/issues/6779) | [TRUE](https://www.nccgroup.trust/us/our-research/matrix-olm-cryptographic-review/) | [FALSE](https://github.com/vector-im/riot-web/issues/2772) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | [PARTIAL](https://github.com/torhve/weechat-matrix-protocol-script/issues/124) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | [FALSE](https://matrix.org/docs/guides/faq.html#why-aren't-you-doing-this-through-the-ietf%3F-or-w3c%3F-or-3gpp%3F) | 2014 |
| [XMPP](https://xmpp.org/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | PARTIAL | [TRUE](http://conversations.im/omemo/audit.pdf) | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | 1999 |
| [NextCloud Talk](https://nextcloud.com/talk/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | 2018 |
| [Wire](https://wire.com/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | [TRUE](https://medium.com/@wireapp/wires-independent-security-review-61f37a1762a8) | [FALSE](https://github.com/wireapp/wire/issues/85) | TRUE | FALSE | TRUE | TRUE | [FALSE](https://github.com/wireapp/wire-android#what-is-included-in-the-open-source-client) | TRUE | TRUE | TRUE | TRUE | [PARTIAL](https://github.com/wireapp/coax) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | 2014 |
| [Briar](https://briarproject.org/) | TRUE | TRUE | TRUE | N/A | N/A | TRUE | TRUE | TRUE | TRUE | [TRUE](https://briarproject.org/raw/BRP-01-report.pdf) | N/A | FALSE | FALSE | TRUE | FALSE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE | 2016 |
| [Tox](https://tox.chat/) | TRUE | TRUE | TRUE | N/A | N/A | TRUE | TRUE | TRUE | TRUE | [FALSE](https://github.com/TokTok/c-toxcore/issues/426) | N/A | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | PARTIAL | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | 2013 |
| [Kontalk](https://kontalk.org/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | TRUE | PARTIAL | 2014 |
| [DeltaChat](https://delta.chat/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | FALSE | FALSE | PARTIAL | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | TRUE | [PARTIAL](https://github.com/deltachat/deltachat-android/blob/master/standards.md#standards-used-in-delta-chat) | 2017 |
| [Ring](https://ring.cx/) | TRUE | TRUE | TRUE | N/A | N/A | TRUE | TRUE | TRUE | TRUE | FALSE | N/A | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | PARTIAL | FALSE | 2016 |
| [BitMessage](https://bitmessage.org/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | [TRUE](https://github.com/Bitmessage/PyBMAndroidQt) | FALSE | FALSE | TRUE | [TRUE](https://github.com/VoluntaryLabs/Bitpost) | TRUE | TRUE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | 2014 |
| [Ricochet](https://ricochet.im/) | TRUE | TRUE | TRUE | N/A | N/A | TRUE | TRUE | TRUE | TRUE | FALSE | N/A | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | [FALSE](https://github.com/ricochet-im/ricochet/issues/405) | FALSE | FALSE | FALSE | TRUE | TRUE | [TRUE](https://github.com/ricochet-im/ricochet/blob/master/doc/protocol.md) | FALSE | 2016 |
| [PSYC-2](https://about.psyc.eu/PSYC2) | TRUE | TRUE | TRUE | N/A | N/A | TRUE | TRUE | TRUE | TRUE | FALSE | N/A | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | 2013 |
| [Status.im](http://status.im/) | TRUE | TRUE | TRUE | N/A | N/A | TRUE | TRUE | TRUE | TRUE | FALSE | N/A | FALSE | FALSE | [TRUE](https://play.google.com/store/apps/details?id=im.status.ethereum) | TRUE |   | FALSE | TRUE | TRUE | FALSE |   |   | PARTIAL |   |   |   | TRUE | TRUE |   | FALSE | 2016 |
| [Rocket](https://rocket.chat/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | FALSE | 2015 |
| IRC | TRUE | PARTIAL | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | 1988 |
| [Mattermost](https://mattermost.com/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | FALSE | 2016 |
| [Zulip](https://zulipchat.com/) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | [FALSE](https://github.com/zulip/zulip/issues/6096) | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | [FALSE](https://github.com/zulip/zulip/issues/356) | FALSE | FALSE | 2014 |
| [Orbit](https://github.com/orbitdb/orbit) | TRUE | PARTIAL | TRUE | N/A | N/A | TRUE | FALSE | FALSE | FALSE | FALSE | N/A | [TRUE](https://orbit.chat/) | [TRUE](https://orbit.chat/) | FALSE | FALSE | FALSE | FALSE | [TRUE](https://github.com/orbitdb/orbit-electron) | [TRUE](https://github.com/orbitdb/orbit-electron) | FALSE | [TRUE](https://github.com/orbitdb/orbit-textui) | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | FALSE | FALSE | 2015 |
| [Mumble](https://wiki.mumble.info/wiki/Main_Page) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | FALSE | FALSE | TRUE | FALSE | TRUE | FALSE | TRUE | FALSE | 2005 |
| [Spectrum](https://spectrum.chat/) | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | [FALSE](https://github.com/withspectrum/spectrum/issues/549) | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | 2011 |
| [Signal](https://www.signal.org/) | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | TRUE | [TRUE](https://eprint.iacr.org/2016/1013.pdf) | FALSE | TRUE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | 2014 |
| Semaphor | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | 2016 |
| [Keybase](https://keybase.io/) | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | FALSE | [FALSE](https://github.com/keybase/keybase-issues/issues/808) | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | 2017 |
| [Surespot](https://www.surespot.me/) | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | FALSE | TRUE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE |   |
| [Silence](https://silence.im/) | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE |   |
| [Telegram](https://telegram.org/) | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | PARTIAL | FALSE | FALSE | FALSE | FALSE | [TRUE](https://web.telegram.org/) | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | [TRUE](https://core.telegram.org/mtproto) | FALSE |   |
| SMS/MMS | TRUE | BROKEN | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | PARTIAL |   |
| [IMS/RCS](https://en.wikipedia.org/wiki/Rich_Communication_Services) | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE | FALSE |   |
| [Discord](https://discordapp.com/) | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| Gitter | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | FALSE |   |
| [Duo](https://duo.google.com/) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | CLAIMED | CLAIMED | FALSE | TRUE | FALSE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| [Keeperchat](https://keeperchat.com/) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | CLAIMED | CLAIMED | FALSE | TRUE | FALSE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | 2017 |
| [Wickr](https://wickr.com/) | TRUE | CLAIMED | FALSE | FALSE | TRUE | FALSE | CLAIMED | CLAIMED | CLAIMED | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| [Threema](https://threema.ch/) | TRUE | CLAIMED | FALSE | FALSE | FALSE | TRUE | CLAIMED | CLAIMED | CLAIMED | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | FALSE | FALSE | FALSE |   |
| Whatsapp | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | CLAIMED | CLAIMED | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | FALSE | [TRUE](https://blog.whatsapp.com/10000621/Introducing-WhatsApps-desktop-app) | [TRUE](https://blog.whatsapp.com/10000621/Introducing-WhatsApps-desktop-app) | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE |   |
| iMessage | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | CLAIMED | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE |   |
| MS Teams | TRUE | CLAIMED | FALSE | FALSE | TRUE | TRUE | CLAIMED | CLAIMED | CLAIMED | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| [Facetime](https://www.apple.com/ios/facetime) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | CLAIMED | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| [Line](https://line.me/en/) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | CLAIMED | CLAIMED | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| Viber | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | CLAIMED | CLAIMED | FALSE | FALSE |   |   | TRUE | TRUE |   | TRUE | TRUE |   |   | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE |   |
| [Allo](https://allo.google.com/) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | CLAIMED | FALSE | FALSE | TRUE | FALSE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE |   |
| Facebook | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | CLAIMED | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| Skype | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | CLAIMED | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| [Kakaotalk](https://www.kakaocorp.com/service/KakaoTalk?lang=en) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | [CLAIMED](https://techcrunch.com/2014/12/07/chat-app-kakao-talk-begins-offering-opt-in-encryption-following-recent-privacy-storm/) | FALSE | FALSE | FALSE | FALSE |   |   | TRUE | TRUE |   | TRUE | TRUE |   |   | FALSE | TRUE | TRUE | TRUE | TRUE |   |   | FALSE | FALSE | FALSE |   |
| Hangouts | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | [TRUE](https://github.com/tdryer/hangups) | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| Reddit Chat | TRUE | CLAIMED | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | FALSE | FALSE | FALSE |   |
| Twitch | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | FALSE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | FALSE |   |
| [Zoom](https://zoom.us/) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| [Slack](https://slack.com/) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE |   |
| Instagram | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE |   |
| Snapchat | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE |   |
| [Steam](https://steampowered.com/) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | [TRUE](https://steamcommunity.com/chat/) |   | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE |   | FALSE | TRUE | TRUE | FALSE | TRUE | FALSE | TRUE | FALSE | FALSE | FALSE |   |
| WeChat | TRUE |   | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE |   | TRUE | TRUE |   | TRUE | TRUE | [TRUE](https://github.com/geeeeeeeeek/electronic-wechat) |   |   | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | 2011 |
| Kik | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE |   |   | TRUE |   |   |   |   |   |   | FALSE | TRUE | TRUE | TRUE |   |   |   | FALSE | FALSE | FALSE |   |
| BBM | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE |   |   |   |   |   |   |   |   |   | FALSE | TRUE | TRUE |   |   |   |   | FALSE | FALSE | FALSE |   |
| [IMO](https://www.imo.im/) | TRUE | CLAIMED | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | TRUE | TRUE |   |   |   |   | FALSE | FALSE | FALSE |   |
| [QQ](http://www.qq.com/) | TRUE |   | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE |   | TRUE | TRUE |   | TRUE | TRUE | FALSE |   | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | 1999 |
| [Zalo](https://zalo.me/) | TRUE | CLAIMED | FALSE | FALSE |   |   |   |   |   | FALSE | FALSE | TRUE |   | TRUE | TRUE |   |   |   |   |   | FALSE | TRUE |   |   | TRUE | TRUE |   |   |   | FALSE |   |
| [Tango](https://www.tango.me/) | TRUE |   | FALSE | FALSE | FALSE |   |   |   |   | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE |   | TRUE | TRUE | TRUE |   |   |   |   |   |
| [Tuenti](https://www.tuenti.com/en/app) | TRUE |   | FALSE | FALSE | FALSE |   |   |   |   | FALSE | FALSE | [TRUE](http://www.tuenti.com/login) |   | TRUE | TRUE |   |   |   |   |   | FALSE | TRUE |   |   | TRUE |   |   | FALSE | FALSE | FALSE |   |
| ICQ | TRUE | CLAIMED |   |   |   |   |   |   |   | FALSE | FALSE |   |   |   |   |   | TRUE |   |   |   | TRUE | TRUE |   |   |   |   |   | FALSE |   | FALSE |   |
| [Gadu Gadu](https://www.gadu-gadu.pl/) | TRUE | CLAIMED | FALSE | FALSE | FALSE |   |   |   |   | FALSE | FALSE |   |   | TRUE | TRUE |   | TRUE | TRUE | TRUE |   | FALSE | TRUE | TRUE | TRUE | TRUE |   |   | FALSE | FALSE | FALSE |   |
| [stealthy.im](http://stealthy.im/) | TRUE |   |   |   |   |   |   |   |   |   |   |   |   | TRUE | TRUE |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| [Pond](https://github.com/agl/pond) | FALSE |   | TRUE | TRUE | FALSE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE |   |   | FALSE | FALSE | FALSE |   | FALSE | TRUE | FALSE |   |
| [SILC](http://www.silcnet.org/) | FALSE |   | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | FALSE | TRUE |   | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE |   |
| PSYC-1 | FALSE |   | TRUE | TRUE | TRUE | TRUE | FALSE | FALSE | FALSE | FALSE | FALSE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE |   | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | TRUE | FALSE | 2000 |
| [Zephyr](https://github.com/zephyr-im) | FALSE |   | TRUE |   |   |   |   |   |   | FALSE | FALSE |   |   |   |   |   |   |   |   |   | FALSE |   |   |   |   |   |   |   |   |   |   |
| AIM | FALSE | CLAIMED |   | FALSE |   |   | FALSE | FALSE | FALSE | FALSE | FALSE |   |   |   |   |   | TRUE |   |   |   | TRUE |   |   |   |   |   |   | FALSE |   | FALSE |   |
| MSN | FALSE | FALSE | FALSE | FALSE | FALSE |   | FALSE | FALSE | FALSE | FALSE | FALSE |   |   |   |   |   | TRUE |   |   |   | TRUE |   |   |   |   |   | TRUE | FALSE |   | FALSE |   |
| Yahoo | FALSE | FALSE | FALSE | FALSE | FALSE |   | FALSE | FALSE | FALSE | FALSE | FALSE |   |   |   |   |   |   |   |   |   | TRUE |   |   |   |   |   | TRUE | FALSE |   | FALSE |   |
| [ooVoo](http://www.oovoo.com/) | FALSE |   |   |   |   |   |   |   |   | FALSE | FALSE |   |   |   |   |   |   |   |   |   | FALSE |   |   |   |   |   |   |   |   |   |   |
| Echo | FALSE? |   |   |   |   | TRUE |   |   |   | FALSE | FALSE |   |   |   |   |   |   |   |   |   | FALSE |   |   |   |   |   | TRUE | TRUE |   |   |   |
| [cfc.io](http://cfc.io/) |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| vero |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| tinode |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| [Dust](https://www.usedust.com/) |   |   |   |   |   |   |   |   |   |   |   |   |   | TRUE | TRUE |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
