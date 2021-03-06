#HSLIDE

## Data Inte`git`ry for the Pharmaceutical Industry

#### Git Merge 2017 Brussels 

#### Katrin Leinweber

###### CC-BY-4.0 

#HSLIDE?image=img/data-integrity-trends.png

#HSLIDE

### Data integrity nightmares

> Failure to prevent unauthorized access or changes to data [[…]](http://www.fda.gov/iceci/enforcementactions/warningletters/2016/ucm501282.htm)

> additional testing was performed but not properly documented [[…]](www.fda.gov/iceci/enforcementactions/warningletters/2014/ucm401451.htm)

> raw data files in the recycle bin […] even in the presence of 'Do Not Delete Any Data' notes [[…]](http://www.fda.gov/iceci/enforcementactions/warningletters/ucm455345.htm)

-– [FDA warning letters](http://google2.fda.gov/search?as_sitesearch=www.fda.gov/iceci/enforcementactions/warningletters&q=%22data+integrity%22+inmeta:search_topic%3DWarning%2520Letters&client=FDAgov&output=xml_no_dtd&proxystylesheet=FDAgov&site=FDAgov&getfields=*&requiredfields=-archive:Yes&partialfields=&filter=1&dnavs=inmeta:search_topic%3DWarning%2520Letters&sort=date:D:S:d1)

#HSLIDE

### Solution

Change control & audit trails for work instructions, measurement data, analytical methods, etc.

> […] secure, computer-generated, time-stamped electronic record that allows for reconstruction of […] creation, modification, or deletion […] chronology of the “who, what, when, and why” 

–- [FDA "Data Integrity…" draft guidance](http://www.fda.gov/downloads/drugs/guidancecomplianceregulatoryinformation/guidances/ucm495891.pdf)

#HSLIDE

## Pharma-specific software can do this…

#### Sometimes…  <!-- .element: class="fragment" -->

###### Kinda…  <!-- .element: class="fragment" -->

## Problems: few users, no or little agility, abysmal UX  <!-- .element: class="fragment" -->

#HSLIDE

### Regulatory requirements mapped to Git's features 

- Attributable => commit author
- Legible => content-agnostic, both human- & machine readable, right?  <!-- .element: class="fragment" -->
- Contemporaneously recorded => same as on paper, but prompts & automation possible  <!-- .element: class="fragment" -->
- Original or true copy => digital & hashed  <!-- .element: class="fragment" -->
- Accurate => down to line & character  <!-- .element: class="fragment" -->

-- World Health Organisation: [Guidance on good data and record management practices](http://www.who.int/medicines/publications/pharmprep/WHO_TRS_996_annex05.pdf)

#HSLIDE

### Brainstorming hurdles to Git adoption in pharma

- remove history-altering functions (`amend`, `filter-branch`…)
  - or audit-trail their use  <!-- .element: class="fragment" -->
- file meta-data not staged & committed alongside content  <!-- .element: class="fragment" -->

#HSLIDE

### Brainstorming killer applications for Git in pharma

- best-in-class audit trail addons/plugins for existing software
- enable regulatory verification with anonymous attestation (0-knowledge proofs + blind signature), "hash-only remotes/mirrors", etc. <!-- .element: class="fragment" -->
- visual hook/automation/workflow designer (BPML)  <!-- .element: class="fragment" -->

#HSLIDE

![](img/pharma-IT-orly.png)

- API = Active Pharmaceutical Ingredient  <!-- .element: class="fragment" -->
- CSV = Computer Systems Validation  <!-- .element: class="fragment" -->
- GMP = Good Manufacturing Practice  <!-- .element: class="fragment" -->

#HSLIDE

# Thanks for your attention!

#### Further info: [ISPE GAMP](http://www.ispe.org/gamp-resources), [US 21 CFR part 11](http://www.ecfr.gov/cgi-bin/text-idx?&node=pt21.1.11)
