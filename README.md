## Andrew Carnegie:  Forerunner of Business Analytics (With Thoughts on What Statistics Was, What it Is, and What it Is Not)


Notes for a virtual presentation by **Dr. Christopher Tong** at the *Nevada Statistics Seminar*, 25 March 2022, at the invitation of Prof. Anna Panorska, [Dept. of Mathematics and Statistics, University of Nevada, Reno](https://www.unr.edu/math).

I received several requests for the slides of my talk.  Rather than sharing the slides, I'm taking the opportunity to post more extensive notes about the presentation here.  --Christopher Tong

### Disclaimers:

- The views expressed are solely my own, and do *not* necessarily represent the views, policies, or opinions of my employer or any organization with which I am affiliated.
- Work on this presentation, and the underlying research on which it is based, was done solely on my personal time.
- I am not an expert on Andrew Carnegie.

### Abstract

American steel tycoon and philanthropist [Andrew Carnegie](https://en.wikipedia.org/wiki/Andrew_Carnegie) (1835-1919) was a member of the American Statistical Association from 1892 until his death. He learned cost accounting at the Pennsylvania Railroad, and later adapted its data-driven approach to managing his steel business.  He successfully outperformed competitors by introducing a detailed data collection program within his steel mills, and using the resulting information for personnel management, marketing, and capital investment decisions. Carnegie was also a consumer of US census data, using it extensively in his polemical book *Triumphant Democracy* to argue in favor of the US political and economic arrangements, as opposed to those of old Europe; and for making decisions on donating public libraries and church organs across the world. However, Carnegie lacked a modern understanding of statistical variation. I argue that such an understanding would only have been a second-order improvement on his wildly successful business analytics.  The statistics profession has advanced, and narrowed, since Carnegie's time.  His methods are now taught in business and industrial engineering curricula, not statistics.  By deepening its commitment to the probability framework for modeling data generating processes, our profession risks committing the ludic fallacy.

### Introduction

The majority of the material from this presentation appears in my article, [The Statistical Endeavors of Andrew Carnegie](https://doi.org/10.1080/09332480.2021.2003633),  *Chance*, **34** (4), 12-17.  I also discuss this topic in Episode 216 of the *Stats+Stories* podcast, [Carnegie the Statistician](https://statsandstories.net/economics1/carnegie-the-statistician) (Jan. 27, 2022).  I will not reproduce that material here, since you should really read the article.  Instead, here you will find additional material from the presentation that was not included in the *Chance* article.  

### The birth of cost accounting

The American railroads of the 19th century represent some of the largest companies in the United States at that time.  In the era before there were business schools or management science, railroad managers had to invent methods of runining large, complex organizations.  Railroad managers such as [Daniel McCallum](https://en.wikipedia.org/wiki/Daniel_McCallum) were civil engineers by training.  McCallum invented the organization chart, and was a prime mover in the development of cost accounting methods, along with others.  Andrew Carnegie learned these methods while employed by the Pennsylvania Railroad, then the nation's largest company.  

Sources:
- W. J. Hopp and M. L. Spearman (2008).  [*Factory Physics*](https://factoryphysics.com/factory-physics-3rd-edition), 3d ed.  McGraw-Hill.
- H. C. Livesay (2007).  [*Andrew Carnegie and the Rise of Big Business*](https://www.pearson.com/us/higher-education/program/Livesay-Andrew-Carnegie-and-the-Rise-of-Big-Business-Library-of-American-Biography-Series-3rd-Edition/PGM53577.html), 3d ed.  Pearson Longman.

### The only statistical graphic in *Triumphant Democracy*

This is a stacked bar chart comparing the aggregate US public debt of 1880 and 1890, including national, state, county, school district, and municipal debt.  It appears on page 477 of the second edition of Carnegie's book *Triumphant Democracy* (Scribner's, 1893).

### A critique of Carnegie from the perspective of Shewhart and Deming

[W. Edwards Deming](https://en.wikipedia.org/wiki/W._Edwards_Deming) was born the year before Carnegie retired from the steel industry, but had the mature Deming been alive to observe Carnegie's management methods, he likely would have accused Carnegie of failing to distinguish between "common cause variation" and "special cause variation" (or to use [Walter Shewhart](https://en.wikipedia.org/wiki/Walter_A._Shewhart)'s terms, "chance cause" and "assignable cause", respectively).  That is because these concepts and the surrounding statistical thinking and methods were developed after Carnegie had died, by Walter Shewhart in the 1920s at the Western Electric division of Bell Telephone.  To put it simply, Carnegie responded to noise, not just signal, in the data being reported to him by his managers.  Deming might have also noted that Carnegie failed to follow some of Deming's "14 points" of management (*Out of the Crisis*, MIT Press, 1982).

Reference:  Walter A. Shewhart, 1931:  *Economic Control of Quality of Manufactured Product* (Van Nostrand).  This has been reprinted by the American Society for Quality.

### What Statistics was, what it is, and what it is not

If you were to survey, as [Stephen Fienberg](https://en.wikipedia.org/wiki/Stephen_Fienberg) (2014) did, the definitions of statistics from modern introductory statistics textbooks, you will likely find some broad definitions of our profession.  However, once you open those books you will find that the majority of the material within them focuses on probability theory, statistical inference, and stochastic models of data generating processes.  This represents a narrow vision of the statistics profession.  How did this come about?

As Herbert Weisberg (2014) noted, the 17th century Dutch savants [Christiaan Huygens](https://en.wikipedia.org/wiki/Christiaan_Huygens) and [Johan DeWitt](https://en.wikipedia.org/wiki/Johan_de_Witt) were working with survival data, and realized that the laws of games of chance (specifically, a lottery process)  could be used to model empirical data.  Huyghens, one of the most important physicists and astronomers of the 17th century, was studying [John Graunt](https://en.wikipedia.org/wiki/John_Graunt)'s *London Bills of Mortality*, while DeWitt (Grand Pensioner of Holland, the most powerful political leader in the country) was trying to price life insurance annuities issued by the Dutch government.  Weisberg notes that this was "the first known example of an analogy between empirical data about a complex causal process, like mortality, and a lottery....this idea was central to the breakthroughs achieved by Jacob Bernoulli about 20 years later."  [Jacob Bernoulli](https://en.wikipedia.org/wiki/Jacob_Bernoulli) is credited with the more general insight that probability theory provides a way of modeling empirical data (not just survival data).

However, that view did not come to dominate the profession until the foundational paper by [R. A. Fisher](https://en.wikipedia.org/wiki/Ronald_Fisher) (1922), published one hundred years ago this year.  Among other things, in this paper Fisher introduced the sample-to-population inference framework, the basis for all major schools of statistical inference (frequentist, Bayesian, likelihoodist, fiducial).  His paper placed stochastic models of the data generating process at the heart of statistical inference.  This allowed the statistics profession to grow both deeper and narrower in the subsequent century.  Consequently the profession has come to exclude the cost accounting methods that Carnegie used (which are now taught in schools of business and schools of industrial engineering, under managerial accounting, and production and operations management) as well as, for many statisticians, the innovations of machine learning that make no explicit stochastic model assumptions.  This exclusionary attitude is eloquently illustrated in the paper of Brown and Kass (2009) that I discuss in my *Chance* article, and was lamented in [Jerry Friedman](https://en.wikipedia.org/wiki/Jerome_H._Friedman)'s 2001 essay, where (as a physicist like me) he provides an operational definition of statistics in terms of what is actually taught in statistics graduate programs (probability theory, measure theory, asymptotics, etc.).  [Leo Breiman](https://en.wikipedia.org/wiki/Leo_Breiman) (2001) also lamented this attitude, and was specifically called out by Brown and Kass.  Other examples include Tony O'Hagan (2004) who wrote that "The theory of statistics rests on describing uncertainties by using probability" and Kristin Lennox (2016) who defined (accurately in my opinion)  the *Central Dogma of Inferential Statistics* as "Statisticians use *probability* to describe *uncertainty*."  This narrow view of statistics, which I call the Bernoulli-Fisher ideology, has always had dissenters from within the profession, including Breiman, Friedman, Weisberg, and of course [John W. Tukey](https://en.wikipedia.org/wiki/John_Tukey) (the pioneering advocate for exploratory data analysis).

While in the 19th century "statistics" could still be broadly defined, and a separate term like "data science" would have been superfluous, that is not the case today.  Statisticians who dismiss data science as "statistics under another name" are, in my opinion, unfairly ignorant of the historical development and narrowing of the statistics profession.  Statistics is not **the** art and science of learning from data, but is at best one of many such arts and sciences.

(See my *Chance* article for additional discussion of these points, including [Stephen Stigler](https://en.wikipedia.org/wiki/Stephen_Stigler)'s views, and more specific comments about Brown and Kass.)

References:

- L. Breiman (2001).  [Statistical modeling:  the two cultures](http://doi.org/10.1214/ss/1009213726).  *Statistical Science*, 16: 199–231.
- E. N. Brown and R. E. Kass (2009).  [What is statistics?](https://doi.org/10.1198/tast.2009.0019).  *American Statistician*, 63:  105-110.
- S. E. Fienberg (2014).  [What is statistics?](https://doi.org/10.1146/annurev-statistics-022513-115703)  *Annual Review of Statistics and Its Application*, 1:  1-9.
- R. A. Fisher (1922).  [On the mathematical foundations of theoretical statistics](https://doi.org/10.1098/rsta.1922.0009).  *Philosophical Transactions of the Royal Society of London*, A222:  309-368.
- J. H. Friedman (2001).  [The role of statistics in the data revolution?](https://doi.org/10.1111/j.1751-5823.2001.tb00474.x)  *International Statistical Review*, 69:  5-10.
- K. Lennox (2016).  [All about that Bayes:  Probability, Statistics, and the Quest to Quantify Uncertainty](https://www.youtube.com/watch?v=eDMGDhyDxuY)  Presentation at Lawrence Livermore National Labs.  
- T. O'Hagan (2004).  [Dicing with the unknown](https://doi.org/10.1111/j.1740-9713.2004.00050.x).  *Significance*, 1 (3):  132-133.
- H. I. Weisberg (2014), [*Willful Igonorance:  The Mismeasure of Uncertainty*](http://doi.org/10.1002/9781118839539).  Wiley.

### The need for judgment

[Nassim Nicholas Taleb](https://en.wikipedia.org/wiki/Nassim_Nicholas_Taleb) (2007) defined the *Ludic Fallacy*.  In my words, this is the fallacy of modeling a system by analogy to games of chance, ie, using stochastic modeling, when it is not appropriate.  [John Kay](https://en.wikipedia.org/wiki/John_Kay_(economist)) and [Mervyn King](https://en.wikipedia.org/wiki/Mervyn_King,_Baron_King_of_Lothbury) (2020) borrow terms from the statistician [Jimmie Savage](https://en.wikipedia.org/wiki/Leonard_Jimmie_Savage) (*Foundations of Statistics*, Wiley, 1954):
- In "small world" problems, you can describe the universe of possible outcomes and potentially assign a probability distribution to that set.
- In "large world" problems, all possible outcomes cannot even be known, therefore probability assignment is not feasible.  That's where we actually live.

As an example of a "large world" phenomemon, or perhaps what Taleb would call a "black swan", on March 8, 2022, the [London Metal Exchange](https://en.wikipedia.org/wiki/London_Metal_Exchange) halted the trading of Nickel for over a week.  But they also canceled the previous 8 hours of transactions, worth 3.9 billion dollars.  I doubt that any nickel trader on the morning of March 7 could have predicted that this was even a conceivable outcome.  Of what use is a time series model or predictive algorithm in such a setting?

Weisberg (2014) and Kay and King (2020) both point to the warnings made by two distinguished economists, also a century ago, that the uncertainty quantified by probabilistic methods is only *part* of the total uncertainty, which can only be understood qualitatively.  See [Frank Knight](https://en.wikipedia.org/wiki/Frank_Knight)'s *Risk, Uncertainty, and Profit* (Riverside Press, 1921) and [John Maynard Keynes](https://en.wikipedia.org/wiki/John_Maynard_Keynes)' *A Treatise on Probability* (Macmillan, 1921).  (Both books have been reprinted by Dover Publications.)  One example of why this is true is model uncertainty and model selection bias, discussed at length in my 2019 paper.

What we need to spend more time teaching is judgment, including judgment about when a stochastic modeling approach is appropriate, and when it is not.  The late General [Colin Powell](https://en.wikipedia.org/wiki/Colin_Powell) tells of a pointless regression modeling exercise of enemy mortar attack data during the Vietnam War, which led him to assert that "Experts often possess more data than judgment".  John Tukey (1962) wrote that “If data analysis is to be well done, much of it must be a matter of judgment, and ‘theory’, whether statistical or non-statistical, will have to guide, not command...it might be well if statisticians looked to see how data was actually analyzed by many sorts of people.”  I hope that I have done that by telling you about Andrew Carnegie's statistical endeavors.  (Brief discussions of two other examples, physicist Max Planck, and epidemiologist John Snow, are discussed in the 2017 *Significance* article by Bert Gunter and myself.)

References:
- B. Gunter and C. Tong, 2017:  [What are the odds!?  The "airport fallacy" and statistical inference](https://doi.org/10.1111/j.1740-9713.2017.01057.x).  *Significance*, **14** (4): 38-41.
- J. Kay and M. King (2020).  [*Radical Uncertainty:  Decision-Making Beyond the Numbers*](https://wwnorton.com/books/9780393541984/about-the-book/description).  W. W. Norton.
- C. L. Powell with J. Persico (1995).  [*My American Journey*](https://www.penguinrandomhouse.com/books/133242/my-american-journey-by-colin-powell-with-joseph-e-persico/).  Random House.
- N. N. Taleb (2007).  [*The Black Swan:  The Impact of the Highly Improbable*](https://www.penguinrandomhouse.com/books/176226/the-black-swan-second-edition-by-nassim-nicholas-taleb/).  Random House.
- C. Tong (2019).  [Statistical inference enables bad science; statistical thinking enables good science](https://doi.org/10.1080/00031305.2018.1518264).  *The American Statistician*, **73** (Sup 1): 246-261.  
- J. W. Tukey (1962).  [The future of data analysis](https://doi.org/10.1214/aoms/1177704711).  *Annals of Mathematical Statistics*, 33:  1-67.

### Recommended reading

I cite a number of biographies of Andrew Carnegie in my *Chance* article.  At one time his definitive biography was considered to be the one by Joseph Frazier Wall, but David Nasaw's has come to surpass it.  Not all readers will have the appetite for a lengthy biography though; for such readers I recommend Harold Livesay's biography, which is a fast read, and also the inspiration for my interest in Carnegie's business analytics, a topic Livesay is particularly strong on.

I strongly recommend all statisticians read Breiman's "Two Cultures" paper.  I am currently reading Kay and King's *Radical Uncertainty*, and in my opinion, the earlier parts of the book should also be recommended to all statisicians, as well as those who use data to make decisions.

**Update, April 15, 2022:**  I have finished reading Kay and King's *Radical Uncertainty*.  It is a blistering indictment of economic theory and practice.  Statistics take a lot of collateral damage in the book, rightly so in my opinion.  I reiterate my recommendation that every statistician read at least the earlier parts of the book.
