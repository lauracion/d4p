# Data for Policy 2019 - Wednesday, 12 June 2019


09:30 – 10:30 Parallel Session 4
Session 4a (JBR): Hands-on-Data: Artificial intelligence for the design of public policy in Latin America
Chair: Tom Smith (@_datasmith), Office for National Statistics, UK (@DataSciCampus)

Slides for these four talks can be found [here](https://docs.google.com/presentation/d/1ZEwh0_R-zg9hu07qNerlrojNo2N5tfBWxxnyWfCmID4/edit?usp=sharing)

[80a] "Hands-on-Data: Description, lessons learned, and future directions of a speedy alternative to integrate artificial intelligence into the design of public policies in Latin America"; Lucila Berniell* (@luberniell), Laura Acion (@_lacion_) and Walter Sosa-Escudero (@wsosaescudero) - CAF, CONICET-UBA and Fundación Sadosky, CONICET-UdeSA, Argentina (@funsadosky & @institcalculo).

[80b] "Computing accessibility metrics for Argentina", Carlos Sarraute (@ch4rleston) - Grandata, Argentina (@GrandataLabs).

[80c] "Using data science to improve public transport in the city of Córdoba (Argentina)"; Andres Vazquez (@avdata99) - Municipality of Cordoba,
Information Systems and Innovation, Argentina (@MuniCba).

Q&A session:

Q: How did you prioritize the projects, problems, questions? A: CAF had an agenda of topics of interest such as labor, health, education, infrastructure. Through SIEMPRO, we were able to have access to some public sector officials working with these topics and who were acquainted with the data. Fundacion Sadosky also contributed its own network of public sector officials with questions to be answered with data.

Q: How do you see these types of initiatives replicating in ten years? A: it is already replicating because the tools developped where open source and where left in repositories. Also each project included some kind of data science literacy for the public officials that participated. Most of the projects are being continued beyond HoD. HoD will be replicated in Uruguay and Colombia in 2019

Q: Does this scale? Is it sustainable? How? It is a difficult question for which the world is still looking for answers. For instance, NY Gov Lab has 250 successfull data collaboratives but it is working to find ways to go beyond the prototype level. In Latin America this is one of the first frameworks that started working. A little funding from CAF and the interaction with scientists in the national scientific system was essential and should be fostered. Gov data labs that take on small projects as proof of concepts before scaling to larger projects are also a good route.

11:00 – 12:00 Keynote Lecture 2 (JBR)
"How to tell when a tech is not ready for government" – supported by GovTech Lab
Jon Crowcroft (@tforcworc), University of Cambridge (@Cambridge_Uni) & Alan Turing Institute (@turinginst)
Chair: Innar Liiv (@innarliiv), Tallinn University of Technology, Estonia (@TallinnTech)

* super provocative keynote with a lot of hot points about "established truths"

* usually, techno optimists oversell readiness (eg internet 1980 versus web 1992, broadband access 2000 vs smart phone 2007, use of internet for hospital booking reminders - still not used, using sms now, the right tech; use of babylon systems for triasge 2018, wellbeing/fitness data from accelerometer, when?; nhs supply like pharma or dressings chains, when? All of that was supposed to be *fast*. 

* Ancient history: internet, email available & negotiable; payment & funds transfer, paypal, musk was the first 1; web: transparency, publishing transport, energy, crime data; cloud affordable compute & analytics, but late to the game.

* Will focus on three technologies: 1. distributed ledger technology (dlt), 2 machine lerninng and ai (ml&ai), 3 internet of things (iot). For people interested in sustainability, none of these technologies were sustainanble when they started for many reasons, including legal reasons. Machine learning can be sustainable, but its more advanced techniques like deep learning are not that sustainable, it requires tons of tagged data and tons of processing gpus, with a large carbon print. It does not escalate to public policy... imagine increasing the carbon footprint while modeling climate for instance or the latency times of a system to attend to millions of public transactions 

* IoT can be a massive fail in many places - heard about printer setup failure? what hope can we have with coffee machines hooked to the internet when sometimes even the internet may not get good signal. somehow some people are finding ways to make realiable things work worse than now by including internet in them.

* dlt concepts. do not mix up cryptocurrency and blockchain. immutable record of transations, but so is a database. smart contracts, but so was ecommerce. why not gov? 3 essential requirements, decentralised? nope. no single point of trust? nope. Long term persistent? maybe

* dlt #2. ask someone peddling blockchain: what transaction rate do you support (read/write)?, what is the latency per transaction commit? where is your open source/spec repo? If the tech is ready for the huge numbers that different use cases can generate, then it is ready for gov

* ml/ai. do not mix up ml and ai. (really like this differentiation between ml and ai): ml is just better stats with bigger faster compute/storage, please use, more! Already used in much gov. but what about ai? anything that isn't explainable. how would gov use black boxes? (#rant about deep learning, of course :-D ), ever, pray? The first implementation of MCMC was 75 years ago, AI? hmmm, not much new under the sun, or at least not so many things are that new after all.

* putting technology into work that can harm people (eg false positives in sentencing) is something to take into account for readiness.

* ml/ai. ask an ai peddler: what's your interpretability model? how did you de-biased your training data (gem: "try sending white people to jail and see what happens with that algo")? where are your reprodicability (reproducibility + replicability - brilliant) results? if all of these can be answered, the tech may be ready for gov. otherwise, not a great idea.

* IoT. do not mix up internet (of things) and smart X. for x = home, car, city. Most IoT systems are silos, cctv, smart meter, fitness monitor&actuator; for good reasons, not just privacy, *safety* is paramount - car brakes, defibrilator, etc. What would gov do: regulate safety, please... eg liability if dont match MUDs, require data minimisation

* IoT#2. Ask to IoT dealer (yes, the person selling you that washing machine that you will hook to internet): where are your product liability statements? waht are the published APIs for me to integrate with other IoT products? What are your software update&suppport plans 6-10 years now for any current product? OMG, compatibility! Sustainability over time... imaginge your washing machine hacked because it lacks a security patch due to a security exploit discovered some months after it was bought.

* generic gov tech lessons. dont listen to academics, massively too early. dont listen to industry, massively too late. especially dont listen to consultants, massively too expensive. _so who do you listen to? all of the above, with a pinch of salt._ hire a lot of people with different literacy on computer, stats, security, and domain experts too. 


Session 6a (JBR): Successful Uses of Data Science and AI for Public Good
Chair: Dave Johnson (@New_To_Dave), Office for National Statistics, UK

[6] "Identifying AI talents within LinkedIn database A machine learning approach"; Thomas Roca (@Thomas_Roca) - LinkedIn (@LinkedIn)

* bringing evidence to the debate of use of AI

* a nontrivial problem, identifying ai talents in linkedin. standard approach in the economic literature is to rely on keywords search, skills, or standardized info. but ai is not a job, it is a broad nonstandard field. and ai is trendy and all that glitters is not gold. Search for ai talent in Linkedin using AI keywords is like looking for a needle in a haystack.

* how to capture ai related workforce hidden in linkedin? Kywords like ai or machine learning triggers profiles such as: ai and ml recruiters, solution sellers, data scientistis, managers etc

* ML for text classification. assumptions: with generic keywords we capture more than the actual ai practitionners population. For ml a traninng set is needed. job offers are good proxies for member profiles. job offers provide a more consistent information in its job title, job description, associated skills vs members profiles.

* ML for text classification. procedure: 1st capture ai relted workforce broadly, using keyword search. 2nd filter the results using a ml model trained with characteristics extracted from job advertisements. the training set included ai and not ai categories to be able to sort out people working in ai and others. All the details of the methods in the paper uploaded to Zenodo. This was done for the EU. All the restuls will be published in september.

* the data will be public with a website when the report is launched in september

[94] "Detecting Areas of Potential High Prevalence of Chagas in Argentina"; Antonio Vazquez Brust, Tomas Olego, German Rosati, Carolina Lang, Guillermo
Bozzoli - Fundación Bungey Born, Argentina, Diego Weinberg - Fundación Mundo Sano, Argentina, Roberto Chuit – Academia Nacional de Medicina, Argentina, Martin Minnoni and Carlos Sarraute* (@ch4rleston) - Grandata, Argentina (@GrandataLabs).

* Chagas Disease. Inspiration: John Snow cholera cases map in 1854. pioneer data viz. chagas is a neglected tropical disease affecting 65 M people exposed in more than 21 Latin American countries. It has a long asymptomatic phase. You can have the parasite for 20 years wo presenting any symptoms. The vector is called the kissing bug. In Argentina you find Chagas in the Gran Chaco with 1 to 2 M people infected (little stats... 1 M dif between those). Only 30% of all infected will develop severe heart disease. Gran Chaco is a rainforest, of poor people in the North of the country with little attention from the government.

* There is transmision from mother to child. The foundations funding this work are focusing on this aspect now. It can be avoided but there is lack of official stats and public detection campaigns. So it is necessary to know where the people infected live to do something.

* Afinity index. Used Mobile Phone data anonymized call detail records from one national telco. 5 months of data. First the residence location of user. Then the communications with endemic users. Heat maps are generated at the antenna levels. The color depends on the use of antenna for the subjects that interact with the Gran Chaco. You can map the amount of interaction between subjects in the Gran Chaco all over in Argentina. This helps identifying areas that are not covered by campaings for Chagas such as Patagonia that is very far away from Gran Chaco and does not have the vector.

* Housing conditions from census data: predominant material of the floors, of the roof exterior - identified the housing conditions that are good for the vector. Added this info to the afinity index

* Health vulnerability: access to health services from the state + socio econommic index of the population. accessibility to hospitals and their life conditions. These two ingridients were added to a chagas potential prevalence index (ChPPI) to prioritize detection campaings in the field. The index is calculated for each census area. A map is generated with the ChPPI. The prevalence is higher in the  Gran Chaco as expected, but also Tierra del Fuego y Buenos Aires have some unexpected prevalence.

* Conclusion: heat maps show temperature falling from Gran Chaco outwards. The affinity does not decrease in a continuous gradient as the localities move away from the endemic area. Localities were detected in the Province of Buenos Aires and Patagonia whose degree of affinity is much higher than population centers in provinces closer to the Gran Chaco. This suggests the existence of considerable migrations from endemic regions to the highlighted localities.

* Future: detection campaigns in the upcoming years analyzing the maps generated from the data + expert input. The map helped include Patagonia in the cmapaign due to these findings.
