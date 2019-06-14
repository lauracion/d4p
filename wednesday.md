# Data for Policy 2019

## Wednesday: Conference

### Morning

Wednesday, 12 June 2019

11:00 – 12:00 Keynote Lecture 2 (JBR)
"How to tell when a tech is not ready for government" – supported by GovTech Lab
Jon Crowcroft (@tforcworc), University of Cambridge (@Cambridge_Uni) & Alan Turing Institute (@turinginst)
Chair: Innar Liiv (@innarliiv), Tallinn University of Technology, Estonia (@TallinnTech)
GovTech Lab (@GovTechLab) Introduction – Tom Wilkinson (DFID) and Giles Pavey (Unilever)

* super provocative keynote with a lot of hot points about "established truth"

* usually, obviously, whenthe governments not ready for tech. but more seriously techno optimist oversell readiness (eg internet 1980 versus web 1992, broadband access 2000 vs smart phone 2007, use of internet for hospital booking reminders - still not used, using sms now, the right tech; use of babylon systems for triasge 2018, wellbeing/ fitness dat from accelerometer, when?; nhs supply like pharma or dressings chains, when? All of that was supposed to be *fast*. 

* Ancient history> internet, email available & negotiable ; payment & funds txfer, paypal, musk was the first 1; web> transparency, publishing transport, energy, crime data; cloud affordable compute&analytics, but late to the game.

* With examples from dlt, ml&ai,iot. 1. distributed ledger technology, 2 machine lerninng and ai, 3 internet of things. For people interested in sustainability, none of these technologies were sustainanble when they started for many reasons, including legal reasons. Machine learning can be sustainable, but its more advanced techniques like deep learning are not that sustainable, it requires tons of tagged data and tons of processing gpus, with a large carbon print. It does not escalate to public policy... imagine increasing the carbon footprint while modeling climate for instance...

* IoT can be a massive fail in many places - heard about printer setup? what hope can we have with coffee machines hooked to the internet when sometimes even the internet may not get a good signal. somehow some people are finding ways to make realiable things work worse than now by including internet in them.

* dlt. do not mix up cryptocurrency and blockchain. immutable record of transations, but so is a database. samart contracts, but so was ecommerce. why not gov? 3 essential requirements, decentralised? nope. no single point of trust? nope Long term persistent? maybe

* dlt #2. ask someone peddling blockchain: what transaction rate do you support (read/write)?, what is the latency per transaction commit? where is your open source/spec repo? If government is ready for the huge numbers that different use cases can generate, then it is ready...

* ml/ai. do not mix up ml and ai. ml is just better stats with bigger faster compute/storage, please use, more! Already used in much gov. but what of ai, anything that isn't explainable. how would gov use black boxes (#rant about deep learning, of course :-D ), ever, pray? The first implementation of MCMC was 75 years ago, AI? hmmm, nothing new under the sun, or at least not so many things are that new after all.

* putting technology into work that can harm people (eg false positives in sentencing) is something to take into account for readiness.

* ml/ai. ask an ai peddler> what's your interpretability model? how did you de bias your training data (gem: "try sending white people to jail and see what happens with bias" )? where are your reprodicability (reproducibility + replicability - brilliant) results? if all of these can be answer, the tech may be ready for gov. otherwise, not a great idea.

* IoT. do not mix up internet (of things) and smart X. for x = home, car, city. Most IoT systems are silos, cctv, smart meter, fitness monitor&actuator; for good reasons, not just privacy, *safety* is paramount  - car brakes, defibrilator, etc. What would gov do: regulate safety, please... eg liability if dont match MUDs, require data minimisation

* IoT#2. Ask to IoT dealer> where are your product liability statements? waht are the published APIs for me to integrate with other IoT products? What are your software update&suppport plans 6-10 years now for any current product? OMG, compatibility! Sustainability over time... imaginge your washing machine hacked.

* generic gov tech lessons. dont listen to academics, massively too early. dont listen to industry, massively too late. especially dont listen to consultants, massively too expensive. _so who do you listen to? all of the above, with a pinch of salt._ hire a lot of people with different literacy on computer, stats, security, and domain experts too. 





09:30 – 10:30 Parallel Session 4
Session 4a (JBR): Hands-on-Data: Artificial intelligence for the design of public policy in Latin America
Chair: Tom Smith (@_datasmith), Office for National Statistics, UK (@DataSciCampus)


[80a] "Hands-on-Data: Description, lessons learned, and future directions of a speedy alternative to integrate artificial intelligence into the design of public policies in Latin America"; Lucila Berniell* (@luberniell), Laura Acion (@_lacion_) and Walter Sosa-Escudero (@wsosaescudero) - CAF, CONICET-UBA and Fundación Sadosky, CONICET-UdeSA, Argentina, respectively (@funsadosky & @institcalculo).


[80b] "Computing accessibility metrics for Argentina", Carlos Sarraute (@ch4rleston) - Grandata, Argentina (@GrandataLabs).


[80c] "Using data science to improve public transport in the city of Córdoba (Argentina)"; Andres Vazquez (@avdata99) - Municipality of Cordoba,
Information Systems and Innovation, Argentina (@MuniCba).


Session 6a (JBR): Successful Uses of Data Science and AI for Public Good
Chair: Dave Johnson (@New_To_Dave), Office for National Statistics, UK

[6] "Identifying AI talents within LinkedIn database A machine learning approach"; Thomas Roca (@Thomas_Roca) - LinkedIn (@LinkedIn)

* bringing evidence to the debate of use of AI. methods: a needly in teh haystack + results

* a nontrivial problemk, identifying ai talents in linkedin. stadndard approach in the econocimi grafph is to relly on keywords search, skills, or standardized info. but ai i not a job, it is a broad nonstandard field. and ai is trendy and all tah glitters is not gold> needle in a haystack.

* how to capture ai related workforce hidden inlinkedin. Kywords like ai or machine learning triggers profiles such as> ai an ml recruiters, solution sellers, data scientistis managers etc

* MLfor text classification. assumptions> with generic keywords we capture more than the actual ai practitionners poppulation. to us ml a traninng set is needed. job offers are good proxies for member profiles. job offers provide a more consistente triptych @job title, job description, associated skills@ vs members profiles.

* ML for text classification. procedure> 1st capture ai relted workforce broadly, using keywords search. 2nd filter the results using a ml model trained with characteristics extracted from job advertisements. the training set included ai and not ai categories to be able to sort out people working in ai and others. All the details of the methods in the paper uploaded to Zenodo. This was done for the EU and it will be published in september.

* the data will be public with a website when the report is launched in september


[70] (Demo) "RIS3-MCAT – a science and technology semantic mapping platform supporting specialisation, research and innovation policy and Sustainable
Development Goals roadmapping in Catalonia"; Enric Fuster* (@enric_fuster) - SIRIS Academic, Spain (@sirisAcademic), Tatiana Fernandez - Generalitat de
Catalunya, Spain, Francesco Massucci, Alessandro Mosca, Arnau Quinquillà, Xavier Gimenez and Guillem Rull - SIRIS Academic, Spain.



[94] "Detecting Areas of Potential High Prevalence of Chagas in Argentina"; Antonio Vazquez Brust, Tomas Olego, German Rosati, Carolina Lang, Guillermo
Bozzoli - Fundación Bungey Born, Argentina, Diego Weinberg - Fundación Mundo Sano, Argentina, Roberto Chuit – Academia Nacional de Medicina, Argentina, Martin Minnoni and Carlos Sarraute* (@ch4rleston) - Grandata, Argentina (@GrandataLabs).

* Chagas Disease. Inspiration: John Snow cholera cases map in 1854. pioneer data viz. chagas is a neglected tropical disease affecting 65 M people exposed in more than 21 Latin American countries. It has a long asymptomatic phase. You can have the parasite for 20 years wo presenting any symptoms. The vector is the kissing bug. In Argentina you find Chagas in the Gran Chaco with 1 to 2 M people infected (little stats... 1 M dif between those). Only 30% of all infected wil develop severe heart disease. Gran Chaco is a rainforest, of poor people in the North of the country with little attention from the government.

* There is transmision from mother to child. Focus of the foundation funding this work now. It can be avoided but there is lack of official stats an publci detection capigns. So it is necessary to know where the people infected live to do something.

* Afinity index. Used Mobile Phone data anonymized call detail records from one national telco tha covers 5 months of data. First the residence location of user. Then the communications with endemic users. Heat maps are generated at the antenna levels. The color depends on the use of antenna for the subjects that interact with the Gran Chaco. You can map the amount of interaction between subjects in the Gran Chaco all over in Argentina. This helps identifying areas that are not covered by campaings for Chagas such as Patagonia that is very far away from Gran Chaco and does not have the vector.

* Housing conditions from census data: predominant material of the floors, of the roof exterior - identified the housing conditions that are good for the vector. Added this info to the afinity index

* Health vulnerability> access to health services from the state + socio econommic index of the population. accessibility to hospitals and their life conditions. These two ingridients were added to a chagas potential prevalence index ChPPI to prioritize detection campaings in the field. The index is calculated for each census area. A map is generated with the ChPPI. The prevalence is higher in the  Gran Chaco as expected, but also Tierra del Fuego has higher prevalence than expected.

* Conclusion> heat maps show temperature falling from Gran Chaco outwards. The affinity does not decrease in a continuous gradient as the localities move away from the endemic aread. Localities were detected in the Province of Buenos Aires and Patagonia whose degree of affinity is much higher than population centers in provinces closer to the EA. This suggests the existence of considerable migrations from endemic regions to the highlighted localities.

* Future: detection campaigns in the upcoming years analyzing the maps generated from the data + expert input. The map helped include Patagonia in the cmapaing due to these findings.



15:35 – 16:45 Plenary Session (JBR) “Sustainable Innovation in the Public/Government Sector” – supported by UCL Digital Ethics Forum
Chair: Barbara Ubaldi (@BarbaraUbaldi), OECD, Paris (@OECD)

Speakers:
Diego Kuonen (@DiegoKuonen), Universite de Geneve, Switzerland

Julia Stoyanovich (@stoyanoj), New York University (@NYUTandon & @NYUDataScience,)

Nicholas Wright (@nicholasdwright), UCL and Georgetown University (@Georgetown)

Natasha McCarthy (@ntshmccrthy), The Royal Society, UK (@RoyalSociety)

Lee Rowley MP (@Lee4NED) All Party Parliamentary Group on Data Analytics, UK (@DataAPG)

16:45 – 17:00 Closing Remarks (JBR)
Lee Rowley MP (@Lee4NED), All Party Parliamentary Group on Data Analytics
Stefaan Verhulst (@sverhulst), GovLab, New York University
Zeynep Engin (@zeynepengin), UCL and Data for Policy