---
layout: post
title:  "Are Bluetooth Beacons secure?"
date:   2015-08-26 12:38:33
categories: Technology,Security
author: Daniel Schofield
---

In the process of determining the feasibility of our project we faced the age old questions when considering new technology; Is it secure? and; What kind of privacy concerns are we facing?

Notoriously, Bluetooth Technology used to be amongst the least secure forms of data transfer. It relied on devices sharing their Bluetooth MAC addresses with one another to create a temporary wireless connection. Anyone with even remote knowledge of half of the words used in the previous sentence have just donned their foil hats. Rest assured, my conspiracy theorist friends, Bluetooth wouldn't have survived to become one of the most widely used protocols for wireless connectivity if the security, and in turn privacy, hadn't improved.

In the revision of Bluetooth, version 2.1, a feature know as Simple Secure Pairing (SSP) was introduced. The objective of SSP was to make the connection (pairing) of devices more secure whilst simplifying the process for the end-user. This greatly improved Bluetooth security, solidifying it's longevity. Luckily, through further improvements in technology, standards, encryption and real-world practices, Bluetooth’s security has improved significantly. Even more luckily, the ways in which Low-energy Bluetooth transmission devices (Bluetooth beacons) are used removes, almost entirely, any security concerns for end-users.

Unlike Bluetooth devices that pair with one another, beacons have no need to capture the Bluetooth MAC address of devices it comes in contact with. Bluetooth beacons have their own unique MAC address that devices identify when they are broadcasting. This practice leaves end-users with far less security concerns.
However, because the beacon broadcasts a MAC address, and openly shares it with feasibly every device which comes in contact with it, they have a far higher risk of being targeted by "You-Know-Who". I am referring to Hackers, of course, not the Dark Lord. They are, however, equally as feared by IT professionals, 'solemnly swearing to get up to no good' and 'stuperfying' operations. For anyone who didn't get any of those references.. Have you been living under a rock? and do yourself a favour and get a library card.

Naturally, there are defences against this. One being, suitably named, Unauthorised Access Prevention. This form of defence makes use of credentials being requested when attempting to access the beacon. Vague usernames and complex passwords can be more than enough to stop the larger majority of “Hackers” - a term used very losely for people who guess passwords. Implementing additional measures such as mechanisms to detect unauthorised authentication attempts and initiating progressively longer timeout periods between authentication attempts can help prevent brute force password attacks.

On that note: Do you have a minute to talk about our Lord and Saviour; a S3cuR3_P@55WoRd. He (or she, or black jesus) didn't die for your sins, he is the first point of defence in a world of stalkers, hackers and all-round douches that try to access your sins. Simple methods of choosing a lengthy password with characters, uppercase characters, symbols and numbers, regular changes and not sharing passwords across different sites prevent your embarrassing emails between your internet girlfriend from going public. That's my 2 cents of gospel for the day, now where were we?

Encryption is another invaluable tool in the belt of a network technician. In the case of Bluetooth beacons, when updating information (on non-wireless beacons) a device still needs to sync using Secure Simple Pairing (the method used to pair phones with one another). This means, if someone were listening to THAT connection, they could mimic the master device’s MAC address and potentially have access to all beacons it syncs with. To reduce the likelihood of this happening, update devices during times in which there is less foot traffic, in a secure place (all devices in one secure room) or using new wireless technology being integrated into newer beacon devices.

The last, and sometimes most overlooked, security measure is Physical security. Choosing appropriate locations in which to house the Bluetooth beacons greatly reduce the probability of attackers physically stealing, tampering or breaking the transmitters. The majority of beacon brands include some degree of adhesion material to allow the beacons to be fixed in hard to reach locations. An added level of physical security may include; encasing the beacons in glass/plastic containers, bolting/locking devices to fixtures or camouflaging to reduce visibility.

<h3>tl;dr</h3>
> * Bluetooth Low-enery is secure for end-users (Us)
> * Steps can be implemented to improve the security of Bluetooth Beacons:
>   * Unauthorised Access Prevention: secure passwords
>   * Encryption
>   * Physical Security
> * Make your password secure or black jesus will find you!

And that's it for security. Thanks for reading and we'll keep you posted!
