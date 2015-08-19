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
- Slides -- http://www.clothedinchrist.org/?attachment_id=241
- Audio -- http://www.clothedinchrist.org/?attachment_id=240

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
- <email redacted>
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

You don't need huge end-to-end solutions. Let everyone at each stage use the best tools.


## Can I Trust My Bible Software? Why Bible Searches May Not Find What You Expect
Harry Hahne

...

Machine-readable Biblical texts.

The Impact of Functional and Unusual Parsings
- Start with ambiguous data, end up with ambiguous data.
- Get to know your text. Read the introduction. Understand the oddities.

Capabilities of search software:

1. Default boolean operator varies between search engines
   - OR (Logos 2, Bibloi)
   - AND (Logos 3-5, BibleWorks, Gramcord)

2. Lemma or inflected form?
   - Logos morphological search: assumes lemma
   - Logos Bible search: assumes inflected form

3. Sensitivity to diacritical marks
   - Logos Bible and basic search: mercifully ignored
   - Logos search on a lemma: exact accents are required

4. Word order sensitivity
   - Gramcord: exact order
   - BibleWorks: must specify
   - Logos: not word order sensitive; can use BEFORE, AFTER.

...

Common Errors in Using the Software

1. Not aware of the features and quirks of the search software.
2. Inadequate understanding of the tagged biblical text.
3. Not understanding how to enter the search correctly.
4. Inadequate understanding of the grammatical construction.
5. Failure to search for all permutations of the construction.
6. Not manually eliminating false matches.

Tips for accurate searches in Bible software:

1. Start by searching a portion of the Bible that includes known examples of the desired construction.
2. Verify that your results include known examples of your construction.
3. Verify that your results are reasonable.
4. Construct a complex search one element at a time.
5. Save your search criteria periodically.
6. Be sure you have selected the correct Bible text.
7. Choose a Bible text to work w/ regularly.
8. Learn about tagging philosophy and assumptions of your Bible.
9.  Understand the limits
...
12. Search for all possible permutations of the construction
13. Manually eliminate false matches.
14. Practice, practice, practice.

Can you trust your Bible software? Yes and no. It's a tool. Get to know it. Become a craftsman.


## Bible Search Systems
Neil Rees
<email redacted>
Putting the fun back into fundamentalism.

Or, why most Bible search systems don't work very well.

English / local name
- German / deutsch
- Welsh / cymraeg
- irish / gaeilge
- Spanish / espanol
- Dutch / nederlands
- Hungarian / magyar
- Mongolian / Mohron (Cyrillic)

Know your localizations! Be sensitive to "foreigners"

### Common problems

#### Localization

Many Bible search systems have many foreign language translations, which are inaccessible to the speakers of those languages.

If you want those who don't speak English to access their Bibles, you shouldn't have to require them to speak English, in order to search their own language.

Localize your interface!


#### Word forms pattern matching

Jesus Wept. Search for weep?

You shouldn't have to know what the verse says, in order to find out what the verse says.

- brother / brethren
- cow / kine / cattle
- pig / swine
- weep / wept
- two / twain
- man / men
- honour / honorable
- go / went


#### Context

What do you call the third hand on a watch? The second hand!

- Have you built a pattern-matching algorithm, or a word searching system?
- Is it built from a programmer's perspective, or a user's perspective?
- Pattern patching kind of works okay most of the time in English and Spanish.
- But it doesn't work on those languages w/ complex morphology. That is, MOST OF THEM.

The problem with dictionaries are that they are sorted alphabetically. You don't always know what letter a word starts with.

You shouldn't have to know how a word is spelt, to look it up. You shouldn't have to know all the forms of a word to look up a word in all its forms.

Test on languages other than English and Spanish. Try Welsh and Hungarian.

#### Melchisedec

- Names spelt differently in OT and NT.
- Alternate names. Jacob/Israel, Saul/Paul, Peter/Cephas, Azariah/Abednego.
 You shouldn't have to know all the variants of a name to know its references.

#### Names and things

Mark the man, Mark the mark on your forehead. Lot, to cast lots, Lot the nephew of Abram.

#### Which language did Jesus speak?

Hebrew, Aramaic, Greek, maybe another.

- Sometimes, it is the question which is wrong.
- It is easier to clarify the question than the answer.
- Filter via a disambiguated data set, e.g. concordance or names index

BFBS has a disambiguated data set!

#### Love

How helpful is it to know all 924 references to love in the Bible?

The correct answer is not always a helpful answer.

Bible searches usually sort results canonically, but what about sorting them by usefulness?

Filter a short concordance or lectionary that has already selected the key verses.

#### The Prodigal Son / The Woman at the Well

You shouldn't have to know what the words are, in order to search the Bible to get to know what the words are.

Search on sub-titles and study Bible notes and return Scripture.

#### Gideon Bible: topical indices

Many things you may want to search aren't directly in the scripture. They're concepts.

The word may not be in the text, but you may want to know what the text says.

#### Metric versions

"the extra mile" -> "the extra kilometer"
"forgive us our trespasses" -- which version is that?

You shouldn't have to know which translation the word is in, in order to find out which translation it is in.

### What are you searching?

- All the occurrences of a cluster of characters
- What are the most useful references to a word?
- Where is the verse that says?
- Where can I find out about
- What version has this...

### Principles

1. Asking a question should not require you to know the answer.
2. Sometimes it's the question which is wrong.
3. The correct answer is not always the right answer.
4. Sorting in order is not always the most helpful order to sort in.

### Solutions

1. Always localize. Don't use Ethlogue to find out the name. Check w/ the locals.
2. Use lemmata data. Derive it from concordances. Test on foreign languages.
3. Melchisedec. Filter by a names index. 4600 proper nouns, disambiguated, cross-referenced, and defined. Get it from the Bible societies. Email Neil about this.
4. mark/Mark. Filter by a semantically defined concordance. Use a names index to cross-reference alternate forms and spellings.
5. love. Filter the results by a short concordance or lectionary. http://bibles.org has relevance voting feature, so users can vote on search results.
6. Prodigal Son. Don't have time or resources to tag. Search the study notes, the pericope.
7. kilometer. Search across translations w/in a language. Don't require the selection of a specific translation first.

### Is this just a theory?

Already doing it: http://bibles.org

It's a fully localisable widget that you can put on your website.

It's free.

### Q&A

You have to identify who your audience is: Logos users, or normal people? Don't load the ordinary people down with clutter. Don't oversimplify for the power users. These are necessarily different search products.

When disambiguating or searching across translations, don't return the same result more than once.

When offering different languages, you have to localize the interface.


## Enabling the Production of High-Quality English Glosses of Every Word in the Hebrew Bible
Drayton Benner

Hebrew ... Print Interlinear Enabler

Software tool to enable a human glosser to quickly produce glosses for every word in the Hebrew.

- Enable user to produce literal, contextual glosses friendly to the translation for each word
- Enable the user to gloss quickly, consistently, at high level
- Not required: UI, customizability, etc.

Exposes existing Hebrew glosses from other sources, along with contextual translation in target text. Also shows how the word has been glossed previously. Drills down to comprehensive lexical, contextual, syntactic data for each word.

User can add a gloss, add a textual crit. note.

Awesome hack: no spell-check, just copy and paste into Word, fix by hand.

Demo: "Enabler" is an apt description. Thom goes to my church, and he's been talking about using this tool. I didn't realize how cool it was.

I don't know Hebrew, but I'm enjoying hearing it spoken by Drayton. Beautiful language, written and spoken.

### Algorithmic Glossing: Sources of Data

- WordNet
- CMU Pronunciation Dictionary
- Lots of lists (e.g. irregular plural nouns in English)

Proper Nouns

- Case 1: User has consistently glossed this proper noun in the past. Easy: Follow the prior example.
- Case 2: User has not consistently glossed.
  - Construct a set of possible glosses:translation, Lexham, user as sources.
  - Assign points to each possibility. Score based on sources, pick the highest score.

Common nouns. More challenging than proper nouns.

- Translation, Lexham gloss may be too long. Shorten them.
- Lexical form may not be enough.
  - Needs to be made plural

Verbs

- The hardest. Need to be divided up not only by root but also stem. Reduces the amount of usable data.
- Subjects and pronominal suffixes must be represented.
- Picking an English tense
  - Consistency helps.
  - Perfects, imperfects, waw-consecutive perfects, waw-consecutive imperfects much more challenging.
  -

### Results

Quality

- Enabler enabled the glosser to produce higher-quality glosses.
- Human glosser has changed over 500 glosses from what he had previously done.

Speed

With enabler, the glosser has been able to work 58% faster.

### Things to do differenetly next time

- Faster load time for a chapter.
- Use Stanford NLP Tools.
- More use of Hebrew context in algorithmic glosser.

### Conclusions

An enjoyable project.
- Hebrew and Aramaic
- Complex algorithms to solve difficult tasks.
- Produces a product that enables people to access the OT.


## Fidelity -vs- Readability: A Quantitative Evaluation of English translations

Translation philosophy is a continuum.

Traditionally, these have been evaluated:

- Qualitative
- Intuitive
- Subjective
- Impressionistic
- Manual
- Anecdotal

### Goals

- Verify our intuitive judgement by quantitative analysis
- Exhaustive examination of every verse
- Identify linguistic features of fidelity and readability
- Explore the relationship between fidelity and readability
- Present the evaluation results in a two-dimensional perspective

Question: Can a Bible translation be both faithful and readable?

### Objectivity

- Automatic process
- No human intervention
- Automatic parsing
- Automatic alignment
- Automatic statistical analysis

Englist Translations Evaluated: CEV, ESV, GNT, HCSB, KJV, NASB, NCV, NET, NIV, NKJV, NLT, NRSV, TNIV

### Data preparation

- Syntactic analysis of the original texts (Hebrew and Greek parse trees)
- Syntactic Analysis of all English translations (English parse trees)
- Alignment of each translation to the original texts

### Fidelity Measures

1. Transfer rate of syntactic relations
2. Consistency rate of word choices

### Syntactic Relations

- All the head-modifier pairs in the parse tree
- Labeled -vs- unlabeled relationships
- Unilateral -vs- bilateral relations

### Transfer rate of syntactic relations

Of all the syntactic relations found in the original, how many of them are found in the translation.
- Syntactic relations are basic units of meaning
- Higher transfer rate indicates higher fidelity

1. ESV
2. NASB
3. NKJV
4. HCSB
5. NRSV
6. KJV
7. NIV
8. TNIV
9. NET
10. NCV
11. NLT
12. GNT
13. CEV

Literal translations have the highest transfer rate, dynamic is lower.

Interesting that the consistency rates are significantly higher Hebrew->English than Greek->English.

### Consistency rate of word choices

How consistent are the correspondence between original words and translation words?

- Each sense of the original word should ideally be translated by the same English word
- Each English word should ideally be used to translate the same original word

On average, how many different English words are used to translate on original word sense?

The higher the value, the higher the consistency.

Random thought: Is this the answer to the Franken-Bible? Statistics cut both ways.

When calculating the consistency rate, words limited to Nouns, Verbs, Adjectives.

1. KJV
2. NKJV
3. NASB
4. ESV
5. NRSV
6. NET
7. HCSB
8. TNIV
9. NIV
10. NLT
11. GNT
12. CEV
13. NCV

Literal translations more consistent, dynamic less consistent.  Interesting that the KJV is more consistent than the NASB.

### Fidelity Ranking

1. ESV
2. NASB
3. NKJV
4. KJV
5. HCSB
6. NRSV
7. NIV
8. NET
9. TNIV
10. NLT
11. NCV
12. GNT
13. CEV

Observation:

The ranking is very similar to what is in the Zondervan Translation Comparison Chart, with small variations.

### Readability Measures

1. Rate of common vocabulary words
2. Syntactic fluency rate

Compare the language of a translation with that of a representative sample of contemporary English.

### Sample of Contemporary English

The Brown Corpus

- 500 samples of English-language text, tagged syntactically
- Roughly one million words
- Multi-genre

### Rate of common vocabulary words

Words that occur at least twice in the Brown corpus. Of all the words in the translation, excluding proper names and numbers, how many are in the common vocabulary?

The higher the rate, the more readable the translation.

Question: Why didn't he use Flesch-Kincaid?

1. NCV
2. GNT
3. CEV
4. NLT
5. NET
6. TNIV
7. HCSB
8. NIV
9. NRSV
10. ESV
11. NASB
12. NKJV
13. KJV


### Syntactic Fluency Rate

Assumption: a translation is easier to read if its language is closer to the everyday language the reader has been exposed to.

Method: measure the degree of similarity between two language models.

Syntactic Pattern: Sequence of words and category labels.

Mix tags and actual words.
- Use actual words for closed set items
- Use tags for open class items
- Focusing on abstraction

Extract Bigrams up through 8-grams.

1. HCSB
2. NLT
3. CEV
4. GNT
5. NIV
6. TNIV
7. NET
8. NRSV
9. ESV
...

### Readability Ranking

1. NLT
2. HCSB
3. CEV
4. TEV
5. NIV
6. TNIV
7. NET
8. NCV
9. ...

Observation: Fidelity and Readability seem to go against each other, but high fidelity does not always imply low readability, or vice versa.


## On the precipice of a "Bible crisis" of biblical proportions

How will the church close the gap between our need for meaningful Bible engagement and our personal Bible practices?

"If we do our jobs right in the next 5 years, we'll increase our customer base 500-1000%"

- Quick overview of US Bible engagement, confronting brutal realities. Wouldn't it be great if Bible users could all grow into super users of the Bible?
- How is the church thinking of addressing the challenge?
- Some key things Bible technologists can do.

The Number 3: The average # of bibles in Christ-followers' homes.

If we engaged in scripture 3 times a week, it would change our lives.

Bible engagement: Bible reading, knowledge, literacy, and influence are all at an all-time low.

- 37% of Christians read the Bible at least once a week
- 70% of all Americans read the bible once per month, or not at all.
- 14% report an involvement beyond reading, e.g. study.
- 85% of all Christians "reading the Bible is very important"
- 77% of all Americans: "reading the Bible makes me feel closer to God"
- 66% "the Bible contains answers to all life's questions"

Why the disconnect between the high value we place on Scripture and our actual behaviors?

The largest cultural shift ever: Monochronism -> Polychronism. The Age of Distraction. Multitasking.

Chronic busyness -> high expectations for the 5Cs (Confidence, Courage, Commitment, Conflict, and Community).

Polychronism radically changing behavior, and it's at the heart of the "Bible crisis".

There are actually indexes (PBI, PMCI) to measure polychronic behavior.

Technology gives more people more access to more info, resulting in polychrons feeling perpetually overwhelmed:
- Flee: People joining monasteries, entering seminaries, at highest rate in generations
- Filter: relying on trust networks to filter the flood.
- Flex: Gap between commitments/values and our behaviors/actions widens.

How will the Church take action to close the gap between commitments/values and behaviors/actions?

"Mobilizing the Church in a Scripture Engagement Movement is a vision to launch the largest, most cohesive and organized Bible-focused movement ever undertaken in the history of our nation." -- Paper: "Mobilizing the Church in a Scripture Engagement Movement", ABS, 2011

Take the Bible off the shelf.

### Social Movements

"Social movements nurture and sustain large communities of followers ... recruit more supporters and mobilize more advocates ... transform public attitudes ..."

When Mandela was released from prison, one of the first people he met was Troy Duster, Institute for the Study of Social Change. UC Berkeley.

"Why does our federal government invest heavily in research in social movements?"

Duster: Social movements are one of the most powerful ways to alter the course of nations and the course of history.

Tahrir Square movement scaled fastest in history.

Building an organization -> Building a movement or institution. P2P network -vs- broadcast network. Command and control -> Empower and engage. Don't seek out a few torch bearers, seek out a bunch of match-carriers. Rules/Procedures -> Unified, shared vision, shared ownership, co-creation. Tell and sell -> Build consensus, working collaboratively. Conservative, preservative -> Innovative. Transactions -> Relationships. Connecting leaders -> Connecting participants. Good of the one -> Good of the many.

Movements CAN'T just happen digitally.

### What can Bible technologists do to help close the gap?

1. Join the movement. Become an insider.
2. Optimize your applications to help foster community.

New research from Duke University:

- Americans more solitary than any other time in history. "Perilously isolated."
- Just over 25% of Americans have "no relationships"
- More than 50% say they have no relationships outside of spouse and children
- Leading culprits: longer work hours.
- Americans are among the loniliest people in the world.
- For Christ followers, being around people is not the same as genuine community.
- Chronic isolation: the less in community we are in, the less engaged we will be in scripture.

Most powerful form of belonging:
- Religiously rooted social networks.
- RRSNs have a powerful effect in predicting engagement.
- Build "community" into your technology, designed to connect people to each other, and to spread the word.

5Cs:
- Choice
- Convenience
- Control
- Clarity
- Community

We can map the decline in the influence of the church directly to the mismatch between what we say and what we do.

For you technologists wanting to add community to your tech, you absolutely MUST read http://feverbee.com


## Seven Ways to Build Your Bible App Community
- Matt Mayer
- <email redacted>
- @matthewmayer
- http://www.reigndesign.com/

"Communities already exist. Instead, think about how you can help that community do what it wants to do." -- Mark Zuckerberg

### 1. Ask for Feedback

This drives product and community.

One button at the bottom of app changed everything: "Suggest a new category." Immediate response.

"I can't emphasise enough how important it is to answer your own customer support emails." -- Matt Mullenweg

Received feedback on search, added translations.

But then you drown in feedback emails! Process/tools required! - for example http://www.uservoice.com

### 2. Internationalization

Natural choice, since they were based in Shanghai. :)

Never forget: You are WEIRD. White, Educated, Industrialized, Rich, Democratic.

They prioritized localization strategy by installed device stats.

- iPhone top markets: US, UK, AU
- Android top markets: US, Nigeria, Phillipines. Top 3 English-speaking Christian populations.

### 3. Inspire daily habits.

Only one app at a time on mobile. Constant context switches. 2-5min sessions, or worse. Median session time is 26 seconds.

Added a banner and chime that always went off at 10am, not customizable. This got a very good response.

### 4. Use social media smartly.

Difficult to grow a new community around an app. Leverage existing social networks.

Which ones? It depends. Understand your audience.

Facebook? Twitter? Pinterest? Tumblr? Sina Weibo? Email? SMS?

Present different info customized to network. Facebook looks different than Twitter, than Pinterest, than Email, than SMS.

Ask open-ended questions: "Which book of the Bible is your favorite? Why?"

### 5. Use data. Use all the data.

Likely 1% of users will comment, suggest, create. 9% share, tag. 90% lurkers. Can we push people up the pyramid? Infer what they want from data: Favoriting, Searching expose lots of data.

### 6. Build a brand.

Starting with one app, it's hard to think of building a brand.

Bible Promises app -> Biblegram (Instagram w/ a Biblical twist).
http://www.youtube.com/watch?v=bl_e-om3uxo

- Visual consistency.
- Cross-promotion
- Naming

### 7. Build a community.

Tara Hunt, Fostering Online Communities.
http://www.slideshare.net/missrogue/fostering-online-communities-by-tara-hunt

1. Lightweight social processes (sharing)
2. Collaborative information structures (Flickr)
3. High end collaboration (Wikipedia, Stackoverflow)

Word of mouth is still the best way to spread a social media application.


## Strong's Numbers and NLP
Matthew Jonas, Olive Tree

Started learning programming at Olive Tree with Perl. Moved to Python + NLTK.

Any repetitive task that can be done by a human can be done by a script. Cost/benefit analysis required!

Think through the steps of the task, and write a function for each step. Add heuristic logic for each decision.

Question: How would I tag a Strong's Bible?

What constitutes Strong's tagging? Is it universal? Maybe not. There are better systems, but not as popular.

1:1 correspondence between Greek/English? No. Strong's system assumes direct correspondence though.

If Strong's numebrs tagged to a KJV, one set of problems. Used as a generic system, another set of problems.

### Strong's Numbering System

Alphabetical list of all Greek and Hebrew words, but didn't work directly from the original texts, so he got weird results. Numbered them sequentially, but with gaps. No usability problem, just weird.

For each concordance entry, gave context and index number. Index in the back. Great system for a lay person. Just have to know how to count.

### Specific Concerns

Differences between Textus Receptus and NA27. Some words in NA27 have no correspondence in Textus Receptus, so no Strong's Number. Many proprietary systems have sprung up to fill in the blanks.

What about mapping Strong's Numbers directly to the Greek text?

Problems with articles:

"The translators of the KJV under the influence of the Vulgate, handle the Greek article loosely and inaccurately." A.T. Robertson, Greek Grammar

Problems with pronouns:

Variations on pronouns sometimes have different strong's numbers.

Problems with Demonstrative:

Missing demonstrative forms that have no number. Often solved by going back to the root form.

Problems with the "be" verb:

Peculiarities in the KJV translation resulted in under/over-tagging.

Etc. etc. etc.

### Actually doing it

Can use extant Strong's numbers for a KJV verse to guide tagging in another translation.

2/3rds of cases map directly. N-gram approach helps a lot in other cases. Still, an error every 7 or 8 verses. Not exactly an automated process. Could achieve higher accuracy with further refinement, but Strong's Number system breaks down under stress.

Works best with literal translations that are close to the KJV in structure and style. He was working with RSV and NRSV.

The machine-tagging problem approaches AI-level requirements.

Other systems (BDAG, etc.) have advantages, but it's inescapable that languages are messy, squishy, slippery.
