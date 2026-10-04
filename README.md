# when-information-must-survive
When Information Must Survive the Interface
# When Information Must Survive the Interface

We spend an enormous amount of time discussing how information should look.

A page needs a clean layout. A photograph should be sharp. A search result has to attract a click. A historical reconstruction should be visually convincing. These things matter, but I have gradually become more interested in another question: what remains when the interface through which we first encountered the information disappears?

I write about very different subjects as [Alexander Khmelnytsky at NAnews](https://news.nikk.co.il/en/author/alexander-khmelnitsky/), from Israeli society and Jewish history to technology and the changing architecture of the web. Two stories that seemed completely unrelated at first made me think about the same technical problem from opposite directions.

One was about making a modern web page understandable to search engines and AI systems. The other was about documenting synagogue paintings in buildings that may physically disappear.

On [this GitHub profile](https://github.com/netkonsaltingu-gif), where text naturally lives beside code, versions and structured files, placing these two stories together feels less strange than it might anywhere else.

## We used to design pages for a person holding a mouse

For a long time, the basic model of the web was easy to imagine. A person typed a query into a search engine, received a page of links, clicked one and visited a website.

The website had to load quickly, be readable and contain the answer. Search optimization was largely about helping the search engine understand which page should appear for which query.

That model has not disappeared, but another layer has been added. A growing number of users now ask an AI system a complete question and expect an answer without necessarily visiting ten websites first.

When I examined [how search changes when AI systems become part of the answer layer](https://news.nikk.co.il/en/search-is-not-the-same/), the most useful conclusion for me was not another acronym. SEO, AEO, GEO and similar terms may help professionals discuss different tasks, but the deeper change is simpler.

A web page is no longer read only by a human visitor.

It is also interpreted by machines trying to determine what the page actually means.

## Machines do not see a page the way we do

A person can understand an imperfect page surprisingly well.

We see a large headline and recognize that it is important even if the markup is poor. We can guess that a date near the top belongs to the article. We understand that the name below the title is probably the author.

We notice context.

A machine needs stronger signals.

Headings, metadata, dates, authorship, links, structured data and consistent terminology all help turn a visually understandable page into information that can be interpreted outside the original layout.

This distinction becomes more important as content is increasingly quoted, summarized, indexed and recombined by systems that may never display the original page at all.

The design can disappear.

The structure has to survive.

## This is where I began thinking about old synagogue walls

The connection appeared while I was working on a completely different story.

In Bukovina, historical synagogue paintings survive in buildings that have endured war, neglect, changes of use, weather and decades in which Jewish cultural heritage was often treated as marginal or simply forgotten.

The project I described in [“Painted Prayers,” where researchers are digitally documenting endangered synagogue art](https://news.nikk.co.il/en/not-a-foreign-story-in/), uses methods that belong as much to engineering and data work as to traditional art history.

Researchers and technical teams photograph the paintings, use laser scanning, record dimensions and build three-dimensional models. In the case of the synagogue in Novoselytsia, a digital twin makes it possible to preserve the geometry and location of elements even if the physical structure continues to deteriorate.

A wall and a webpage are obviously not equivalent.

But the underlying problem suddenly looked familiar.

## The original container cannot be trusted to live forever

Every format has a lifespan.

A building decays.

A hard drive fails.

A CMS is abandoned.

A domain expires.

A proprietary file format loses software support.

A social platform changes its rules or disappears.

Even a perfectly maintained website can be redesigned so completely that the original relationship between its components is lost.

This does not mean that physical buildings and original websites are unimportant. Quite the opposite: the original object contains context that a copy cannot fully reproduce.

But if the only surviving form of information is inseparable from one fragile container, then losing the container means losing the information too.

## Preservation begins by separating information from presentation

This principle is familiar in software.

We separate data from the interface because the interface will change. We store configuration outside the application logic because tomorrow's version may need the same information in another form.

We use documented formats so that another tool can read the data later. Version control exists because replacing a file is not the same as understanding how it changed.

Cultural preservation increasingly works in a similar way.

A digital scan does not replace a synagogue. A 3D model does not reproduce the experience of standing beneath a painted ceiling, hearing a prayer or knowing the community that once filled the room.

What it can preserve is measurable information that otherwise may vanish with the wall.

Dimensions.

Geometry.

Color.

Location.

Relationship between fragments.

High-resolution visual evidence.

Those elements can later be interpreted again through tools that do not yet exist.

## A good archive does not assume today's software will win

This sounds obvious until we look at how much information is stored in formats that depend completely on one product or platform.

The Library of Congress approaches digital preservation with a very practical principle in its [Recommended Formats Statement](https://www.loc.gov/preservation/resources/rfs/): the technical characteristics of a format influence the chances that content will remain accessible in the future.

Openly documented formats, metadata, clear character encoding and the absence of unnecessary access restrictions all matter because preservation is not simply about keeping the same sequence of bytes somewhere.

Future systems need to know how to interpret those bytes.

That is the part we often forget.

Copying is not the same as preserving.

## The web has its own version of a ruined building

We usually notice digital decay less dramatically because there is no collapsed roof.

A page simply disappears.

An old link returns 404.

A JavaScript application stops loading because one dependency no longer exists.

Images were stored on another service that has since shut down.

The article technically survives in a database, but its author field was lost during migration. Or the text survives while the captions explaining the photographs do not.

From the outside, nothing spectacular happened.

A small piece of context simply ceased to exist.

Repeat that process a few million times and a surprising amount of recent history becomes difficult to reconstruct.

## Git is interesting because it assumes change instead of fearing it

This is one reason GitHub is an unusually appropriate place to think about preservation.

Git does not promise that a project will remain unchanged. It assumes the opposite.

Files will be edited.

Mistakes will happen.

Structures will be reorganized.

Different people may work on the same material.

The valuable part is that change can leave a trace.

That principle is useful far beyond software development. An article, dataset, transcription or research note also has versions. Corrections matter. Sources change. New evidence appears.

A text with history is more useful than a text pretending it appeared in its final form from nowhere.

## Journalism has traditionally hidden much of its version history

Newspapers corrected errors long before the web existed, but digital publishing created an interesting paradox.

Changing an online article is technically effortless. The old version may disappear the moment the editor presses Update.

That is convenient, but it can also erase useful information about how our understanding developed.

A factual correction should not leave a false statement online merely for historical purity. But there is value in saying that something was corrected, updated or expanded.

The reader learns not only what we know now, but that knowledge itself had a history.

For journalism, transparency about change is not a weakness.

It is metadata.

## AI makes provenance more important

The more information is summarized outside its original page, the more important provenance becomes.

A sentence may travel from an article into a search index, from the index into a model, and from the model into an answer presented to someone who never sees the original context.

At every step there is a risk of losing something.

Who said it?

When?

Was it a confirmed fact or an author's interpretation?

Was the article later updated?

What was the primary source?

A beautifully designed page cannot answer these questions once its content has been detached from the design.

Clear authorship, dates, source links and structure can.

## This is where technical cleanliness becomes an editorial value

People often treat structured markup as an SEO trick.

Sometimes it is used that way, of course. Publishers want better search visibility, rich results and more traffic.

But structure has another purpose.

It reduces ambiguity.

If the machine can clearly identify the title, author, publication date, language and source hierarchy, the content has a better chance of remaining understandable when it leaves the environment for which it was originally designed.

The same logic applies to a digital model of a historical building.

A beautiful 3D rendering is not enough. Without measurements, documentation, metadata and information about how the model was produced, future researchers inherit a picture rather than evidence.

## Screenshots are useful and dangerous

This is another similarity between websites and heritage documentation.

A screenshot preserves appearance very well.

It may also preserve almost nothing underneath.

You cannot reliably recover the semantic structure of a complex website from an image. You cannot know from a screenshot which element was a heading, which text was metadata, what URLs the links pointed to or what data was generated dynamically.

A photograph of a synagogue wall has the same limitation.

It is invaluable, but it cannot automatically tell a future architect the exact dimensions of the room, the three-dimensional position of the painting or how the wall surface bends.

That is why multiple representations matter.

Photograph.

Scan.

Model.

Description.

Measurements.

Source files.

Each preserves a different property.

## Redundancy is not necessarily waste

In everyday digital work, duplicate files feel like clutter.

In preservation, carefully managed redundancy is protection.

One copy is vulnerable.

One format is vulnerable.

One institution is vulnerable.

One domain is vulnerable.

This does not mean creating random duplicates without knowing which version is authoritative. Preservation needs checksums, versioning, metadata and a method for determining what changed.

The goal is not “many copies.”

The goal is recoverability.

## The Israeli context makes this especially tangible to me

I usually write from Israel, where physical preservation and digital continuity are not abstract concerns.

Historical sites exist beside rapidly changing cities. Family histories cross languages and continents. Archives contain documents created under different governments and in different alphabets.

At the same time, a modern multilingual publication may exist in Hebrew, Russian, Ukrainian, English and French, each with slightly different contextual explanations.

That makes one lesson difficult to ignore: **Israel news** is not preserved merely by keeping an article online.

The relationships around the article matter too.

Which language is this version?

Which article is its counterpart?

Who wrote it?

What was the source?

When was it updated?

Without those relationships, we retain text but lose part of its meaning.

## A digital twin is not immortality

There is a danger in becoming too enthusiastic about technology.

Scanning an endangered synagogue does not save the building.

A 3D model does not preserve temperature, smell, acoustics, material aging or the social life that once existed inside the walls.

Likewise, putting an article into a repository does not guarantee that anyone will read it in fifty years. File formats can survive while context disappears.

Technology creates another chance to preserve information.

It does not abolish loss.

That distinction matters because otherwise digitization becomes a convenient excuse for allowing physical heritage to deteriorate.

“We scanned it” cannot mean “therefore the original no longer matters.”

## The best digital preservation creates options for people we will never meet

This may be the part I find most compelling.

When researchers scan a building today, they cannot know what software a restoration team might use thirty years from now.

When we publish structured text, we cannot know how future search systems will retrieve it.

When developers document an API, they do not know which unexpected application will depend on it later.

Good preservation does not try to predict the exact future interface.

It preserves enough underlying information that future people can build their own interface.

That is a much more modest ambition than immortality.

It is also much more realistic.

## Human-readable and machine-readable should not be enemies

There was a period in web publishing when optimization often meant writing for algorithms at the expense of people.

The result was terrible text.

Keywords repeated mechanically.

Articles stretched to absurd lengths.

Headings designed for search queries rather than readers.

AI creates a risk of repeating the same mistake in a new form. If every page is written as though its primary reader were a machine, the web will become structurally impeccable and unbearable to read.

The better goal is compatibility.

Write clearly for a person.

Structure clearly enough for a machine.

The two objectives usually support each other when the work is done well.

## The synagogue project offers the same lesson

The technological part of “Painted Prayers” is valuable because it does not stand alone.

There are historians.

Architects.

Artists.

Students.

Archivists.

Researchers of Jewish culture.

Digital specialists.

A 3D model enters an exhibition beside historical photographs, reconstructed paintings and explanations of the communities that created them.

Technology works because it remains attached to interpretation.

Without that human layer, we would have very accurate geometry of a building and very little understanding of why the building mattered.

## Data without context survives badly

This is true even when the file remains perfectly intact.

Imagine finding a folder fifty years from now containing thousands of high-resolution images named:

`IMG_001.jpg`

`IMG_002.jpg`

`IMG_003.jpg`

The files survived.

The archive did not.

Without information about the location, date, photographer, subject and relationship between the images, the future researcher must reconstruct context that could have been recorded easily at the beginning.

Metadata looks boring because its value is delayed.

We appreciate it most when the person who could have explained everything is no longer available.

## The same applies to journalism

A headline without a date can mislead.

A quotation without a speaker is nearly useless.

A translated article without a link to its source version loses provenance.

An image without a caption becomes vulnerable to reuse in a completely different context.

Digital publishing gives us extraordinary distribution, but distribution is not preservation.

Sometimes they even work against each other: the easier something is to copy, the easier it becomes to separate it from the information that explained what it originally was.

## I no longer think of optimization as merely getting found

That was one of the changes in my own thinking after placing these two stories together.

Good optimization is also about remaining interpretable.

A page with clear structure can be understood by search engines today, but it is also easier to migrate tomorrow.

A documented dataset can feed a current application, but it is also more likely to remain useful after the application is gone.

A carefully built digital model helps an exhibition today, but its underlying data may become evidence for a restoration project later.

The best structure serves more than one moment.

## Perhaps this is what “future-proof” should actually mean

The phrase is usually marketing nonsense.

Nothing is truly future-proof.

Programming languages become unfashionable. Standards are replaced. Storage media fail. Companies disappear. Institutions change priorities.

We cannot eliminate those risks.

What we can do is make information less dependent on one interface, one platform, one vendor and one person's memory.

Use documented formats.

Keep source files.

Record metadata.

Maintain versions.

Preserve provenance.

Make exports possible.

These are not glamorous habits.

They are the digital equivalent of writing the name on the back of an old photograph.

## The wall and the webpage will both change

One will weather physically.

The other will be redesigned, migrated, indexed, summarized or perhaps eventually abandoned.

What matters is whether something useful can still be reconstructed afterward.

That is the connection I did not expect to find between an article about AI search and another about endangered synagogue paintings.

Both eventually ask the same question:

**What part of this information belongs to the interface, and what part must survive without it?**

For developers, archivists, journalists and historians, I suspect that question will become more important rather than less.

Because almost everything we create today will eventually be opened by a tool we did not design, on a system we did not choose, by a person we will never meet.

Our job is not to control that future.

It is to leave them enough structure to understand what we meant.
