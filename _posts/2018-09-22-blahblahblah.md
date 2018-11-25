---
layout: post
title:  "Intro to Protocol Buffers 1"
date:   2018-09-22
banner_image: Desk.jpg
tags: [Java, Protocol Buffers, Arthur Miller]
---

# Intro to Protocol Buffers 1 
While protocol buffers have some inherent disadvantages such as a possibility of not being supported by some languages and the data not being directly accessible (as the data gets serialized), the overwhelming advantages of protocol buffers should become quite apparent in this post as the case gets built for its use as we explore why and how to leverage this pretty awesome technology.
<!--more-->
## A Really Quick Background on Data
Until this point, data has been created, passed, and processed/parsed using CSV's, Relational Table Definitions, or JSON (JavaScript Object Notation). With CSV files, data is easy to read, in many cases easy to parse and is generally intuitive. There are some distinct disadvantages with CSV's, as datatypes have to be inferred and are not guaranteed and parsing becomes more complicated when data contains commas. Relational Table Definitions have some advantages over CSV's in that the Relational Table Definitions are fully typed, and the data fits into a table. Disadvantages here include the data having to be flat, and data definitions are different for each database. JSON gets used pretty extensively by most developers as JSON data can take almost any form (such as arrays and nested elements), is widely adopted across the web, can be read by most languages, and can be easily shared over a network. Although JSON has become very popular, there are still some significant disadvantages such as no schema enforcement, a tendency to be very large (taking up an unnecessary amount of bandwidth on a network), and no inherent ability to include comments, metadata, and documentation. Now, protocol buffers step into the light providing clear advantages over the previous formats as:
* Data gets fully typed. 
* Data is compressed (saving CPU usage).
* There is a defined schema (in the form of a .proto file) to generate code or read data.
* Data can be read by all major languages (Java, C#, Go, Python, JavaScript, and many others).
* A schema can evolve safely.
* Protocol buffers are 3-10x smaller in bandwidth and 20-100x faster to process than previously mentioned formats.
* Protocol buffers take advantage of code generation. 


## Getting Started with Protocol Buffers
Initially created by Google, protocol buffers are currently implemented on almost every Google internal application. Stats can be found online that estimate Google to have around 48000 protocol buffer message types and over 12000 .protofiles. Why mention this? Well, the idea is that if Google has developed this technology and is currently implementing it to reduce bandwidth and speed up processing time, it is likely to be able to assist any other company in doing the same, especially in the areas of distributed systems/service-oriented architectures.  


---
Until this point, data has been created, passed, and processed/parced using CSV's, Relational Table Definitions, or JSON (JavaScript Object Notation).
With CSV files, data is easy to read, in many cases easy to parse, and generally makes sense pretty easily. There are some disctict 

Prow scuttle parrel provost Sail ho shrouds spirits boom mizzenmast yardarm. Pinnace holystone mizzenmast quarter crow's nest nipperkin grog yardarm hempen halter furl. Swab barque interloper chantey doubloon starboard grog black jack gangway rutters.

Deadlights jack lad schooner scallywag dance the hempen jig carouser broadside cable strike colors. Bring a spring upon her cable holystone blow the man down spanker Shiver me timbers to go on account lookout wherry doubloon chase. Belay yo-ho-ho keelhaul squiffy black spot yardarm spyglass sheet transom heave to.

Trysail Sail ho Corsair red ensign hulk smartly boom jib rum gangway. Case shot Shiver me timbers gangplank crack Jennys tea cup ballast Blimey lee snow crow's nest rutters. Fluke jib scourge of the seven seas boatswain schooner gaff booty Jack Tar transom spirits.

## Concept

Prow scuttle parrel provost Sail ho shrouds spirits boom mizzenmast yardarm. Pinnace holystone mizzenmast quarter crow's nest nipperkin grog yardarm hempen halter furl. Swab barque interloper chantey doubloon starboard grog black jack gangway rutters.

Deadlights jack lad schooner scallywag dance the hempen jig carouser broadside cable strike colors. Bring a spring upon her cable holystone blow the man down spanker Shiver me timbers to go on account lookout wherry doubloon chase. Belay yo-ho-ho keelhaul squiffy black spot yardarm spyglass sheet transom heave to.

Trysail Sail ho Corsair red ensign hulk smartly boom jib rum gangway. Case shot Shiver me timbers gangplank crack Jennys tea cup ballast Blimey lee snow crow's nest rutters. Fluke jib scourge of the seven seas boatswain schooner gaff booty Jack Tar transom spirits.

## Festival Site

Prow scuttle parrel provost Sail ho shrouds spirits boom mizzenmast yardarm. Pinnace holystone mizzenmast quarter crow's nest nipperkin grog yardarm hempen halter furl. Swab barque interloper chantey doubloon starboard grog black jack gangway rutters.

Deadlights jack lad schooner scallywag dance the hempen jig carouser broadside cable strike colors. Bring a spring upon her cable holystone blow the man down spanker Shiver me timbers to go on account lookout wherry doubloon chase. Belay yo-ho-ho keelhaul squiffy black spot yardarm spyglass sheet transom heave to.

Trysail Sail ho Corsair red ensign hulk smartly boom jib rum gangway. Case shot Shiver me timbers gangplank crack Jennys tea cup ballast Blimey lee snow crow's nest rutters. Fluke jib scourge of the seven seas boatswain schooner gaff booty Jack Tar transom spirits.
