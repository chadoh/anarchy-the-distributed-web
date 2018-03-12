Anarchy/The Distributed Web
===========================

A technical talk about the experience of building a distributed app, and where distributed apps could take us in the future.

The slides, contained in `index.html`, are built using [remarkjs](https://github.com/gnab/remark), which allows you to write your slides in nice simple markdown and turns them into beautiful, browser-powered slides complete with speaker notes. Read its readme to find out more about it.

There's lots of custom styling on the slides, found at the top of the `index.html` file.


Talk Outline
============

0. Prelude: consider asking a question or posing a thought-provoking idea. Maybe one of these:

    * How many kinds of monarchy are there? How many kinds of democracy are there?
    * What changed human society more fundamentally, democracy or the internet?
    * Slide: anarchy symbol. Ask: when you hear the word “anarchy,” what do you think of?

1. Chad: The rebirth of CitrusLabs: an opportunity to build a Distributed App

2. Gorka: What is a dapp? 

    Possibly explain with an analogy to current, centralized apps:

      * HTTP; client-server model
      * Data storage/databases
      * File storage
      * Identity

    Then explain how each of these would work, theoretically, in a distributed fashion. Possibly also introduce idea of append-only ledgers/immutable data modeling.

3. Chad: "Anarchy" as "chaos": Current distributed web ecosystem

    * JS fatigue as a walk in the park
    * 2017, "Year of the ICO", oversold distributed technologies as ready-for-the-mainstream
    * Actual state of ecosystem is more like internet in early 80s, or possibly earlier than that
    * All existing protocols are alpha-stage at best
    * We thought we would have a good map of the ecosystem after 3 months; we were wrong
    * Many competing protocols, no clear winner: 
      1. HTTP equivalent: IPFS, Dat, Substrate, Tribler, ...
      2. Identity management: MetaMask, Blockstack, Keybase, ...

4. Gorka: The dapp stack we chose; how Thicket works

    * Where we were headed
    * Full in-browser experience; no downloads needed
    * No identity right now
    * IPFS for data storage/transmission
    * YJS for CRDT

5. Chad: "Anarchy" as political philosophy: the new adjacent possible for societal organization; how distributed tech helps the biggest diffusion of power since not the invention of the web, but since the invention of democracy

6. Gorka: Mad science; let's try it out
