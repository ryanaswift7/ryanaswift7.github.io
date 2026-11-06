---
layout: about
title: about
permalink: /
subtitle: Computer Science PhD Student, University of Southern California

profile:
  align: right
  image: myPortrait.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>Office: RTH 418</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hey there! My name is Ryan and I'm a CS PhD student at USC. This website serves as my personal portfolio/CV/blog kind of thing. It is still heavily under construction, with some leftovers from the template I used, but I'll continue adding to it over time, updating it as I finish papers, projects, posts, etc. For now, I'll start by telling you a little bit about me.

## Research

I do research in representation learning and applied interpretability for LLMs and agentic systems. Generally, the question I try to answer is:

> "How can I take what we've learned about how LLMs learn/store/process information and translate that to practical improvements in performance, efficiency, safety, etc.?

Initially in my PhD, I was primarily interested in pure mechanistic interpretability and trying to figure out how LLMs work. At some point, I got tired of thinking of ways to convince people that interpretability is important, and I ended up making the entire focus of my research a demonstration of why interpretability truly does matter.

Thus far in my PhD, I've done a lot of work in knowledge distillation and some in data-efficient finetuning. I'm particularly interested in research on small models and making things more efficient. I am of the opinion that, if we *actually* knew what we were doing, we could cheaply (in both financial and resource costs) train very capable, very small models. But since we don't, we have instead resorted to massively scaling data and model sizes. My research tries to come up with ways that we might leverage the intuitions derived from mechanistic interpretability to train and/or evaluate models in a more principled way.


## Development & Engineering

While the bulk of my professional experience has been in academic research, I was fortunate to have had a really fantastic internship at Lawrence Livermore National Lab in Summer 2026. I got the opportunity to dive deep into agentic systems and contribute to the design and development of a custom agentic harness in the very early stages. I got to help design the MCP interfaces, custom tooling, connections to internal knowledge bases, integrate expert knowledge with a SKILL-like setup, and implement agent routing for expertise and internal information reference prior to tool execution. It was an awesome experience, with feature sprints, lots of Costco pizza, and some really smart, really kind people.

One of the most valuable things that I learned in my agentic systems work was how quickly I can ramp up and start meaningfully contributing to a team. I knew *about* agentic systems before that internship, but hadn't gotten much hands-on experience. But if there is anything that research has taught me, it is how to gather information, anticipate problems, and solve them before they cause issues. This skill was invaluable in my meetings with different team members, and knowing what questions to ask and how to target their priorities helped me go from zero hands-on experience to designing, integrating, and committing new features in a matter of weeks.


## Personal Interests

I have a small handful personal interests. If you talk to me for more than 5 minutes, I can almost guarantee that I will bring up one of these things.

#### Baseball

Outside of my family, I cannot think of a single thing that I love more than baseball. There have been many times in my life where I have watched 4 full baseball games in a single day. I grew up playing it basically year round until my junior year of high school, when a mixture of health issues meant my playing days were over. I grew up loving the Cardinals because Yadier Molina was my favorite player (yes, I was a light-hitting, defense-first catcher), but now that I'm in Los Angeles I've become a huge Dodger fan and watch (nearly) every game.

Some day I think it would be really awesome to work in baseball research and development. I definitely think I have the technical background, and I would also say that I have a pretty decent baseball IQ. I don;t have much experience combining those things in the modern world of basebal R&D, but I suppose the only way I could actually get that experience is working in the field.


#### Cars and Motorsports

Similar to baseball, cars have been a lifelong passion of mine. For as long as I can remember, one of my dream cars has always been an NA MX-5 Miata ([POP UP, UP AND DOWN HEADLIIIIIGHTS](https://www.youtube.com/watch?v=GDtiO29v1Ac)). I love all kinds of cars, but some of my favorites are generally small, light, (relatively) reliable cars that are easy to work on and modify. Outside of some Porsche 911's, the Audi RS2 Avant, the and Cadillac CTS-V wagon with a 6-speed, basically every one of my other favorite cars is Japanese (e.g. FC/FC RX-7, GR Yaris, Autozam AZ-1, and of course every Miata).

As much as I love cars and would love to get more into motorsports, the financial aspect is an unavoidable barrier. I can't (yet) afford a project car, or even modifications to my own car, so unfortunately all I get to do is oil changes and some other basic maintenance. It's even tough to watch F1 knowing that only a handful of teams have a chance to win, and I'd have to burn all of my emergency fund just to get a single ticket to an F1 race weekend.

I've watched a handful of Indycar, IMSA, DTM, and WEC races and I don't know why I haven't watched more. They're all super fun to watch: competition, interesting personalities, and lots of diversity in cars, driving styles, and strategies. I really like a lot of the recent changes Indycar has made and I've recently found it more engaging to watch than even F1. 


#### Linux

I am a self-proclaimed Linux nerd-- specifically desktop since I can't afford any servers right now. I run [NixOS](https://nixos.org/) in a dendritic setup with [Niri](https://github.com/niri-wm/niri) as my window manager with [DankMaterialShell\Dux Shell](https://duxlabs.dev/). Was it a painful experience to build my config? Yeah, a wee bit. Was it worth it? Absolutely. All of the key things that NixOS offers-- atomic updates, reproducible builds, declarative configuration, mixing stable and unstable packages-- are well worth the time and complexity of setup to me. I highly recommend giving it a whirl if you're interested in those kinds of things. You can check out my [dotfiles](https://github.com/ryanaswift7/nix-dots), but it has been a looong time since I gave it a proper update. Still running great though :)


#### Space, again

When I was a kid, I was obsessed with space. I remember spending my Saturday mornings in second grade watching "*How the Universe Works*" on the Discovery channel. In third grade I *knew* that I wanted to be an astrophysicist, so that I could learn more about space. In middle school, I decided that I needed to change my goal to aerospace engineering, because those were the people building the rockets, satellites, and telescopes that enabled us to learn more. 

But, as happens with a lot of people, I hit some bumps in life that made me sufficiently uncertain about my future that I didn't feel like I had the luxury of chasing after that dream I had when I was a kid. When I went to college, I chose instead to study computer science because I had heard about all of the aerospace layoffs during the Great Recession, and (at the time) computer science majors were easily getting six-figure jobs out of undergrad.  As it turns out, computer science is now undergoing a radical shift in the age of AI and the job market is abysmal.

I've always been a pragmatist, and I have a history of sacrificing my interests and passions in exchange for (what I had hoped) would be better security and stability in the future. With how terrible things have been lately, I finally stopped and asked myself, *What was all of that sacrifice even for?* I took risks and made decisions, and they didn't pay off. So what now?

All of this got me thinking about that little kid I used to be: full of wonder and curiosity and passion for space and learning more about what's out there. It made me realize that maybe that kid had it right all along. Even if things were tough, the job market is bad, money is tight, and everything else goes wrong...at least I can still be that kid who looked up at the stars and wondered why there was something instead of nothing. 

So, I've decided that I'm going to try to be more like that kid again. Right now I find myself with a particular set of skills and expertise, and although the ship has sailed on me being an astrophysicist or aerospace engineer, there is still a chance to work on project and with people who are also obsessed with space. Obviously working at NASA would be a dream. But also, Relativity Space seems like it might be the kind of place I would like to end up. I've got a friend who works there, and from what it seems, everyone else there is a space nerd too. They have an interplanetary sciences program, are building the launch vehicles, and (most pertinent to my background) have a key focus on advanced computing systems. While actually getting a job there may be a bit of a moonshot, I'll give it a whirl and see how it goes.

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
