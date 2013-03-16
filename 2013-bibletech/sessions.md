# BibleTech 2013

## A Semantic Referent Database
- Its Development, Challenges and Usefulness
- Scott Fleischman & Josh Westbury

- Scope: People, places, things. Linking text to concepts. Names, pronouns, etc. across entire Hebrew and Greek texts.
- Ex. Ruth 1: the land (Judah), a man (Elimelech), etc.
- Collated from Hebrew & Greek, not a translation. Inserted translation text does not link to referents.
- Enables intertextual results: "the man" in Josh 6:24 -> 1 Kings 16:34.
- Feature: Explorer view. Get summary of all referents for a passage.
- Feature: Bible facts. How is this referent referred to throughout the Bible?

### Methodology

- Annotate people, places, things across entire Hebrew & Greek texts.
- No abstract concepts: love, etc. even when personified (e.g. Wisdom).
- BUT: Stone water jars at Wedding at Cana in John 2:6.

### Heuristic Rules

No one's ever done this before. Developed rules and strategies.

**Generic -vs- Specific.**: "servants" in John 2:5 refers to "Servants at Wedding feast at Cana". John 13:16, "servant" and "master" -> all servants, all masters.

**Avoid the long tail.** Omit entries occurring < 5 times. Mark 5, Jairus and girl mentioned several times, get entities. Girl's mother mentioned once, tagged with generic "mother" entity. "messengers" in various places get generic "messengers" entity. Guiding rule: what provides the most value to the reader?

**Avoid interpretation.** Daniel 8:23: "king of bold face". Commonly thought to be Antiochus IV Epiphanies. Hand-curated to entity "King of Bold Face" with Antiochus in the description.

**Strictly Biblical.** Mentioned in the Bible explicitly. Previous example, Antiochus not mentioned in Bible by name, so no entity. daniel 11:3: "mighty king"--Alexander the Great? Again, hand-curated to "Mighty King of Greece" with Alexander in the descrption.

### Challenges

#### People groups:

- General: Israelites
- Divided into time periods, archored to people or events:
  - Israelites (the Exodus)
  - ... (the Conquest)
  - ... (Judges)

 Numbers 26:64 caused them to reconsider their approach, dividing Exodus and Conquest Israelites. Time periods were hand-curated. Groups have overlap (e.g. Caleb, Joshua).

#### People or place?

Jerusalem: geographic location, or the people of Jerusalem?
- Jeremiah 5:1: "streets of Jerusalem", a place. "her"...? Refers to city still, grammatically. v.2 "They" switches to people referent.

Personification:
- Isaiah 60:1: "Arise"->city of Jerusalem.

### Further Application

Search capabilities:
 - More than proper names.

- Combines syntax and referent data.

Searching for Jesus: word search only, 256 results. With referent database, 1,821 results.

Clause search! Example search: subject:Satan object:Jesus place:Jerusalem. -> Matt 4:5, Luke 4:9, temptation narrative. Nuance!

### Questions

Ambiguities? Which Zechariah? Lots of hairy issues, esp. minor prophets. Apply heuristic rules, check scholorly consensus. Go with majority opinion. No majority, unimportant, no tag. No majority, important, tag with both options.

Process? Manual tagging? How to scale? All annotation done by hand. "Several people" working on it, including "scholars-in-residence" of Biblical Studies. Also programmers helping.

29 cities? UX/UI question, really. Experimented with visual notification of reference presence, but dropped it as too much visual noise.
Joshua/Hiel example, anachronistic? Goal was to provide value to reader.

Where does the referent data description come from? Hand-curated.

Is it done? Yes, but still room for ongoing improvement.

But it's interpretive! Well, yeah, sorta. We set boundaries of interpretation.

Ruth 1:1 the land/Judah: evokes more than the territory, it's a concept more important than that. Does this approach reduce too much? These are interlinked to other data, which may help evoke the concept of "the land".


## From Paper to Pixels
- The effects of Technology on the Bible.
- Josh Westbury/Scott Fleischman
- @AdamGraber -- http://thesecondeclectic.blogspot.com
- @KeithWilliams -- http://clothedinchrist.org

Print bibles editorial team.

How we present the bible impacts how readers experience and understand the text.

- What is the Bible?
- Traits of print and digital Bibles.
- Picture of an ideal Bible reader.
- Best practices for Bible publishers.

### What is the Bible?

- The Bible miniseries
- Tim Tebow
- Westboro Baptist
- Brick Bible
- Isaiah scroll, Dead Sea Scrolls
- Pew bible
- Binary representation of John 3:16

"What hath God wrought?" -- first telegraph message, quoting Balaam replying to Balak, "look how God is blessing these people." Ripped from context, seems ominous.

**How do we remain faithful to scripture in representing it?**

What does this have to do w/ how we read the Bible?
 - **Presentation of text.** Gives readers cues, how to engage with the text. (Concrete ex. later.)
 - **Relationship to additional content.** Clarify and expound.
 - **Integrity of Scripture.** Bible is not segmented.
 - **Context is king.** PRESENTATION IS CONTEXT. THE MEDIUM IS THE MESSAGE. :)

Layers of context provide meaning. "The wages of sin is death", when isolated, misleads. When included with full sentence the true message is revealed, "but the gift of God is eternal life through Christ Jesus our Lord."

### Ideal bible reader

- How should readers apprach the scriptures?
- What habits should Bible readers be building?
- What postures and practices should we encourage?

We often think of helping readers by educating. But we want to help readers cultivate good **habits**. Reading segments, or broader context? Habits.

#### Postures to encourage

- Submitted
  - Prayerful
  - Receptive
- Immersed
- Curious
- Informed and educated

#### Practices

- Consistency. Return to the text over and over.
- Perseverance, continuing through difficulties.
- Read widely. Don't get stuck in just a few places.
- Read repetitively. Engage the entire counsel of God.
- Community. Read in community. Don't be isolated.

### Contexts: Print and Digital

#### Common impulses

- Economy
- Portability
- Accessibility
- Distributability
- Personalization

Print and Digital allow these to happen. The Church is on the leading edge. Bible publishers are the leading edge of print.

#### Print Technology

- Codex format. 2nd century tech, still going strong.
- Navigation. Book/chapter/verse system(s). Standardized in 16th century. Helps communities navigate together.
- Page limitations affect textual presentation.
- Visual/spatial separation of Bible from other content.

#### Digital Technology

- Text as data.
- Multiplicity of formats.
- Infinitely reproducible.
- Hardware affects interaction with text. (Desktop -vs- iPad -vs- Phone)

#### Divergences

Digital, doing more that we've already been doing. But there are distinct differences!

- Print / Digital
- Standardized / Customizable
- Wholeness / Selectivity (search!)
- Sequentiality / Hypertextuality
- Selective Indexing (concordances) / Searchable
- Bounded / Edgeless
- Contextualized / Networked
- Static / Dynamic and remixable

#### Communicating Value

We represent the value of Scripture in different ways.

- Print / Digital
- Bindings / Software, hardware
- Paper quality / --
- Proportions / --
- Added Content / Added Content
- Source of Content / Source of Content
- Static Remixes / Navigation, Interface
- Design / Design

### Effects of Technology

Most focus is on effects on the reader: enabling the reader, encouraging the posture of Curiosity, asking questions prompted by hyperlinks.

However, these also have radical effects on the Bible itself and the reading experience. Chapter and verse numbers a perfect example. The chapter numbers draw the eye and segment the text. These may however weaken the meaning and argument of the text.

#### Best Practices

 - Relentlessly preserve contextual relationships. (N: What about highlighting the verse, instead of isolating it?)
 - Easy navigation or communal reading and study.
 - Provide access to meaningful additional content.
 - Clearly proritize Scripture over all other content.
 - Identify biases of your publishing environment and counterbalance them in some way.

#### Ideas

 - Make sharing large chunks the default. Link to the whole chapter? Chapter w/ verse highlighted?
 - Keep verses out of isolation. Show with context.
 - Retain a sense of proportionality through creative navigational features. Google Earth sensibility. Like the nav mode in Sublime text.
 - Distraction-free reading mode.

#### Fixes

 - Verse of the Day:
   - Always display in context.
   - Choose unexpected texts.
   - Open-ended questions instead of verses.
 - Search bias
   - Suggest related texts or topics from curated content
   - Deemphasize popularity
 - Treat chapter and verse numbers as invisible metadata.


### Further reading

- http://thesecondeclectic.blogspot.com/2013/03/recommended-reading-about-digital-books.html
- http://www.clothedinchrist.org/


## Searching the Bible On The Go
Dave Dunkin, Logos

Top search terms.

- love
- faith
- grace
- prayer
- marriage
- peace

Anomalous search terms peak around world events.

Terms:

acceptance: accepting a search result. 34% of searches have at least one result accepted.
refinement: re-search, clarifying the search terms. 41% change the query.
25% of searches are dead ends, neither accepted nor refined.

CHART JUNK.

Query types:
49% single term
28% multi-term
8% References
8% Cication
4% Phrase
2% Reference maybe?
2% Complex

Search types: Term, topic, bible ref, phrase, pericope, library, citation, advanced

**Google's approach: Search first, ask questions later. Match topics at the top, then proceed to the rest of the search.**

DO THIS.


## Automatically Learning Topical Content
- Sean Boisen
- #BibleTech #BibleData

http://www.semanticbible.com/other/talks/2013/BibleTech/LCV.html

### Outline

- The Logos Controlled Vocabulary (LCV) (http://www.semanticbible.com/other/talks/2010/BibleTech-LCV/BibleTech-LCV.html)
- The LCV Corpus
- Learning from the corpus:
  - Topic importance
  - References
  - Key terms
  - Topic relationships

Semantic Organization at Logos: organizing the world's Biblical information

- Bible Knowledgebase: people, places, things, events
- Logos Controlled Vocabulary
- Referent Analysis
- Bible Sense Lexicon
- Timeline
- Preaching Themes

### Why Topical Analysis

- A primary way to explore the text (topical search)
- Facilitates discovery
- Enables and rewards a large library (radically deconstructing the notion of a book as a container)

### Logos Controlled Vocabulary (LCV)

- controlled vocabulary, baleling content
- supports topic search/exploration, connection
- mitigase problems of ambiguity
- provides semantic organization of concepts
- organizes content from bible dictionaries, etc.

Manually created, maintained.

Book > Article > Term > Reference: Terms-Weights-Concepts mapping

- 34m words, 140k articles, annotated w/ concepts. All hand-crafted!!!
- ~50 "independent" sources
- Varying styles and purposes
- 13,000 concepts.
  - 56% have <= 5 sources
  - 95% have <= 20 sources
  - 140 concepts w/ 30 or more sources

### Learning Concept to Reference Associations

- Content about Biblical subjects typically includes references
- Estimate the association between a concept and references by aggregating counts across all content (voting scheme)
- Provide a ranked list of references to explore for a concept
- These estimates should get *better* as more content as added

### Learning Reference -> Concept Associations

- Reversing this data enables going from a passage to associated concepts.
- Not just frequency of association, but distinctiveness.
- Nebai and Neh 10:19 are both fairly unique content indicators.
- Determining identity can be tricky
  - Same word? (stemming or morphological analysis)
  - Same reference? Overlapping...
- Word repetition is important evidence for topical relevance; references not so much

### Learning Term -> Concept Associations

- What terms occur most frequently in a concept? Aquila, Corinth, Paul, Apollos, Rome.
- Other high-frequency terms not in this article: husband, church, Christian, couple, Ephesus
- Suggests new concepts that are related. Term -> concept data means no dead ends.
- Article context can increase precision (i.e. ambiguous terms like "bear")

### Concept Relatiionships through Reference Vectors

- Compare reference vectors to find concepts w/ similar references
- Example: ointment
  - Top ten ointment references have 133 instances out of 672 (20%)
  - Find other concepts that have Mk 14:3 as a reference
  - Score them against the top ten ointment references
 - 92 other concepts have Mk 14:3 as a reference

### Conclusions

- Developed a large corpus of concept-aligned content
- Demonstrated ways to learn novel associations between terms, references and concepts
- Future directions:
  - Building systems to generate conceptual associations
  - Collocation analysis (meaningful phrases)
  - Concept annotation of running text


## “Exploring NoSQL and the Bible”
Keller Davis
http://bibletech.kellerdavis.com/

Big Data


## Franken-Bible (Algorithmic translation)
- Stephen Smith
- ***REMOVED***
- www.adaptivebible.com

Accelerating pace of new English translations

Pressures on Bible Translations:
- Linguistic
- Academic
- Theological / doctrinal
- Social (loss of shared biblical knowledge and language)
- Moral
- Institutional (less trust?)
- Market (monetization!)
- Technological

Clayton Christensen: The Innovator's Dilemma

English Bible Translation is ripe for disruption.

### Book Publishing

Two Book Publishing Disruptions in past 20 years
1. Distribution (Amazon)
2. Content (ebooks)

Main Publisher Functions
1. Gatekeeping (quality control, imprimatur)
2. Marketing
3. Distribution

Ebooks allow:
1. Wider variety of content
2. Proliferation of often-terrible self-published books

### Bible Translations

Bible Translation Disruptions

1. Distribution
2. Content (Franken-Bibles, partially algorithmic, personalized translations)

Colossians 1:2 (ESV)
    To the saints the holy | God's [holy] people
    and faithful
    brothers | brothers and sisters
    in Christ.

What happens if the Word of God becomes the Wiki of God?

Potential Trust Axes

- Horizontal social network
- Teachers or elders in your church
- Your pastor
- Your denomination
- A megachurch pastor or celebrity
- Parachurch org/nfp
- Corporation

Trust becomes networked, fragmented. Translation becomes an indicator of group identity. Own, self-published magisterium.

How this could happen:
1. Open an existing translation
2. Use technology to produce a Franken-Bible

### Franken-Bible Premise

Given the abundance of English translations, can we use an algorithm to map the possibility space of valid English renderings for each verse?

www.adaptivebible.com

Phases:
1. Alignment of English translations
2. Generation of new translation

#### Alignment

1. Collect translation text for a verse.
2. Normalize the text.
3. Tokenize and linguisticaly analyze. Identify lemmas and syntactic relationships. Stanford Core NLP
4. Identify WordNet similarities. NLTK
5. Run off-the-shelf translation aligner. Berkeley Aligner.
6. Consolidate data.
7. Apply machine learning. Python Sidekick(?) Learn
8. ...

Factors Used in (Machine Learning) Aligning Translations:

1. Relative position in verse
2. Sentence
3. Similarity of grammatical context
4. Part-of-speech similarity
5. Aligner output (forward and reverse) (Jesus and He, He and Jesus)
6. Aligner output across translations
7. Dependency overlap (direct word relationships, subject/verb/object/directobject)
8. WordNet similarity
9. Major-word phrases
10. Major-word dependency matches

#### Generation Process

1. Consolidate alignments into phrases.
2. Cluster translations.
   Jesus - say - be - clean
3. Apply actual keywords.
4. Fill in gaps between keywords.
5. Restore punctuation.
6. Reduce possibility space using bigrams.
   Jesus healed the man.
   Jesus the man healed.
7. Render output.

#### Testing Validity

- Support from two independent translation streams.
- Able to render 96% of verses in the New Testament.

#### Limitations

- No guarantee of grammatical or semantic correctness
- Bigrams can lead to repetition ("Jesus said, 'be healed,' Jesus said.")
- No handling transitions between verses
- No formatting

By-product: Probabilistic Strongs-to-Wordnet mapping
By-product: Translation Similarity

Franken-Bibles are coming.
They'll only get more sophisticated over time.


## Emdros
http://emdros.org/

### What is Emdros?

A text database engine for annotated text
A Full Text Search engine
A powerful query engine for linguistics data (original languages research queries)
A digital library backend, capable of doing most of the heavy database lifting involved in creating a digital library

Pluggable backends: Postgres, MySQL, SQLite, proprietary BPT
Can store db in one file with no config.

### Primary advantages:

- Speed (scales from iPod to server)
- Versatility: focus on textual data, assemble data as documents for display
- Ease of use. Think about and work w/ text in a natural way that fits the worldview of text.
- Thin API, powerful query language


### Emdros philosophy

- Based on pure math. Pure, simple, easy-to-understand math.
- Math permeates from bottom to top.
- Software stack not based on complex interrelationships, but simple, clean, thin interfaces between layers.
- Simple API. Powerful query language.
- Consistent API.


## XML-based Workflows
- Sean A. Harrison, Tyndale @saharrison
- http://seanharrison.org/xmlworkflow
- He's available to train in this process

### Traditional Workflow

- Stretches the editors very thin, as the editor becomes a bottleneck, esp. when dealing with many authors/freelancers.
- Handoff to typesetter is more "toss it over the wall".
  - Proofreading corrections via paper, PDF (or InCopy, if you're lucky)
  - Typeset file is the de facto archival form of the content.
- Ebooks/apps/web are outsourced to the lowest bidder.
  - How are corrections made?
  - Who is responsible for content quality?
  - Esp. with Study Bibles, constant, ongoing corrections are necessary

Tyndale has completely automated Bible ebook production.

### XML Archive Workflow

Centered around one archival XML repository.

Inputs / Validation
- Authoring
- Develpomental eiting
- Early reader feedback

Interfaces / Curation (XML repo)
- Intake
- Editing
- Validation
- Review

Outputs / Transformation
- Layout
- Proofreading
- Printing
- Distribution

Requirements:
- Version control is a necessity. NLT Study Bible kept all the Word docs in Subversion! No fear. Apparently, Tyndale's (nontechnical) editors work directly w/ version control via TortoiseSVN.
- Validation on commit, or reject with an error message.
- Filesystem access via working copy or WebDAV.
- NLT executive editor (Mark Taylor), very non-technical user, used WebDAV w/ auto-versioning to read/edit every article in NLTSB.

Inputs:
- Word
- Google Drive
- Wordpress
- Blogger

Outputs:
- Indesign
- Epub
- iBooks
- Kindle

#### XML Demonstration

Appears that each article in the NLTSB has its own XML file. Much easier to track changes!

- Open question: How does Word get transformed to XML?
- Do Tyndale editors work directly in XML? YES. The whole Bible department is doing this.
- Sean works directly to support editors when they have trouble.

Each commit gets validated by the server, and is rejected if the schema doesn't validate.

They use RelaxNG Compact schema, and python/lxml to validate.

Goals: creating XML that works well in InDesign, can be transformed to apps, web.

Very important to have pre-commit hooks to validate or reject commits.

XSLT 1 very limited. He does some additional transformations using Python scripts.


#### InDesign Output

Circular Workflow: XML -> InCopy Markup Language (ICML) -> InDesign -> Proofreading -> Corrections -> XML

Important to know who's "got the controls". Are corrections happening in XML or InDesign at a given time?

Typesetter must be careful when editing, as InDesign ICML codes can be deleted but should not be.

ICML is the only way. Indesign's XML import features are poorly designed and do not support important use cases.

#### Web Output

Real-time, transformed directly from canonical repo.

### Amplitude python library

http://code.google.com/p/amplitude

"A simple, light, fast and powerful application tool chain and framework for Python."

Includes a lot of his XML tools for validation, pre-commit hooks, etc.

Whoah, he's driving Word, InDesign, Photoshop, etc. from Python scripts using win32com. Magic.

### Book production

Different editor, but similar process. "Use a workflow that makes sense." All Tyndale products are being done in a process similar to this!!!

All the bible editors use this process. Some fiction editors do their editing in a wiki. Most of the book editors still use the Word -> InDesign, then XML processing happens in content composition department.


### Editorial Culture

DON'T try and get your editors to stop using Word. Let them use Word. Word outputs XML (docx). Train them to use structured styles. Do the XML behind the scenes.

Divide between developmental editors (Word) and production/copy editors (->XML).
