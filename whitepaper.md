# Title: Urgency and Impact of the National Open Hardware Infrastructure
(working title) 

## Executive summary
t.b.c.

# Demonstration through cases

-> alternative cases are very welcome.

## Opentrons
Opentrons is a company that produces laboratory robots designed to automate experiments based on the open source 3D printing framework. From the outset, their robots are designed to be affordable and accessible, allowing researchers to focus on their work rather than manual pipetting.

In 2019, when the Covid-19 pandemic hit New York very hard and the limited test capacity was not enough to cover even a small fraction of the patients, Opentrons succeeded in adjusting their robots to automate the process of testing patient samples for the virus, allowing researchers to process more samples more quickly, all in a few days.

Opentrons played a crucial role in increasing the test capacity during the COVID-19 pandemic in New York. By automating the process of testing patient samples for the virus, Opentrons helped researchers process more samples quickly, which was essential in the face of the high demand for testing.

The cost reduction of each test from $2000 to $14 was a significant achievement, as it helped make testing more affordable and accessible to a larger population. Additionally, the reduced duration of testing from 20 days to less than 24 hours allowed for quicker results, enabling individuals to receive prompt medical attention and reducing the spread of the virus.

At the same time, in the Netherlands the test capacity reached its limit very quickly, despite the well-equipped national health services (the GGD) because of the limited availability of the proprietary buffer from the exclusive provider company

The impact of Opentrons' efforts during the pandemic cannot be overstated. Their contribution in increasing testing capacity and developing low-cost, open-source ventilators has helped save numerous lives. Their work is a testament to the power of open source innovation and collaboration.

Currently Opentrons is also working with researchers to develop a low-cost, open-source ventilator to help with the shortage of ventilators during the pandemic.

The evident contrast between the impact of open source vs proprietary technologies in the times of urgency, begs the question if the old paradigm of technology transfer from research to practice based on long and secretive process of attracting private investors needs revision

## Open-flexure
-> From the talk of Richard Bowman in Veldhoven, must be shortened.
 
The open flexure microscope, currently in it 7th generagion costs less than an Xbox, nonetheless, it's a serious piece of lab research equipment. Due to its small footprint it can go to a lot of places that a big microscope can't. It fits in an incubator, or a backpack and it's relatively inexpensive. That also opens a lot of doors in terms of applications where you might not be able to spend a hundred times that much on a big commercial automated microscope. And because it mostly prints in a single piece, it's easy to replicate, um, which leads to a lot of fun sharing the design with people around the world. 

The majority of open-flexure funding was provided for working with collaborators in Tanzania to develop locally produced microscopes for better malaria diagnosis. Reports on using the microscope have been published from 45 countries and the list if growing. As not everyone who works in a research lab, the project maintainers set up a website that pulls the necessary things out of the project repository and makes them available in a friendly manner and also host an online discussion forum where people can discuss in a slightly more informal way.

Richard Bowman, lead of the open flexure project argues that open hardware is a particularly good fit for scientific research. Unlike most mass produced hardware that benefit from  the economies of scale, for research hardware we need to understand what goes on inside the black box. Researchers we need to customise the equipment for the specific measurements they need. That means that a black box covered in warranty stickers is often quite a bad fit for a science laboratory. 

At the same time, even if it is an off-the-shelf scientific instrument, it's still a specialist thing, There aren't really economies of scale when you're shipping hundreds or even thousands of units per year. That means that the companies can't afford to put enough engineering effort into the software. There is a flourishing community that is growing, uh, of people who are publishing and using, make it yourself scientific instruments. Um, and indeed this is not a recent phenomenon. Scientists have shared designs for apparatus for, uh, hundreds of years. But unfortunately, less so in recent times. It is good time to revisit how something gets from an idea in a researchers' head to a useful tool in somebody else's laboratory. 

# International and national context

## Open source technology development
-> Transcribed from the talk of Richard Bowman in Veldhoven, must be shortened.

The currently prominent mode of technology creation out of fundamental research is as follows: I have an idea. I developed my idea. At some point that idea is well enough developed to disclose it to my tech transfer office. If they like it, then they will patent it. That gives us some measure of protection that nobody else is allowed to use the idea without our permission. We then license that patent to a company, the company do some manufacturing. The fact that the company probably have to do about 10 times as much work in R&D as I did developing the idea in the first place. That company can potentially generate some revenue money. And if we've gotten the paperwork right, some of that money flows back to research. But, in order for this to work, the first half of that process has to be secret, because many of the current partnerthisp scheme are geared towards secrecy and non-disclosure. Without secrecy one has prejudiced your own patent with prior art. The second part of the process is generally exclusive because that allows the company to take on investment. It is gives them an incentive to take the risk on bringing up a new product. And fair enough, that's how this is all justified. But actually it's a very leaky pipeline. Um, and there are a lot of places where your project ends up being abondened. Maybe the tech transfer office don't like it and they won't patent it. Maybe once they patented it, nobody wants to license it. And maybe after a company has licensed it, all they want to do is use the patent to troll other people and they're not actually interested in putting your equipment into other people's labs. 

An alternative pathway: I have the idea, I immediately share the idea before the idea is patentable. That then means there are a lot more brains that can work on the project. This isn't work in progress. It's open right from the start. Um, and nothing stops a company coming along using that non-exclusive license and manufacturing it. And in fact, people can still make money this way and do like open trons. Um, but your friends can also make it themselves. And the open license, uh, gives you confidence that if you do make it yourself and if you develop something exciting based on that, that you are not then going to be embroiled in lots of nasty litigation. Furthermore, because you shared this early and lots of people have gotten on board means not only that, hopefully your stuff's already getting used in research, which also enables you to improve, the design. And so this community can start improving something that then becomes a community resource. 

It is not difficult to argue that the majority of scientific instruments are not suitable for mass commercial use. Therefore, the benefits of doing it openly, far outweigh the relatively small chance of commercial success by keeping everything secret. While the cost of keeping the invention or some details of secret are huge for the advancement of science and obviously waste a lot of resources that could be spent on training and exploratory research. 

## Open hardware developments in US
TODO: Would be nice to review shortly what has been done recently in US, e.g. in NASA, NIH, and CZI

## Open hardware in academia

## Open hardware for research (worldwide)

# National preparedness

TODO: Here we can argue that the Open Science NL program has created a focus point for open science, but has not ellaborated on open hardware

TODO: we can also bring the examples of Delft, Eindhoven and Utrecht on how local initiative have brought open hardware development into education and reasearch. 

# Experience of the eScience center
-> Transcribed from the talk of Nicolas Renaud

The Nederlands eScience center has been created in 2011 by NWO to professionalized the development of research software. At the moment about a hundred people are working at this center, with 60 research software engineers working on the projects granted to researchers at a rate of about 50 project each year year. The center covers several disciplines from artificial intelligence and machine learning to high performance computing and data processing. The main thing that links all the project usually is the software quality. All the software that the center develops in each project should be reusable, maintainable, sustainable, so that the software outlive the project and can be really reused by all the people outside of the research team. The center also covers across all domains: life science, natural science, social science, and humanities. 

We do a lot of software releases. So we do sync as it's been mentioned before, that software is also a publication. So paper are one type of publication, but not the only one. So we really try to raise the profile of software as a first class citizen in the, in the academic landscape. So we do a lot of release and publication of software. We do have also normal scientific publication to which we contribute to together with our research partner. And another thing that we do that I will touch upon at the very end of the, the presentation is we do a lot of training as well to train people into better software practices in the academic landscape. 

The center also provides training for researchers. In all the project, the emphasis is on consolidating the code and making the work source open, easily documented, easily usable so that an entire community can benefit from the project. 

One example from climate science domain. The code is called ??? with a large number of contributors. So we have more 80 contributors. In presentations at the UN this tool was used, for a presentation on climate change. This is only one example of the broad impact of such an open source research software. 

So in terms of supporting and uh, disseminating software, we also try to develop tool for people to, make the software available or known to a much broader audience. So not so long ago we released what we call the, the research software directory, which is a platform where people can submit the software so that all the researcher can find it much more easy. So either we give away for, uh, research software engineer to show the impact of their work. I'm gonna come back on that point in a second. It also sh other organization to showcase what they've been doing and all the research they've been doing in, in the, in that project. You can also find more, uh, pro more research software more easily once through the, through the tool. And you also citation the software itself, not of the paper, but of the software itself. 
Organization can also use that to see and show to funders what they've been doing.

Quantifying the impact and userbase of the software is one of the tools for eSceince center to make sure that all the policymaker keep on, funding open source and open science. So that's something that we invite everyone to use and we could extend it for open hardware. Another area of impact is to participate in this teaching. The center has a wide range of courses from basic programming skills to GP programming to keep learning to all sort of things. Education of the end users is important for each project to maintain the software also after the end of the project at the eScience center 
# Proposed activities of the NOHI

+ also check the proposition of the NEWS science communication proposal. 
