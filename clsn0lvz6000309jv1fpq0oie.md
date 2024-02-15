---
title: "Crippling analogies in software"
datePublished: Thu Feb 15 2024 09:24:54 GMT+0000 (Coordinated Universal Time)
cuid: clsn0lvz6000309jv1fpq0oie
slug: crippling-analogies-in-software
tags: management, software-development, saas, agile, software-engineering

---

As a Software Engineering Manager, I often hear or read analogies aimed at explaining *software* engineering to stakeholders, sometimes using *other* engineering disciplines like civil or mechanical engineering as the analogy.  
Software engineering even shares a role name with civil engineering: the famous *architect*.

These analogies take many shapes, from comparing “building software” to “building cars in assembly lines” e.g.

* **Software is like building a house**. You have an architect who draws plans and gets approvals, budgets, and plans upfront (a.k.a. *BDUF*). Then a “project manager” takes over, orchestrates the different crafts, and *whoosh!* You have a house. And all you need to do is repaint it every decade or so.
    
* **Software is like building a car.** You design a prototype, and then an assembly line and different crafts get handed over a set of specifications to mass-produce a *finished* vehicle. And *whoosh*! Cars get delivered to the sellers.
    

Unfortunately, it’s often used to explain *planning — and deviation from planning —* to non-technical people. You’ve probably seen this picture below that tries to convey software agility—and probably misled a lot of decision-makers. Yes, I’m saying this picture is bad!

![How NOT to explain Agile to someone…](https://cdn-images-1.medium.com/max/800/1*jf1C0kUpfuGC0iZRnRpylw.png align="left")

While making analogies is a useful communication tool, this is also a double-edged sword. 

I would argue that it’s fine to explain to our moms and sons what we do — provided they’re not software engineers— but if we have to use those analogies in our workplaces with our managers or our sales team to explain why *feature X* or *Y* is not yet “ready,” or why planning 12+ months of features is useless, analogies become harmful.

> Since software most likely ate the whole world already, it’s time we stop explaining it with analogies!

I believe analogies in the workplace, especially, are harmful. It means the person we are communicating with is unable to...

* .. understand the subtle difference between different processes and tools and why software has a different lifecycle compared to other well-known things
    
* .. comprehend the full value stream. While everyone understands the value of a house and how the building process works, how do we expect our colleagues to sell, manage, support, and communicate about the software if they don’t get that a “feature is never done”?
    

Today, in 2024, [any business leader who doesn’t understand how software is built is doomed](https://www.theregister.com/2022/07/26/from_beetles_to_bugs_vw/).

### Why building software can't be compared to building houses and cars

People understand “physical” things. They have interacted with them for the last 300,000 years. Building houses are probably one of the oldest crafts in the world. Computers and software have been around for the last 100 years. Modern software is less than 50 years old, give or take a decade. 2 generations max. Humans, even those born with a computer in their hands, are terrible at grasping software still.

Why is that?

* **Software is virtual**. Where is “virtual” on the map of the universe? It’s closer to the world of dreams than to the Andromeda galaxy.  
    The laws of physics apply, but they don’t have the same priorities as they would for civil or mechanical engineering. Once you understand magnetism and how light travels, units, and quantities are vastly different in the virtual world (when was the last time you used the *peta-* or *exa-* prefix in the physical world? — not talking to you astronomers….)
    
* **It doesn’t have the same supply chain challenges** (e.g., dependency on “raw material”). Provided your computers are turned on, your only supply chain problem is having people working on it. No, the raw material of software is not *lines of code*. Lines of code ARE the software.   
    In the era of the Cloud, brains — and knowing what you’re doing — make or break a software company. Not the supply of silicon or aluminum).
    
* Software building is [**iterative and incremental.**](https://www.linkedin.com/posts/andrealaforgia_agilesoftwaredevelopment-agile-softwareengineering-activity-7039006284481716224--oVA/) Duplicating software is as easy as completely erasing software. **Software is fluid and dynamic;** it’s not constrained by time and physical material, as a house or a car would be. It doesn’t rot because it’s exposed to oxygen. It rots because its ecosystem has evolved.
    
* The software ecosystem itself is very dynamic and changing fast. Software doesn’t become obsolete; its ecosystem evolves and makes it outdated, while physical goods break down even when the world around them doesn’t change much, just by being in contact with oxygen.   
    From one day to another, the whole software ecosystem could change, and it happens a minimum of once or twice a year, sometimes a lot more often. Take a glimpse into the “Javascript ecosystem” or the number of changes each mobile platform (iOS and Android) brings each year and compare that to someone working on an assembly line for cars.
    
* Software is “living” in the sense that a program (like “Excel”) is evolving internally. To replace or evolve software, you patch it. Try patching the engine of a car to add a piston chamber! The Excel you use today probably shares only a tiny percentage of “lines of code” with the version you used ten years ago. Yet, it’s still Excel! If you keep your car for ten years, chances are that 90% of its composition is still the same.
    

*A better analogy about an Agile, incremental, iterative development process. Replace years with sprint numbers, and you get Scrum-for-cars*

![](https://cdn-images-1.medium.com/max/800/1*3PIpJKk-Oc92ZMwVo2fYVw.jpeg align="left")

To visualize even more how those analogies are flawed, imagine…

* … waking up a morning, and no service station in the world can provide gas for the next 24h. It’s like gas disappeared. No warning sign.   
    → [That’s what happens when “a developer” breaks the internet with on](https://arstechnica.com/information-technology/2016/03/rage-quit-coder-unpublished-17-lines-of-javascript-and-broke-the-internet/)[ly 17 lines of code. How would you deal with that as a construction worker?](https://arstechnica.com/information-technology/2016/03/rage-quit-coder-unpublished-17-lines-of-javascript-and-broke-the-internet/)
    
* .. adding more floors to your house without needing a crane? Because the house itself has a crane preconfigured. Imagine that adding one floor had the same complexity, planning, and material cost as adding ten or even 50 floors. That’s what “build pipelines” are (a.k.a. CI and CD toolchain)
    
* … that each car comes with its assembly line in the trunk so that you can “reproduce and replace your car” whenever you want to add a feature. 
    
* Imagine changing your car’s engine from gas to electricity simply by paying the higher plan to the supplier.
    
* Imagine changing your walls from wood to concrete by simply pulling a switch next to the light switch.
    

### What are some crippling effects of bad analogies?

1/ Separating planning from design and execution is common in construction and physical products. The processes are linear there. Taylorian.

But Software Engineering is non-linear by nature.

**Examples:**

* Software Engineers are then considered "executors". They have no say in planning and design. Which is a waste and why so many organizations have so many problems at execution time and later. They are not expected in the design (or specification) phase, where they actually would bring the most value due to their unique understanding of software.
    
* The whole DevOps movement was born to address this question. Planning, execution, and delivery are the responsibilities of the same people.
    
* We plan as if improvements were terribly inconvenient and expensive. Planning is important. However, the planning scope and schedule are not the same as when you build a bridge. Planning itself should be iterative and continuous.   
    It’s very hard to build Bridge 2.0. It’s very easy to build Feature 2.0 since the tooling (CI, CD, testing, and processes) is part of Feature. (you usually don’t keep the crate and workers around Bride 1.0 more than necessary. You dismantle them)
    
* [The cost of maintenance is never accounted for](https://cutlefish.substack.com/p/tbm-234-maintenance-ktlo-and-bau). *“Which team is almost done with their feature so we can give them another one?”*
    

---

2/ Non-engineer people are usually kept out of the execution and maintenance, hence failing to understand the extent of complexity of scale and speed of the software world.

**Examples:**

* [The complexity of a 99.99% SLA is ~50x higher than a 99.5% uptime](https://world.hey.com/itzy/uptime-guarantees-a-pragmatic-perspective-736d7ea4) [commitment. I’m pretty sure everyone would prefer signing a cont](https://world.hey.com/itzy/uptime-guarantees-a-pragmatic-perspective-736d7ea4)ract with a 99.99% uptime commitment. But does it have any value? Most of the time, not, and most of the time, it cannot even legally be achieved since our cloud platforms (running the internet) don’t have that kind of SLAs themselves…
    
* A house in a non-seismic area, a non-war zone, would have SLAs at 100% for 20 years or more. No one talks about SLAs because the ground on which it's built, and the supply chain of materials needed for maintenance also have this kind of SLAs.
    
* [If your car br](https://arstechnica.com/information-technology/2016/03/rage-quit-coder-unpublished-17-lines-of-javascript-and-broke-the-internet/)eaks down below 100,000km or 3 years, you're unlucky an[d the manufacturer will accept a warranty case most likely, because you're an outlier.](https://arstechnica.com/information-technology/2016/03/rage-quit-coder-unpublished-17-lines-of-javascript-and-broke-the-internet/)
    

---

3/ The supply chain and factories are part of the product design, not separated, like houses and cars.

**Examples:**

* Building a website for 10,000 users is not the same cost as building it for 10'000'000. Although from the outside, it looks the same. It's not the same product. And no, it's not just a question of type of EC2 instances...  
    When you build a car, whether you build 10,000 of them or 10'000'000 of them, the bulk of the difference is on the supply chain and factory, hardly on the car's design itself.
    
* If you consider the infrastructure for a 10 million-user website to be similar to the "factory" that will build 10 million cars, you've been fooled by a bad analogy.
    

---

4/ The differences in crafts between engineers are not the same as those in construction.

**Examples:**

* To an extent, a C++ engineer and a Javascript engineer cannot exchange their seat and be as productive. Although, both of them can build a web cloud app, and both of them can build embedded software. Because they have all an understanding of how software works and how CPUs process code, and their environment allows that.  
    I would never ask an electrician to build an entire house from scratch. But if all I have are Rust engineers around, I would feel confident they could build us a web app.
    

---

5/ Value offering and definition of done

* Since we have this idea that things should be “finished” that comes from our physical world habits, we keep asking “*when is it ready*” instead of asking “*what will it solve*” in the virtual world.  
    Indeed, a car or a house has to be finished to be used. But the “definition of *finished*” for software is way more difficult to pin down.
    

---

6/ Missed opportunities and cost reduction

* Comparing software with physical counterparts prevents us from thinking in terms of opportunities software can bring, like scale and fluidity of the business relation. Instead of seeing our customers as long-time partners, we see them as if the relationship exists only when we make financial transactions (a one-time exchange of money for a physical good). Hence we sell them readyness dates instead of selling them a problem-solving system that evolves with them.
    
* Instead of seeing a continuous value stream, we think of 1-time specifications mapped to 1-time deliveries and 1-time payment.
    
* Instead of looking at a world of opportunities, we look at our known physical area (district, town, country, etc.) and fail to comprehend how the same software can reach 10, 1000, or millions of people.
    
* Inversely, it makes us think that focusing on a niche today prevents us from conquering the world later. So, we tackle all the problems all the time and fail to comprehend the complexity it brings. *Chasing peta-rabbits prevents us from bringing a few thousand rabbits home now.*
    
* Thinking this way prevents us from helping our customers think otherwise. I am still amazed at how the leading exchanges between software providers and customers — especially in the B2B world — still look like a long list of specifications (RFP) rather than regular and common design workshops.
    
* Instead of failing early (meaning discovering the social or business uselessness or infeasibility of our ideas early) and redirecting our funds and brains to something worthwhile, we double down on initiatives and work because “it’s not done.” We waste time and money doing things that are not validated because we think they need to be “built completely the right way” to deliver value.
    
* Work-in-progress in the physical world is simple to see. It’s physical. You get a pile of crap somewhere that has cost in itself (metal, bricks, etc…)   
    Work-in-progress in software is intangible and difficult to measure. It’s invisible, yet it has an incredibly high cost on productivity, adaptability, and value creation that companies who don’t understand software fail to reduce.
    

### Closing words

* The best Software companies understand the fundamental differences between software engineering and other engineering disciplines up to the CEO and board level. If not, software engineers and product managers are condemned to deliver software like we buy cars. When nobody needs cars anymore, the car company ceases to exist.
    
* If you are the CEO/manager/customer of a Software company and your software people are explaining things with analogies, you probably need to take a few courses and try to push Python to production before you tell them to give you a date. If you think I talked about a snake, you should retire.
    
* If you’re talking with your parents or your spouse, keep the analogies… It will make the Sunday dinner more enjoyable.
    

And if you insist and still need an analogy, try using “gardening” or “sailing a boat through the oceans around the world”. It’s not perfect, but it’s still an improvement.