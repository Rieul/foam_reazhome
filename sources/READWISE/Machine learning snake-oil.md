---
title : [Machine learning snake-oil]
authors: [ Cory Doctorow ]
date : 2021-08-30
type : tweets
url : https://twitter.com/doctorow/status/1422239691034664991
---

%% tags : #type/tweets #discipline/ia #cat/critique %% 

---
Machine learning snake-oil
===
> by [Cory Doctorow](https://twitter.com/doctorow)
> ([View Tweet](https://twitter.com/doctorow/status/1422239691034664991))

 ![](https://pbs.twimg.com/media/E7y7zuZUYAk12mp.jpg)

## Highlights
- The worst part of machine learning snake-oil isn't that it's useless or harmful - it's that ML-based statistical conclusions have the veneer of mathematics, the empirical facewash that makes otherwise suspect conclusions seem neutral, factual and scientific.
  1/   ([View Tweet](https://twitter.com/doctorow/status/1422239691034664991))
- If you'd like an unrolled version of this thread to read or share, here's a link to it on https://t.co/iSBh8s9m7q, my surveillance-free, ad-free, tracker-free blog:
  https://t.co/PKMLq14Tfx
  2/ ([View Tweet](https://twitter.com/doctorow/status/1422239693484093443))
- Think of "predictive policing," in which police arrest data is fed to a statistical model that tells the police where crime is to be found. Put in those terms, it's obvious that predictive policing doesn't predict what criminals will do; it predicts what POLICE will do.
  3/ ([View Tweet](https://twitter.com/doctorow/status/1422239695388299265))
- Cops only find crime where they look for it. If the local law only performs stop-and-frisks and pretextual traffic stops on Black drivers, they will only find drugs, weapons and outstanding warrants among Black people, in Black neighborhoods.
  4/ ([View Tweet](https://twitter.com/doctorow/status/1422239697133203459))
- That's not because Black people have more contraband or outstanding warrants, but because the cops are only checking for their presence among Black people. Again, put that way, it's obvious that policing has a systemic racial bias.
  5/ ([View Tweet](https://twitter.com/doctorow/status/1422239698924175360))
- But when that policing data is fed to an algorithm, the algorithm dutifully treats it as the ground truth, and predicts accordingly. And then a mix of naive people and bad-faith "experts" declare the predictions to be mathematical and hence empirical and hence neutral.
  6/ ([View Tweet](https://twitter.com/doctorow/status/1422239701541396489))
- Which is why @AOC got her face gnawed off by rabid dingbats when she stated, correctly, that algorithms can be racist. The dingbat rebuttal goes, "Racism is an opinion. Math can't have opinions. Therefore math can't be racist."
  https://t.co/HW4z6r0TMZ
  7/ ([View Tweet](https://twitter.com/doctorow/status/1422239703760130049))
- You don't have to be an ML specialist to understand why bad data makes bad predictions. "Garbage In, Garbage Out" (#GIGO) may have been coined in 1957, but it's been a conceptual iron law of computing since "computers" were human beings who tabulated data by hand.
  8/ ([View Tweet](https://twitter.com/doctorow/status/1422239706289295365))
- But good data is hard to find, and "when all you've got is a hammer, everything looks like a nail" is an iron law of human scientific malpractice that's even older than GIGO. When "data scientists" can't find data, they sometimes just wing it.
  9/ ([View Tweet](https://twitter.com/doctorow/status/1422239709019860998))
- This can be lethal. I published a @Snowden leak that detailed the statistical modeling the NSA used to figure out whom to kill with drones. In subsequent analysis, @vm_wylbur demonstrated that NSA statisticians' methods were "completely bullshit."
  https://t.co/72QPCzpuvJ
  10/ ([View Tweet](https://twitter.com/doctorow/status/1422239712153010177))
- Their gravest statistical sin was recycling their training data to validate their model. Whenever you create a statistical model, you hold back some of the "training data" (data the algorithm analyzes to find commonalities) for later testing.
  https://t.co/iV8X7EGJe9
  11/ ([View Tweet](https://twitter.com/doctorow/status/1422239714002673686))
- So you might show an algorithm 10,000 faces, but hold back another 1,000, and then ask the algorithm to express its confidence that items in this withheld data-set were also faces.
  12/ ([View Tweet](https://twitter.com/doctorow/status/1422239715818807307))
- However, if you are short on data (or just sloppy, or both), you might try a shortcut: training and testing on the same data.
  There is a fundamental difference from evaluating a classifier by showing it new data and by showing it data it's already ingested and modeled.
  13/ ([View Tweet](https://twitter.com/doctorow/status/1422239717609795586))
- It's the difference between asking "Is this LIKE something you've already seen?" and "Is this something you've already seen?" The former tests whether the system can recall its training data; the latter tests whether the system can generalize based on that data.
  14/ ([View Tweet](https://twitter.com/doctorow/status/1422239719555932172))
- ML models are pretty good recall engines! The NSA was training it terrorism detector with data from the tiny number of known terrorists it held. That data was so sparse that it was then evaluating the model's accuracy by feeding it back some of its training data.
  15/ ([View Tweet](https://twitter.com/doctorow/status/1422239721359482893))
- When the model recognized its own training data ("I have 100% confidence this data is from a terrorist") they concluded that it was accurate. But the NSA was only demonstrating the model's ability to recognize known terrorists - not accurately identify UNKNOWN terrorists.
  16/ ([View Tweet](https://twitter.com/doctorow/status/1422239724119330816))
- And then they killed people with drones based on the algorithm's conclusions.
  Bad data kills.
  Which brings me to the covid models raced into production during the height of the pandemic, hundreds of which have since been analyzed.
  17/ ([View Tweet](https://twitter.com/doctorow/status/1422239725981634562))
- There's a pair of new, damning reports on these ML covid models. The first, "Data science and AI in the age of COVID-19" comes from the @turinginst:
  https://t.co/EFs73iXmve
  18/ ([View Tweet](https://twitter.com/doctorow/status/1422239728582070272))
- The second, "Common pitfalls and recommendations for using machine learning to detect and prognosticate for COVID-19 using chest radiographs and CT scans," comes from a team at Cambridge.
  https://t.co/ODv5NrRzE9
  19/ ([View Tweet](https://twitter.com/doctorow/status/1422239730519842836))
- Both are summarized in an excellent @techreview article by @strwbilly, who discusses the role GIGO played in the universal failure of ANY of these models to produce useful results. 
  https://t.co/z4aRCLHujI
  20/ ([View Tweet](https://twitter.com/doctorow/status/1422239733204226049))
- Fundamentally, the early days of covid were chaotic and produced bad and fragmentary data. The ML teams "solved" that problem by committing a series of grave statistical sins so they could produce models, and the models, trained on garbage, produced garbage. GIGO.
  21/ ([View Tweet](https://twitter.com/doctorow/status/1422239735028719628))
- The datasets used for the models were "Frankenstein data," stitched together from multiple sources. The specifics of how that went wrong are a kind of grim tour through ML's greatest methodological misses.
  22/ ([View Tweet](https://twitter.com/doctorow/status/1422239737176203282))
- * Some Frankenstein sets had duplicate data, leading to models being tested on the same data they were trained on
  * A data-set of health children's chest X-rays was used to train a model to spot healthy chests - instead it learned to spot children's chests
  23/ ([View Tweet](https://twitter.com/doctorow/status/1422239740544258049))
- * One set mixed X-rays of supine and erect patients, without noting that only the sickest patients were X-rayed while lying down. The model learned to predict that people were sick if they were on their backs
  24/ ([View Tweet](https://twitter.com/doctorow/status/1422239743224389647))
- * A hospital in a hot-spot used a different font from other hospitals to label X-rays. The model learned to predict that people whose X-rays used that font were sick
  25/ ([View Tweet](https://twitter.com/doctorow/status/1422239745094995969))
- * Hospitals that didn't have access to PCR tests or couldn't integrate them with radiology data labeled X-rays based on a radiologist's conclusions, not test data, incorporating radiologist's idiosyncratic judgements into a "ground truth" about what covid looked like
  26/ ([View Tweet](https://twitter.com/doctorow/status/1422239901492207620))
- All of this was compounded by secrecy: the data and methods were often covered by nondisclosure agreements with medical "AI" companies. This foreclosed on the kind of independent scrutiny that might have caught these errors.
  27/ ([View Tweet](https://twitter.com/doctorow/status/1422239903136452611))
- It also pitted research teams against one another, rather than setting them up for collaboration, a phenomenon exacerbated by scientific career advancement, which structurally preferences independent work.
  28/ ([View Tweet](https://twitter.com/doctorow/status/1422239904864477197))
- Making mistakes is human. The scientific method doesn't deny this - it compensates for it, with disclosure, peer-review and replication as a check against the fallibility of all of us. 
  The combination of bad incentives, bad practices, and bad data made bad models. 
  29/ ([View Tweet](https://twitter.com/doctorow/status/1422239906454118405))
- The researchers involved likely had the purest intentions, but without the discipline of good science, they produced flawed outcomes - outcomes that were pressed into service in the field, to no benefit, and possibly to patients' detriment.
  30/ ([View Tweet](https://twitter.com/doctorow/status/1422239908295450625))
- There are statistical techniques for compensating for fragmentary and heterogeneous data - they are difficult and labor-intensive, and work best through collaboration and disclosure, not secrecy and competition.
  31/ ([View Tweet](https://twitter.com/doctorow/status/1422239909893476355))
- Image:
  Cryteria (modified)
  https://t.co/ICebVcdH1f
  CC BY:
  https://t.co/5YJhpDj3vT
  eof/ ([View Tweet](https://twitter.com/doctorow/status/1422239911319506945))

---
> links : 
> references :