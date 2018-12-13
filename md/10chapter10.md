---
Pr-id: MoneyLab
P-id: INC Reader
A-id: 10
Type: article
Book-type: anthology
Anthology item: article
Item-id: unique no.
Article-title: title of the article
Article-status: accepted
Author: name(s) of author(s)
Author-email:   corresponding address
Author-bio:  about the author
Abstract:   short description of the article (100 words)
Keywords:   50 keywords for search and indexing
Rights: CC BY-NC 4.0
...


# Chapter Ten: Making Data Public? The Open Data Index as Participatory Device

Jonathan Gray and Danny Lämmerhirt

**Abstract**

The Open Data Index is a 'civil society audit' which strives to shape
the availability and openness of public sector data from around the
world. In this chapter we examine the social life of this project,
including how it evolved, the changing visions and practices associated
with it, and how it serves to assemble and involve different publics in
the assessment of institutional practices and forms of datafication.
Drawing on recent work on statactivism, data activism and the
performative effects of numbers, rankings and indices, we look at how
the index organises participation and data politics in specific ways,
raising questions about not only making data public but also the making
of public data. It plays two roles which are sometimes in tension: (i)
conventionalising assessment to facilitate comparability, and (ii)
reflecting the diversity of different interests, issues and settings
involved in opening up public sector data. It also facilitates the
creation of 'enumerated entities' as objects of concern in open data
advocacy and policy. The Open Data Index may thus be viewed as a site
where participation is both configured and contested, and where
practices of valuation and enumeration are both conventionalised and
brought into question.

## Introduction

How can various publics participate in shaping what data is created,
collected and distributed by states? How might public participation
around the availability and openness of public data lead to 'good data'
(or at least 'better data')? In this chapter we reflect on the social
life of the Open Data Index, a civil society project which aims to
measure and influence how government data is made available. In
particular we attend to how the index organises participation and data
politics in specific ways, raising questions about not only making data
public but also the making of public data.

There are many ways that one might appraise such an initiative. From the
perspective of what Bruno Latour calls an 'anthropology of
modernity',[^10chapter10_1] there is a lot to be unpacked in these three little
words: 'open', 'data' and 'index'. For example, one might consider
imaginaries and practices of the 'index' in light of research on
cultures of auditing and accountability.[^10chapter10_2] One might tell a tale of
the rise of the index as a style of political mobilisation alongside the
rally, the petition or the hashtag. As well as public sector indices
such as the United Nations 'Human Development Index' and 'Human Poverty
Index', there are now a wide variety of non-governmental and civil
society indices, such as the 'Corruption Perceptions Index', the 'Press
Freedom Index', the 'Happy Planet Index', the 'Financial Secrecy Index',
the 'Global Slavery Index' and the 'Global Food Index'.[^10chapter10_3]

The rise of the index can also be understood in relation to recent
research exploring the social life and performative effects of rankings,
indices and indicators.[^10chapter10_4] Indices not only *represent* aspects of the
world, they can also participate in *shaping* the world, including
through reactive effects. They enable scores, rankings and comparisons
of different issues across countries through processes of commensuration
and quantification. Indices can thus be envisaged as devices for the
production of social facts, which in turn enable different dynamics of
competition and concern. The following passage from the press release
accompanying a recent edition of the 'Corruption Perceptions Index',
presented alongside coloured maps and rankings, provides an example of
how indices can give rise to 'enumerated entities'[^10chapter10_5] as objects of
attention and concern:

> This year, New Zealand and Denmark rank highest with scores of 89 and
> 88 respectively. Syria, South Sudan and Somalia rank lowest with
> scores of 14, 12 and 9 respectively. The best performing region is
> Western Europe with an average score of 66. The worst performing
> regions are Sub-Saharan Africa (average score 32) and Eastern Europe
> and Central Asia (average score 34).[^10chapter10_6]

Here the function of the index is render corruption across different
countries commensurable, comparable and quantifiable. The scores enable
normative claims about which countries are doing better and worse, and
aspirations for future action.[^10chapter10_7]

The Open Data Index may be considered a *database about data*, as it is
concerned with the availability of governmental data across borders.
Along with other similar initiatives such as the Open Data Barometer,
the index raises questions about which data is to be made available and
how it is to be made available. In doing so it also surfaces issues
around the governance and politics of public data, such as who gets to
decide what is measured and what kinds of reactive effects are imagined
and observed. While previous literature discusses this index in the
context of information policy and the practices of public
institutions,[^10chapter10_8] it can also be considered in terms of recent work on
data politics, including 'stactivism'[^10chapter10_9] and 'data activism'.[^10chapter10_10] The
Open Data Index can be envisaged not only as a way to measure
accessibility but also as a particular kind of intervention around
official regimes of quantification and datafication -- including around
the horizons of intelligibility, the formation of collectives and the
varieties of transnational coordination that they give rise to.[^10chapter10_11]

  --------- ----------------------- --------------------- -----------------------
  Year      Number of submissions   Number of countries   \% of "open" datasets
  2012      177                     34                    Not given
  2013      597                     77                    16%
  2014      970                     97                    12%
  2015      1586                    122                   9%
  2016/17   1410                    94                    11%
  --------- ----------------------- --------------------- -----------------------

*\
Table 1: Numbers of submissions, numbers of countries and % of open
datasets from Open Data Index and Open Data Census 2012-2017. Numbers
obtained from archived websites and materials.*

In what follows we examine what the Open Data Index is, what it does and
how it has developed from 2012 to 2017 (Table 1) with reference to its
various websites (current and archived), blog posts, reports, events,
videos, software repositories, mailing lists and other materials. We
also draw on our own involvement with the project in various capacities.
We are particularly interested in how it organises participation around
both *making public data* (i.e. what counts, what is counted, the forms
of quantification and datafication which are held to matter) and *making
data public* (i.e. the specific social and technical arrangements for
making information available). We consider the index as an online
'device',[^10chapter10_12] which both shapes and is shaped by the assembly of
publics around the openness and availability of data as a 'matter of
concern'.[^10chapter10_13]

As a participatory device, the index plays two roles which may sometimes
be in tension: (i) to *conventionalise* the assessment of the openness
of data (thus facilitating comparability, objectivity and coordination
across settings); and (ii) to facilitate public involvement in a way
which is *receptive and flexible* enough to align with diverse
interests, issues and activities around opening up governmental data.
With the Open Data Index it is notable that this tension between
conventionalisation and receptivity plays out through an open-ended
invitation from a non-profit organisation to involve various publics
through open source software and replicable components which enable the
adaptation and multiplication of projects, including through
forking.[^10chapter10_14]

*Figure 1: Detail of Open Data Census submission form showing types of
data availability*.

In July 2011 the idea of an index on 'Open Knowledge' or 'Open Data'
arose on the mailing list of a working group on 'open economics',
advocating for open access to economic data, publications, code and
other materials. As one group member put it:

> There are many indices out there - for tracking democracy, corruption,
> innovation and human development - so why not a measure to track
> progress in opening government?

The immediate predecessor to the project was the 'Open Data Census',
conceived in 2011 and described as 'an attempt to monitor the current
status of open data across the globe'. Information about these
government datasets was initially gathered with a Google Form embedded
on a dedicated website, which recognised and recorded four types of
availability: 'a) available in a digital form; b) machine-readable; c)
publicly available, free of charge; d) openly licensed'. This later
developed into seven questions about data availability (Figure 1), which
were used to evaluate the openness of ten areas of data 'which most
governments could reasonably be expected to collect':

> 1\. Election Results (national)
>
> 2\. Company Register
>
> 3\. National Map (Low resolution: 1:250,000 or better)
>
> 4\. Government Budget (high level -- spending by sector)
>
> 5\. Government Budget (detailed -- transactional level data)
>
> 6\. Legislation (laws and statutes)
>
> 7\. National Statistical Office Data (economic and demographic
> information)
>
> 8\. National Postcode/ZIP database
>
> 9\. Public Transport Timetables
>
> 10\. Environmental Data on major sources of pollutants (e.g. location,
> emissions)

The census was promoted via email lists, events, blog posts and social
media platforms, including through two URLs: one for submissions (with
the embedded Google Form) and one with visualisations and numbers
summarising the results (Figure 2).

*\
Figure 2: Map showing preliminary results of the 2012 Open Government
Data Census.*

The Open Data Census was originally envisaged as a means to 'gather
responses from every country in the world' around the openness of
different types of government data through pre-structured options
('yes', 'no', 'unsure') to questions through which this could be
evaluated. This basic format served as the basis for the Open Data Index
and associated projects. As the project served to assemble publics to
monitor the openness of government data, we can consider it not only as
in terms of its *analytical* capacities, but also in terms of its
*interactivity* as a form of 'infrastructuring' around public sector
data.[^10chapter10_15] In the case of the 2012 census, the input was structured
through the form, and feedback was invited through an email alias and a
public mailing list.

What kind of participation does the index facilitate? One approach would
be to consider the dynamics between the 'formal social enterprise' of
Open Knowledge International, the non-governmental organisation which
coordinates the project;[^10chapter10_16] and its 'organised publics', i.e. the
various contributors to the census.[^10chapter10_17] The politics of the project
play out between the views of contributors, how project coordinators
manage input and resolve issues, and how the project was situated in
relation to the strategic and organisational prerogatives of its host
NGO, its collaborators, funders, states, IGOs, and other actors. Some of
these issues were raised in a blog post by open data advocate David
Eaves highlighting the potential risk that 'British biases -- with its
highly centralized national government -- have strongly shaped the
census':

> Thus, while the census evaluates countries some of the data sets being
> counted are not controlled by national governments. For example --
> will national governments Canada or the United States get counted for
> public transport data if any of their cities release transit data?
> Indeed, transit data -- while demonstrably useful -- strikes me as an
> odd duck choice since it is almost always not managed by national
> governments. The same can be said for company/corporate registers, in
> which the most important data sets are managed by sub-national
> entities.[^10chapter10_18]

Inquiring about the 'details about the selection process' regarding the
datasets included in the 2012 census, he further suggested others that
he wished to see added to the list, including:

-   Access to Information (ATIP or FOIA) made, completed, rejected and
    average response time, broken down by government entity.

-   Government procurements and contracts, broken down by government
    entity

-   Electoral Boundary Data

-   Voting Booth Locations

-   Land Registry Data

-   Payments to Government for Extractive Industry Resources

-   Foreign Aid Data

-   Campaign Finance Data

-   Registered Lobbyists List

In 2013 saw the release of the Open Data Index as a 'community-based
effort' which is 'compiled using contributions from civil society
members and open data practitioners around the world' and 'peer-reviewed
and checked by expert open data editors'.[^10chapter10_19] Described as 'a
Scoreboard for Open Government Data', it was explicitly positioned in
relation to other civil society index projects:

> Inspired by work such as Open Budget Index from the International
> Budget Partnership, the Aid Transparency Index from Publish What You
> Fund, the Corruption Perception Index from Transparency International
> and many more, we felt a key aspect is to distill the results into a
> single overall ranking and present this clearly.[^10chapter10_20]

The transition from 'census' to 'index' brought a number of changes. The
census remained the mechanism for collecting data about the openness of
government data, and the index became the mechanism for displaying
rankings. A numerical score was introduced for each country by weighting
different aspects of data availability (Figure 3). These weightings
rewarded specific legal and technical conventions associated with open
data.[^10chapter10_21] For example, while 5 points (out of a total of 100) would be
added if the dataset was available in digital form, 15 points would be
accrued if it was 'machine readable' and 30 points if a dataset was
'openly licensed'. These dataset scores would then be used as the basis
for an overall country score. Any number of submissions could come in
for a given country through the website. These would be reviewed by a
'country editor' (which could be one person or a shared role), who would
check and approve incoming submissions (Figure 4). A community manager
at OKI worked to coordinate the project and communicate with
contributors and editors.

*Figure 3: Table showing weightings for Open Data Index 2013.*

*Figure 4: Review process for contributors and editors, Open Data Index
2013.*

In terms of its material organisation, the index was a *bricolage* of
different elements. It continued to use a Google Form embedded on a
website to gather submissions accompanied by a review process conducted
with Google Spreadsheets. Submissions were gathered through the census,
then normalised, reviewed and published as part of the index. Results
were displayed on a NodeJS application, deployed on Heroku, and the code
was made available on GitHub. A dedicated '\[open-data-census\]' public
mailing list was set up for contributors to discuss and support the
review process. On Twitter the hashtags \#OpenDataCensus and
\#OpenDataIndex were used to promote activity and discussion around the
project.

Activity around the census was organised to align with relevant
international events. An 'Open Data Census Challenge' was hosted on
International Open Data Day in February 2013 to encourage public
involvement in the assessment of not only country-level data, but also
city-level datasets. Events and activities took place in Amsterdam,
Berlin, Prague, London, Shanghai, Montevideo and other cities, organised
in association with local groups and partners such as the newspaper Zeit
Online in Germany and the Fond Otakara Motejla in the Czech Republic,
resulting in a dedicated city-focused section of the census
(census.okfn.org/city).[^10chapter10_22] Another push of activity took place in the
run up to the 39^th^ G8 Summit in Lough Erne, UK, which included a focus
on 'tax and transparency' and the release of a G8 'Open Data
Charter'.[^10chapter10_23] Another mini-site focusing on G8 members was released
ahead of the summit.[^10chapter10_24] This was editorialised with a press release
contending that 'G8 countries must work harder to open up essential
data' and that 'progress is lagging behind promise', which was
translated into several languages by volunteers.[^10chapter10_25] These two examples
suggest how the index was adapted and aligned with subnational and
transnational events and advocacy opportunities, in order to intervene
at different scales in accordance with different event-based and
policy-oriented rhythms.

The mailing lists and communications activities around the index also
surfaced frictions in the process of creating a single score and ranking
for the openness of data in countries and cities around the world.
Submissions included comments and queries about pricing, licensing and
the availability of data -- such as concerns that the norms of the index
were in tension with administrative and governance arrangements of
countries being scored. A researcher contributing to the Canadian
assessment suggested 'the methodology does not work well for federations
with divisions of powers and thus different data responsibilities at
different levels of jurisdiction'.[^10chapter10_26] In a similar vein, a submission
for Germany stated:

> ... the census it very tricky for a country like Germany with a
> federal system. Some of the datasets simply are not available at the
> national level as they belong to the federal states. To draw a
> \[realistic\] picture for Germany, we would need to do a census 16+1
> (for the 16 federal states + 1 for the federal government).[^10chapter10_27]

Over the coming years the index explored different ways of responding to
the tensions between conventionalising the assessment of open data for a
range of data types, and the wide range of practices, policies and
advocacy initiatives around government data. One way was to provide more
support for common assessment practices. As well as having editors and
review processes, 2014 saw the introduction of 'mentors', video
tutorials and online drop-in sessions catering to different time zones.
Continuing to evaluate government data from around the world according
to a common set of metrics enabled the production of rankings, as well
as claims such as 'only 11% of the world's published datasets are open
according to the open definition' (Figure 5). We might consider the
value and practical utility accorded to such rankings and claims in
relation to their reactive effects in the context of information policy.
As with the examples of indices above, activists and public servants
were thus provided with material and 'enumerated entities' to make the
case for changes.[^10chapter10_28]

*Figure 5: Graphic to illustrate results of Open Data Index 2014.*

Another way was to enable more flexibility and customisation for
different practices for assessing the openness of data at different
scales and in different settings. In addition to the country-level
censuses that were the basis for the Open Data Index, there were a
proliferation of more local censuses and topical censuses, including
through collaborations and alliances with other civil society
organisations and projects such as the Sunlight Foundation and Code for
America.[^10chapter10_29] This enabled the inclusion of datasets which were deemed
most relevant for different situations. For example, several groups in
Belgium ran a series of workshops, consultations and other activities to
solicit input on what should be included in their census to create 'a
crowdsourced product that is specifically designed for cities in
Belgium'.[^10chapter10_30]

The 2015 Global Open Data Index (GODI) saw further efforts to both
consolidate the transnational assessment process as well as to broaden
it to include other interests and concerns. A list of 'dataset
definitions' sought to clarify assumptions around how the openness of
government data should be assessed, including the role of states in
coordinating the production of data. For example, it was claimed:

> Our assumption the national government has a role as a regulator to
> create and enforce publishing \[of\] such data. Therefore, even if the
> data is not produced by the government, we see it as responsible to
> ensure the open publication of the data.

The question of which forms of data public institutions do create and
should create raised further issues and concerns around different
histories and contexts of governance and administration, such as the
following comment from a Canadian open data advocate:

> This doesn\'t work for Canada. There is a clear division of powers in
> our constitution between the federal government and the provinces. The
> federal government isn\'t going to walk into a constitutional battle
> over e.g. education data just to satisfy this index\... Different
> provinces collect health and education data in different ways. It may
> not be possible to have one consolidated dataset. Please, just respect
> countries\' differences instead of harmonizing everything to a central
> government structure like the UK.

UK government officials from Government Digital Service also commented
that 'some criteria are an awkward fit in different national contexts',
contending that changes in the assessment criteria around election data
had 'cost \[them\] the top spot' and that '\[they'd\] need to change the
laws governing our electoral system to make progress'.[^10chapter10_31]

There was also a consultation around which datasets should be included
in the 2015 edition of the Global Open Data Index, which encouraged
participants to vote on different datasets as well as to propose other
suggestions (Figure 6). This was part of a repositioning from 'a simple
measurement tool' to 'civil society audit of the open data revolution'
exploring 'which datasets are of high social and democratic value',
resulting in the addition of five new datasets: government procurement
data, water quality, weather forecasts, land ownership and health
performance data.[^10chapter10_32] Public input and involvement was also encouraged
in a forum, which saw more extended discussions about questions and
issues around the index.

*Figure 6: "Crowdsourced survey" to inform choice of datasets included
in 2015 Global Open Data Index.*

The code for the project was used to create a prototype of a 'Global
Goals Data Census', in order to track data relevant to the United
Nations Sustainable Development Goals (SDGs), raising the question of
the relationship between the transnational coordination of societal
progress and the openness of governmental data.[^10chapter10_33]

The 2016 edition saw a shift from 'countries' to 'places'. This was said
to be because national government is not always the most important unit
of analysis (especially with regards to sub-national governments with
'administrative and legislative autonomy'). It also aimed to accommodate
'submissions for places that are not officially recognised as
independent countries'.[^10chapter10_34] A 'dialogue phase' in the assessment
process was also introduced in order to enable 'civil society and
government \[to\] talk to one another'.

More recently there has been more reflection about what the Open Data
Index does. Blog posts in 2017 have warned against 'volunteer
fatigue',[^10chapter10_35] guarded against inappropriate comparisons between years
after changes in assessment methodology,[^10chapter10_36] and advocated for a 'shift
in focus from a mere measurement tool to a stronger conversational
device'.[^10chapter10_37]

In summary, the Open Data Census and the Open Data Index aim to
intervene around what is considered 'good data' by assessing the extent
to which the publication of government data conforms with specific legal
and technical norms and conventions, such as open licensing and
machine-readability. It can thus be read in relation to the history of
ideals and practices of open data, as well as free/open source
software.[^10chapter10_38] In contrast to other civil society indices which aim to
advance their issue work by means of specialised research and policy
teams, the Open Data Index has been designed to organise public
involvement around the assessment of public data. It might thus be
considered in terms of its capacities to enable not only *analysis*, but
also *interactivity* using digital technologies -- as well as
structuring participation in particular ways which are not without
tension.[^10chapter10_39] Through this discussion of the development and social life
of the Open Data Index, we suggest how it may be viewed as a
participatory device whose function may vary from 'crowd-sourcing'
assessment, to facilitating more substantive deliberation and public
involvement around the politics of public data. Such indices may thus be
viewed as sites where participation is both configured and contested,
and where practices of valuation and enumeration are both
conventionalised and brought into question.

## References

Bruno*,* Isabelle, Emmanuel Didier*,* Tommaso Vitale. 'Statactivism:
Forms of Action

Between Disclosure and Affirmation', *Partecipazione e Conflitto* 7
(2014).

Buckley, Oliver. 'Open Data - the race to the top', *Gov.Uk blog*, 15
December 2015,
<https://data.blog.gov.uk/2015/12/15/open-data-the-race-to-the-top/>.

Dawes, Sharon S., Lyudmila Vidiasova and Olga Parkhimovich. 'Planning
and designing open government data programs: An ecosystem approach',
*Government Information Quarterly* 33 (2016): 15--27.

Eaves, David. 'How To Evaluate The State Of Open Data', *Techpresident*,
8 May 2012,
<http://techpresident.com/news/wegov/22161/how-evaluate-state-open-data>.

Espeland, Wendy N., and Mitchell L. Stevens. 'Commensuration as a Social
Process',

*Annual Review of Sociology* 24 (1998): 313--343.

Espeland, Wendy N., and Michael Sauder. 'Rankings and Reactivity: How
Public Measures Recreate Social Worlds', *American Journal of Sociology*
113 (2007): 1--40.

Fish, Adam, Christopher M. Kelty, Luis F.R. Murillo, Lilly Nguyen, and
Aaron Panofsky. 'Birds of the Internet'. *Journal of Cultural Economy* 4
(2011): 157--187. [ ]{.underline}

Gray, Jonathan. 'Towards a Genealogy of Open Data', *European Consortium
for Political Research General Conference*, Glasgow, 3-6 September 2014,
<http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2605828>.

\_\_\_\_\_. 'Three Aspects of Data Worlds', *Krisis: Journal for
Contemporary Philosophy* (2018).

Guyer, Jane. 'Percentages and perchance: archaic forms in the
twenty-first century', *Distinktion, Journal of Social Theory* 15
(2014): 155-173.

Kelty, Christopher M. *Two Bits: The Cultural Significance of Free
Software: The Cultural Significance of Free Software and the Internet*,
Durham NC: Duke University Press, 2008.

Latour, Bruno. 'Why Has Critique Run out of Steam? From Matters of Fact
to Matters of Concern', *Critical Inquiry* 30 (2004): 225--248.

\_\_\_\_\_. *An Inquiry into Modes of Existence: An Anthropology of the
Moderns*, trans C. Porter, Cambridge MA: Harvard University Press, 2013.

Law, John, and Evelyn Ruppert. 'The Social Life of Methods: Devices',
*Journal of Cultural Economy* 6 (2013): 229--240.

Le Dantec, Christopher A., and Carl DiSalvo. 'Infrastructuring and the
formation of publics in participatory design', *Social Studies of
Science* 43 (2013).

Maron, Mikel. 'Let's Build the Global Goals Data Census', *Medium*, 5
October 2015,
https://medium.com/\@mikelmaron/let-s-build-the-global-goals-data-census-
c38b0458c9a.

Marres, Noortje. *Digital Sociology: The Reinvention of Social
Research*, Cambridge: Polity Press, 2017.

Milan, Stefania and Lonneke van der Velden. 'The Alternative
Epistemologies of Data Activism', *Digital Culture & Society* 2 (2016):
57--74.

Montiel, Oscar. 'Our Country Sample and What It Tells Us About Our
Contributors', *Open Knowledge International blog*, 3 May 2017,
https://blog.okfn.org/2017/05/03/our-
country-sample-and-what-it-tells-about-our-contributors/.

Open Knowledge International. 'Government data still not open enough --
new survey on eve of London summit', *Open Knowledge International
blog*, 28 October 2013,
<https://blog.okfn.org/2013/10/28/government-data-still-not-open-enough/>.

\_\_\_\_\_. 'The Future of the Global Open Data Index: Assessing the
possibilities', *Open Knowledge International blog*, 2 November 2017,
https://blog.okfn.org/2017/11/01/the-future-of-the-global-open-data-index-assessing-
the-possibilities/.

Pauwels, Pieter-Jan. 'Results of Wiki Survey and final steps', 12
September 2014,
<http://openbelgium.be/2014/09/results-of-wiki-survey-and-final-steps/>.

Pollock, Rufus. 'The Open Data Census -- Tracking the State of Open Data
Around the World', *Open Knowledge International blog*, 20 February
2013,
https://blog.okfn.org/2013/02/20/open-data-census-tracking-the-state-of-open-data-
around-the-world/.

\_\_\_\_\_. 'G8 countries must work harder to open up essential data',
*Open Knowledge International blog,* 14 June 2013,
https://blog.okfn.org/2013/06/14/g8-countries-must-
work-harder-to-open-up-essential-data/.

\_\_\_\_\_. 'Announcing the Local Open Data Census', *Open Knowledge
International blog*, 4 February 2014,
https://blog.okfn.org/2014/02/04/announcing-the-local-open-
data-census/.

Power, Michael. *The Audit Society: Rituals of Verification*, Oxford:
Oxford University Press, 1999.

Prime Minister's Office. '2013 Lough Erne G8 Leaders\' Communiqué', 18
June 2013,
https://www.gov.uk/government/publications/2013-lough-erne-g8-leaders-
communique.

Rottenburg, Richard, Sally E. Merry, Sung-Joon Park and Johanna Mugler
(eds). *The World of Indicators: The Making of Governmental Knowledge
through Quantification*, Cambridge: Cambridge University Press, 2015.

Rubinstein, Mor. 'What should we include in the Global Open Data Index?
From reference data to civil society audit', *Open Knowledge
International blog*, 18 June 2015,
https://blog.okfn.org/2015/06/18/what-should-we-include-in-the-global-open-data-
index-from-reference-data-to-civil-society-audit/.

Strathern, Marilyn. *Audit Cultures: Anthropological Studies in
Accountability, Ethics and the Academy*, London: Routledge, 2000.

Thorsby, Jeffrey, Genie, N.L. Stowers, Kristen Wolslegel and Ellie
Tumbuan. 'Understanding the content and features of open data portals in
American cities', *Government Information Quarterly* 34 (2017): 53--61.

Tkacz, Nathaniel. *Wikipedia and the Politics of Openness*, Chicago:
University Of Chicago Press, 2014.

Transparency International. 'Corruption Perceptions Index',
*Transparency International blog*, 21 February 2018,
<https://www.transparency.org/news/feature/corruption_perceptions_index_2017>.

Verran, Helen. 'Number as an inventive frontier in knowing and working
Australia's water resources', *Anthropological Theory* 10 (2010):
171--178.

\_\_\_\_\_. 'Enumerated Entities in Public Policy and Governance', in
Ernest Davis and Philip J. Davis (eds), *Mathematics, Substance and
Surmise,* New York: Springer, 2015, pp. 365--379.

Villum, Christian. 'The Open Data Census Challenge on Open Data Day
2013', *Open Knowledge International blog,* 5 March 2013,
https://blog.okfn.org/2013/03/05/the-
open-data-census-challenge-on-open-data-day-2013/.

[^10chapter10_1]: Bruno Latour, *An Inquiry into Modes of Existence: An Anthropology
    of the Moderns*, trans C. Porter, Cambridge MA: Harvard University
    Press, 2013.

[^10chapter10_2]: Michael Power, *The Audit Society: Rituals of Verification*,
    Oxford: Oxford University Press, 1999; Marilyn Strathern, *Audit
    Cultures: Anthropological Studies in Accountability, Ethics and the
    Academy*, London: Routledge, 2000.

[^10chapter10_3]: The corresponding organisation in order of the indices named:
    Transparency International, Reporters Without Border, New Economics
    Foundation, Tax Justice Network, Walk Free, Oxfam.

[^10chapter10_4]: Wendy N. Espeland and Michael Sauder, 'Rankings and Reactivity:
    How Public Measures Recreate Social Worlds', *American Journal of
    Sociology*, 113 (2007): 1--40. Richard Rottenburg, Sally E. Merry,
    Sung-Joon Park, and Johanna Mugler (eds.), *The World of Indicators:
    The Making of Governmental Knowledge through Quantification*,
    Cambridge: Cambridge University Press, 2015.

[^10chapter10_5]: Helen Verran, 'Number as an inventive frontier in knowing and
    working Australia's water resources', *Anthropological Theory*, 10
    (2010): 171--178; Helen Verran, 'Enumerated Entities in Public
    Policy and Governance', in Ernest Davis and Philip J. Davis (eds),
    *Mathematics, Substance and Surmise,* New York: Springer, 2015, pp.
    365--379.

[^10chapter10_6]: Transparency International, 'Corruption Perceptions Index',
    *Transparency International blog*, 21 February 2018,
    https://www.transparency.org/news/feature/corruption\_perceptions\_index\_2017.

[^10chapter10_7]: Jane Guyer, 'Percentages and perchance: archaic forms in the
    twenty-first century', *Distinktion, Journal of Social Theory* 15
    (2014): 155-173.

[^10chapter10_8]: Sharon S. Dawes, Lyudmila Vidiasova and Olga Parkhimovich,
    'Planning and designing open government data programs: An ecosystem
    approach', *Government Information Quarterly* 33 (2016): 15--27;
    Jeffrey Thorsby, Genie N.L. Stowers, Kristen Wolslegel, and Ellie
    Tumbuan, 'Understanding the content and features of open data
    portals in American cities', *Government Information Quarterly* 34
    (2017): 53--61.

[^10chapter10_9]: Isabelle Bruno*,* Emmanuel Didier and Tommaso Vitale
    'Statactivism: Forms of Action Between Disclosure and Affirmation',
    *Partecipazione e Conflitto*, 7 (2014).

[^10chapter10_10]: Stefania Milan and Lonneke van der Velden, 'The Alternative
    Epistemologies of Data Activism', *Digital Culture & Society* 2
    (2016): 57--74.

[^10chapter10_11]: Jonathan Gray, 'Three Aspects of Data Worlds', *Krisis: Journal
    for Contemporary Philosophy* (2018).

[^10chapter10_12]: John Law and Evelyn Ruppert, 'The Social Life of Methods:
    Devices', *Journal of Cultural Economy* 6 (2013): 229--240.

[^10chapter10_13]: Bruno Latour, 'Why Has Critique Run out of Steam? From Matters of
    Fact to Matters of Concern', *Critical Inquiry* 30 (2004): 225--248.

[^10chapter10_14]: Nathaniel Tkacz, *Wikipedia and the Politics of Openness*,
    Chicago: University Of Chicago Press, 2014.

[^10chapter10_15]: Christopher A Le Dantec, and Carl DiSalvo, 'Infrastructuring and
    the formation of publics in participatory design', *Social Studies
    of Science* 43 (2013).

[^10chapter10_16]: The NGO underwent several name changes over the course of the
    project. It started as Open Knowledge Foundation (OKF), then became
    Open Knowledge (OK) and finally Open Knowledge International (OKI).
    For clarity we use the current name throughout.

[^10chapter10_17]: Adam Fish, Christopher M. Kelty, Luis F.R. Murillo, Lilly Nguyen,
    and Aaron Panofsky, 'Birds of the Internet', *Journal of Cultural
    Economy* 4 (2011): 157--187. [ ]{.underline}

[^10chapter10_18]: David Eaves, 'How To Evaluate The State Of Open Data',
    *Techpresident*, 8 May 2012,
    http://techpresident.com/news/wegov/22161/how-evaluate-state-open-data.

[^10chapter10_19]: Open Knowledge International, 'Government data still not open
    enough -- new survey on eve of London summit', *Open Knowledge
    International blog*, 28 October 2013,
    https://blog.okfn.org/2013/10/28/government-data-still-not-open-enough/.

[^10chapter10_20]: Rufus Pollock, 'The Open Data Census -- Tracking the State of
    Open Data Around the World', *Open Knowledge International blog*, 20
    February 2013,

    https://blog.okfn.org/2013/02/20/open-data-census-tracking-the-state-of-open-data-around-the-world/.

[^10chapter10_21]: Jonathan Gray, 'Three Aspects of Data Worlds', *Krisis: Journal
    for Contemporary Philosophy* (2018).

[^10chapter10_22]: Christian Villum, 'The Open Data Census Challenge on Open Data
    Day 2013', *Open Knowledge International blog,* 5 March 2013,
    https://blog.okfn.org/2013/03/05/the-open-data-census-challenge-on-open-data-day-2013/

[^10chapter10_23]: Prime Minister's Office, '2013 Lough Erne G8 Leaders\'
    Communiqué', 18 June 2013,

    https://www.gov.uk/government/publications/2013-lough-erne-g8-leaders-communique.

[^10chapter10_24]: census.okfn.org/g8

[^10chapter10_25]: Rufus Pollock, 'G8 countries must work harder to open up
    essential data', *Open Knowledge International blog*, 14 June 2013,
    https://blog.okfn.org/2013/06/14/g8-countries-must-work-harder-to-open-up-essential-data/.

[^10chapter10_26]: http://lists-archive.okfn.org/pipermail/open-data-census/2013-July/000082.html.

[^10chapter10_27]: Submission via Google Form for Open Data Census 2013.

[^10chapter10_28]: Helen Verran, 'Number as an inventive frontier in knowing and
    working Australia's water resources'. *Anthropological Theory* 10
    (2010): 171--178. Helen Verran, 'Enumerated Entities in Public
    Policy and Governance', in Ernest Davis and Philip J. Davis (eds),
    *Mathematics, Substance and Surmise,* New York: Springer, 2015, pp.
    365--379.

[^10chapter10_29]: Rufus Pollock, 'Announcing the Local Open Data Census', *Open
    Knowledge International blog,* 4 February 2014,
    https://blog.okfn.org/2014/02/04/announcing-the-local-open-data-census/.

[^10chapter10_30]: Pieter-Jan Pauwels, 'Results of Wiki Survey and final steps', 12
    September 2014,
    http://openbelgium.be/2014/09/results-of-wiki-survey-and-final-steps/.

[^10chapter10_31]: Oliver Buckley, 'Open Data - the race to the top', *Gov.Uk blog*,
    15 December 2015,
    https://data.blog.gov.uk/2015/12/15/open-data-the-race-to-the-top/.

[^10chapter10_32]: Mor Rubinstein, 'What should we include in the Global Open Data
    Index? From reference data to civil society audit', *Open Knowledge
    International blog*, 18 June 2015,

    https://blog.okfn.org/2015/06/18/what-should-we-include-in-the-global-open-data-index-from-reference-data-to-civil-society-audit/.

[^10chapter10_33]: Mikel Maron, 'Let's Build the Global Goals Data Census',
    *Medium*, 5 October 2015,
    https://medium.com/\@mikelmaron/let-s-build-the-global-goals-data-census-c38b0458c9a.

[^10chapter10_34]: https://index.okfn.org/methodology/.

[^10chapter10_35]: Oscar Montiel, 'Our Country Sample and What It Tells Us About Our
    Contributors', *Open Knowledge International blog,* 3 May 2017,
    https://blog.okfn.org/2017/05/03/our-country-sample-and-what-it-tells-about-our-contributors/.

[^10chapter10_36]: Oscar Montiel, 'Our Country Sample and What It Tells Us About Our
    Contributors', *Open Knowledge International blog*, 3 May 2017,
    https://blog.okfn.org/2017/05/03/our-country-sample-and-what-it-tells-about-our-contributors/.

[^10chapter10_37]: Open Knowledge International, 'The Future of the Global Open Data
    Index: Assessing The Possibilities', *Open Knowledge International
    blog*, 2 November 2017,
    https://blog.okfn.org/2017/11/01/the-future-of-the-global-open-data-index-assessing-the-possibilities/.

[^10chapter10_38]: Christopher M. Kelty, *Two Bits: The Cultural Significance of
    Free Software: The Cultural Significance of Free Software and the
    Internet*, Durham NC: Duke University Press, 2008. Jonathan Gray,
    'Towards a Genealogy of Open Data', *European Consortium for
    Political Research General Conference*, Glasgow, 3-6 September 2014,
    http://papers.ssrn.com/sol3/papers.cfm?abstract\_id=2605828;
    Jonathan Gray, 'Three Aspects of Data Worlds', *Krisis: Journal for
    Contemporary Philosophy* (2018).

[^10chapter10_39]: Noortje Marres, *Digital Sociology: The Reinvention of Social
    Research*, Cambridge: Polity Press, 2017.
