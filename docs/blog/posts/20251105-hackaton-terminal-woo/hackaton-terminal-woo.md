---
date:
  created: 2025-11-05
categories:
  - events
authors:
  - mlarooij
title: "OpenGov Lab at the Hackaton Terminal Woo: 'Zoek en Verrijk'!"
description: On Friday, October 31st, and Saterday, November 1st, the Ministry of the Interior and Kingdom Relations and programme Open Government (Programma Open Overheid) organised a hackaton to improve the internal process of responding to Woo-requests. David, Damiaan, Maik and Jos (PhD student @ Utrecht University) represented the OpenGov Lab as one of the ten teams that participated in the event!
image: at-work.jpg
---

# OpenGov Lab at the Hackaton Terminal Woo: 'Zoek en Verrijk'!

On Friday, October 31st, and Saterday, November 1st, the Ministry of the Interior and Kingdom Relations and the program Open Government (Programma Open Overheid) organised a hackaton to improve the internal process of responding to Woo-requests. David, Damiaan, Maik and Jos (PhD student @ Utrecht University) represented the OpenGov Lab as one of the ten teams that participated in the event!

![The team, very focused, at work while the time was running out ](at-work.jpg?w=768){ loading=lazy }
*The team, very focused, at work while the time was running out*

<!-- more -->

The hackaton kicked of with talks from [Martijn Aslander](https://martijnaslander.nl/) and [Guido Enthoven](https://www.imi.nu/over-imi). The location was the impressive 'Fokker Terminal' (an old aircraft hangar):

![The terminal](terminal-front.jpg?w=768){ loading=lazy }

![Every team seated in a 'circle'. We were in the bottom left, but probably were out getting coffee...](terminal-overview.jpg?w=768){ loading=lazy }
*Every team seated in a 'circle'. We were in the bottom left, but probably were out getting coffee...*

## The problem to solve
In a little bit more than 24 hours, we had to built a complete and working demo and create a four-minute pitch to convince the jury of our idea. We spent most of Friday afternoon brainstorming about possible solutions. The most challenging part turned out to be to turn off our academic thinking patterns and think like a requester or government official. Fortunately, our mercenary [Jos Zuijderwijk](https://joszuijderwijk.nl/) from Utrecht University proved his worth by keeping us structured and on the right track. Building on practical insights of our appointed mentor, [Tim van Alten](https://www.juridealist.nl/over-mij/), we discovered that 58% of all Woo-requests result in an objection, mostly because the 'search was incomplete'. This can happen, for example, if:

- The citizen discovers a reference to another document that is not in the published documents
- The citizen knows or suspects that more documents are available in the organisation
- The citizen claims that the search was too narrow: for example he/she asked for information about multiple projects but got only one

For example (if you speak Dutch):

![An example objection](objection-example.png?w=768){ loading=lazy }

## The solution
Our final product, 'Zoek en Verrijk' (search and enrich) was an extension of the already existing tool 'Zoek en Vind' (search and find) that is currently in use by the Dutch government. The goal of the product is to prevent objections by finding the possible 'missing' documents in advance. To do this, we use the documents that are a result of a first search query to aid the government official in his search process in two ways (based on techniques from science, we're scientists after all!):

- **Query extension**: we leverage an LLM to find relevant other terms in the documents that are also relevant for the original Woo-request
- **Reference extraction**: we leverage an LLM to extract possible references to other documents

In this way, the official can iteratively search for all the relevant documents. We believe that it is very important to let the official stay in control instead of leaving it all to AI, as such the official has the option to keep or delete the proposed query terms before searching again. This results in an iterative search process, which also benefits transparency - our tool also explains why it thinks that terms are relevant and enables reconstructing and justifying the search process.

## The pitch
In four minutes, we had to pitch and demo our idea to the jury. This was scary for scientists, as we like to go in depth about our technologies and solutions. Fortunately, all went well, and Jos and Maik seemed like a hip-hop duo on stage.

![Dr. Jos and MC Maik giving the demo](hiphop-duo.jpeg?w=768){ loading=lazy }
*Dr. Jos and MC Maik giving the demo*

In our tool, the government official first uploads the original Woo-request and then starts by supplying some basic search terms. This results in a list of documents, in our demo straight from our live database and search engine [WooGLe](https://woogle.wooverheid.nl). The official has the option to search for additional terms (query expansion) or references (reference extraction), which get added visually to the search query. The official is in control and has to choose which of the recommended terms is used for the next search iteration.

![A screenshot of our tool 'Zoek en Verrijk'](screen-demo.png?w=768){ loading=lazy }
*A screenshot of our tool 'Zoek en Verrijk'*

During the pitches, we didn't take home the trophy, but we did manage to stay true to ourselves in applying "old" IR research (query expansion and reference extraction) to a relevant problem! And most of all, we had fun and grew as a team!

## Photo gallery

![A surprise visit of the Dutch minister Frank Rijkaart and CIO Rijk Art de Blaauw](minister.jpg?w=768){ loading=lazy }
*A surprise visit of the Dutch minister Frank Rijkaart and CIO Rijk Art de Blaauw. Maik thought that everyone was going to cheer -> photographer chose this picture over all the normal ones -> little bit of shame that this is the press picture of us with the minister*

![The organizer of the hackaton, Marc Minnee, showed lots of energy!](jumping-marc.jpg?w=768){ loading=lazy }
*The organizer of the hackaton, Marc Minnee, showed lots of energy!*

![At work](at-work-1.jpeg?w=768){ loading=lazy }
![At work](at-work-2.jpeg?w=768){ loading=lazy }
![At work](at-work-3.jpeg?w=768){ loading=lazy }
![At work](at-work-4.jpeg?w=768){ loading=lazy }
*Some pictures, taken by David, of us at work!*

![Damiaan was the only real hacker to spend the night at the Fokker Terminal](sleep.jpeg?w=768){ loading=lazy }
*Damiaan was the only real hacker to spend the night at the Fokker Terminal*

![All participants](everyone.jpg?w=768){ loading=lazy }
*All participants, organizers and some special guests of the hackaton! Can you spot us?*

The aftermovie and more pictures of the whole event are available [here](https://ecp.nl/terugblikhackathonterminalwoo/#fotoimpressie)!