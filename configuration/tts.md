---
title: TTS
source: https://github.com/naomiproject/naomi-docs/blob/master/configuration/tts.md
meta:
  - property: og:title
    content: "TTS Guide"
  - property: og:description
    content: an open source platform for developing always-on, voice-controlled applications
---

# TTS Configuration

TTS, stands for Text To Speech, and is software that transforms text into speech, which is how Naomi can speak to you

| Engine name   | Privacy Respect | Type    | Self Hosting | Requests (free account) | Quality     | Platform        |
|:-------------:|:---------------:|:-------:|:------------:|:-----------------------:|:-----------:|:---------------:|
| Google TTS    | 👎              | Online  | NO           | 50/day                  | Perfect     | Any             |
| Microsoft TTS | 👎              | Online  | NO           | 5000/month              | Perfect     | Any             |
| Festival      | 👍              | Offline | Yes          | Unlimited               | Good        | Linux 🐧        |
| Espeak        | 👍              | Offline | Yes          | Unlimited               | Bad         | Linux 🐧        |
| SvoxPico      | 👍              | Offline | Yes          | Unlimited               | Really good | Linux 🐧        |
| Flite         | 👍              | Offline | Yes          | Unlimited               | ?           | Linux 🐧        |
| Mary TTS      | 👍              | Online  | Yes          | Unlimited               | Really good | Linux 🐧        |
| SayOSX        | 👍              | Offline | Yes          | Unlimited               | Perfect     | Mac OSX only    |
| Cereproc      | 👍              | Online  | Yes          | Unlimited               | Really good | Any             |

You will need to pick one of the above and then follow the instructions below that is denoted for the TTS engine you select

>Note: Some engines do not require you to do anything other than input information during the profile setup which is covered in section four!

## Google TTS

No installation required, proceed to the next section!

## Microsoft TTS

No installation required, proceed to the next section!

## Festival

>Note: Only English is available at this time!

Install with the following command

```console
sudo apt-get install festival festvox-kallpc16k
```

## Espeak

Install with the following command

```console
sudo apt-get install espeak
```

## SvoxPico

Install with the following command

```console
sudo apt-get install libttspico-utils
```

## Flite

Install with the following instructions

[Follow steps here](http://www.festvox.org/flite/)

## Mary TTS

MaryTTS is too heavy and memory hungry to be installed on a Raspberry Pi, to use it you will have to setup a server using the following steps or use a server provided by the community

[Follow steps here](../plugins/marytts-server.html)

## Say OSX

>Note: Only available on Mac OSX platform!

No installation required, proceed to the next section!

## Cereproc

Install with the following instructions

[Follow steps here](https://www.cereproc.com/fr/products/server)

<DocPreviousVersions/>
<EditPageLink/>
