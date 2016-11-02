# Awesome-twilio-golang
The place to start if you develop Twilio integrations in Go

## Motivation
Unlike for other programming languages Twilio doesn't provide an official Go library. This repo provides developers with links and reference to quickly find what they are looking for.

## Contributing

Contributions are very welcome. Please send a PR if you want to add or change this list.

## Wrappers and libraries

This list is ordered by the number of features implemented.

Name                                                                      |SMS|Call|TwiML|IP Msg|Usage|Conf|Acc|Queue|Rec|Av Num|Inc Num|Tw App|Media|keys|Noti|Transcript|Out Call Id|Lookup|Alerts|SIP
--------------------------------------------------------------------------|---|----|-----|------|-----|----|---|-----|---|------|-------|------|-----|----|----|----------|-----------|------|------|---
[natebrennand/twiliogo](https://github.com/natebrennand/twiliogo)         |yes|yes | yes |      |yes  |yes |yes|yes  |yes|yes   |yes    |yes   |yes  |    |yes |yes       |           |      |      |yes
[kevinburke/twilio-go](https://github.com/kevinburke/twilio-go)           |yes|yes |     |      |     |yes |yes|     |yes|      |yes    |      |yes  |yes |    |yes       |yes        |      |yes   |
[ckvist/twilio](https://bitbucket.org/ckvist/twilio)                      |yes|yes | yes |      |yes  |yes |yes|yes  |yes|      |       |      |     |    |yes |          |yes        |      |      |
[chrisenytc/twilio](https://github.com/chrisenytc/twilio) Fork            |yes|yes | yes |      |yes  |yes |yes|yes  |yes|      |       |      |     |    |yes |          |yes        |      |      |
[carlosdp/twiliogo](https://github.com/carlosdp/twiliogo)                 |yes|yes |     |yes   |     |    |   |     |   |      |yes    |      |     |    |    |          |           |      |      |
[tulip/twiliogo](https://github.com/tulip/twiliogo) Fork                  |yes|yes |     |yes   |     |    |   |     |   |yes   |yes    |      |     |    |    |          |           |      |      |
[fabriziomoscon/twiliogo](https://github.com/fabriziomoscon/twiliogo) Fork|yes|yes |     |yes   |yes  |    |yes|     |   |yes   |yes    |yes   |     |    |    |          |           |      |      |
[eazynow/twilio-go](https://github.com/eazynow/twilio-go)                 |   |yes | yes |      |yes  |    |   |yes  |yes|      |       |      |     |    |yes |yes       |           |      |      |
[cousine/go-twilio](https://github.com/cousine/go-twilio)                 |   |yes | yes |      |     |yes |yes|yes  |   |      |       |      |     |    |    |          |           |      |      |
[wyc/utwil](https://github.com/wyc/utwil)                                 |yes|yes |     |      |     |    |   |     |   |      |       |      |     |    |    |          |           |yes   |      |
[agonzalezro/twilio-go](https://github.com/agonzalezro/twilio-go)         |yes|yes |     |      |     |    |   |     |   |      |       |      |     |    |    |          |           |      |      |
[sfreiberg/gotwilio](https://github.com/sfreiberg/gotwilio)               |yes|yes |     |      |     |    |   |     |   |      |       |      |     |    |    |          |           |      |      |
[rodzzlessa24/twiliogo](https://github.com/rodzzlessa24/twiliogo)         |yes|yes |     |      |     |    |   |     |   |      |       |      |     |    |    |          |           |      |      |
[subosito/twilio](https://github.com/subosito/twilio)                     |yes|    |     |      |     |    |   |     |   |      |       |      |     |    |    |          |           |      |      |
                                                                          |   |    |     |      |     |    |   |     |   |      |       |      |     |    |    |          |           |      |      |
                                                                          |   |    |     |      |     |    |   |     |   |      |       |      |     |    |    |          |           |      |      |


## User identity and access tokens
[kevinburke/twilio-go](https://github.com/kevinburke/twilio-go) Provide a full implementation of access token with all Twilio grants for IPMessaging, Video and Programmable Voice. And provide an implementation for capabilities tokens.

[corytodd/accesstoken-go](https://github.com/corytodd/accesstoken-go) 
Go implementation for Twilio access tokens and Programmable Video.
Go AccessToken creator for Twilio with support for grants. This library supports HS256, HS384, and HS512 hashing using a minimal JWT implementation.

[xaviiic/twilioGo](https://github.com/xaviiic/twilioGo) Implements both capabilities and access tokens

[enahum/twilio-accesstoken-go](https://github.com/enahum/twilio-accesstoken-go)
Similar to [corytodd/accesstoken-go](https://github.com/corytodd/accesstoken-go)

[ZBoxApp/twilio-accesstoken-go](https://github.com/ZBoxApp/twilio-accesstoken-go) 
Similar to [corytodd/accesstoken-go](https://github.com/corytodd/accesstoken-go)


## Capability tokens
[kevinburke/twilio-go](https://github.com/kevinburke/twilio-go) Provide a full implementation of access token with all Twilio grants for IPMessaging, Video and Programmable Voice. And provide an implementation for capabilities tokens.

[xaviiic/twilioGo](https://github.com/xaviiic/twilioGo) 

## Tools and projects written in Go

[saintpete/logrole](https://github.com/saintpete/logrole) LogRole for Twilio - Create User Roles for Limited Access to Twilio Logs

[titanous/twilio-forwarder](https://github.com/titanous/twilio-forwarder) Forward calls and SMS to email

[Syerram/twilio_load](https://github.com/Syerram/twilio_load) A Load tester tool for Twilio endpoints

[Swatto/promtotwilio](https://github.com/Swatto/promtotwilio) Send text messages for Prometheus alerts using Twilio

[tulip/terraform-provider-twilio](https://github.com/tulip/terraform-provider-twilio) Terraform provider to allocate and configure local phone numbers on Twilio

[streamrail/twilio-gae](https://github.com/streamrail/twilio-gae) simple Twilio Google App Engine client for Go

[kyleconroy/htwml5](https://github.com/kyleconroy/htwml5) Convert HTML to TwiML

## Blog articles

[Twilio: make and receive calls](https://www.twilio.com/blog/2014/10/making-and-receiving-phone-calls-with-golang.html)

[Twilio: sending SMS](https://www.twilio.com/blog/2014/06/sending-sms-from-your-go-app.html)

[Google Cloud Platform: Using SMS and Voice Services via Twilio](https://cloud.google.com/appengine/docs/flexible/go/using-sms-and-voice-services-via-twilio)

## License

[MIT](LICENSE)
