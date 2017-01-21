https://cfp.githubapp.com/events/git-merge-2017/proposals/new

# Title (60)

Data Inte`git`ry for the Pharmaceutical Industry

# Abstract (600)

Pharma is strictly regulated because _their_ APIs literally get under your skin (**a**ctive **p**harmaceutical **i**ngredients). Currently, regulators zero in on "data integrity", because it is vital to proving an API's chemical purity, stability during storage (thus its safety for patients), and of course it's pharmaceutical effectiveness. One mistake can cost pharma companies their business, but they seem unaware of the VCSs we know & (sometimes) love could help.

Combing through regulatory documents (e.g. from the [USA](https://www.regulations.gov/document?D=FDA-2016-D-1113-0002), [EU](http://www.ema.europa.eu/ema/index.jsp?curl=pages/regulation/q_and_a/q_and_a_detail_000027.jsp#section16) & [UK](https://www.gov.uk/government/publications/good-manufacturing-practice-data-integrity-definitions)), we'll catch many data integrity requirements that are already covered by basic functionality of Git & Co. Just a few tweaks may be necessary to expand (G)it into the pharma domain.

# Details (Explain theme & flow! Audience takeaways?)

I will show some examples of current data integrity problems, and map existing Git features to requirements from the regulatory agencies mentioned in the abstract. Finally, I'll present some raw, pharma-relevant tweaking ideas. The audience should thus be introduced into the application potential of the IT they know in the pharma industry that's hopefully new to most of them. The talk is aimed both for beginners and experts, and for both their fresh ideas and well-founded critique.

Slide drafts (or draft slides?): https://gitpitch.com/katrinleinweber/gm17-data-integitry

# Pitch (Why pertinent? Your involvement?)

The software industry adopted randomised, (placebo-)controlled trials (RCTs) from pharma and perfected them as A/B-tests. Although the pharma industry of course uses software for many tasks, it seems that for the extremely important core task of audit-trailing their digital files, it has not hit upon the obvious solution. I believe that version control (and thus Git, obviously) should be adopted in order to fundamentally tackle the data integrity requirements that pharma (rightfully) faces from the regulatory agencies. Which interestingly write guidance documents, that conspicuously read like layman's summaries of what version control can already do.

In about two years of working in laboratory automation, I've never encountered Git or colleagues who were familiar with it. Although of course we were in need of version-controlling method and data files in scientific software, instrument configurations, training documents, etc., _and_ needed to collaborate on analysis scripts. Particularly, the pharma industry seems to have established a parallel universe of "audit trailing" and "change controlling" such digital files. Similarly, the software developers I asked about this didn't know that/how their dev tools and workflows already fulfil many pharma requirements. I want to help connect these universes.


