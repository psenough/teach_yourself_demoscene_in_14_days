# Teach Yourself to Be Part of the Demoscene in 14 Days

A guidebook idea for newcomers to the demoscene, spawned from [a certain pouet.net forum thread](http://www.pouet.net/topic.php?which=10882&amp;page=1).

## Day 1 - Demoscene?

The [demoscene](https://en.wikipedia.org/wiki/Demoscene) is an underground computer art culture. The term demoscene comes from the word demo, short for demonstration. Which in the context of the demoscene means a realtime audiovisual application demonstrating the capabilities of the machine.

We call demosceners the folks with too much free time that like to use their computer skills to create releases under the demoscene.

Demosceners often use nicknames to identify themselves and hang around in so called demogroups. Some demosceners are active members in multiple demogroups, with or without using the same nickname.

Demoscene has no commercial purpose. The releases are meant to show the limits of the machines and the technical skills of the makers. There are no rules to what kind of release you can make. Some are made as technical benchmarks, others as conceptual art, and others just for fun. It is entirely up to you to explore what you like doing and share it with other demosceners.

Demoscene releases commonly are of these categories:
* Track, an audio piece (can be in executable format, tracker module format or pre-rendered wav/mp3)
* Graphics entry, drawn images with fixed resolutions and/or palettes with restricted number of colors
* Demo, an audiovisual real-time executable demonstration of a certain machine
* Intro, typically a demo with file size limitation all packed into a single executable file that includes all the assets (popular sizes: 256bytes, 512bytes, 1kb, 4kb, 8kb, 64kb)
* Animation, rendered graphics videos
* Demopack, a collection of demos in a single disk
* Musicdisk, a collection of demoscene tracks with an executable player
* Diskmag, a collection of texts about the demoscene with a graphics interface
* Wild entry, everything else (including live performance, videos of demos on weird platforms, etc)

Releases typically occur at [demoparties](http://www.demoparty.net/). Demoparties come in many flavors but they are usually 2 or 3 day events that bring together demosceners and ask them to participate in a series of competitions (also called compos). The entries are shown on the big screen, people vote what they liked best, and the winners take home a symbolic prize.

Given all this knowledge, your mission, should you choose to accept it, is to, in 14 days, make your first demoscene entry, meet some fellow demosceners, participate in a compo at a demoparty and eventually "bring a big shock to Japanese brain" as some sceners say.

On this first day of the rest of your life you should probably google a bit more about the demoscene and watch some demos! If you have trouble running most demos on your platform of choice [url=https://www.youtube.com/user/Annikras]Annikras spent a lot of time capturing demos into high quality videos and uploading them to his youtube channel[/url], which might be useful, although demos are always best experienced running live on their target platform.

## Day 2 - Find your Vocation

On the second day of the rest of your life you should figure out what you want to do on the demoscene.

A demo is usually a group effort. Sceners are typically divided into 3 roles:

1. Graphician - responsible for the artwork, 3d modelling and animations
2. Musician - composer and producer of the audio soundtrack
3. Coder - programmer of "effects" and tools that will enable you to get your demo done before the deadline

You can always just do everything yourself, but it obviously takes some hefty ammount of effort to be proficient in each of the areas, so it's common practice that people specialize in one of them while retaining some additional capacity on the others.

So what do you want to do when you grow up? Draw imaginary worlds? Annoy your dog with high pitch sounds? Spend your whole night debugging spaghetti code? Now is the time to figure it out. You can always go back and learn something else, but if you want to finish a demo before the deadline it helps to know what you will be focusing on.

There is an additional role on the demoscene, which is the role of the organizer, although not directly involved in the production of demos, they are often critical to a successful sprint and keeping the spirit alive. Their tasks can range from finding complementary group members to join the project, managing people and deadlines, organizing events, promoting releases, etc.

You should never be afraid to try out or experiment in an area you don't dominate, even if you don't stick with it you'll learn invaluable information on how it works that will undoubtedly help you in the other areas in the future. So embrace your curiosity, don't be afraid to fail. People learn with mistakes and everybody has to start somewhere, just follow your heart, ignore any prejudices and explore what you want to explore, be it drawing and modelling, animating, composing, programming or syncing your demo. Just give it a try.

It won't be easy to master a role. All of them are life-long commitments that take years of practice and exploration to achieve something great, but we all have to start somewhere, so let's get started!

By the end of day 2 you should have an idea of what you want to explore more seriously. If you have doubts what each area actually entails then i strongly suggest you search for some beginners tutorials on the different areas to help you decide. We will cover the basics of each role during the next days but the more prior information you have the better prepared you will be to tackle the challenges ahead!

## Day 3 - Basics of Graphics

The role of doing graphics for a demo is typically supported by a so called graphician. To be a successful graphician in the demoscene you should hopefully enjoy drawing and being randomly creative. There are many tools you can use to do graphics:

Pixel art graphics typically focus on a limited palette of colors and image size. The restrictions come from the oldschool machines that had such limitations on hardware. These images are typically called sprites. 2D animations are created by cycling between sprite frames in the right order. You can [google for pixel art graphics tools](http://lmgtfy.com/?q=pixel+art+graphics+tools) and find a whole bunch of modern editors for pixel art. Real sceners will tell you about [Grafx2](http://www.pouet.net/prod.php?which=51865) or the more recent [Multipaint](http://www.pouet.net/prod.php?which=66976).

If pixeling makes your stomach all queasy that doesn't mean your career as a graphician will be over before it even started. You can still take the role of 3D modeler (using 3DS Max, Maya, Lightwave, ZBrush, etc) and 3D animator.

The graphician may also be responsible by the overall design of the demo. Including concept, scene composition, transitions, etc.

Most graphicians are proficient with Photoshop and illustrator, or their free / open source clones.

By the end of day 3 you should know what tools to use if you want to do graphics for a demo or a graphics compo entry. Try a few of them out, check some tutorials, learn the shortcuts and master the tool you find most interesting.

## Day 4 - Basics of Audio

There are many tools to produce audio freely available. Ranging from sample editors to complete DAW (Digital Audio Workstation) solutions.

Modern PC demos typically play a pre-recorded final mix of the audio (an mp3 of the track), but the roots of the demoscene involve sample generation and the so called tracker formats. Most demos for oldschool platforms still feature live mixing playback of a tracked track.

The [tracker format](https://en.wikipedia.org/wiki/Module_file) can be divided into 3 main concepts: samples & instruments, patterns and sequencing order. You can typically load or configure the parameters of samples that can be played. Certain trackers allow you to configure samples into instruments by defining behaviors on how the sample will be played when triggered under different pitches. The samples or instruments are then sequenced in patterns that will be played back under the stipulated tempo. And you can set the order of how the patterns will be played under the song sequence. These simple rules are the basis for most trackers that exist out there, each of them with their unique counter-intuitive menus.

Certain platforms have sample and instrument restrictions like only generating sinus, saw or square wave forms. Or only allowing certain types of filters. The limitations of each soundchip popularized on different 8bit and 16bit machines gives certain platforms it's distinctive sound.

To create sound for limited size intros demomakers have developed their own synthesizers, forcing the musicians to create instruments procedurally. Storing the function steps required to recreate the instruments procedurally takes less space than storing the entire sample. Popular demoscene synths include [4klang](http://4klang.untergrund.net/) and [clinkster](http://www.pouet.net/prod.php?which=61592).

Of course if you are doing sound for demos you are not limited by size, so you can do your soundtrack in whatever application your prefer (Fruity loops, Ableton live, Cubase, reason, logic pro, etc.).

By the end of day 4 you should know what tools to use if you want to do sound for a demo or a music compo entry. Try a few of them out, check some tutorials, learn the shortcuts and master the tool you find most interesting.

## Day 5 - Basics of Code

Learning how to program is relatively easy, there are tons of books and free courses on the subject. Some people even made [online lists of these things](http://codepancake.com/learn-code-online-ultimate-list/).

[Khan Academy](https://www.khanacademy.org/) is as good place as any to learn how to program in general. You'll need to learn about variables, functions, classes, data structures, loops and algorythms. There are many programming languages, platforms and styles of programming with their respective zealots. Some languages favor certain styles over others but overall you should focus on the language you're most interested or comfortable with.

To avoid initial frustration you should probably start with something that lets you throw something on the screen relatively quickly, languages such as [Processing](https://processing.org/), or platforms such as [Unity3D](https://unity3d.com/) are great ways to get into graphics programming. Whatever language, development platform or APIs that you choose to pursue, there will surely be a graphical canvas for you to dirty with pixels, triangles and quads. And that's what you should focus on at start.

There are many ways to program a demo, there is no such thing as the single best way. You should do demos as it feels most natural to you. As long as the entry gets done in time to get shown on the big screen, you're doing it right.

Some programmers get a bit caught up in the right way to code, reading books, following the best practices, debating them, getting caught up in endless refactoring cycles and never finishing the actual demo. If that's you i suggest you read [http://programming-motherfucker.com/](http://programming-motherfucker.com/) and focus on getting the demo done.

Another point worth addressing is that you don't have to prepare the entire development chaintool and engine yourself to still program a demo. Some coders prefer working on engines and tools for other demosceners to use instead of coding an actual demo themselves. Others hate dealing with those things and just like to put the final product together. It's useful to dabble on the different fields but at the end of the day you should focus with the area you are more interested in or comfortable with.

If you're focused on doing tiny bytesize intros (128bytes, 256bytes, 512bytes) you can find some great resources on this subject at [sizecoding.org](http://www.sizecoding.org/wiki/Main_Page). If you're more interested in 1k / 4k development, you can find resources at [in4k](https://in4k.github.io/).

Try to program a new effect each day and you'll eventually start to get the hang of it and figure out areas that you should read up on to improve your skillset.

By the end of day 5 you should know what it takes to take on the programming role of demomaking.

## Day 6 - Tools and Resources

There are many ways to do demos. Some folks enjoy coding everything from scratch, others prefer to use tools to facilitate their work. There are many types of tools, some are commercial (like Maya, 3DS Max, Photoshop), others are open source or freeware, and then there are the so called demotools. Tools made by demosceners especially to help create demos. Demotools are especially important if you're working on size limited entries. Some groups develop their internal demotools, others open source their tools and libraries in order to have more users and raise the bar. The end goal is always to make more good demos.

I would strongly advise you to take a quick look at the different demotools available and see which ones you can use to avoid reinventing the wheel and achieve cool results sooner. You can find a list of the most famous demotools on [pouet](http://www.pouet.net/prodlist.php?type%5B0%5D=demotool&page=1&order=thumbup), they range from texture generators, music trackers, synths or graphics tools or format converters to full featured demomaking engines, executable packers and linkers.

The best way to know what tool might interest you is to either check them all out one at a time, or visit a demoparty on location and just randomly ask another fellow scener. Your tools largely depend on your demoscene role of choice and target platform so i hope you have a hint of a plan by now.

Similarly important to knowing the tools of the trade available to you are what resources are out there, ranging from free tracks, samples, free sprites, free animated models, usable tools, editors and engines, tutorials, irc channels where to get motivation and support, etc. It's usually a matter of doing a few google searches or asking fellow sceners about their demomaking habits.

Demosceners typically have very strong opinions on what is the cool and what is lame. The demoscene has no written rules. Different people have different concepts of what "their" demoscene is about. So it's easy to get negative commentary, you should realize that an opinion is just an opinion, you don't have to please everyone. The demoscene is a hobby, so you should above all please yourself first. If you put effort and dedication into your entry I’m sure people will acknowledge your effort regardless of if they liked it or disagree with the "shortcuts" you took in their eyes to get the demo done. My recommendation is to be honest with your sources, entries typically have a readme.txt file in the package where you can describe your work process, what tools you used and why. If you include proper documented information the people who read it will no longer feel that cheated if your demo used a ripped soundtrack, repurposed shaders or a commercial engine. They will evaluate it accordingly.

That being said, the more "original" material and effort you put into the entry the more impact it will have on the viewer. Generally speaking: reuse with proper crediting is generally considered fair game, claiming ownership of someone else's work is not.

By the end of day 6 you should have a good idea of what tools and resources are out there to assist you on your plan for demoscene world domination.

## Day 7 - Experiment

Whether you're a musician, graphician or coder: don't be afraid to experiment.

Experiment with tools, experiment with ideas.

Repurpose, remix, discuss with other sceners.

Don't be afraid to fail, it's normal to fail, that's how you find interesting things, that's how you learn how to do things properly. Go forth and fail, eventually you will succeed!

Don't expect your first track to be great. Don't expect your first pixel graphics to look good. Don't expect your first demo to be any good. The first demos from 90% of sceners are a total load of crap!

You should also be aware that it's common to get creative blocks or lose your motivation to do things from time to time. Just remember that demoscene is a hobby, you're free to do whatever you want at whatever pace you please. Some sceners take decades working on their demoscene masterpiece on and off!

As long as you keep yourself motivated to try new things, eventually you will manage to release something you are truly proud of.

At the end of day 7 you should now have a good grasp on the importance of not being afraid to just try things and experiment.

## Day 8 - Achievable Goals

There are many ways of making a demo. The only right way is your own way. The way that is interesting and fun.

That being said you should always aim for achievable goals. If you are not reasonable with your capabilities you'll soon find yourself demotivated to carry on improving your release. Always better to start small and build on top of what you already have working.

If you have no idea where to start here are a few pointers:
* Some people try to replicate some effects after seeing something interesting in other demos, movies, adverts or nature. Building up a set of different effects and then trying to find a soundtrack that can glue them together into something nice.
* Others prefer to nail down a concept and only then get to work on it's different components. Some sceners only feel the drive to create something when someone requests them to do something or throws them a challenge.
* Some coders only do engines, frameworks and tools. Some graphicians only fool around with engines until something seems interesting. 

All these approaches are valid. Demoscene is a hobby, so don't treat it as work, do whatever you like whenever you feel like doing it.

Some pro tips to keep in mind:

1. There is a finite number of productive hours per day, there is a finite number of days until the deadline, aim for achievable goals, and build on top of them after you've reached them.
2. If you have no ideas, try to do random things, eventually you will come up with something more concrete. Don't let a lack of concept stop you.
3. Do stuff on the project for at least 5 minutes each day, even if it's just tweaking some colors, it helps to keep the project in the back of your mind.
4. Communicate your progress with your team mates, they might give you feedback, and it'll motivate them to go do something for the project as well.

If you keep all these things in mind by the end of day 8 you should have plotted an achievable goal.

## Day 9 - Proof of Concept

## Day 10 - Deadlines are Important

## Day 11 - Get Help

## Day 12 - Crunch Time

## Day 13 - The Real Party is Outside

## Day 14 - Pouet != Scene && Scene != Pouet


## Aknowledgements

Greetings to Danny and hardy for proof-reading and comments.
