# What the groups said: synthesis of the first run

Nordic Centres of Excellence meeting, Sandbjerg, 23 November 2026. Twelve groups of four to six people from RITMO, Music in the Brain and MMBB answered the [case](README.md) in a shared slide deck. Each group's answers were coded by hand, and every number below is counted from that coding.

The short version: the groups agreed on more than they expected. Nobody moved Petra down because she worked with a chatbot, and nobody accepted "AI was used for language editing" as a disclosure. The disagreements were about the people at the edges (Mette, Rasmus, Pekka) and about whether a model can be credited, not about whether AI use should be disclosed.

## 1. Who are the authors, and in which order?

Petra is first in 12 of 12 lists (in Group 7 after "AI", see below), and Poul is last in 12 of 12. Sanna is on all 12 lists, Astrid and Erlend on 11. The most common list, given word for word by 2 groups, is Petra, Sanna, Erlend, Pekka, Astrid, Poul; 4 groups had exactly these six in some order.

| Person | Author | Of which on a condition | Acknowledgements | Not mentioned |
|---|---|---|---|---|
| Petra | 12 | 0 | 0 | 0 |
| Astrid | 11 | 0 | 0 | 1 |
| Poul | 12 | 0 | 0 | 0 |
| Erlend | 11 | 0 | 0 | 1 |
| Sanna | 12 | 0 | 0 | 0 |
| Pekka | 10 | 1 | 2 | 0 |
| Mette | 7 | 3 | 3 | 2 |
| Rasmus | 2 | 1 | 5 | 5 |

The single missing Astrid (Group 10) and Erlend (Group 3) look like oversights rather than positions.

The edges:

- Mette splits the room. Seven groups list her, three of them on a condition: if the drum model was built for this study (Group 6), if she reads and contributes to the manuscript (Group 11), or if she is interested (Group 10). Three put her in the acknowledgements.
- Pekka is on 10 lists, but Group 6 asked why he was involved at all if an agent drafted his section and he edited it lightly, and Groups 3 and 12 moved him to the acknowledgements.
- Rasmus goes to the acknowledgements, or is not mentioned, in most groups. Translation and summarising were treated as they would have been before AI: support, not authorship.
- One group (7) put "AI" first on the author list and let the author list carry the disclosure. It was the only group to do so; the question it raises is in section 7.

Petra's drifting idea and her chatbot-written draft did not change her position in any group. The groups treated the chatbot's part as something to disclose, not as something that takes authorship away from her.

## 2. What should the disclosure say, and who is responsible?

10 of 12 groups wrote a statement that lists the stages where AI was used, and 5 of 12 named or asked for the model and version. 4 of 12 added that the authors take full responsibility. Two groups moved the disclosure into the author list (Group 7) or into the contribution statement, per author and per model (Group 6: "Author X did the literature review using model A").

Responsibility: all authors, with the first author doing the writing (Groups 4, 6 and 11), the first and last authors (Group 9), or Petra disclosing and Poul setting the standard (Group 10).

## 3. Should the coding agent be credited in the codebase?

9 of 12 groups would credit the agent in the repository with model and version. One group (4) would not credit it but would disclose the tool and version; one asked for as much detail as possible (2); one proposed a credit system that flags AI use at each stage (10). The suggestions for how: the README and each script (3), the model as co-author of the commits it wrote (6), type, model, version and date in the code (8), and publishing the development chat logs (7).

## 4. Who is the performer on the recording?

Every group that answered named Mette, or, in Group 11, "the people involved", the drummer and the developer. 5 groups said Mette alone, 4 said Mette and the model together, and one counted the pilot musicians as performers too (Group 2). 7 of 12 named the pilot musicians, or the training data, as something to credit in the description of the model.

## 5. Were any of the uses a problem for the participants?

Three problems came up:

- Interview summaries in a chatbot: personal data sent to a model that may not be local or approved (7 groups).
- The drum model trained on the pilot recordings without the musicians' consent to that use (5 groups).
- Consent forms translated by a chatbot and not checked by a speaker of the language (5 groups).

One group saw no problem in the case as written (11), and one said it depends on what the consent form says about processing and storage (7).

## 6. Two years later

7 of 12 groups reached the follow-up case. Of these, 3 said the results can be reproduced, 3 said only if the code and pipeline were published, and 1 said no. The responsibility lies with the team, with the PI named by Groups 11 and 12 and Petra by Group 3. What should have been recorded: model, version, prompts and the repository history, or "everything". On the reviewer, 5 of 7 said to tell the editor; Group 12 added checking the journal's policy and whether the model trains on uploaded data.

## 7. Collective answers

One answer per question, built from where the groups agreed. The open points are where they did not.

1. Authors: Petra, Sanna, Erlend, Pekka, Astrid, Poul. Mette is an author if the drum model was built for this study and she takes part in the paper; otherwise the acknowledgements, with the pilot musicians. Rasmus in the acknowledgements. No model on the author list.
2. Disclosure: "Generative AI tools ([model, version, date]) were used to develop the research idea, write the analysis code, translate the consent forms, summarise the interviews, draft the methods section and draft the manuscript. All output was reviewed by the authors, who take full responsibility for the content." The first author writes it; all authors sign off; the PI sets the standard in the group.
3. Codebase: the agent is named, not credited as an author: model, version and date in the README and in the commits it wrote.
4. Recording: "Mette, with a drum model trained on recordings of the pilot concerts by [the pilot musicians]."
5. Participants: three things should have been done: consent that covers training a model, personal data only in approved or local models, and translations checked by a speaker of the language.
6. Two years later: reproducible only if code, data, model version and prompts were archived when the paper was published; the team, led by the PI, is responsible. Tell the editor about the reviewer.

Still open:

- Group 7 put the model on the author list. What would have to be true for that to be right?
- Is Pekka an author if an agent wrote his section and he edited it lightly? The groups were stricter with Pekka, whose own contribution was small, than with Petra, whose drafting was also done by a chatbot.
- Credit or disclose: is a model in a commit trailer a credit or a disclosure, and does the difference matter?

## 8. What the case shows

The case started from the premise that we are often stricter with machines than with people. The answers suggest the opposite in one respect: the groups kept the human author list much as it would have been without AI, and handled AI use as disclosure. Where they disagreed, it was about the humans at the edges, the musician and the assistant, whose positions were unclear before AI too. AI raised the questions about consent, data and reproducibility more than it raised the question of authorship.
