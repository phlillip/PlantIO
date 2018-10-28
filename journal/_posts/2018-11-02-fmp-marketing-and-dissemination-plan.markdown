---
layout: post
comments: false
title:  Marketing & Dissemination Plan
tagline: Assignment 3
date:   2018-10-02 12:00:00 +0000
categories: FMP
---

<h2 class="text-center">PlantIO</h2>
<img src="/media/ruuts__tech.svg" />
<h3 class="text-center">Grow perfect food, automatically.</h3>

<span class="contents-title page-break">Contents</span>
* TOC
{:toc .NOshallow-list}

## Product Overview

### Value Proposition

> PlantIO allows you to grow perfect food for your family all year round at a low cost to you and the environment, completely automatically.

### Summary
<div class="flex-col">
<p><strong>In the developed countries of the modern world we are now eating a wider variety of foods than ever before, with incredible accessibility. However, this global transportation of food comes at a cost, creating issues which society is becoming more informed about, such as the quality of our food, its true origins and what it really means to be organic, and what impacts this process is having on the environment.</strong></p>

<p>The fact is, it is far easier to have a seemingly limitless supply of food any time of the year than it is to try to grow our own. Time, space, and our attention spans are at an ever increasing premium. Food is one of the 3 key elements all humans need to survive, along with warmth and shelter, and it deserves more of our attention. We can do better, and here at Ruuts we have done better.</p>
</div>

#### Description

**PlantIO is a fully automated system for controlling and managing all aspects of plant growth. Controlled from pre-selected recipes, it provides for all your plants' needs until it comes to fruition, only contacting the user in the event of an emergency or when the plant is ready to be harvested.**

For further information, reference the [differentiation compared to competitors](#differentiation-compared-to-competitors) section.

#### Features

PlantIO provides complete control of plant growth. Watering and feeding, light exposure, and temperature are all delivered to exact specifications based on your starting seed. Using our 'recipes' we do all the hard work for you.

The PlantIO app monitors all aspects of the plants' health and adjusts the system as required, only sending you notifications if emergency situation arise. Of course, users can check the status of their plant at any time using the real-time status screen.

##### 3 steps to success

<div class="flex-col">
<div><h5>Connect</h5>Simply connect your PlantIO system with your account via wi-fi, select the recipe you desire; place your seeds into your system and the germination phase then begins automatically.</div>
<div><h5>Select</h5>The PlantIO app will monitor the seeds as they develop into sproutlings, and when ready, PlantIO will instruct you to select the superior sproutling and remove the others.</div>
<div><h5>Collect</h5>The PlantIO app will now monitor complete growth of the plant and let you know when it is time to pick the final fruits.</div>
</div>

##### Freedom of growth

This fully automated growing can be adjusted to give you back some control; we provide two extra kinds of recipes to live alongside the fully automatic variety.

<div class="flex-col">
<div><h5>Automatic</h5>Simply connect your PlantIO system with your account via wi-fi, select the recipe you desire; place your seeds into your system and the germination phase then begins automatically.</div>
<div><h5>Semi-automatic</h5>'Semi-automatic' recipes work in the same way as standard fully automatic recipes, however they notify you when it's time to feed, water or give light to your plant rather than doing it automatically. You must then use the apps to control the grow system yourself, in real time.</div>
<div><h5>Manual</h5>Finally, we have 'manual' recipes which provide no instructions whatsoever; it is up to you to decide how and when to care for your plant. This can be set up ahead of time or managed on the fly, just as you would a normal plant.</div>
</div>

##### Evolutional database

All plant data is recorded so you can save any recipes which work particularly well and share them  with the Ruuts community, this will help to evolve our recipes over time for growing food to specific requirements; the biggest tomato, the crunchiest lettuce, the best looking strawberries.
90% of the components of the Ruuts system can be 3D printed if replacements or additional modules are required - meaning the home user can expand at very little cost.

#### Technical information

##### Software
* Progressive Web Application (PWA) communicating with the hardware through the johnny5 javascript library.
* 24/7 remote access from any internet enabled browser
* Cross platform, single codebase, automatically updating software
* Optional manual & semi-automatic modes enable more interactive growing

For the technology stack, a PWA was chosen to ensure maximum accessibility. Users can check their plant status regardless of the device, so long as they have can access a web browser. Each PlantIO system comes with it's own Raspberry Pi Zero W allowing it to connect wirelessly to the internet, and Arduino controllers are used to turn the PlantIO signals into actions.

The user can monitor their plant at any point using the PWA from any device with a web browser. The PWA communicates with the PlantIO hardware, which takes the form of a blackout growing box housing LED lights for complete control of lumen levels, an aeroponic atomiser nozzle for accurate delivery of food and thermostatically controlled heater to maintain the optimum ambient temperature.

##### Hardware
* Custom built blackout enclosure extends to any plant size and ensures complete separation of light from plant roots.
* Aeroponic atomiser nozzle delivers exacting amounts of feed at the optimum atomic size to enable maximum nutrient uptake from the plants roots
* LED lighting delivers the optimum wavelength for the plant at extremely low energy consumption levels and zero heat creation.
* Thermostatic heater element maintains optimum temperature of enclosure 24/7 with minimal power usage.

##### Dataware
* Databank of recipes specify exact feed, light and temperature requirements for each plant, delivering perfect day/night cycles and rest periods.

### Audience
>> Millennial families looking to appear aware and improve their diets with minimal effort through the use of technology.

#### Millenials
<img src="/media/persona__millenial-man-mark.jpg" style="float: left; width: 25vw; margin: 0 1em 1em 0" />
Millenial man Mark is a highly aware individual; happily married with a very young family and a busy schedule. Mark is aware of the environment, aware of what we eat, and aware of our impression on others. Mark see the popularity behind lifestyle choices and provides an opportunity for marketing purposes for our product. Defined as a first-time passive user of the system, Mark will be looking for results and will use the system in fully automatic mode to fit in with his busy schedules. Should he see success with the system he is likely to form part of the subscription base, he has disposable income which he is happy to use to improve the quality of live for his family.

Frequency | First time | Intermediate | Casual | Power |
Engagement | Passive | Active | Advocate
Usage | Enthusiast | Prosumer | Professional
Vertical Specific | Hobby | Home | Business
Channel | Social | Inbound | Traditional Ads
Sales Funnel Position | High | Middle | Low
Financial Model | Free | Freemium | Paid | Enterprise
Handling User Needs | Automatic | Semi-automatic | Manual | AI
{:.channels}

#### Other segments

##### Generation Z
Youth Yasmin, part of "Generation Z" is in her early twenties and is an avid gym goer and clean eater. She loves to travel, loves animals and is an active blogger. Yasmin provides a huge opportunity for free marketing - the Instagram generation are all too eager to show off their exploits to their followers, particularly when it comes to health and their bodies. What can be healthier than the purest, sustainable food possible? Unlikely to create revenue through the subscription model, Yasmin will require a workable free setting to continue using the product. We expect Yasmin to want increased product engagement so will be using the semi-automatic recipes and documenting her every interaction via social media. Strong app branding is important for all the screen time Yasmin will generate. She will appreciate the fine UI details such as subtle animations, and a fast, smooth experience.
##### Environmentalists
Environmentalist Ed is highly aware of the damage the human race is doing to the planet, and seeks to promote a better way of living in all that he does. He rides a bike everywhere, and people know it. He recycles everything in his home, and people know it. One of our power users during the first phase, Ed will be an advocate for the system, preaching to his peers about the massive benefits it brings to society and the health of the planet. Ed will provide plenty of product feedback, and use his system religiously, yet will push for freedom of use and likely not contribute much in the way of direct revenue. Ed's value is in his evangelic promotion of the idea and rigorous testing.
##### Small Business Owners (stage 2)
Chef Cheryl is a small food business owner, serving vegan food from her converted van. Though forming the bulk of phase 2, it is important to connect with Cheryl during the first product phase, she needs to believe that this is a product that can take her business to the next level. It needs to provide economic benefit, as well as seamless operation. Cheryl will likely upgrade to a paid installation to suit her needs, and demand A.I. technology from her recipes to ensure she is growing the best possible food for her business needs.

## Go-To-Market (GTM) Strategy

<img src="/media/ruuts__model.svg" >

### Business Plan

>> A four stage business model initially targeting the consumer market, reaching into small businesses and finally entering the industrial market. Space is the final frontier.

#### Strategy
The Ruuts business model is composed of 3 major sequential phases&mdash;consumer, business, and industrial. There is a 4th end goal phase which the company is always driving towards.

##### Phase 1
Ruuts will launch directly into the first phase which will focus on the consumer market. Initially, revenue will be generated through the sale of systems and equipment for occasional, home-based use, accompanied by the corresponding phase 1 of the PlantIO app. During this phase, everything will be open source in line with the values of the company; individuals will be free to use our code and create their own systems. The consumer will serve as a major source of promotion for the company during this phase and help Ruuts gain traction within the press and social media.
The controlling application will be free to use for the first 3 harvests, giving the user enough time to benefit from the technology and have it form a part of their lifestyle. After this period, a subscription model will be implemented, charging monthly operating costs if the user wishes to have the full version of the software; otherwise they will be limited in some way, either by functionality limits or advertisements, yet to be determined.
Continual investment will need to be made into promotion, online presence, and product development as issues are ironed out and consumer recommended enhancements are implemented. In addition to this, product development will need to be made into preparing for phase 2.

##### Phase 2
Having gained stability and popularity within the consumer market, we will shift a portion of our focus into business applications; investment will now concentrate on semi-bespoke installs for small businesses in return for promotion. Using our modular designs, this approach can also be adopted by consumers to set up their own larger systems. The app will be further developed to monitor multiple connected systems and help businesses create growing plans to maximise daily yields.

##### Phase 3
With exposure from small business applications will come interest from larger-scale industrial applications; supermarkets are an obvious candidate for bespoke installation of bolt-on 'Ruuts-Farms' on their premises. Investment during this phase will be into a large-scale demonstration system providing free produce for charity and food banks, doubling as a live exhibition for potential investors. The app will be developed in the areas of security and scalability, with careful assessment of the back-end services to manage big plant data.

##### Phase 4
The fourth and final phase of the business will focus on extreme environments such as polar, desert, and space, with the company heavily investing into development in these areas to become a world leader in this market segment. The development of a cost-effective, self-sustaining container farm that can be deployed in areas of need will be the first focus.

[//]: # (The first key business growth driver is strategy. Every fast-growing business starts with an idea, which turns into the business plan. The strategy might revolve around bringing a new product to market, or be based on an existing product or service applied or delivered in a new way. Accelerated growth can be driven by developing more new products, and/or expanding into new markets.)
PlantIO will initially serve the consumer market with advanced technology for a competitive price, backed by social. Following this, the B2B market will be targeted through custom installations before eventually being positioned to provide a viable solution on an industrial scale. The ultimate goal for Ruuts is to grow plants in space with their PlantIO technology.

#### The Ruuts Team & Operations

[//]: # (Alongside strategy, people and operations represent another key growth driver. Companies that grow fast often have a key individual driving them forward – the person with the initial vision, energy and determination to step out along the entrepreneurial road. However, growing a business fast relies on teamwork. Entrepreneurs need to draw around them a group of individuals who they can trust, who share the same dreams and apply the same values when trying to bring that dream alive. On the operations side, a growing business needs to develop an appropriate infrastructure and keep adjusting that infrastructure as the business grows. This involves IT systems, processes, even basic office space. If you are growing fast, will you have enough room for your expanded team in six months’ time? And as the business grows, new operational systems may need to be developed to maintain efficiency.)

<div class="flex-col" style="align-items: center">
<img src="/media/ruuts__team--combo.svg" style="height: 40vw" />

<blockquote><p>Ruuts is powered by 3 founders all of whom are key individuals with unique, complementary skills.</p></blockquote>
</div>

We combine the perfect mix of an experienced product designer in myself, with over 15 years of professional design experience, focusing on the digital side of the business, developing the software and social strategy; a horticulture expert in Brett Bartlett with a vast knowledge of plant growth characteristics and an aeroponic research programme behind him, focusing on developing optimum plant recipes to ensure a quality end product. and electronics engineer Ashley Banner who specialises in designing electronic systems with off-the-shelf components to create bespoke products, essentially taking Ruuts designs and turning them into a feasible, realistic tangible product; focussing on develop the hardware systems.

<div class="flex-col">
<p>Ruuts have successfully worked together on a separate startup - <a href="https://carboncandy.co.uk">Carbon Candy</a> - producing bespoke carbon fibre and more recently 3D printed components for various industries, focusing on the drone industry of late, with a multi-page publication in Drone Magazine.</p>
<p>Carbon Candy was designed as a stepping stone into Ruuts, enabling us to acquire the skills necessary build our own system using advanced materials, as well as learning the skills required to work together and form a successful business.</p>
</div>

#### Funding
[//]: # (Clearly no business can grow fast without the right funding, and so capital is another key growth driver. Finding the right form of financial backing, and at the right time, is critical. That’s not to say that high growth can only be achieved with large amounts of funding, or that high funding levels will automatically result in fast growth.)

**Ruuts are looking for £250,000 of funding to take the product to market.**
This will cover salary for all 3 founders over the course of 15 months of product development, starting in January 2019 after creation of the MVP. It will also cover investment in an initial stock of 100 PlantIO units.

#### Transactions
[//]: # (Transactions are also important for driving growth. These could include alliances in the form of strong supplier relationships. In addition, as the business grows, mergers and acquisitions may offer the potential to achieve a step change in growth, or facilitate entry into a new geographical market or a complementary service area.)

**Several opportunities are available to increase conversions and sales.** Potential relationships with established seed suppliers such as Mr. Fothergills can add a reputability to the business in its' early days. The opportunity to create a charity serving global hunger can further strengthen out reputation.

#### Risk & Reporting
[//]: # (Last but not least among the five business growth drivers comes risk and reporting. As the business grows, so it is essential to establish controls to manage the inevitable risks that accompany rapid business development. The reporting element is also important for growing companies, both internally and externally. Management teams need to communicate clearly between themselves, to understand business performance and delivery against future targets. Similarly, the company needs to report effectively to external investors and other stakeholders to maintain their ongoing confidence and support.)

#### Key Performance Indicators

Though there is plenty of research still to be done on our pricing model and component selection, we have still generated a basic 3 year plan to focus our efforts.

##### Year 1
Initial product development will offset the revenue from early sales and subscriptions as we respond to user feedback and solidify our offering. Investment will also go into maintaining an active online brand that is engaged with users and responds to the social environment. Product development will be focussed on optimising the application with its current feature-set, and developing the system in preparation for small to medium business installs.

##### Year2
Sales in the business segment will again be offset by further product development and marketing of the business, any profits being re-invested into the company to build a fully working bespoke demonstration system.#

##### Year 3
We expect to provide a slight return on investment with the launch of our complete system which will truly cater for all market segments and allow us to approach larger companies for bespoke installs and custom management solutions.

Goal | KPI | Year 1 Target | Year 2 Target | Year 3 Target
---- | --- | ------------- | ------------- | -------------
Mass adoption of consumer unit | Number of sales of the PlantIO system | 100 | 500 | 5000
Active, growing knowledge base & online community | Number of monthly active users (MAU) on forum | launch | 50 | 500
Integration into SMB market | Number of custom installs | 1 | 10 | 50

#### Strategic differentiators

PlantIO is differentiating from the competition in two main areas:
 * Pricing model
 * Product offering

#### Market Behaviours

[TODO] Reference to the instagram generation and free marketing, early adopters etc etc

### Projections

### Product Strategy

[//]: # (This section of the plan identifies the key products you will launch in your cloud portfolio, along with any bundling plans, special promotions, or other attachment strategies that will help you sell the products—including upselling and cross-selling to both new and existing customers. Any specifics you can include about differentiators between your offerings and those of your competitors will help you build your sales messaging as you progress further into the launch.)

#### Key Products
* PlantIO base system
* Heirloom seedpacks
* PlantIO app

##### Special Promotions / Attachment strategies

##### Up-sells & Cross-sells

Component | Base | Upsell 1 | Upsell 2
---- | --- | ------------- | -------------
Feed | Basic mister | Low pressure nozzle | High pressure atomizer
Light | LED | Multi-color LED | Low-power LED
Temperature | Basic thermostatic element | Min-max thermostat | Low energy thermostat
Enclosure | Basic fabric skeleton | Modular enclosure | AR Enclosure

Upsells are a key part of our product strategy; the user can purchase the base system at minimal cost and upgrade virtually all of the components depending on their budget and requirements. Cross-sells include offering heirloom seed packs with every purchase as well as recommended plant feeds.

##### Bundling plans

Similarly to the individual component upsells and cross-sells, bundles will play an important role in our product strategy. Essentially combining upgrades from each component into its own bundle along with seed packs and feed.

##### Differentiation compared to competitors

**Using the Ruuts growing system, we can grow perfect food, whenever we want, wherever we want, really fast, using trustworthy seeds, saving water, saving land, saving the planet, all automatically. We can grow enough food to feed our family, with virtually no time cost. We can teach our family how to grow food and care for plants using optional manual or semi-automatic recipes. We can create our own recipes and share them with the world. We can even compete to grow the biggest tomato, the brightest, the tastiest or the fastest.**

Aeroponics is used to grow the plant, negating the need for any soil and reducing the water and land usage by over 90% compared to traditional growing methods.

Aeroponics is used to feed the plants and is the most advanced growing technique available. Plants are suspended in a growing medium in air&mdash;normally gauze or cotton&mdash;and the roots are misted with controlled droplets of feed to ensure they have optimum nutrition uptake, without the need for soil.

<div class="flex-col">
<div><h3>95%</h3>less water</div>
<div><h3>90%</h3>less land</div>
<div><h3>30%</h3>faster</div>
<div><h3>no</h3>pesticies or fertilisers</div>
</div>

We will focus on 5 key areas of differentiation:

1. Quality (conditions)
2. Trust (organic)
2. Environmental (low-impact)
3. Speed/consistency/reliability (due to conditions)
4. Convenience/automation (time/involvement)
5. Availability (24/7/no seasons)

<!-- PLANET -->
The clean, secure, enclosed environment provided by the system negates the need for any pesticides or fertilisers; pests and disease are no longer an issue.
<!-- PERFECT -->
By providing the plant with the exact conditions needed for growth we can produce perfect quality fruit every time, maximising the potential of the seeds.
<!-- SPEED -->
All this allows us to grow food up to 30% faster using aeroponics;  and, by combining multiple systems and using our advanced scheduler, you can effectively remove the wait for growth after the initial harvest.
<!-- SEASONAL -->
By controlling the entire climate of the plant, we can render weather as a factor obsolete, meaning traditional seasons become a thing of the past and allow for true all year round growing.
<!-- LOCATION -->
The compact system enclosure will fit anywhere in your home - behind the sofa, under the stairs, in a kitchen cupboard, practically anywhere you can provide it with power. Growing food at home completely removes the need for global transportation because the food is grown in its final destination.
<!-- TRUSTWORTHY SEEDS  -->
Know exactly what you are growing by choosing the seeds yourself, thus giving you 100% control over the food you are eating. Moving forward we will offer ancient and heirloom seeds from our store so you can grow guaranteed unmodified foods, opening up a wide and diverse range of new tastes to try.
<!-- APP -->
Everything is monitored by the accompanying PlantIO application to provide constant, real-time feedback to the user about their plant and serve as a community for sharing growth recipes, providing feedback for further product development, and giving control to the user to grow their plant their own way using our semi-automatic and manual recipe settings.

There is a huge gap in the market for our product; our competitors either cannot match our technology, or our pricing models, or our scale.
Small hobbyist programs such as PlantFriends are free, but are not suited for substantial, regular food growth and require significant user investment to set them up and get them working.
FarmBot, our nearest competitor, have an attractive and unique application, however they offer an entry level option of over £2000, yet still requires outdoor growing space and uses dated farming methods.
AeroFarms are a huge player and serve the industry with prices starting from tens of thousands of dollars. They use advanced technology and are really focussing on the top end of the market.
The Sahara Forest Project is at the very top end of the industry, setting standards in growing in extreme conditions and are a serious competitor for phase 4 of our business model only.
There is an opportunity for low cost, low management convenient home growing using advanced techniques. All of the systems around the pricing model for our phase 1 users are vastly overpriced for what they offer; for example, the £99.50 KRYDDA/VÄXER from IKEA is simply a two tier stand with slots to grow 16 small plants, or approximately 200 lettuces from the supermarket. The Conran Shop are selling the "Smart Garden 9" which boasts NASA technology in the form of smart soil, provides slots for 9 small plants at the whopping cost of £199, or 400 cucumbers.
The closest competitor with an app is the Flower Care Smart Monitor, which is nicely designed and professionally presented with strong branding, including a well thought out UX, however it provides no automation and utilises none of the agricultural advancements the Ruuts system is built around, focuses on flowers and single use systems.
The competitor analysis has shown that the PlantIO system provides multiple USP's and will target an underserved segment of the market.



### Channel Strategy

[//]: # (This is where you identify the primary channels that you’ll use—both to sell your products and to educate and support your customers—along with the resources, training, and incentives that will drive channel performance. In complex channel organizations, products and offers may differ from one channel to the next, playing on the unique advantages of specific channels, such as direct sales teams or online portals.)




### Marketing Strategy

[//]: # (This section summarizes the activities you’ll use to drive awareness and generate leads, both in your identified markets and within your existing customer base. In large organizations, the marketing strategy may also include activities for generating internal awareness. Such internally oriented activities are particularly important in situations where many groups will “touch” customers as they progress from purchase to activation to support.)

### Customer Experience

[//]: # (This section documents the anticipated customer journey—either at a high level or in detail. Starting with how customers first hear about a product, it progresses through their purchase, activation, renewal, and possible cancellation. Exploring this journey helps to identify any “fall-off” points that may reduce conversion rates, or drive churn, while also helping to ensure that you’ll have the right people and systems in place to support the new products.)

### Technical Requirements

[//]: # (This section documents the technical requirements needed to support the new products. These requirements, which may be affected by decisions made in the previous sections of the plan, may include branding your customer-facing portals, and integrating sales and provisioning systems with third-party resources you’ve employed. Parallels can help you identify the technical requirements needed to launch your products.)

### Evaluation

[//]: # (This is where you spell out and prioritize the factors you’ll use to measure your success—for example, reaching a certain volume of sales in specific channels, or reducing churn of an existing product by attaching a cloud service. Try to be as specific and detailed as possible in outlining your goals and evaluation tactics—it will keep your team aligned and help to optimize activities through your launch.)

### Timeline and Execution

<img src="/media/ruuts__status.svg" >

[//]: # (Finally, your plan needs to identify the timeline for execution, including next steps, the critical path for decisions, key milestones, and plans for reviewing and fine-tuning the GTM plan. This last point should not be overlooked, as good GTM plans are not static, but evolve with the project. As your plans progress, you can add details to increase the plan’s accuracy.)

We are currently developing the minimum viable product (MVP); whilst I design and develop the PlantIO application, Ashley is sourcing the components required to build the initial system to for scenario testing, whilst Brett is conducting detailed research into plant growth to create the first of our recipes.

We expect the MVP to be ready in 3 months time, for our very first internal alpha testing which itself will run for a 3 month period. Following this, we will commit a further 6 months to product development and finalise the physical design and initial consumer model. We will then repeat our 3 month alpha test, and follow it up with a second 3 month period of improvements. This will then lead into the 3 month public beta test which, if successful, will allow for an initial product launch during the Autumn of 2020 in 21 months time.

> It is important for us to remain agile as a company, and we will be using the length of harvests (around 21-30 days) to line up our sprints.

The PlantIO System is at an extremely early stage of development, and requires considerable time dedication to product development. The physical components must undergo safety checks along with long-term testing, and the complete financial side of the product is yet to be calculated. Should the system be deemed to expensive for phase 1, we may have to begin our product in phase 2.

There is also the question of maintenance; as with any machine with moving parts, users will need to perform basic periodic checks on their systems. This maintenance procedure will be designed into the system, perhaps using sensors to check that the user has inspected the required components and cleaned where necessary.

#### Phase 1: MVP creation
We are currently developing the minimum viable product; whilst I design and develop the PlantIO application, Ashley is sourcing the components required to build the initial system to for scenario testing, whilst Brett is conducting detailed research into plant growth to create the first of our recipes. We expect the MVP to be ready in 3 months time, for our very first internal alpha testing which itself will run for a 3 month period.

| Key Deliverables |
--- |
Software | Software simulation of the PlantIO PWA
Hardware | Software simulation of the PlantIO PWA
Knowledge | A variety of recipes for the most common plants

#### Phase 2: Initial alpha test

#### Phases 3-5: Product Development Sprints
Following this, we will commit a further 6 months to product development and finalise the physical design and initial consumer model. We will then repeat our 3 month alpha test, and follow it up with a second 3 month period of improvements.



#### Phase 6: Beta Test
This will then lead into the 3 month public beta test which, if successful, will allow for an initial product launch during the Autumn of 2020 in 21 months time.

#### Phase 7: Product Launch
The PlantIO System is at an extremely early stage of development, and requires considerable time dedication to product development. The physical components must undergo safety checks along with long-term testing, and the complete financial side of the product is yet to be calculated. Should the system be deemed to expensive for phase 1, we may have to begin our product in phase 2.

There is also the question of maintenance; as with any machine with moving parts, users will need to perform basic periodic checks on their systems. This maintenance procedure will be designed into the system, perhaps using sensors to check that the user has inspected the required components and cleaned where necessary.

Period | Phase | End date
------ | ----- | --------
0-6 months | MVP creation | December 2018
6-9 months | initial alpha test | March 2019
9-15 months | product development | October 2018
15-18 months | second alpha test | January 2019
18-21 months | product development | April 2019
21-24 months | beta test | July 2019
24 months | product launch | October 2019



## Launch

### Beta Launch

The company will remain agile, specifically within the first 12 months of product launches in order to fine-tune the product and ensure a successful press launch. A beta-release of the system will be offered over a period of 90 days (roughly equating to 3 consecutive harvests) to 100 people serving the 4 main market segments of phase 1, with a free base system provided in return for regular feedback. A/B testing of fully automatic, semi-automatic and manual recipe settings will need to be conducted.

Following from this, a staggered product launch will provide the opportunity for users to buy in at a very low level, then upgrade components as the system forms part of their daily life and habits. The modular design allows for limitless expansion and upgrading, whilst the sharing of recipes will build a social community and a huge knowledge base.

A promotional campaign will run during the first phase as Ruuts provides demonstrations and education to schools, exhibition events and pairing up with local businesses to provide instant ingredients, likely to be served from a specially modified demonstration vehicle allowing for cross-country promotions.

### Press release

Embargoed for: 2019-10-01
{: .text-center}

> **Grow food, automatically.**

**The new PlantIO system allows you to grow perfect food for your family all year round at a low cost to you and the environment, completely automatically.**

Simply connect your PlantIO system with your online account, select the recipe you desire; place your seeds into your system and the germination phase begins automatically. The PlantIO app will monitor the seeds as they develop into sproutlings, and when ready, PlantIO will instruct you to select the superior sproutling and remove the others. The PlantIO app will now control the  complete growth of the plant and let you know when it is time to pick the final fruits.

> &ldquo;For too long our food has been compromised and an afterthought; it is one of the three key elements of survival and should be treated as such.<br />Take back control and grow your own.&rdquo;

Using PlantIO you can grow perfect food, whenever you want, wherever you want, really fast, using trustworthy seeds, saving water, saving land, saving the planet, all automatically. You can grow enough food to feed your family, with virtually no time cost. You can teach your family how to grow food and care for plants using optional manual or semi-automatic recipes. You can create your own recipes and share them with the world. You can even compete to grow the biggest tomato, the brightest, the tastiest or the fastest.

> &ldquo;Your plant can be accessed twenty-four seven using any web browser on any Internet enabled device anywhere in the world in a matter of seconds. Not that you'd ever need to.&rdquo;

**Ends.**

For further information, please contact Phillip Penny at [phil@plantio.co.uk](mailto:phil@plantio.co.uk) or on [07961732861](tel:+447961732861)

##### Notes to Editors

* Ruuts combine the perfect mix of a product designer, horticulture expert and electronics engineer.
* Photos are available on request.

### Social media

### Analytics

### Feedback Channels

### Bug Tracking

## Post Launch

### Maintenance

### Future Development

### Continued User Engagement


## Appendix

Competitor Case Studies

[ 1 ]  Farmbot
[ 2 ]  Click & Grow

FarmBot
COMPETITOR CASE STUDY


Figure 1: The FarmBot homepage ( https://farm.bot/ )

Location
USA
Mission Statement
Grow a community that produces free and open-source hardware plans, software, data, and documentation enabling everyone to build and operate a farming machine.
Product Offering
FarmBot Express (Not yet released)
FarmBot Genesis ($2,595.00 USD)
FarmBot Genesis XL ($3,795.00 USD)

Content
Blog posts  |  Whitepapers  |  eBooks  |  Videos  |  Webinars  |  Podcasts  |  Slides/Powerpoints  |  Visual content  |  FAQs  |  Feature articles  |  Press releases  |  News  |  Case studies  |  Buyer guides

Strengths & Weaknesses
Following the open-source route creates a strong community, and a very strong online presence provides documentation, forums, videos and reviews.
The system requires a big upfront investment, technical skills to build and setup the machine, and a large area of space to run, all the while using traditional inefficient farming methods.
Category of Competition
Primary  |   Secondary   |  Tertiary

FarmBot offer a high-end version of our product at a much higher price to a slightly different audience, using lower-end hardware.
Click & Grow
COMPETITOR CASE STUDY


Figure 1: The Click & Grow homepage ( https://eu.clickandgrow.com/ )

Location
USA & Estonia
Mission Statement
We create transformative technologies that allow growing fresh, vitamin-packed food locally and sustainably.
Product Offering
Smart Garden 3 / Smart Garden 9 (€99.95 / €199.95)
Wall Farm Mini / Wall Farm (€899.00 / €1,299.00)
Plant Pods (€9.95)

Content
Blog posts  |  Videos  |  Visual content  |  FAQs  |  Forum

Strengths & Weaknesses

Category of Competition
 Primary   |  Secondary  |  Tertiary

Click & Grow offer a low-end version of our product at a higher price to a very similar audience, using lower-end hardware and software.


> Let him who would move the world first move himself. - Socrates
