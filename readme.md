![](https://www.lozano-hemmer.com/image_sets/33_questions_per_minute/monterrey_2019/33_questions_per_minute_monterrey_2019_my_505A7543.jpg)

# Best practices for conservation of media art from an artist’s perspective

[RAFAEL LOZANO-HEMMER](http://lozano-hemmer.com) · SEPTEMBER 28, 2015


Dear colleague,

For most artists I know “Art conservation” is a troubling affair: we are already too busy maintaining operations as it is, we think of our work as a “living” entity not as a fossil, we are often unsure if a project is finished, we snub techniques that may help us document, organize or account for our work as something that stifles our experimentation and creative process. In addition, especially when we are resentful that institutions are not collecting and preserving our work in the first place, we reject the whole concept of an Art collection, —agreeing with critical historians for whom collecting and preserving contemporary Art represents an obsessive-compulsive vampiric culture of suspended animation and speculation that is grounded in a neo-colonial, ostentatious, identitarian drive: Nietzsche’s “will to power” mixed with Macpherson’s “possessive individualism”.

For this text let’s assume you are already at peace with the contradiction that is conservation: you are now interested in both creating the work and overseeing its death or zombiefication. Perhaps despite being a staunch democratic socialist you now have your own Art collection. Or maybe you have met a few collectors who take risks with you, acquire your work and help keep your studio afloat financially. Most importantly, especially if you are an insecure megalomaniac like me, you don’t want to disappear from history like so many great artists who are not collected by important Museums.

So here we are, thinking about the topic of conservation in media art. As you know, there is a plethora of existing initiatives to preserve media artworks, but these are always from the perspective of the institutions that collect them. While most institutional programs include excellent artist-oriented components like interviews and questionnaires, the programs are all *a posteriori*, almost forensic, as they look at the work in retrospect, as a snapshot of time.

This text is written to outline what artists may choose to do on the subject in order to i) simplify our life in the long run, ii) generate income, and iiii) take ownership of the way our work will be presented in the future. I welcome variations, additions and comments. Yes, it is absolutely unfair for the artist to have to worry about conservation of their work. Now let’s get on with it.

## BEFORE MAKING
- Mistrust anyone who has a “method” for conservation of Media Art. Anyone, such as myself, who offers a set of rules is someone who is not considering the vast range of disparate experiences, methods, constraints and dependencies that can arise even within the work of a single artist. All we can do is suggest a bunch of tips, wait for an artist to prove those tips useless, and then review the tips. 

- Study instruction-based art, in particular Moholy-Nagy “Construction in Enamel 2”, his 1923 painting reportedly ordered over the telephone, and then study the instructions of established artists who pushed and are pushing the boundaries of the art of instructions like Sol LeWitt, Felix González Torres and Tino Seghal. Citing these precedents, and Duchamp of course, will immediately relax the concerns that may arise with your own work’s materiality because this discussion already has been happening in the artworld for a hundred years. 

- Study precedents of technological art. I find that underlining connections between my work with historical experimental traditions is much more productive (and honest) than pretending what I do is “new”. Quote meaningful precedents that allow the collector to contextualize your work. For example, I often cite the pioneering use of radio broadcast technology by the Estridentista poets in Mexico in the 1920s, or the first use of neon lighting by Gyulia Kosice in 1946, or the first use of a live video feed in art installation by Marta Minujín in 1965 (50 years ago! How can we pretend what we do is “new” media?). 

- Decide if the work you are about to make will be a one-off ephemeral performance, a computer virus that is meant to multiply in ways you cannot control, a happening that is so site- and time- specific that it can never be owned, restaged or reproduced. If you decide this is the case then do not ever think about conservation, not once, and work with reckless abandon with the certainty that the death of your creation may be the highest form of beauty and experience. Some voyeur, flâneur, dilettante, opportuniste (or other person who can be described with a French word) will try to capture your piece and sell it or get a PhD, but really all that does is say “you had to be there”. If on the other hand you are interested in conserving the specific work you are making right now then read on.

## WHILE MAKING
- Keep a notebook and/or electronic document where you put any sketches, prototypes, parts lists, bits of research on the project.

- Work in any development platform you feel is best for the project or for you, but if you have a choice always go for open source tools. At my studio we have often used closed commercial systems, such as “FaceAPI” for face recognition and “Shout3D” a proprietary online 3D API, only for the companies to go bankrupt or orphan the software leaving us with the task to re-engineer the work with more open equivalents (OpenCV in one case and Google Earth in the other).

- Consider using versioning systems, like Git. These allow your software projects to be traceable incrementally and they are a great repository for fundamental information on how a project evolves. Of course code can and should have comments to help follow the code, but Git gives conservators a more global view. In my studio we are only now starting to use Git but I really wish we had started earlier. Versioning is important also in schematics, prototypes and manuals. In fact the whole idea of Versioning can be applied to the artwork itself as suggested in the next section.

- Your software is your “score”, the fundamental instructions that create your work, so back it up! At my studio we have a less than stellar system, which is basically a central repository of files in a drive which gets mirrored to an identical drive that is offsite. I also run Apple’s time machine in my laptop to two drives: one at the studio and one at home. I do recommend a cloud-based solution as it can scale up, is (almost) always available and is cost-effective; however, you do need to feel comfortable that a corporation has your data (they always do anyhow) and that you can continue paying monthly fees, which is a big if. Some Museums are starting to have dedicated servers to hold all of their software collections, in the future all Museums will have to have this kind of data repository and conservation will be very linked to IT. If you keep your own server with all your data this may eventually also be co-located at a place for archives such as a particularly forward-looking library.

- As you work, say on a complex installation with hardware, software, manufactured and found components, prepare a “Bill of materials” (BoM), which is basically a list of all components of a piece. List each separate component, writing its brand and model, its function, the URL for information, and a small picture.

- Next to each item in your BoM, write whether the element is replaceable or irreplaceable. An irreplaceable element is for example a Nixie tube that you feel is crucial to the look or functioning of the final piece. If future conservators can’t find an exact replacement the piece should have an honourable death. A replaceable element is everything else; but for every replaceable element there should be notes on what is acceptable, e.g. “this motor can have any specification so long as it fits in the cavity and it can spin the mechanism 5 times a second” or “this screen can be any CRT, LCD, LED, OLED or other technology provided it is between 15 and 17 inch diagonal, has a brightness of around 500 nits and can show XGA resolution” or “this cover is made of acrylic but it can be changed for glass so long as it is tempered and can stand the vibration, please do not use polycarbonate as that is not transparent enough”.

- When choosing hardware, try to limit any moving parts as much as possible, these are the parts that tend to fail most over time. An example is using solid state rather than spinning platter hard disks or heat sink cooling instead of fans. Another example is using a solid-state relay instead of a contact switch. A final example is choosing a wide-angle camera with virtual pan and tilt using region of interest rather than a motorized pan/tilt camera.

- If you have a choice, use “off the shelf” components that are abundant. At my studio we developed our own computer vision tracking systems using industrial cameras for 15 years but now we have moved to Microsoft Kinect2 whenever possible as these are readily available. Another example is microcontrollers, as my studio now mostly develops with Arduinos, which are widespread, open and friendly. Your own developed systems of course should be used if they deliver better results, but then you need to document those appropriately.

- Make global choices in your procurement. For example, choose gear that can function in a range of voltages 100-240V ideally with auto-switching circuitry; or if you are Canadian never use Robertson screws despite how great they are, as no one outside of our proud country has drill bits for this screw head. All your measurements should be metric and all your notes in English (yeah, I said that).

- Program an “Idle mode” and/or an automatic shutdown for your piece. Collectors sometimes just leave a piece operating while they go on a holiday for two months. You need to detect if no one has interacted with the piece for a certain time for it to go into an Idle state that stops or slows down motors, shuts down or dims displays, and in general protects the piece. An auto shutdown is another way to save the piece unnecessary cycles, but ensure that you have a programmable power bar so that all hardware is turned off in the right sequence.

## AFTER MAKING
- Make a video of the project, ideally with you speaking over it and explaining proper functioning. If you are shy then get someone to interview you.

- Install the project in a variety of computers, operating systems and/or devices and test for any SW or HW dependencies. Note these very carefully in a “Read Me” document that is in a way a version of the BoM for hardware. Bundle the Read Me file with installers for every single item in the list. For example include operating system, DirectX, any graphics drivers, APIs, programming environments, etc.

- Prepare one or several flash drives with all the source code for your project, including firmware, binaries, media assets, schematics, 3D print files, EVERYTHING. Then add all the installers for the dependencies from the previous point. These flash drives are meant to be like a time capsule that hold all the instructions required to reproduce the work. Do include a document that explains that they should make a backup copy of the contents of the flash drive and ensure the integrity of the data from time to time.

- Write a manual with the following parts: i) a “meta” narrative describing the key concepts and elements of the piece and how it works; ii) a detailed set-up procedure, including pictures of example installations, wiring diagrams, museographic notes such as desired lighting or acoustic conditions, sample layouts showing what is and is not allowed; iii) maintenance section on how to clean the piece and turn it on and off; iv) preservation section with the Bill of materials, all schematics, comments to the code.

- Set your computers to perform uninterrupted for a long time. Ensure you are not defeating fans so it is cooled properly, no screen savers, disable automatic software updates for operating system and java for example, no virus checkers, monitor temperature inside boxes or enclosures, stop all notifications, stop all login passwords, etc.

- Prepare a toolkit with any drill bits, special tools, adapters and with spares of components that you think are most hard to come by. 

## DEALING WITH A COLLECTOR
- Take the video, the flash drives, the manual, the toolkit and the spares and make a BOX. Give the box to the collector explaining how important it is and warn them that replacing it will cost $750 (or choose a number that is profitable). Many collectors will quickly lose this box. When they come to you asking for a replacement make a buck for godsakes. 

- Explain the concept of digital copy to your collector. Most do not understand that an original file is identical to a copy. And if they do, they are so completely absorbed with the aura of authenticity that I have heard of artists having to destroy a digital file once they print copies of a digital picture. This is absolutely absurd and unnecessary for work like mine (and yours). If a collector buys an image from me I want to give her the Tiff file with colour looking tables and printing instructions so that she can reproduce the work in the future when the UV rays wash the colours out or when a child takes a knife to the image. So long as you copy the data from the flash drive onto other future media, as USB dies, the work that you own will be perfectly reproducible, like the instructions of a Sol LeWitt or a Gonzalez-Torres. In this sense, digital prints are orders of magnitude easier to preserve than any other print. 

- Once the collector understands that they have the digital files needed to reproduce most or all of the work they might panic asking how their investment is protected from reckless reproduction. The answer is centuries old: with a signature. For each of my pieces I give a certificate of authenticity that is the tradable commodity of my work. In my case, the certificate is an A5-sized doubly anodized aluminium ingot that shows the details and picture of the work. I sign the certificate by hand, adding the edition number. The certificate is also engraved with our studio numbering system, has three digital watermarks and soon it will also have a blockchain unique signature. This is what you keep in the safety deposit box as it is completely irreproducible. If you do not have this certificate the piece you have is completely worthless. This certification system is retroactive, and we are slowly giving one of these for each piece acquired in the past. Running a personal certification system also has the side benefit of protecting you from potential fraud from gallerists or intermediaries who may be reproducing your work behind your back. This has not happened to me but I have heard many stories. Another benefit of personal certification is that if the collector does not pay you in full you simply do not hand-over the certificate. He or she may have the work after paying an advance, but the purchase is not complete until the work is fully paid and the collector is in possession of the unique certificate.

- Unless the piece is very simple, the price of acquisition of a work should include an honorarium for you or a technician to help with installing the work on site (what is not included in the acquisition price is the flight, accommodation and per diem for you or the technician). Make it clear to the collector that their installers need to follow your instructions on how to hang the work physically, run the wires and provide electricity. You cannot do those things because you are not insured. You are there only to supervise and to calibrate the system.

- Once you or your technician calibrate the work, show it to the collector, teach them how to turn it on and off and clean it. Then ask them who you should train for a full technical run through of the piece, e.g. the collector herself if she is nerdy, her installer, the IT department, the conservator of the collection, etc. Do a complete walk through of the work with this person and show them the manuals, spare parts, and so on. This person will be the first one that the collector will go to when the work malfunctions so he or she is very important for your own peace of mind. Once you have trained the collector and the technical person, make them sign a document that simply says that the work has been installed to their liking, that they received training on the operation, maintenance and preservation of the piece.

- Install VNC or, better, LogMeIn and explain how you can log in remotely to fix problems if needed. Show the collector how to disconnect the piece to the net if they want privacy. Depending on how fancy the work is, you can consider also using networked power bars to cycle the power remotely if necessary. 

- Have the collector install surge protection and grounding to the power that is supplied to the piece. Many problems we have seen throughout the years come from bad power: fixing a burnt transformer is often a tedious and expensive job and often the circuitry is also affected. 

- Talk about maintenance. To the best of your ability give a specific Mean Time Between Failure (MTBF) estimate, which is basically the time it will take for components to break, on average. For example if the piece has a projector quote the number of hours that it will work for before a bulb needs to be changed and specify how much that will cost to replace. I typically use two metaphors to explain maintenance on a media artwork, depending on the collector and situation: 1) The artwork is like a car, —you should drive it from time to time, change the oil and tune it, but the more you drive it the more it will it cost to preserve; and 2) The work is like a fountain, —you have a capital investment but then there is a maintenance budget for changing rusty valves, chlorinating the water, etc.

- Talk about warranty. You should let the collector know about whatever warranty there is on the individual components of the piece, for example a computer usually has a 1-year warranty. But you should under no circumstances guarantee that the work will function a given amount of time. You are not a corporation, you do not control the conditions of the exhibition or the handling of the piece after you depart. The spirit of giving the collector all schematics, software and code, plus the training, spare parts and manuals, is that you are now delegating conservation to his or her collection. When the collector is uncomfortable about the lack of warranty clarify the technical support you are willing to give.

- Providing technical support can be a nightmare in Media Art. Not providing it is even worse. If a piece fails the collector needs to know exactly who to call and have a support network. If they don’t it is possible they will never invest in media art again. Often artists make networks that include their galleries, trusted technicians or AV companies. In our case here is what we ask the collectors to do in case of failure:

  i) Read the manual. Over 95% of failures are something simple like a power cable that is not nestled in fully.

  ii) Contact the installer who was trained by you or your technician, he or she should be able to troubleshoot at a higher level.

  iii) Contact the gallery in case they have a technician who can help.

  iv) Call or email my studio and we will try to fix the problem remotely for free, over the phone and remote login if available. 

  v) If the problem is not solved, we are happy to go on site to solve it. The costs are: return flight for you or the technician to go to the city, accommodation and per diem, any parts that needed replacement, and $750, or some other daily fee you establish, for honorarium. Please note a travel day is charged at half the daily rate. It is my experience that collectors rather get direct support from the artist studio even if that may be costly. This money helps the studio maintain operations and instead of technical support being a nightmare it is now a source of income. 

- Provide a migration path and explain versioning for artwork. When collectors acquire a media artwork they need to know they are getting an “event-based” living piece that is closer to a performing arts commission than a traditional visual artwork. Many conservators understandably cringe at the possibility of an artwork changing over time, but that is exactly what Media Art should aspire to do. In an epic conversation with Tate expert and friend Pip Laurenson, I realized that what she was after was completely different but not entirely incompatible with what I envisioned. Tate acquired my work “Subtitled Public” made in 2005. In this work you enter an empty room, are tracked by computerized surveillance, and a random verb is projected on your body which follows you everywhere, —the only way to get rid of the word is to touch somebody and exchange words with him or her. The project was written in Delphi, using firewire cameras, IR illuminators and XGA projectors. Using an impressive and comprehensive method Pip ensured that the piece that is at Tate can be performed using these original technologies, giving the public a snapshot of what computerized tracking was like in 2005. So far so good. Ten years later there are hardly any Delphi programmers, firewire is dead, projectors now have over 10x the pixel resolution and Kinect2 tracking is orders of magnitude faster, more accurate and easier to install. I am now planning a migration path for “Subtitled Public” to work with these new technologies because this particular project is not about the specific tracking and projection used but about the experience of words branding the public. I am eager to see the project in a second version because the experience will be more ominous. The cost for this migration is relatively low, especially if you consider that you would not need to stockpile older gear or interpret Delphi code. Versioning is almost as if a collector buys a piece of software for an initial amount, then the artist improves this over time (in a way the artist provides a Conservation path for the artwork) and charges a small upgrade fee. Like in industry, versioning can also be a source of income for the studio. Of course in the future Tate can choose to exhibit either version or both. It depends on the show. The key is not to think that both these approaches are mutually exclusive. Obviously, the artist cannot go and offer version 2 to a different collector, a migration is available only to the collector who originally acquired the work.

- Versioning should end with the death of the artist unless you leave specific instructions on what you need your estate to accomplish (like Gonzalez-Torres did).

- A collector should be free to decline migrating their piece along the artist or estate suggested path. If in the future the piece is acquired by a different party the new owners can decide to pursue a migration. Should the collector attempt to preserve the work with a migration path that is egregious and not approved by the artist or estate the title of the work will be automatically void and the artist will be able to sell it again (I learnt this from James Turrell’s practice! It so smart: you need to be protected from someone adding or taking away an element to the piece that you did not approve of).

## FINAL NOTES
- Trust conservators! They are absolutely fundamental for your work to have a future performance. They also have a lot of experience in preserving the most diverse things you can imagine. Establish a dialog with them and work out a migration plan, they tend to be relieved when the artist has thought through these issues. Above all you don’t want the collector to think they are acquiring a future conservation problem (though admittedly every work, even a painting is a future conservation problem).

- Trust curators, but not as much as conservators. In the future the curator is the person who will stage your work in a variety of different contexts. Try to explain in your documentation what is and is not possible with the work. Many curators are sadly too rushed to read manuals, which is why you must trust conservators more.

- Keep a website! For each piece that I have ever made I have a webpage with videos, photos, descriptions, bibliography and most important: the manual for the work in PDF and a list of credits of the people who worked on the project. Giving public credit to engineers, programmers, and other assistants is an honest thing to do but is also a way for future conservators to track projects by different coding styles, for example.

- This final note is not for everyone, but it is something that makes sense for my work: In my upcoming monographic show in Mexico City’s MUAC Museum we will publish a USB flash drive which will contain absolutely all the source code and schematics of every single artwork on display (there are 42 pieces!). We already have a GitHub account where we share some of our programming to the open source community, but this new idea is designed to be more radical. We want to make software and methods something more dialogical, less precious, more open, more viral. If my servers crash and no museum has backup copies my work will already be in the forks of dozens or hundreds of other projects that other artists-programmers have developed from my studio’s code. Infecting future projects is our new strategy for preservation. To our knowledge this will be the first time that a comprehensive art show will be made available with an open source code.


Version 0.9.1

PS. The cover image is “33 Questions per Minute” a piece from 2000 which ran on Windows 98 and was programmed in Delphi. In 2006 MoMA’s acquired the work and used my source code to port it to C++ and run it on Linux, thus proving that stockpiling old PCs was not necessary to assure conservation. That was some next level shit right there and a big relief for all. I have only now found this new initiative from the Museum and I shall look at it closely <http://www.moma.org/explore/inside_out/2015/05/13/open-sourcing-momas-digital-vault/>

PS2. I want to acknowledge the talks I have had with numerous friends and colleagues, most notably my studio assistants and the great Kim Brickley whose interviews helped me put some order to it all; but also Steven Sacks, Patricia Ortiz Monasterio, Zimoun, Daniel Canogar, Pip Laurenson, Glenn Wharton, Christiane Paul, Ben Fino-Radin, Kate Lewis, Sarah Cook, Beryl Graham, Matthew Biederman, Kathleen Forde, Rudolf Frieling, Barbara J. London, Pablo Helguera, Colin Griffiths, Alain Depocas, Jean Gagnon, Abigail Susik, Steve Dietz, Erkki Huhtamo, and other artists, collectors, historians, curators and conservators who like talking about this kind of thing.
