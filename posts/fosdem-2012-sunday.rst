.. description: FOSDEM 2012 - My Sunday's schedule
.. tags: fosdem
.. date: 2012-02-09 19:15:06 GMT
.. title: FOSDEM 2012 - My Sunday's schedule
.. slug: fosdem-2012-sunday
.. type: text

This is the list of talks/presentations I attended on the Sunday of FOSDEM 2012.

Each talk contains a link to its FOSDEM page, where you can find extra links on the topic or the presenter.

* `Asterisk 10: New Features, New Testing <http://fosdem.org/2012/schedule/event/asterisk_10>`_ - Matt Jordan: Asterisk 10 added many new features, and includes substantial automated testing.

  Asterisk 10 was recently released, and incorporates many new features, including nearly unlimited support for codec formats and sample rates, wideband audio conferencing, and much more. In addition, the Asterisk project team has built a large suite of unit and functional tests that are now run against each Asterisk release.

  This talk will cover the major new features of Asterisk 10, and also cover how the Asterisk testsuite is developed and used to improve the code quality of each release.
* `debtags.debian.net reloaded! <http://fosdem.org/2012/schedule/event/debtags_reloaded>`_ - Enrico Zini: I have just finished redesigning the Debtags website, consolidating a 9 years long history of bringing categories to a large and complex distribution like Debian.

  There is more to Debtags than meets the eye: interesting library science concepts, anonymous submissions, an efficient review workflow, a fully automated tagging engine, dynamically generated tagging hints, fancy tag search algorithms.

  On top of that, there is not much that is Debian-specific in the new codebase, so if you are interested in implementing categories on your distribution of choice, this could give you quite a head start.
* `From zero to VoIP provider in 15 minutes <http://fosdem.org/2012/schedule/event/zero_to_voip_provider>`_ - Andreas Granig: By using the sip:provider Community Edition, an open source VoIP soft-switch leveraging powerful and widely used open source components, we will in 15 minutes create a VoIP deployment from scratch in order to provide future-proof voice and video communication services, preceded by an introduction into the system architecture.

  There are various open source components (e.g. Kamailio, Asterisk, Freeswitch and Sems) available to build a reasonably sized VoIP service from scratch. There are also some administrative web interfaces (e.g. Webmin, Siremis), allowing you to control the most basic things in such a system. And in order to escape the lab stage, you can even put an open source billing engine (e.g. a2billing) into the mix. Since your customers would like to manage their accounts and features, you will then develop a customer self-care interface as well. Time to market: at least two months. Feature set: basic. Service quality: uncertain at best. Future-proof: not.

  There is a solution to that though. During this talk, I will present how to deploy a solid VoIP Provider platform from scratch in just a few minutes, using the Sipwise sip:provider CE (SPCE) v2.4. The SPCE is a free and open source soft-switch based on Kamailio, Sems and Asterisk, providing fully featured and seamlessly integrated administrative and customer-self-care web interfaces, SOAP/XMLRPC provisioning APIs, a flexible rating engine and a huge load of subscriber features like conferencing, voicemail, call forwards, block lists etc. On reasonable hardware, the SPCE can serve 50k subscribers and more.

  As an introduction, I will outline the basic elements involved in a VoIP deployment. Then I will dive into the architecture of the SPCE, showing the building blocks and their interaction. Finally, I am going to do a live presentation on how to configure an SPCE instance for a typical deployment.
* `29,000 packages in 24 hours - Releasing Debian <http://fosdem.org/2012/schedule/event/releasing_debian>`_ - Neil McGovern: This talk is to give an overview of what is involved in releasing Debian. It will cover policy, tools and an insight into what it takes to release the largest linux distribution.
* `Enhancing FreePBX with Adhearsion <http://fosdem.org/2012/schedule/event/adhearsion_freepbx>`_ - Luca Pradovera: Demonstration of building applications with the Adhearsion voice application development framework. 

  Many open source hackers see the allure of building applications that integrate with the telephone network. However layers of industry jargon, proprietary technology and arcane knowledge lead many to believe that telephony is "hard." Adhearsion will change their minds. The Adhearsion project is an open source voice application development framework, the first of its kind in the open source world. In this talk we will build several working voice applications and demonstrate how to integrate them with existing PBX installations. Along the way, we will discuss voice application design and show how to avoid common pitfalls.
* `A real Skype alternative using standards compliant FLOSS <http://fosdem.org/2012/schedule/event/skype_alternative_floss>`_ - Emil Ivov: The University of Strasbourg has built a 'Skype replacement' for ~60,000 users using open source standards and software.

  A few years ago the French Ministry of Education and Research, issued a memo that strongly advised against use of Skype in universities and research centers. Security and excessive bandwidth consumption were among the main concerns.

  In practice however, the directive has been rarely applied for one major reason: (perceived) lack of alternatives.

  Therefore, in the beginning of 2011, the University of Strasbourg has started an effort that aims to propose an actual Skype alternative to both its faculty and students (~60.000 users). The project started with a number of extensions added to the Jitsi project in order to add support for features such as GTalk interoperability for example.

  It then continued with a deployment of the actual network using exclusively FLOSS projects such as Openfire, Jinglenodes, FreeSWITCH/Asterisk, TurnServer and others.

  The talk will also cover aspects such as NAT traversal with ICE and JingleNodes, redundancy, security and confidentiality.
* `PMH: Home Automation made right™ <http://fosdem.org/2012/schedule/event/phm_home_automation_made_right>`_ - Vasilis Georgitzikis: PMH is a home automation system built from the ground up to be easy to use, modular and as open as possible. Our software and hardware are completely open source, with source code, schematics and CAD files available online. PMH consists of 3 layers. The hardware layer, the überdust layer and the apps.

  In the hardware layer, we use a wireless sensor network with sensor nodes and actuators that communicate with each other using the low-power IEEE 802.15.4 protocol and with a computer that acts as the main controller. The wireless sensor network consists mostly of Arduino nodes which control lighting, heating/air conditioning and electrical devices while at the same time using sensors to measure things like power consumption, temperature, light, movement, air quality etc.

  Überdust is responsible to bridge the other two layers by capturing and saving the data from the WSN to a central database, and provide easy to use interfaces (i.e. REST, Web Sockets) to the application layer. This way, applications can get sensor values from the wireless sensor nodes, and control the nodes accordingly.

  In the application layer, we have developed a web and smartphone application that gives users the ability to remotely control the system, view the current status of the various sensors and set automated behaviors such as turning on the lights when there are people in the room, sending a notification to the user's smartphone when someone enters your room, turning on the water boiler on predefined times, etc.

  Last but not least, due to the modular and open source nature of our system, its easy to add additional data providers in the hardware layer, such as an arduino with additional sensors, or even your computer and smartphone (i.e. your smartphone's accelerometer, the status of your server). It's just as easy to develop your own apps using our APIs, and extend the capabilities of the system to meet your own needs (remote controlled BBQ anyone?)
* `Debian Secrets - what I wish I knew before joining Debian <http://fosdem.org/2012/schedule/event/debian_secrets>`_ - Lucas Nussbaum: Debian is usually advertised as a volunteer project with a subtle mix of democracy and do-ocracy. While this is correct, implementation details are mostly undocumented, and it is often difficult for prospective or relatively new contributors to really understand the inner workings of the project.

  This talk will detail some useful lessons, and also some secrets about Debian learned over the years. It is hoped that it will be helpful to people willing to get things done in Debian.
* `Freedom, Out of the Box! <http://fosdem.org/2012/schedule/event/freedom_ootb>`_ - Bdale Garbee: Update on activites at the FreedomBox Foundation

  FreedomBox is a personal server running a free software operating system and free applications, designed to create and preserve personal privacy by providing a secure platform upon which federated social networks can be constructed. Eben Moglen articulated the need for FreedomBox in his 2011 FOSDEM keynote, this presentation is a status update on the work done to turn Eben's vision into reality over the past year. Software for FreedomBox is being assembled by volunteer programmers around the world who believe in Free Software and Free Society, with Bdale coordinating development of a reference implementation on behalf of the non-profit FreedomBox Foundation.

The descriptions of the talks come from the FOSDEM site.

