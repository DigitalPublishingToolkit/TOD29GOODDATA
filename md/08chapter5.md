---
Pr-id: Publications
P-id: Theory on Demand
A-id: 29
Type: book
Book-type: anthology
Anthology item: article
Item-id: u
Article-title: Good Data
Article-status: accepted
Author: Editors: Angela Daly, S. Kate Devitt, Monique Mann 
Author-email:   corresponding address
Author-bio:  about the author
Abstract:   In recent years, there has been an exponential increase in the collection, aggregation and automated analysis of information by government and private actors, and in response to this there has been a significant critique regarding what could be termed ‘bad’ data practices in the globalised digital economy. 
In order to paint an alternative, more optimistic but still pragmatic picture of the datafied future, this book examines and proposes ‘good data’ practices, values and principles from an interdisciplinary, international perspective. From ideas of data sovereignty and justice, to manifestos for change and calls for activism, this collection opens a multifaceted conversation on the kinds of futures we want to see, and presents concrete steps on how we can start realising good data in practice.
Keywords:   data, datafication, data collection, data practice, sovereignty, activism
Rights: CC BY-NC 4.0
...


# 5: An Energy Data Manifesto

*Declan Kuch, Naomi Stringer, Luke Marshall, Sharon Young, Mike Roberts,
Iain MacGill, Anna Bruce and Rob Passey*

**Abstract**

This collaborative manifesto, co-written by a social scientist and
engineers, situates the demands for data about energy use and planning
by regulators, consumers and policy-makers in an historical and
regulatory context, most notably the shift from state ownership of large
coal power plants to competition policy. We outline paths forward in
three overlapping areas: firstly, data for the empowerment of consumers
should see easier access to usage data provided by retailers, whilst new
collectives to produce energy should be encouraged and enabled. Secondly
under the umbrella of ‘data for accountability’, we situate practical
work we have undertake in open source modelling in a wider set of
concerns about how retailers and electricity supply (poles and wires)
businesses are run. Finally, building on these two areas, we speculate
how moving past the binary between individual versus corporate interest
may enable a more democratic and accountable research capacity into
energy planning. We conclude noting the scale and scope of challenges
facing energy policy makers in Australia and underscore the importance
of a strategic ‘technopolitics’ – the technical details of market design
– to both effective action on climate change and robust, sustainable
energy systems. 

## Introduction

A spectre is haunting Australia – the spectre of an energy transition.
All the powers of the old energy sector have entered an unholy alliance
to exorcise this spectre.[^05chapter5_1] Enabled by rapid technological changes,
including developments in distributed solar, storage, metering and
control, the prospect of an environmentally sustainable, equitable and
reliable energy system driven by community knowledge and engagement has
emerged. The control of the resultant explosion of energy data lies at
the heart of the battle for our energy future. Although enthusiasm for
much broader access to energy data to monitor and facilitate this
transition is growing, some key incumbent energy sector businesses,
politicians and others are pushing to maintain present asymmetries in
energy data collection and access. Two things result from the struggle
to remedy these asymmetries:

1.  A revolution in how we collect and disseminate energy data –
    especially that of end-users – is sorely needed. This is widely
    acknowledged by Australian policy-makers.
    
2.  Appropriate frameworks are urgently needed for collecting and
    sharing suitably anonymised energy data to enable a rapid transition
    to a democratic and sustainable energy future.

As energy researchers, we use energy data to inform our work, build our
models and provide insights on possible energy transition futures. By
collectively and openly publishing our views about what good energy data
access and oversight might look like, and the prospects for an energy
data revolution, we hope to facilitate public debate to help bring about
a just transition in the energy sector in ways that empower and enable
communities to determine their own futures.

We focus on the electricity sector that is the primary subject of our
work, and where the quantity and complexity of energy data is increasing
rapidly, with only limited guidance from policy-makers regarding who
should have access and under what terms. This work is both technical and
political – it redraws the boundaries of which actors have access to
relevant data, and, therefore, who can make decisions. Political
structures are important in shaping regulation, but equally, politics
and regulations are shaped by technical details and flows of data.

## A History of the Current Paradigm Through Data

The history of the Australian electricity system is a history of
paradigms: small, local generation and governance at the municipal level
has given way to large, state-owned, and generally vertically integrated
electricity commissions. These became responsible for planning, building
and operating large centralised generation assets and networks to serve
energy consumers under a social contract of affordable and reliable
electricity provision. Unlike some jurisdictions, such as those States
in the US that established Utility Commissions to oversee monopoly
electricity utilities, there was remarkably little transparency about
the operation of these Australian state electricity commissions. To this
day, Utilities themselves have had very limited information on nearly
all energy consumers because data infrastructure has typically comprised
simple accumulation meters that provided only quarterly consumption
data.

Events in the 1980s, such as attempts to build power stations for an
aluminium smelting boom that never materialised, increased pressure to
establish greater government and public oversight of the Utilities in
some key states. However, these initiatives were overtaken by a
micro-economic reform agenda in the early 1990s that established a very
different direction for the electricity sector.

The reform agenda for electricity focussed on the vertical separation of
generation and retail from the natural monopoly networks, the
introduction of competition and the sale of publicly-owned electricity
generation, transmission and distribution assets to the private
sector.[^05chapter5_2] The key role of publicly available data (see Box 1) to
facilitate an effective market in electricity provision was appreciated
at an early stage of this restructuring.[^05chapter5_3]

A key objective of micro-economic reform was to provide energy consumers
with greater choice, which according to economic rationalist theory
would put them at the heart of decision-making in the industry.[^05chapter5_4]
There was far less focus on the role of public energy data (Box 1) to
facilitate effective engagement at the distribution network and retail
market level.

| **Box 1: What is ‘Public Energy Data’?**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Energy data typically refers to information over time regarding the level of energy consumption, generation, quality,[^05chapter5_5] and price. When coupled with metadata (such as consumer location or demographics), this data can yield valuable insights for researchers, and policymakers in domains such as urban planning, demography, and sociology. We use the prefix ‘*public’* to refer to energy data which is freely and publicly available. This can be contrasted to proprietary data held by privately owned retailers or within government departments. Public refers to both the state of accessibility and the process of making otherwise enclosed data freely available. |
*Box 1: What is ‘Public Energy Data’?*

Market design decisions in the 1990s mean that key parameters of the
energy markets are published online. The Federal regulator AEMO
publishes energy consumption and wholesale price across regions (such as
New South Wales) and updates this information every five minutes. energy
data demonstrate the importance of aggregation^.^[^05chapter5_6] When household
data includes thousands or even millions of households, it yields
insights relevant to decision-making about the supply and distribution
system (poles and wires), retail and wholesale markets. Because Retailer
and Network Business access to consumer data is generally far superior
to that of consumers, regulators or researchers, there are substantial
information asymmetries with implications for competition, regulation
and broader decision-making.

## Data for Empowerment of Consumers and New Collectives

Decarbonising an electricity sector governed through the competition
policy paradigm has proven incredibly problematic.[^05chapter5_7] A new paradigm of
governing carbon emissions through a nationally regulated cap and trade
scheme spluttered into life briefly in 2012 before being snuffed out by
the Coalition Government of Tony Abbott in 2014.

In this contentious policy context, private action by households to
reduce emissions by deploying household PV has been one of the few
environmental success stories for effective transition to a sustainable
energy system in Australia. Collectives have also sprung up in the ashes
of the carbon emissions trading regime seeking to make the transition to
sustainable electricity industry infrastructure. The competition policy
paradigm preserves universal individual household access to competitive
retail markets. However, these markets have generally served retailers
better than their customers. Moreover, the competition policy paradigm
has constrained collectives at the community scale seeking to building
mini or microgrids or develop shared energy resources like solar and
batteries. Crucially, groups organising around contracts that would
effectively remove choice of provider have been scuppered by competition
justifications. Furthermore, competition policies have further
constrained access to data by locking these groups into market
arrangements where legacy retail businesses have advantages of scale and
incumbency.

At present, households can be both consumers and producers of energy
(prosumers) yet do not have real-time access to their energy consumption
data. This data is collected by the metering service providers and then
passed to the electricity retailers and network companies for billing,
sales and planning needs. While consumers are able to obtain their past
consumption data, it is usually not a straightforward process and there
is no consistent format of delivery. As decentralised energy becomes
increasingly prevalent, secure energy data sharing is needed to
facilitate new markets and options.

Community groups such as Pingala and ClearSky Solar have been asking the
question, ‘who should have energy usage data and under what
circumstances?’ with quite different perspectives to those of network
operators, the large retailers and Federal regulators that are a legacy
of the old paradigm. These community groups seek to democratise
ownership of the energy system through facilitating communities’
investment in solar PV assets and sale of the electricity generated.[^05chapter5_8]
However, without visibility over relevant data to investment
decision-making and electricity loads, participation in the electricity
market is more difficult. Managing a decentralised, variable renewable
energy supply requires an accurate and time-sensitive set of monitoring
tools.

While millions of rooftop distributed solar generators have been
installed across Australia, the required data acquisition tools have not
been deployed in parallel at a similar scale. Distributed resources to
monitor and forecast their own operation are much better able to
integrate with and respond to price signals, especially when aggregated
into Virtual Power Plants – where a host of smaller controllable loads
such as battery systems, electric cars, air conditioners and/or pool
pumps act together like a physical power station.

In this political and regulatory context, data empowerment for the
grassroots provides hope. For individual consumers, this can simply mean
being able to compare their retail offer with others. This has been made
somewhat possible, to the extent possible just by using bill data, via
the Australian Government’s ‘Energy Made Easy’ website, while the
Australian Consumer Association, Choice, is also developing a tool to
inform consumers in the marketplace, particularly around purchases of
solar or batteries. For communities, empowerment can mean accessing the
electricity usage data of one or more sites like breweries or community
halls, to size an appropriate suite of distributed energy technologies
to reduce dependence on what are often unfair contracts with retailers.
Or it can be as complex as using high temporal resolution load and
generation data to facilitate real-time peer-to-peer local energy
trading in a microgrid or across the network as exemplified by Power
Ledger or LO3. However, even timeseries usage data from a single site is
currently typically not available or easily accessible. Rather than
being “allowed” retrospective access to their data, there are collective
benefits in households having real-time access to their energy use data,
with the ability to control access to that data and to share it with
trusted organisations.

A proposed trial in the sunny Byron Bay region of Northern NSW provides
an apt example for a new paradigm of data flows. In this case, community
owned retailer Enova is seeking to enable local sharing of generated
solar power between consumers in an arts and industrial estate and is
considering battery energy storage to increase the volume of solar power
consumer locally.[^05chapter5_9] In this instance, the data is essential to
allowing peer-to-peer energy trading, which otherwise would not be
possible and critically, understanding of the collective energy needs
for the estate would not be known. Furthermore, the ability for a
battery to provide network benefits requires understanding of network
conditions, typically known only by the local distribution network
service provider.[^05chapter5_10] Open Utility in the UK is a similar example,
enabling consumers to trade peer-to-peer through a retailer, and looking
to offer networks flexibility services.[^05chapter5_11]

These examples demonstrate that appropriate data access can foster
creativity with legal structures and contracts which enables communities
to work around the intransigence of incumbent organisations and rules,
and for new collectives to form. These new collectives are based on the
sharing of data on energy loads in ways that can catalyse a transition
to distributed, sustainable energy economy.

### We Recommend

-   Opt-in data access to energy use data beyond just networks and
    retailers.
-   Residential consumers be granted straightforward access to their own
    energy use data and be given consent to give or withdraw data for
    specific purposes; and so are able to easily come together to
    produce and consume energy as community energy groups.
-   Further experimentation with the legal form of electricity
    businesses that will enable investments in renewable energy.

## Data for Accountability

The corporatisation of large centralised generation and transmission
brings with it requirements of accountability. The displacement of a
public service provision model with market and corporate logics has
resulted in incentives to seek rents on what was public infrastructure,
as electricity systems globally are becoming more decentralised and
decarbonised.

Decentralisation presents is both an opportunity to empower new
collectives, and brings with it risks of high costs and new power
imbalances. The Australian Energy Market Operator have recently
identified a potential cost reduction of nearly \$4 billion if
distributed energy resources (namely rooftop solar PV and battery energy
storage) are effectively integrated,[^05chapter5_12] whilst also flagging the
substantial risks associated with the lack of visibility and control
that distributed energy resources afford.[^05chapter5_13] In this context of
technological change and associated market and regulatory reform, we see
public energy data as a critical tool in a) ensuring efficient outcomes,
particularly as they can remedy historical incentives and incumbent
player advantages, and; b) supporting fair outcomes by increasing
visibility of the distribution of costs and benefits associated with the
transition.

Network Service Providers (NSPs) own and operate the ‘poles and wires’
across Australia and present a particular challenge for regulators and
rule makers. As regulated monopolies, they need to be effectively
supervised without stifling innovation. They are subject to five yearly
reviews in which their revenue for the upcoming ‘regulatory period’ is
set by the Australian Energy Regulator (AER), based on information
provided by the NSPs. Their regulated task of ensuring energy supply is
technically complex and they are increasingly challenged as distributed
energy resources such as rooftop photovoltaic solar (the most common
form of flat, black panels on roofs) grow in number. Technologies such
as solar can reduce consumer bills and therefore utility profitability.
Therefore, without transparency about network investment there is a risk
that technical challenges can be used to justify limiting access to
networks, or the use of tariff structures that disadvantage consumers
that install these technologies. Improved independent oversight of
technical conditions in the depths of the network (e.g. Box 2) may lead
to more efficient and fair investment and operational outcomes.

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Box 2: The importance of voltage data for integrating distributed renewables **
  
  Understanding how networks are functioning at both the high voltage transmission and low voltage distribution ends is crucial to integrating renewable energy resources effectively and at a fair cost to society. For instance, as PV uptake continues, a technical upper voltage limit is reached at local transformers, at which point it is difficult for additional PV to connect to the network. The responsibility of Network Service Providers to maintain a stable electricity network can lead them to a cautious approach to integration of distributed renewables, and in some jurisdictions, this has resulted in NSPs drastically restricting deployment of residential PV.[^05chapter5_14]<br /><br />
  However, recent data analysis – which used information captured from independent monitoring of household PV systems – shows that network voltages are generally high due to historic network decision making (distribution transformer set points were generally set at a high voltage, leaving minimal ‘headroom’ for PV).[^05chapter5_15] This has implications for exporting rooftop PV electricity to the national grid. The visibility afforded by voltage data readings across the network may enable scrutiny of network expenditure to ensure money is spent in a judicious manner;[^05chapter5_16] there may be cost-effective solutions to maintain grid stability without placing unnecessary restrictions on deployment of distributed PV.<br /><br />Access to such data is key to overcoming integration barriers and market asymmetries, and as such is an important companion to wider policies on a just energy transition that have received more widespread attention such as the Renewable Energy Target and carbon pricing schemes.
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

*Box 2: The importance of voltage data for integrating distributed renewables*
 
We believe the existing regulatory hierarchy of access rights to
electricity usage data requires restructuring. As things stand,
incumbent retailers automatically have full access to their customers’
data which they can use for commercial purposes beyond just ensuring
accurate billing, such as targeted marketing. While recent regulatory
changes give customers the right to access their electricity consumption
data from retailers or NSPs, [^05chapter5_17] householders must apply
retrospectively for the data, while both the application process and the
format of data supplied lack consistency and clarity. Although the
regulation allows a customer to authorise a third party to access their
data, as yet there is no consistent mechanism for obtaining multiple
consents, nor for making bulk data requests, while these bulk requests
are exempted from the time limits imposed on retailers and NSPs to
provide data. This leaves researchers, along with community groups and
other players needing data from multiple users, at the bottom of the
pile. The creation of Consumer Data Rights will likely entrench this
hierarchy, further entrenching a regulatory mindset of ‘individual
household vs. corporations’, hobbling collectively forms of action from
these other forms of actors.

A hierarchy based on the purpose of data usage could be designed to
require customer opt-in to allow their retailer (or other parties) to
access their data for targeted sales. Conversely, use of anonymised data
for public-interest research or for non-profit, community-based
engagement in the energy market could be opt-out for initiatives like
Enova, contingent on strict standards of data-protection and governance
schemes that include ongoing re-evaluation of the data usage. Customers
should be empowered to easily give or withdraw consent to access their
data for specific purposes, which may involve a role for a delegated
authority (similar to the community representative committees in
Nepal)[^05chapter5_18] to respond to specific access requests on their behalf.

A good energy data regime cannot continue to play by the incumbent
rules. Good policy-making and robust regulation depend on access to data
and the development of appropriate models and methods for analysis that
allow efficiency, competition and equity to be assessed. Outdated rules
must be reformed so that data can be harnessed by individual consumers
and those that act on their behalf, community energy groups and
consumer-advocates.[^05chapter5_19]

It has been especially challenging for consumer advocacy groups, NGOs,
and general public to effectively participate and engage in regulatory
decision-making processes. Network operators’ submissions to regulatory
process could be made available to consumer groups and researchers for
greater scrutiny. To effectively engage with these groups, they should
also provide access to appropriate analysis and modelling platforms.
CEEM’s tariff analysis tool (Box 3) provides an example of a transparent
and open-source modelling platform that can improve stakeholder
engagement around electricity prices.

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Box 3: Opening the black boxes: CEEM’s Tariff Analysis Tool**
  
  CEEM’s tariff analysis tool is an example of an open source model which is accessible by stakeholders like think tanks, community energy organisations, local councils and policy-makers.[^05chapter5_20]<br /><br />Consumers’ ability to reduce their consumption using energy efficiency and solar is altering the distribution of revenue collection from consumers via tariffs, and has drawn attention to apparent cross-subsidies from traditional electricity-consuming customers to solar ‘prosumers’, while users of air-conditioning have also been identified as placing an unfair cost burden on other customers. Along with emerging costs of transforming the electricity network to a more distributed model, this has driven regulatory changes that now require network utilities to develop more cost-reflective tariffs. However, the proprietary energy models used by network providers and their private consultants are often complex, opaque and based on assumed variables, making it possible for the energy modellers to exploit uncertainties within a regulatory context biased towards recovering capital expenditure on electricity infrastructure.<br /><br />To overcome this information asymmetry, CEEM’s tariff tool allows stakeholders to test different electricity network tariffs on different sets of customers and investigate the impact on users’ electricity bills, their cost-reflectivity, and distributional impacts using anonymised load data. Because it is open-source, the tool and results can be easily verified and can therefore facilitate transparency and more robust regulatory decisions.<br /><br />Unlike black-box and expensive proprietary energy models which are usually only available to powerful incumbent stakeholders, open source modelling platforms can be used, expanded, scrutinised, and verified by any interested stakeholders. This democratisation of tariff analysis is an example of how open source tools can empower more stakeholders, improve the operation of markets, regulation and policymaking.
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
*Box 3: Opening the black boxes: CEEM’s Tariff Analysis Tool*

Regulators of energy retail licenses (AER), energy reliability (AEMO)
and market competition and power (ACCC) have particularly important
roles in maintaining the accountability of energy market players. and
existing so-called markets in energy services have some fundamental
problems at the retailer level: incumbent retailers have some unfair
advantages selling energy devices and services to their customers
because they have energy use data that is unavailable, or at least
challenging to obtain, for other potential energy service providers.

### Recommendations:

-   Retailers be required to obtain opt-in permission for targeted
    sales.
-   The expansion of tools to enhance market participation of individual
    consumers and community groups, created in the public interest.
-   Some communities of modellers be granted delegated authority to
    access fine-grain energy data: good energy data requires an
    appropriate interface between energy users, regulators and power
    providers.
-   Increased expert resources for regulators to enable them to access
    to usage and tariff data.
-   Support for open-source modelling and data transparency in
    regulatory decision-making to reduce reliance on opaque analysis
    from private consultants

## Data for the People: The Potential of Standards

Ethical protocols of informed consent for research serve to formalise
relationships through a bureaucratic agency and assist universities in
managing risks to research participants and to their own reputation.
Rights to privacy, to withdraw from research and so forth, can act as
valuable bulwarks against the abuse of the powers and privileges to
access sensitive data.

But singular moments of ‘consent’ are not ideal for the dynamics of
energy data research, nor are they suitable for the digital platforms
upon which much of today’s interactions take place. Blurred boundaries
between public-interest research and commercially-driven consultancy
(exacerbated by privatisation of public institutions and increased
corporatisation of universities) sharpen the need for consent
conditional on the *purpose* of proposed data usage. Data activist
Paul-Olivier Dehaye has recently quipped that a lot of ‘data protection
issues come from a narrow-minded business view of personal data as
commodity. Much better is to embrace the European view, with a notion of
personhood covering flows of personal data as well’.[^05chapter5_21] This move from
liberal privacy to communal personhood, he suggests is analogous to the
shift from property rights to granting rights to rivers.

Ongoing public dialogue over the trade-off between privacy concerns and
the granularity and reliability of data for analysis is required in such
a shift – especially where the appropriation of data for private gain
has often occurred at the behest of government agencies. Privacy,
granularity and reliability of data for analysis and decision-making are
intimately related for the purposes of infrastructure planning. Usage
data at varying temporal and spatial resolutions is valuable to
researchers, consumers and networks. For example, electricity
consumption data at specific points in the electricity network is
essential to network operators and useful to new energy business models
based on sharing or aggregating consumer load and generation, and also
potentially to other market participants and researchers. Since
individual household data cannot typically be extracted from such data,
there is little privacy or commercial risk involved in releasing it.
However, the same data identified by street address, while potentially
even more useful for certain purposes, requires more careful handling.

Public debate over energy data privacy often focuses on an individual’s
place of residence. This is often a result of imagining an individual
household as a final fortress in an increasingly invasively connected
world. As a result, energy researchers are hamstrung by highly
anonymised data sets, for instance limiting geographical specificity to
a postcode area. There are two primary challenges arising from this
abstraction of data:

1.  The first arises because the fabric of everyday life sustained
    through energy networks is vastly complicated. Electricity networks
    do not fit neatly into postcode-shaped areas. Aggregation of data
    points and the capacity to assess the impacts of decisions on the
    wider network is severely limited by the lack of granularity. For
    instance, the contribution of a certain customer demographics to
    peak demand on their local network infrastructure requires
    researchers to make clear connections between household and
    distribution network usage data. This connection is important
    because it forms the basis of significant supply, demand and network
    investment decisions.
    
2.  The second arises because of the extremely rapid growth of
    distributed generation such as rooftop PV and batteries. These
    systems can have significant impacts on the security of the
    electricity system (i.e. the ability for the system to keep working
    without significant risk of power quality issues),[^05chapter5_22] however
    their behaviours need to be understood in the context of their local
    network. Postcode level anonymisation makes this near impossible,
    whereas street location or even location on a specific section of
    the ‘poles and wires’ would be ideal.

Just as a more communal notion of personhood can foster better data
practice outcomes, social scientists have argued that shifting the focus
away from individual choice towards collective responsibility is key to
effective climate action.[^05chapter5_23] During our research, we have observed
that individual consumers do not act as rational agents without help
from material devices that enable calculation: they need apps, meters,
interfaces and other market tools to act as ‘rational actors’ in the
context of competitive retail markets. Moreover, it is often only
through co-ordinated activity – selling aggregated generation from
multiple small PV systems, co-ordinating temporal shifting of their
electricity use to periods of low demand or applying the output of a
collectively owned generator to their aggregated load – that they can
engage effectively with the market.

Accessing data requires careful consideration about the purpose and
access rights granted in research. Household-level electricity usage
data can yield rich and diverse insights for effective energy research
for public good and bad. Consider the identification of illicit
facilities and improved network planning, yet also opportunities for
well-resourced burglars to identify unattended dwellings, or for
targeted advertising campaigns based on identification of existing
appliances through their usage footprints. Highlighted in the rollout of
‘smart meters’ or Advanced Metering Infrastructure across Victoria,[^05chapter5_24]
similar challenges are also flagged by the CSIRO in its ongoing Energy
Use Data Model project,[^05chapter5_25] which seeks to collect an array of data
across Australia for research and consultancy purposes.[^05chapter5_26]

Data misuse, targeted marketing or malicious attacks on the energy
market participants requires vigilance and effectively resourced
regulators.[^05chapter5_27] As researchers, we are mindful of the trust we solicit
when we ask for data at a time when purposeful exploitation of personal
data is a commonplace business model. If we cannot engender trust, we
rightly risk losing access to appropriate data.

The rights and responsibilities of all energy data stakeholders need to
be rebalanced to harness the power of energy data in the interests of
energy users and society. Privacy is vital but should be considered in
this wider context. Policies mandating social and ethical
responsibilities integrated with public research and innovation,[^05chapter5_28]
such as those in the EU Horizon 2020, offer one platform to address the
challenge of maintaining trust. Researchers have a responsibility to
maintain security and confidentiality, through de-identification of
individual data in the context of ongoing dialogue and its potential
commercial uses. A suitable consent-for-purpose mechanism would support
sharing of anonymised data with other public-interest researchers and
groups and undermine commercial exploitation of publicly-funded or
personally-sourced data.

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Box 4: Making a Data Commons from Household Photovoltaic Solar Output** http://pvoutput.org
  
  PVOutput is a free online service for sharing and comparing distributed photovoltaic solar generation unit output data across time. It provides both manual and automatic data uploading facilities for households to contribute the outputs from their photovoltaic system.<br /><br />PVOutput began in 2010 as an open-access commons in response to the interest and enthusiasm of many households deploying PV to let others know of their system performance. It then, unintentionally but certainly fortuitously, came to fill the growing need for an aggregate measurement of the contribution of photovoltaic solar to the grid. The site has become a public resource that is used by a wide range of market participants, including those seeking to facilitate rule changes that recognise the value of distributed PV systems, and others seeking to improve network planning. Today there are over 1.7m households in Australia with photovoltaic solar and PVoutput.org has played a key role in helping researchers and other stakeholders understand the challenges and opportunities this presents.
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
*Box 4: Making a Data Commons from Household Photovoltaic Solar Output*

### Standards are sorely needed

Research currently requires a pragmatic approach to making sense of
data. Metadata is often incomplete or incorrect. Strings of numbers with
no indication of the units of measurement (e.g. kWh, kW or kVA) have
little value. Time stamps are particularly vexatious, as inconsistent
treatment of daylight-saving periods, time zones and even time period
‘ending’ or ‘starting’ can all lead to misleading analysis outcomes. The
detail on exactly what a data set contains must be documented (and kept
current) and have a clear standard across the industry.

The Australian Energy Market Operator has recently gone to great lengths
to establish a data communication standard at the utility scale,[^05chapter5_29]
whilst requirements for a new register of distributed energy resource
metadata is in the final stages of consultation.[^05chapter5_30]

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Box 5: The Green Button Initiative has empowered electricity consumers**
  
  *‘The Green Button initiative is an industry-led effort that responds to a 2012 White House call-to-action to provide utility customers with easy and secure access to their energy usage information in a consumer-friendly and computer-friendly format for electricity, natural gas, and water usage.’*[^05chapter5_31]<br /><br />Inspired by the success of the *Blue Button* in providing access to health records, *Green Button* was an initiative of the US Chief Technology Officer that was taken up by utilities, network operators, technology suppliers and integrators, policy makers and regulators. *Green Button* is a standardised API web service and a common data format for transmission of energy data.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
*Box 5: The Green Button Initiative has empowered electricity consumers*

Standardised reporting criteria and formats enable collective
knowledge-sharing.[^05chapter5_32] By standardising energy data, consumers,
researchers and industry will be able to build tools and perform
analysis upon a stable platform, eliminating a wide range of common
errors and miscalculations. As such, we recommend that, through
collaboration between research groups, a standardised energy time-series
data format be developed, with the following criteria as an initial
basis for discussion:

-   Human-readability (e.g. standardised labelling, sensible time
    series)
-   Cross-compatibility between common processing platforms (Excel,
    Matlab, Python, R)
-   Standard use of Unicode file formats for internationalisation
-   Development of open-source tools for standard conversions (e.g.,
    JSON -&gt; CSV) and translations (e.g. labels English -&gt; Chinese)
-   Standard labelling & protocols for handling missing data
-   Clear labelling of data types (e.g. Power, Energy, Real vs.
    Reactive)
-   Mandatory fields (e.g. period length, time)
-   Standardised time format (suggest addition of Unix and/or GMT
    timestamp for elimination of general ambiguity)
-   Standardisation of time-ending data (vs. time-starting data)
-   Standardisation of metadata, with common fields (e.g. Location and
    range, Country of origin, Postcode etc.)
-   Standardised procedure for de-identification and anonymisation of
    datasets
-   Standard approach for data quality assessment
-   Standard platform to validate the meta-data
-   Standardised data compression protocols for storage

It is also important to consider the current impact of inadequate data
standards on the emerging market for distributed energy resources. A
lack of clear data formats may represent a significant barrier to entry
for some markets. In the Australian National Electricity Market, for
example, metering data for billing is required to be collected and
distributed in a standardised format (NEM12), as specified in detail by
the Australian Energy Market Operator. This format is however
effectively non-human-readable and could be classified as a type of
low-level machine code. Interpretation of NEM12 data requires conversion
to a different format before it can be interpreted in any meaningful
way, yet there are no tools provided by the market operator to help the
public interpret these files. This means that energy data in the NEM12
format is inherently opaque for the consumer; further, it means that
developers of new energy systems (which may not have the expansive IT
infrastructure of their retail competitors) must invest heavily in
custom data processing software simply to be able to bill their
customers. Anecdotal evidence has suggested that these overheads can
cost solar developers significant sums in setup and metering costs, as
well as lost revenues from inaccurate file conversion (and hence
miscalculated bills).

From a market design perspective, if distributed energy resources are to
be integrated into operational decision-making in restructured
electricity markets, a stable, trusted and interrogable data format is
required so more organisations can observe or participate in the market.
Additionally, the emergence of real-time energy metering may require a
rethink of how energy is sent and received between participants. In
computing terms, these protocols are generally referred to as APIs
(application programming interfaces) - broadly, languages and protocols
that are used to send messages between smart meters, cloud
infrastructure, market participants and consumers.

Data retrieval services have historically been designed by a mixture of
hardware and software developers, as well as regulators and operators
(such as AEMO in the Australian context), using diverse languages and
designs, which may have different security, frequency and formatting
characteristics. This means that enforcement of security, reliability
and data quality is incredibly difficult across existing meters and
platforms. All is not lost however, as the rollout of smart metering
infrastructure is still in its infancy in many parts of Australia and
the rest of the world. We believe that a regulator-enforced, set of
clear standards for the transmission of energy data from energy meters
to cloud infrastructure would enable adequate security and clarity as
the proportion of internet-connected meters grows.

The impetus for such standards becomes clearer when we examine the
coming wave of controllable, dispatchable energy resources such as
batteries. Without a standardised language with which these devices can
communicate, control of a large proportion of the electricity network
may fall to a cloistered, privately controlled and relatively small
subset of stakeholders, namely the manufacturers of popular distributed
energy resource devices. It appears reasonable to ask that devices
connected to a national electricity network be required to allow
regulators or operators access to ensure stability of supply; such
access would require the development of a set of standardised formats
for these different stakeholders to share worthwhile data to enable new
community enterprises to flourish and wrest power from the incumbents.

### Recommendations: 

-   Maintain appropriate privacy in the context of existing information
    and power asymmetries with a view to opening up a more communal
    notion of personhood upon which trustworthy data sharing may occur.
-   Learn from other successful delegated authorities in other
    countries: make consumers aware of benefits of good governance. For
    example, in Nepal there are representative committees at community
    level that can make decisions on behalf of others.
-   Some communities of modellers be granted delegated authority to
    access fine-grain energy data. Good energy data requires an
    appropriate interface between energy users, regulators and power
    providers.

### We underscore:

-   The importance of creating a process for communities to access data
    and enable studies based on energy use data.
-   That good data is embedded in good governance. Community energy
    projects need to build their authority to make decisions.
-   The need for ongoing dialogue about how and where data is used.
    Analysis can discover new valuable insights that may require consent
    to be re-evaluated - one form isn’t enough!
-   Researchers have responsibility to act in the public interest when
    using public funds or public data and be mindful of data security
    and anonymity, and the importance of allowing broad access to their
    algorithms, data, assumptions and findings.

## Conclusions

The operators and regulators of an increasingly complex energy system
have a duty to the public interest, which requires them to be
transparent about their decision-making process. This means clearly
stating their assumptions, allowing access to their data, and opening up
their models for testing and scrutiny. Similarly, researchers and
academics, often working with public money, must champion open
modelling, share their data generously and communicate their findings
broadly to break open the struggle between neoliberal rationality on one
hand and individual privacy on the other.

Our recommendations may not seem radical. However, energy debates have
been shaped by a range of political constraints: the opacity of market
design decisions, slow speed of rule changes, an increasing political
disconnect between voter opinion and administrative decision-making in
electricity market design, and especially the polarised nature of policy
debates about the suitable role for Australian institutions in
addressing climate change mitigation obligations.

Political advocacy aimed at challenging these various constraints
remains a profound challenge. Traditional political advocacy focused on
building coalitions, writing letters, protesting and so forth remains
vital to reforming energy politics, but it has also proved entirely
insufficient. Political advocacy can be complemented with what Donald
MacKenzie has termed ‘technopolitics’: an attention to details of policy
designs that may be highly consequential to the efficacy or otherwise of
political interventions such as climate change policies.[^05chapter5_33]

Climate change debates demonstrate that simply sharing evidence is
insufficient to swaying political opinion. A growing body of Science and
Technology Studies literature shows, instead, that evidence-making is
situated in peculiar contexts according to the issues considered and
audience. Evidence is contextual,[^05chapter5_34] and this is consequential to how
distinctions between technology and politics are drawn, how and why
coalitions around energy policies succeed or fail to affect political
power structures. Our energy data manifesto should be read in this
context – a call for a new energy society.

## References

AEMC. ‘Final Rule Determination: National
Electricity Amendment (Customer access to information about their energy
consumption)’, 2014.

AEMC. ‘National Electricity Amendment (Register of distributed energy
resources) Rule’, 2018.

AEMO. Power System Data Communication Standard, 2018.

AEMO. ‘Integrated System Plan’, 2018.

AEMO. ‘Visibility of Distributed Energy Resources’, 2017.

Björnmalm, Mattias, Matthew Faria and Frank Caruso. ‘Increasing the
Impact of

Materials in and beyond Bio-Nano Science’ *Journal of the American
Chemical Society*

138.41 (2016): 13449-13456. DOI:10.1021/jacs.6b08673.

Callon, Michel and Fabian Muniesa. ‘Peripheral vision: Economic markets
as calculative collective devices’, *Organization studies* 26.8
(2005):1229-1250.

CSIRO. ‘Energy Use Data Model (EUDM)’, 2015,
https://research.csiro.au/distributed-systems-security/projects/energy-data-use-model/.

Green Button Alliance. ‘Green Button Data’, 2015,
http://www.greenbuttondata.org/.

International Energy Agency. ‘Digitization and Energy’, 2017
http://www.iea.org/publications/freepublications/publication/DigitalizationandEnergy3.pdf.


Islam, S. N., M. A. Mahmud and A.M.T. Oo. ‘Impact of optimal false data
injection attacks on local energy trading in a residential microgrid.’
*ICT Express*, 4.1 (2018): 30-34, DOI:
http://doi:10.1016/j.icte.2018.01.015.

Kuch, Declan and Bronwen Morgan. ‘Dissonant Justifications: an
organisational perspective of support for Australian community energy’,
*People Place and Policy* 9 (2015): 177-218.

Lew, Debra, Mark Asano, Jens Boemer, Colton Ching, Ulrich Focken,
Richard Hydzik, Mathias Lange and Amber Motley. ‘The Power of Small -
The Effects of Distributed Energy Resources on System Reliability’,
*IEEE Power & Energy Magazine.* 15 (2017): 50-60.

Lockstep Consulting. ‘Privacy Impact Assessment Report Advanced Metering
Infrastructure (AMI)’, Dept of Primary Industries, 2011.

MacGill, Iain, and Stephen Healy. ‘Is electricity industry reform the
right answer to the wrong question? Lessons from Australian
restructuring and climate policy.’, in Fereidoon P. Sioshansi (ed.),
*Evolution of Global Electricity Markets*, Cambridge MA: Academic Press,
2013, pp. 615-644.

MacGill, Iain, and Robert Smith. ‘Consumers or prosumers, customers or
competitors?-Some Australian perspectives on possible energy users of
the future.’ *Economics of Energy & Environmental Policy* 6.1 (2017).

MacKenzie, Donald. ‘Constructing Carbon Markets: Learning from
Experiments in the Technopolitics of Emissions Trading Schemes’, in A.
Lakoff (ed.), *Disaster and the Politics of Intervention*, New York:
Columbia University Press, 2010, pp. 130-149.

Owen, Richard, Phil Macnaghten and Jack Stilgoe. ‘Responsible research
and innovation: From science in society to science for society, with
society’. *Science and public policy*, 39.6 (2012): 751-760.

Passey, Rob, Navid Haghdadi, Anna Bruce and Iain MacGill. ‘Designing
more cost reflective electricity network tariffs with demand charges’,
*Energy Policy*, 109 (2017): 642-649.

Rhodes, T., K. Lancaster, M. Harris, M and C. Treloar. ‘Evidence-making
controversies: the case of hepatitis C treatment and the promise of
viral elimination.’ *Critical Public Health* (2018): 1-14.

Scottish and Southern Electricity Networks (SSEN). ‘SSEN and Open
Utility partner to trial revolutionary smart grid platform’, 2018,

http://news.ssen.co.uk/news/all-articles/2018/april/ssen-open-utility-smart-grid-platform/.

Shove, Elizabeth. ‘Beyond the ABC: climate change policy and theories of
social change’ *Environment and planning A*, 42.6 (2010): 1273-1285.

Simpson, G. ‘Network operators and the transition to decentralised
electricity: An Australian socio-technical case study.’ *Energy Policy*,
110 (2017): 422-433.

Stringer, Naomi, Anna Bruce and Iain MacGill. ‘Data driven exploration
of voltage conditions in the Low Voltage network for sites with
distributed solar PV’, paper presented at the *Asia Pacific Solar
Research Conference*, Melbourne, Australia, 2017.

Trundle, Catherine. ‘Biopolitical endpoints: Diagnosing a deserving
British nuclear test veteran.’ *Social Science & Medicine* 73.6 (2011):
882-888.

Wilkenfeld, George. ‘Cutting greenhouse emissions-what would we do if we
really meant it?’, *Australian Review of Public Affairs,* 2007,
http://www.australianreview.net/digest/2007/08/wilkenfeld.html.

Wilkenfeld, George and Peter Spearritt. ‘Electrifying Sydney’, Sydney:
EnergyAustralia*,* 2004.

[^05chapter5_1]: Of course, we understand this is not entirely true, and that toxic
    politics is a major barrier, but we adapt this quote from another
    famous manifesto to illustrate the difficulties being faced by
    proponents of sustainable energy in Australia.

[^05chapter5_2]: George Wilkenfeld, ‘Cutting greenhouse emissions-what would we do
    if we really meant it?’, *Australian Review of Public Affairs,*
    (2007)
    http://www.australianreview.net/digest/2007/08/wilkenfeld.html;
    George Wilkenfeld & Peter Spearritt, ‘Electrifying Sydney’, Sydney:
    EnergyAustralia*,* 2004.

[^05chapter5_3]: The Australian National Electricity Market uses detailed data
    regarding large-scale generation, namely five-minute market offers
    of all scheduled generators, their dispatch and market prices.

[^05chapter5_4]: This is of course not true as consumers would still only be
    responding to the products offered to them.

[^05chapter5_5]: Information regarding power quality relates to technical
    characteristics of power delivered such as voltage. Power quality
    can determine how well equipment and household appliances function,
    and in extreme cases, poor power quality can cause damage to
    appliances.

[^05chapter5_6]: Available on the Australian Energy Market Operator’s website:
    https://www.aemo.com.au/

[^05chapter5_7]: Iain MacGill and Stephen Healy, ‘Is electricity industry reform
    the right answer to the wrong question? Lessons from Australian
    restructuring and climate policy.’, in Fereidoon P. Sioshansi (ed.),
    *Evolution of Global Electricity Markets*, Cambridge MA: Academic
    Press, 2013, pp. 615-644.

[^05chapter5_8]: See Declan Kuch and Bronwen Morgan, ‘Dissonant Justifications: an
    organisational perspective of support for Australian community
    energy’, *People Place and Policy* 9 (2015): 177-218.

[^05chapter5_9]: See https://enovaenergy.com.au/about-us/\#structure for Enova’s
    corporate structure, which includes a holding company divided into a
    retailer which channels 50% of profits into its non-profit arm.
    Enova’s constitution specifies that most shareholders must reside
    locally to the Northern Rivers region of NSW.

[^05chapter5_10]: We note that there are ongoing efforts to make network
    information more widely available, for instance through the
    Australian Renewable Energy Mapping Infrastructure project.

[^05chapter5_11]: Scottish and Southern Electricity Networks (SSEN), ‘SSEN and Open
    Utility partner to trial revolutionary smart grid platform’, 2018,
    http://news.ssen.co.uk/news/all-articles/2018/april/ssen-open-utility-smart-grid-platform/

[^05chapter5_12]: AEMO, ‘Integrated System Plan’, 2018.

[^05chapter5_13]: AEMO, ‘Visibility of Distributed Energy Resources’, 2017.

[^05chapter5_14]: G. Simpson, ‘Network operators and the transition to
    decentralised electricity: An Australian socio-technical case
    study’, *Energy Policy* 110 (2017): 422-433.

[^05chapter5_15]: Naomi Stringer, Anna Bruce and Iain MacGill, ‘Data driven
    exploration of voltage conditions in the Low Voltage network for
    sites with distributed solar PV’, paper presented at the *Asia
    Pacific Solar Research Conference*, Melbourne, Australia, 2017.

[^05chapter5_16]: See also the ‘network opportunities map’ project by UTS ISF:
    https://www.uts.edu.au/research-and-teaching/our-research/institute-sustainable-futures/our-research/energy-and-climate-2

[^05chapter5_17]: AEMC, ‘Final Rule Determination: National Electricity Amendment
    (Customer access to information about their energy consumption)’,
    2014.

[^05chapter5_18]: See
    https://medium.com/@accountability/leadership-by-local-communities-in-nepal-paves-the-path-for-development-that-respects-rights-bdb906f43209

[^05chapter5_19]: Michel Callon and Fabian Muniesa, ‘Peripheral vision: Economic
    markets as calculative collective devices.’ *Organization studies*,
    26.8 (2005): 1229-1250.

[^05chapter5_20]: Rob Passey, Navid Haghdadi, Anna Bruce & Iain MacGill, ‘Designing
    more cost reflective electricity network tariffs with demand
    charges’, *Energy Policy* 109 (2017): 642-649.

[^05chapter5_21]: See https://twitter.com/podehaye/status/1030773658975981569

[^05chapter5_22]: Debra Lew, Mark Asano, Jens Boemer, Colton Ching, Ulrich Focken,
    Richard Hydzik, Mathias Lange and Amber Motley, ‘The Power of Small
    - The Effects of Distributed Energy Resources on System
    Reliability’, *IEEE Power & Energy Magazine,* 15 (2017): 50-60.

[^05chapter5_23]: Elizabeth Shove, ‘Beyond the ABC: climate change policy and
    theories of social change.’ *Environment and planning A*, 42.6
    (2010): 1273-1285.

[^05chapter5_24]: Lockstep Consulting, ‘Privacy Impact Assessment Report Advanced
    Metering Infrastructure (AMI)’, Dept of Primary Industries, 2011.

[^05chapter5_25]: CSIRO, ‘Energy Use Data Model (EUDM)’, 2015,
    https://research.csiro.au/distributed-systems-security/projects/energy-data-use-model/.

[^05chapter5_26]: CSIRO ‘partners with small and large companies, government and
    industry in Australia and around the world’
    https://www.csiro.au/en/Research/EF/Areas/Electricity-grids-and-systems/Economic-modelling/Energy-Use-Data-Model

[^05chapter5_27]: S.N. Islam, M. A. Mahmud and A.M.T. Oo, ‘Impact of optimal false
    data injection attacks on local energy trading in a residential
    microgrid.’ *ICT Express*, 4.1 (2018): 30-34, DOI:
    http://doi:10.1016/j.icte.2018.01.015

[^05chapter5_28]: Richard Owen, Phil Macnaghten and Jack Stilgoe, ‘Responsible
    research and innovation: From science in society to science for
    society, with society’, *Science and public policy*, 39.6 (2012):
    751-760.

[^05chapter5_29]: AEMO, ‘Visibility of Distributed Energy Resources’, 2017.

[^05chapter5_30]: AEMC, ‘National Electricity Amendment (Register of distributed
    energy resources) Rule’, 2018.

[^05chapter5_31]: Green Button Alliance. ‘Green Button Data’, 2015,
    http://www.greenbuttondata.org/.

[^05chapter5_32]: Matthias Björnmalm, Matthew Faria and Frank Caruso. ‘Increasing
    the Impact of Materials in and beyond Bio-Nano Science’, *Journal of
    the American Chemical Society* 138.41 (2016): 13449-13456,
    DOI:10.1021/jacs.6b08673.

[^05chapter5_33]: Donald MacKenzie, ‘Constructing Carbon Markets: Learning from
    Experiments in the Technopolitics of Emissions Trading Schemes’, in
    A. Lakoff (ed.), *Disaster and the Politics of Intervention*, New
    York: Columbia University Press, 2010, pp. 130-149.

[^05chapter5_34]: Catherine Trundle, ‘Biopolitical endpoints: Diagnosing a
    deserving British nuclear test veteran.’ *Social Science &
    Medicine* 73.6 (2011): 882-888.
