# English Version

[العربية](https://ikhwaniya.github.io/instant-messaging-study/arabic)

Millions of Muslims are spied on every year illegally by terrorist organizations such as the NSA and Mossad, this repository/page is to bring awareness of anonymity guides and privacy guides to Muslims.

I highly recommend you also read [the anonymousplanet guide to anonymity](https://anonymousplanet.org/guide.html), if you have ADHD and are unable to read it then simply skim over the necessary resources.

The jist of this project is; if you use WhatsApp don't use it and use [Signal](https://signal.org/download/) instead

If you are an advanced user who speaks to other advanced users, I highly recommend using an [XMPP](https://xmpp.org/) client such as [Gajim](https://gajim.org/) or [Dino](https://dino.im/) in combination [i2p](https://geti2p.net/en/)

or just use both and don't let your topics be on multiple platforms at once

After you have finished reading this please share it to spread awareness.

If you see anything wrong with this page you can submit a pull request or submit an issue [here](https://github.com/Ikhwaniya/instant-messaging-study/issues).

[Here's a video](https://www.youtube.com/embed/aHp4eyMLVHM) by privacy advocate "Mental Outlaw" if you don't want to spend time reading and do better with videos.

*Note 1: This YouTuber gets very passionate and angry in this video, and they are not Muslim, do not watch around children.*\
*Note 2: The video is outdated and Signal now has MOST of the same extra features as Telegram and WhatsApp, Telegram is not recommended either.*

## A message for the people stuck in Gaza

I highly recommend using [Briar](https://briarproject.org/quick-start/ar/) if you have a android mobile device. Briar will allow you and your family to stay in contact even when there is no internet. If you are by the border of Egypt and Gaza, and you have an Egyptian friend with briar on their phone, your phones can connect via bluetooth and you will be able to get messages out to people who are in other parts of the world by your friend's phone automatically relaying the message.

**DO NOT USE WHATSAPP**
as of April 23rd, 2024, WhatsApp has been providing Israeli terrorists (specifically the IDF) with the information needed to find and kill Palestinian civilians.

<br/>

<blockquote class="twitter-tweet" data-media-max-width="560"><p lang="en" dir="ltr">Whatsapp leaked Palestinians&#39; information to the Israeli army. If a Palestinian family is at home, information is leaked to the Israeli army and they target the house where the family lives. <a href="https://t.co/Obqe6e894F">pic.twitter.com/Obqe6e894F</a></p>&mdash; Gaza Notifications (@gazanotice) <a href="https://twitter.com/gazanotice/status/1782759075048026322?ref_src=twsrc%5Etfw">April 23, 2024</a></blockquote>

<iframe width="560" height="315" src="https://www.youtube.com/embed/mt4cJelQIPI?si=U7MyAIM_2XruJlsm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br/>

## A notice about Berty and SimpleX
The applications "Berty" and "SimpleX" have an oddly overwhelming amount of features that appeal too much to criminals and put more effort into advertising it than the app itself. Be very wary about these apps as they may be honeypots.

## Introduction

[Please review this CSV file or have it in another tab while reading.](https://github.com/Ikhwaniya/Instant-Messaging-Study/blob/main/Instant%20Messengers.csv)

WhatsApp started as a fork of [Signal](https://signal.org/download/) by former Yahoo employees and eventually bought by Jewish-American CEO Mark Zuckerburg, who is also the CEO of Facebook, a company known for spying on and collection information on billions of people. WhatsApp has been known for having tons of vulnerabilities and issues involving and not limited to; cryptography, trust, and backdoors. 

WhatsApp is not the only problem in terms of mass security vulnerability, but also apps that are likely on your teenage childrens' phones, such as Discord and Snapchat. If you take a look at the CSV I have linked at the beginning of this introduction, you can see that Discord and WhatsApp have the lowest score, I didn't bother to add Snapchat due to how ridiculous Snapchat's security is, but if it was there it would certainly be lower than both Discord and WhatsApp.

If you take a look at the tweet embedded in this site above in the Gaza message section, WhatsApp has been ***willingly*** sending information to Israeli terrorists for their campaign of killing innocent Palestinian civilians. This means that by using WhatsApp you and your friends and family who use WhatsApp are indirectly complicit in genocide by contribution to the information network put together by the help of Jewish-American Facebook CEO Mark Zuckerberg and the terrorist Israeli "intelligence" Mossad.

Let's go through the CSV column by column

### **Points**
This is the score I have given the app based on it's features of privacy and anonymity. The highest score goes to XMPP and the lowest score is tied by Discord and WhatsApp.

### **License**
You can disregard this column if you are not a developer or someone planning to make an app with better features.

### **OS limited**
If an application is OS limited, it means you can only use it on certain platforms (such as Windows or iOS). This is noted because some operating systems are not open source and can breach your privacy more than the App can.

### **Minimal storing**
If an application has minimal storing as "YES" it means the application stores as minimal information as possible, otherwise it stores unnecessary information. For an example the application "Signal" is made to delete messages from their server after they are delivered to all devices of the contact. If the application has "P2P" or "TOR-P2P" it means that the data is not sent to a server but rather directly to the recieving contact.

### **14 Eye Alliance**
The 14 Eye Alliance is an intelligence alliance between 14 countries that share and collect information on people including CEOs, they will also sometimes have another country seize control of a company (such as a VPN service) with a gag order in order to plant a [honeypot](https://en.wikipedia.org/wiki/Honeypot_(computing)) to collect information on customers of said company. The company most imfamous for doing this is Australia. You can read more about this [here](https://securitymadesimple.org/cybersecurity-blog/fourteen-eyes-surveillance-explained/).

### **I2P Possible**
If you are not an advanced user, you dont really need this. I2P is an Anonymization network like TOR, but without exit nodes.

### **Onion possible**
If you are not an advanced user, you also dont really need this. the Onion protocol is recommended for TOR users to evade the downsides of exit nodes and full encryption between the user and the onion service.

### **TOR Proxy Possible**
TOR should be used when possible if you are a journalist or need to conceal your identity, especially on non-decentralized services.

### **Track record**
I'll be skipping this since it's pretty self explanatory, you can research the apps yourself for confirmation of track records.

### **Default settings**
If the default settings of the application are not marked as "GOOD", you may need to make some modifications to the settings yourself in order for privacy and/or anonymity

### **FOSS**
FOSS stands for "Fully Open Source Software" some applications such as Signal and Session have dependencies that are not fully open source, such as google analytics. There are alternative mobile clients for Signal on Android such as "Molly" and "Signal-FOSS" which remove these dependencies if you are paranoid.

### **Metadata OBF**
Obf is short for "Obfuscation", the metadata may include things like when your message was sent, or location data in a photo, this is actually how an [imfamous man who didn't kill himself](https://athenaforensics.co.uk/john-mcafee-and-the-photograph-exif-metadata/) was arrested.

### **Zero AEAR**
Zero-Access Encryption at rest is used when you store data at some provider (let us say your chat history or chat backups) but this history or backup is encrypted on your side and cannot be read or decrypted by the provider hosting it.

### **Politics**
Some applications may have a politicol agenda, for an example, although this isn't a communication app, the application "Duolingo" used by children for learning languages pushes far left pro-LGBTQ+ agenda while showing Muslim characters.

### **Non-profit**
Applications that profit from their users or stock investors may change their bias to fit the bigotry bubble that the current consumers and investors have.

### **Anon register**
Applications with anonymous registration paired with good encryption can be very good for privacy and anonymity.

### **Post-quantum**
Quantum computers have the ability to bruteforce

### **Auto-Delete**
Automatically deleting messages allows for more private conversations that are harder to track.

It is important to note that the reason the application "Session" is marked as "BAD" here is because multiple users (including myself) that Session's source has completely removed PFS and does not properly remove messages from their servers, there seems to also be a "main node" where messages are stored. After logging in on a new device, any auto deleted messages will immediately appear and then disappear. This can be intercepted and used to log messages that are automatically "deleted".

### **PFS**
You can read about this [here](https://en.wikipedia.org/wiki/Forward_secrecy).

### **MITM-Proof**
MITM stands for "Man In The Middle" and is a type of attack used by hackers and terrorist intelligence such as the NSA and Mossad.

Signal, the Matrix client "Element", and many other instant messaging clients will alert both users when a new signature/key is created and used in a new device, you can also confirm key information with the other person either in real life or over mail to be sure the key belongs to the contact.

### **Decentralized**
You don't really need this if you're not an advanced user. Decentralized means there is no main server involved. This can refer to multiple servers, p2p (pier to pier communication), TOR-p2p (end to end communication over the decentralized TOR network), or even i2p.

### **Bluetooth**
Some chat applications (such as Briar) are implementing the ability to text people over bluetooth, then if one of the piers involved has internet, it will forward to other recipients from the original user via signed messages.

### **Honeypot**
Common opinion on how likely the tested application is a honeypot.

### **Anon net**
Some chat applications use anonymization networks so you can speak to untrusted individuals without them knowing who you are. If you are only speaking to trusted individuals, you don't need this.

### **E2EE**
End-to-end encryption is used to make sure that not only you and the contact are the people exchanging messages, but also so no other device than yours and the contact's can read it

## Why should I care
By allowing your information to be given to federal agencies, it may allow progression within their information network. If you have connection to journalists or friends of friends of journalists, you may cause their information to be at risk simply by using an application that gives all it's information to authorities while being friends with them. You are also submitting to unlawful surveillance with and without your knowledge, which could be violating your rights depending on what country you live in.
