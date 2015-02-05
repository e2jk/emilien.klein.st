.. title: FOSDEM 2015 recap
.. slug: fosdem-2015-recap
.. date: 2015-02-05 07:12:38 UTC+01:00
.. tags: fosdem, fosdem 2015
.. category: 
.. link: 
.. description: 
.. type: text

This year was no exception: `FOSDEM 2015 <https://fosdem.org/2015/>`_ was just as fun as previous years.

I did have a car issue (gear stick not responsive) when arriving at the Janson parking on Saturday, which meant missing talks until about noon, but the issue was fixed promptly by the ANWB/Touring, which was a relief. I didn't have a working SIM card in my phone, but thanks to Stappers who lended me a spare one, I was able to get in touch with the ANWB and get this solved promptly.

.. TEASER_END: Read on to see which sessions I attended.

Follows the list of sessions I attended on both days.

Saturday sessions:
------------------

* `Developing FOSDEM Companion <https://fosdem.org/2015/schedule/event/developing_fosdem_companion/>`_ - Christophe Beyls: How to build a modern, user-friendly schedule app for Android.

  FOSDEM Companion is a mobile schedule app for Android, first released for FOSDEM 2014. Its code is open source and designed as a reference implementation for this kind of application. This session will cover the architecture of the app and its building blocks, the motivation behind its features, what's new in the 2015 version and the best practices for designing a modern Android application.

* `Ultra - Smallest. Web server. Evar. <https://fosdem.org/2015/schedule/event/ultra_web_server/>`_ - Steven Goodwin:

  This talk introduces a brand new web server - Ultra. With a binary at just 51K it's small, fast, and encompasses an all-in-memory web server with an in-built NoSQL datastore, a data processing language, SSI, multiple configurations, and logging. If you want to learn basic networking programming, its source is small enough for you to learn from. The talk covers the basic architecture and approach in keeping a small footprint, and breaks down the source into easily understandable blocks.

  The talk covers the history and development of a unique project - one that tells a classic open source story about a developer scratching an itch, and solving a problem he didn't have! It covers the code from 47 lines of C, to 1500 of C++. It also details how the processing language was governed by code re-use, and how the data store uses convention over configuration to work efficiently. It's one of the few projects that is small enough to do serious work, but small enough to be explained line-by-line in a talk! (Although it won't be that direct!)

* `How adblockers work <https://fosdem.org/2015/schedule/event/how_adblockers_work/>`_ - Sebastian Noack:

  There is an increase in popularity of adblockers. Adblock Plus is the oldest and most popular one, with over 50M users. But most people still don't know how an adblocker actually works. In this talk I will attempt to explain how adblocking works, at least how we have implemented it in Adblock Plus.

* `A Whirlwind Introduction to OpenUI5 <https://fosdem.org/2015/schedule/event/openui5_introduction/>`_ - DJ Adams: The Responsive, Enterprise Strength HTML5 Toolkit

  SAP open sourced their HTML5 toolkit that is used as the foundation for all SAP's present and planned UI endeavours. It's responsive, enterprise strength, has a ton of features including full MVC support, a powerful data binding system, declarative view mechanics, support for internationalisation, right-to-left and accessibility right out of the box. And it's great to use, too.

  This lightning talk will take you on a whirlwind tour of OpenUI5: no slides, just code and activity in the Chrome Developer Tools console.

* `Homebrew - The Good, Bad and Ugly of OSX Packaging <https://fosdem.org/2015/schedule/event/homebrew_the_good,_bad_and_ugly_of_osx_packaging/>`_ - Mike McQuaid: Some of the things that Homebrew does well, badly and the special challenges that OSX packagers need to deal with.

  Homebrew is a popular package manager for OSX. We have a relatively unusual contribution and maintenance model and some practices that differentiate us from other package management systems on both OSX and on Linux. This talk will discuss some of the lessons learnt from maintaining Homebrew to facilitate discussion of how we and other package managers can do better.

  The audience for this talk is primarily developers of other package managers and maintainers of Unix distributions. We all do things in slightly different ways so this talk aims to facilitate discussion of what we can do better and how we can work together to minimise repeated work. Audience members will learn about Homebrew, how to encourage more contributions to package managers and how to handle a large number of packages will very few maintainers and time spent.

  The plan would be a 15m somewhat interactive talk with 15m discussion afterwards.

* `codebender: Arduino programing, online <https://fosdem.org/2015/schedule/event/codebender/>`_ - Vasileios Georgitzikis: Learn how to program an Arduino faster and easier, online, using codebender

  Arduino is the favorite programming platform for embedded hardware, especially for beginners, but also for more advanced users who take advantage of its ease of use. We will show how to program more effectively, easily, and in collaboration with others. By using codebender, you can code, compile, and test Arduino code online, take advantage of the ~500 included libraries, and use code available by the community.

  We will show how someone can use Arduino with the power of codebender.

Sunday sessions
---------------

* `First Steps in Receiving Digital Information with RDS/TMC <https://fosdem.org/2015/schedule/event/sdr_rds_tmc/>`_ - Bastian Bloessl:

  The Radio Data System (RDS) is a digital subcarrier on ordinary FM radio broadcasts that is used to convey a bunch of information including station name, time, alternate frequencies, and optionally traffic information with the Traffic Message Channel (TMC) protocol. Given its ubiquity, narrow bandwidth demands, and frequency band, RDS might be a good first digital project for SDR newcomers, extending the 'Hello World' of SDR, i.e., the FM receiver. RDS can be received with very cheap hardware like the RTL-SDR and simple antennas making the technology accessible for everybody.

  In this talk, I will give a short introduction in RDS / TMC and present the current state of the GNU Radio RDS project. Besides the receiving part, we will also have a brief look in the transmit side that allows you to create your own small radio station including RDS and TMC messages. The information is hopefully just enough to whet your appetite and helps to get you started.

* `LuaRocks - fostering an ecosystem of Lua modules <https://fosdem.org/2015/schedule/event/luarocks/>`_ - Hisham Muhammad: Creating the package manager for the Lua language

  This talk will present LuaRocks, the package manager for modules for the Lua programming language. Lua has successful as a scripting language embedded into applications, especially in the gaming industry. However, its "no-batteries-included" design prevented it from getting traction as a stand-alone application language. LuaRocks was created to target this problem. This talk will discuss the particular challenges of developing a package manager for Lua. With this project, we've been successfully fostering an ecosystem of extension modules, improving reuse of Lua code.

* `How to create your own Exchange compatible backend <https://fosdem.org/2015/schedule/event/openchange_rest_api/>`_ - Julien Kerihuel: Dive into the OpenChange REST API

  At OpenChange, we work on offering a portable Open Source implementation of Microsoft Exchange Server and Exchange Protocols. During the past 10 years, we have seen the community growing but not the number of developers. The conclusions were clear. The price to pay to develop on OpenChange was too high: C language only, very complex, too much knowledge required, too much time before you get visible results. We have addressed all these obstacles and will teach you during this talk how to set up the development environment in no time, understand the basics of the OpenChange REST API and leverage its resources and samples to get first visible results in Outlook today.

* `GCompris goes Qt Quick with the help of KDE <https://fosdem.org/2015/schedule/event/gcompris/>`_ - Bruno Coudoin: GCompris is educational software for children 2 to 10

  GCompris is a high quality educational software suite comprising of numerous activities for children aged 2 to 10. It was created in 2000 using the GTK+ graphical toolkit. It is available on different platforms, GNU/Linux, and the proprietary platforms MacOSX and Windows.

  Willing to address the large number of tablet users and to enhance the user experience the choice was made in January 2014 to rewrite GCompris in Qt Quick.

  The presentation will address the following topic:

  -  Project goal and history
  -  Community and commercial. Starting in 2003 a Windows version was created and is distributed under a commercial model while being still Free Software. We will see how and why we decided to do so
  -  Why we selected Qt Quick. This development toolkit is based on Qt and let the developer create dynamic user interface that can run on desktop and mobile platforms
  -  Why we became a KDE project. GCompris has always been a community project, leaving the GTK+ toolkit it does not make sense to develop the new version under the Gnome umbrella
  -  State of the Qt Quick port

* `Mobile == Web <https://fosdem.org/2015/schedule/event/mobile_web/>`_ - Stormy Peters: the best mobile "apps" are on the web

  The next billion people to come online will do so through their phone. If they don't have access to awesome mobile web content, their experience will be controlled by the app ecosystem of the phone they purchase.

  Help them - and all your friends - by making sure that all the websites and apps you create are great mobile experiences. Increase your reach to mobile and make sure that everyone has access to your content by creating a discoverable, responsive, awesome mobile experience on the web.

  Why?

  1) All mobile users have access to the web. Not all mobile users will download an app.
  2) Web pages are more accessible through search.
  3) All users, regardless of their platform, have access to mobile websites.
  4) Nobody is censoring content, nor taking part of the profits, on the web.
  5) Everyone can create mobile web content without needing third party approval.
  6) Your mobile website can easily become an app for mobile platforms.

* `Get ready to party! <https://fosdem.org/2015/schedule/event/get_ready_to_party/>`_ - Larry Wall:

  The last pieces are finally falling into place. After years of design and implementation, 2015 will be the year that Perl 6 officially launches for production use.

  In this talk, the creator of Perl reflects on the history of the effort, how the team got some things right, and how it learned from its mistakes when it got them wrong. But mostly how a bunch of stubbornly fun-loving people outlasted the naysayers to accomplish the extraordinary task of implementing a language that was so ambitious, even its designers said it was impossible. Prepare to be delightfully surprised.

* `Introducing SILE: A New Typesetting System <https://fosdem.org/2015/schedule/event/introducing_sile/>`_ - Simon Cozens:

  SILE is a system for creating beautiful printed documents. It borrows extensively from TeX, but brings some of TeX's ideas into the 21st century with frame-based layouts, native support for Unicode, PDF, Opentype and XML processing, and extensibility and programmability in a modern, high-level language.

  Hello, my name's Simon and I wrote a typesetting system by mistake. Then I found out that people needed to use it. Come and hear about how SILE got started, how it's developed since then, and how you can use it to make printed documents.

  SILE is a typesetter designed to meet the needs of a particular translation community, with an emphasis on extensibility and layout flexibility. Existing solutions (TeX and friends) were not able to provide the required features in these areas, and so translators and publishers have been looking around for an alternative solution for many years. SILE takes a lot of inspiration from TeX, but updates many of its ideas to match the changes in the software ecosystem in the past 35 years.

  SILE does not, however, aim to be a replacement for TeX, but is a separate system for document layout and rendering. Because of this, functionality which is a challenge for TeX users - for instance, laying out text on a grid, or magazine-style frame based layouts - becomes very easy in SILE. SILE is written in an interpreted language, so parts of the system's operation, including core typesetting algorithms, can be redefined at run time.

  SILE is also designed to meet the realities of today's data processing. Documents these days are often prepared in authoring software and stored in XML format. This applies both to document-specific XML DTDs, such as DocBook and the Text Encoding Initiative, and also tagged text database formats, such as those for storing linguistic and other annotation data such as the LIFT standard for dictionary data and the USX format used by translators. SILE classes can define processing expectations for XML elements, which means that XML files can then be read in and typeset directly. We will look at examples of complex book layouts driven by XML data sources.

* `Free and open-source software for medical imaging <https://fosdem.org/2015/schedule/event/medical_imaging/>`_ - Sébastien Jodogne: Bringing technological independence to hospitals

  The amount of medical images that are generated, analyzed and exchanged by hospitals is dramatically increasing. Medical imaging is indeed the first step to the treatment of more and more illnesses, such as cancers or cardiovascular diseases.

  In turn, the data management of clinical images and the administration of the computer network of a medical imaging department imply continuously growing technological challenges. Tasks such as autorouting between imaging modalities, exchanging data between clinical departments or hospitals, or anonymizing images are still hard to achieve in practice. This is a direct consequence of the lack of interoperability software that could bring technological independence to hospitals by creating low-cost gateways between proprietary ecosystems.

  In this talk, I will explain the pains behind modern medical imaging, from the perspective of the hospitals. The DICOM standard will be introduced, together with free and open-source software supporting this standard.

  I will then put emphasis on the free software Orthanc, a lightweight, versatile DICOM server. Thanks to its REST API and to its Lua scripting engine, Orthanc is primarily conceived as a central, robust building block to bring technological independence to clinical departments by automating their very specific imaging flows. Orthanc was nominated at the Zénobe Award 2013 for social innovation.

  Table of Contents

  -  Introduction: Imaging flows for radiology and radiotherapy
  -  DICOM and the pains of medical imaging
  -  Free and open-source software for DICOM
  -  Orthanc:

     -   Description and architecture
     -   Automating imaging flows with Orthanc
     -   The present and the future of Orthanc
  -  Conclusion

* `Leihs, the leading free equipment booking system <https://fosdem.org/2015/schedule/event/leihs_booking_system/>`_ - Ramón Cahenzli: It took us eight years to get it right. What we learned about being a FOSS project.

  leihs is probably the most widely used free inventory management and equipment booking system. Started at the Zürich University of the Arts (ZHdK) in order to manage their own sizeable pool of equipment, it quickly became clear that other organizations have exactly the same problems. It now made sense to release leihs under the GPL. In this talk, Ramón talks about mistakes made, challenges and things learned in the last 8 years of managing a free software project from within a government organization.

  leihs began as a small internal project, written when Ruby on Rails was still young and considered cutting-edge technology. Deployment was messy and unreliable, the code had to be changed significantly with every Rails upgrade and even Ruby itself had a few pretty bad bugs at the time. But we stuck with it and rewrote the core and most of the interface for version 2.0. This was the initial version of leihs released under the GPL. Later GitHub came along, and so leihs went there. With GitHub came some popularity, and the project really took off when we redesigned the user interface yet again, this time with real interaction designers.

  The main takeaways from eight years of free software development:

  -  If you choose a technology that's immature, things get very exciting. But be prepared to rewrite your code again and again as the foundation you built on shifts.
  -  Don't add internationalization at a later time, do it from the start. One of my biggest regrets is not going with a complete German/English interface from the start.
  -  Make sure your management understands what it means to do free software, and that you can't just do your own thing. Be part of your own community. Comment on bug reports, write change logs, have a project blog -- if you treat the community as if it isn't there, it will soon not be there anymore.
  -  If you're doing something with a GUI and don't have interaction- or UX people, hire professionals to do it for you.

  leihs has now been installed at some very important universities and colleges in and outside Switzerland. I want to encourage anyone who is paid with taxpayer money to develop free software and to politely urge their management into letting them do it. But I don't want to create the illusion that it will be easy.

See you again next year, hopefully!
