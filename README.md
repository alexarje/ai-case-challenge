# AI Case Challenge: who did what, when a machine was on the team

A group exercise on authorship, credit, disclosure and responsibility when generative AI is part of a research project. First run at the Nordic Centres of Excellence meeting "Music between Mind and Machine" (RITMO, Music in the Brain and the Centre of Excellence in Music, Mind, Body and Brain), Sandbjerg, 23 November 2026, led by Alexander Refsum Jensenius.

It builds on the [coauthorship exercise](https://www.arj.no/2023/06/02/coauthorship-exercise/) and its [arts version](https://www.arj.no/2026/06/03/coauthorship-exercise-arts/). We are often stricter with machines than with people: research assistants, supervisees and language editors have helped for years without always being named. The case asks whether AI tools should be treated differently, and why.

## How to run it

1. Why this case (5 minutes).
2. Groups of five or six, mixed across centres and career stages; each group reads the case and picks a note-taker (30 minutes).
3. The follow-up case, read aloud (10 minutes in the same groups).
4. Plenary: each group gives its author list and its disclosure statement in one minute, then the debrief prompts (15 minutes).

## Follow-up: Human–Computer Improv

After the discussion, a 30-minute improvisation on phones turns the same questions into music: see [Human–Computer Improv](improv.md).

## The case

A three-centre project studies how groove is felt in the body and the brain during live concerts. The team first records two pilot concerts in the lab, then collects the main data at a public concert.

- Professor Poul secures the funding and leads the project.
- Associate Professor Astrid co-develops the theoretical framework and the preregistration with Poul.
- PhD fellow Petra comes up with the core idea for the first paper on a walk. She sketches it in half a page and discusses it with a chatbot over several days. The idea that ends up in the paper differs a lot from her sketch, and she is no longer sure how much of it is hers.
- Engineer Erlend builds the pipeline that synchronises EEG, motion capture and audio. A coding agent writes most of the code from his specifications. He reviews the code and keeps the history in the project repository.
- Research assistant Rasmus uses a chatbot to translate the consent forms into three languages and to summarise the post-concert interviews.
- Musician Mette trains a drum model on recordings from the project's pilot concerts and performs with it at the public concert where the main data are collected.
- Statistician Sanna does the statistical analysis: she runs the mixed-effects models with Erlend's code and checks the results against a subset of hand-coded analyses.
- Postdoc Pekka lets an agent draft the methods section from the repository history and the lab notes, and edits it lightly.
- Petra writes the first full draft of the paper by giving a chatbot her notes, Sanna's results and Pekka's methods section, and revises what comes back over several rounds. Poul and Astrid comment on the draft but write none of it.
- The paper's disclosure statement, written at the last minute, says only "AI was used for language editing."

The project produces three outputs:

1. A journal article
2. An open dataset and codebase
3. The concert itself, released as a recording

### Questions

1. Who should be listed as authors on the article, and in which order? Do Petra's drifting idea and her chatbot-written draft change her position?
2. What should the disclosure statement say, and who is responsible for it being correct?
3. Should the coding agent be credited in the codebase, and if so, how? Does it matter which model and which version it was?
4. Who is the performer on the concert recording, and how should the drum model be described?
5. Were any of these uses a problem for the participants (the pilot recordings used to train the drum model, the translated consent forms, the summarised interviews)?

## Follow-up case: the model has changed

Two years later, a reviewer of a follow-up paper asks the team to rerun the analysis. The commercial model behind the coding agent has been replaced, and the new one produces slightly different code. Petra has defended her thesis; Pekka has moved to another centre. In the same round, it turns out that one of the reviewers uploaded the manuscript to a chatbot to write the review.

### Questions

1. Can the results still be reproduced, and whose responsibility is that?
2. What should have been recorded at the time (model, version, prompts, the repository history)?
3. What should the team, and the journal, do about the reviewer?

## Debrief

- Did your group treat the agents' contributions differently from those of research assistants or language editors? Why?
- Where do you draw the line between a tool and a contributor?
- What should a supervisor have asked Petra, and when?
- Would full transparency (versioning, timestamps and a unique identifier for every contributor, human or machine) have made the decisions easier?
- Do different research environments have different norms here, and should they?

## Resources

- [Vancouver guidelines (ICMJE): defining the role of authors and contributors](https://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html#two)
- [CRediT Contributor Roles Taxonomy](https://credit.niso.org/)
- [NESH's draft guideline on responsible use of generative AI in research](https://www.forskningsetikk.no/om-oss/komiteer-og-utvalg/nesh/hum-sam/horing-ansvarlig-bruk-av-generativ-ki/)
- [Danish Code of Conduct for Research Integrity (2026), which covers the use of AI](https://ufsn.dk/english/publications/2026/januar/danish-code-of-conduct-for-research-integrity/)
- [The Danish Agency for Higher Education and Science's overview of international guidelines on AI in research](https://ufsn.dk/english/research-and-innovation/framework-for-research-and-innovation/integrity-in-research/international-guidelines-on-the-use-of-artificial-intelligence-ai-in-research/)
- [TENK's recommendation on artificial intelligence in research (Finland, 2026)](https://tenk.fi/en/news/tenk-publishes-new-national-recommendation-ai-research)

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Use and adapt the case freely, with a reference to this page.
