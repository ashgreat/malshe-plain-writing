---
name: malshe-plain-writing
description: >-
  Writes and edits prose in Ashwin Malshe's own style, learned from his
  published marketing papers and current manuscripts, with the plain-writing
  rules as a second layer. Use when drafting or revising his journal
  manuscripts (abstract, introduction, theory, hypotheses, methods, results,
  discussion, web appendix), responses to reviewers, practitioner articles,
  reports, summaries, emails, READMEs, slides, commit messages, or PR
  descriptions. Use when the user asks to write in his style or voice, or to
  simplify, tighten, reword, or clean up writing. Use when the user invokes
  /malshe-plain-writing deslopify or asks to deslopify a response. Do not
  apply to code, only to the words around it.
license: MIT
metadata:
  version: "1.0.0"
---

# Malshe plain writing

The skill has two sources. The first source is the author's own writing: two
first-author papers in Journal of Marketing (JM 2015) and Journal of Marketing
Research (JMR 2020), a current working manuscript, five coauthored journal
articles, and two Harvard Business Review articles. The second source is the
plain-writing skill, a set of 25 rules for plain and literal prose.

The author's style is the primary source, and plain writing is the secondary
source. Part 1 holds the rules of the author's style. Part 2 holds all 25
plain-writing rules and says how each one applies to his manuscripts. Part 3
is a lookup table for the places where the two sources disagree.

## How to apply the skill

1. **Decide which register the text belongs to.**
   - Manuscript register: journal articles, working papers, web appendices,
     conference abstracts, grant text, and responses to reviewers.
   - Practitioner register: articles for managers, executive summaries, and
     posts about research for a business audience.
   - Working register: chat replies, emails, reports, READMEs, slides,
     documentation, commit messages, and PR descriptions.

2. **Apply the rules that govern the register.**
   - Manuscript register: Part 1 governs. Part 2 applies wherever Part 1 is
     silent, in the form that the "In manuscripts" notes give.
   - Practitioner register: section H of Part 1 governs, then Part 2.
   - Working register: Part 2 governs in full. From Part 1, keep rules D1
     and F1 to F3.

3. **Read the reference file that fits the task before you write.**
   - `references/manuscript-playbook.md`: read it before you draft or revise
     any section of a manuscript. It gives the moves and sentence patterns for
     each section, from the title to the limitations.
   - `references/reporting-and-phrases.md`: read it before you write results,
     methods, citations, or numbers. It gives the formats for statistics,
     numbers, citations, cross-references, and punctuation, and a phrase bank.
   - `references/plain-writing-original.md`: the plain-writing skill as
     published. Part 2 repeats its rules, so you rarely need the file.

4. **Follow the order of authority.** The user's instruction for the task
   comes first. The style guide of the target journal comes second, and it
   decides citation format, heading format, the person of the abstract, and
   spelling. The rules of the skill come third.

5. **Do not invent content.** Do not make up a citation, a number, a result,
   a quotation, or a sample fact. When a sentence needs a fact that you do not
   have, write a placeholder in square brackets, e.g., [citation] or [number of
   firms], and list the placeholders at the end of your reply.

6. **When you edit his text, keep what already follows the rules.** Keep his
   meaning, his numbers, his citations, and his hedges. Change a sentence only
   when it breaks a rule, and do not rewrite a sentence to show a different
   way of saying the same thing.

7. **Check the text against Part 5 before you return it.**

## Part 1. The author's style (primary)

Examples are quoted from his published papers and carry a source tag.
Statistics describe his two first-author papers and his current manuscript.

### A. Voice and stance

A1. **Write in the first person plural and the active voice.** Use "we" for
what the authors argue, do, and find, and "our" for the study, the sample, and
the results. He uses "we" 10 to 15 times per 1,000 words. The method section
has the most, and the theory section has the fewest. Do not write "I". Write
"the authors" only in an abstract for a journal that wants the third person.
Refer to the work as "our study", "our research", or "this research", and not
as "this paper".
Example: "We argue that leverage affects customer satisfaction through two
mediating observable expenditures: R&D and advertising." (JM 2015)

A2. **Do not use contractions in a manuscript.** None of his papers has one.

A3. **Match the strength of the verb to the evidence.** State a cited finding
and your own estimate without a hedge. Hedge a mechanism, a prediction, an
explanation of a surprising result, and advice. Use "may" for how actors may
react, "can" for what a factor is able to do, "should" for a predicted relation
or for advice, "likely" for a probable outcome, and "could" for future
research. He uses "may" about three to four times per 1,000 words. Use one
hedge per claim, and do not stack two, as in "may potentially".
Examples: "Higher debt can also change the firm's incentives to honor implicit
contracts (Maksimovic and Titman 1991)." (JM 2015) "Short sellers may
effectively utilize customer satisfaction and dissatisfaction in their
investing decisions (Diamond and Verrecchia 1987)." (JMR 2020)

A4. **Keep evaluation rare, and give the reason at once.** When you call a
finding important, the same sentence or the next one must give the reason or
the number. Do not write "very", "highly", "extremely", "clearly", "novel",
"interestingly", or "notably". The words "important", "critical", "key", and
"crucial" may appear a few times in a paper, most often in the introduction.
Example: "The finding that leverage moderates the customer satisfaction–firm
value link is important. Previous research has found a wide variation in this
link across industries (Anderson, Fornell, and Mazvancheryl 2004)." (JM 2015)

A5. **Use associational words for estimates from observational data, and
causal words for theory.** In hypotheses, results, and robustness checks,
write "is positively associated with" and "the association between". In the
framing of the paper, in the mechanism, and in the discussion, the verbs
"affects", "reduces", "leads to", and the noun "effect" are fine. Describe
identification as reducing a concern, with "to address", "to alleviate", or
"to account for". Do not claim a causal estimate that the design cannot
support.

A6. **Say plainly when a result is unexpected, unsupported, or limited.** He
uses "unexpected", "counterintuitive", "puzzling", and "contrary to our
conjecture". Offer one possible explanation, mark it as possible, and say what
stops the paper from testing it.
Example: "A potential explanation for this puzzling result is that
high-sales-growth firms might have achieved the sales growth by offering price
promotions and shrinking the profit margins." (JM 2015)

A7. **Explain with literal, concrete material.** Use a worked example with
round numbers, a named firm, or a named industry. Do not explain with an
analogy.

A8. **Position the paper against prior work by coverage, not by fault.** Say
what earlier studies examined, used, or assumed, and then what the present
study does. Credit the exception by name. Do not write that earlier authors
ignored, overlooked, or failed to see something.
Example: "Luo, Homburg, and Wieseke (2010) is one exception, and they show
that the dispersion in financial analysts' recommendations partially mediates
the association of customer satisfaction and firm financial outcomes." (JMR
2020)

A9. **Choose the tense by the kind of statement.** Use the present tense for
a general claim, for what one study finds, for your own argument, and for your
results. Use the present perfect for a stream of work, e.g., "Previous research
has shown". Use the present tense for the model and the measures, and the past
tense for a one-time step on the data. Use "could" and "should" for future
research.

A10. **Do not address the reader.** A manuscript has no "you" and no advice in
the imperative. A thinking verb such as "Consider" or "Recall that" may open a
worked example or a reminder, once or twice in a paper.

A11. **Cite your own earlier papers in the third person, as you cite any
source.**
Example: "Following Malshe and Agarwal (2015), we use the Herfindahl–Hirschman
index (HHI) to calculate industry concentration." (JMR 2020)

### B. Paragraphs

B1. **Give each paragraph one job, and state it in the first sentence.** Two
openings dominate. In the first, "We" or "Our" is followed by a verb that says
what the paragraph does or claims, e.g., "We argue that", "We use", and "We
find". About one paragraph in three opens in that way in the current
manuscript. In the second, the construct or the topic is the subject, and the
sentence states the claim at once. The first sentence may carry a citation
when the claim comes from the literature.

B2. **Write paragraphs of five to six sentences and 100 to 140 words.** Most
paragraphs have three to eight sentences. A paragraph may reach ten sentences
or more for a hypothesis argument or a numbered procedure. Paragraphs in the
introduction are shorter, at about four sentences.

B3. **Order the support as claim, evidence, example, consequence.** The
evidence sentences carry the citations. The example is a named firm or a
named industry.

B4. **End the paragraph on a sentence that does a job.** The last sentence
states the consequence, leads into a hypothesis or an equation, or points to a
table or an appendix. Do not end a paragraph on a question, on a slogan, or on
a restatement for effect.

B5. **Announce the count before you list reasons, steps, contributions,
checks, or limitations.** Then mark each item with "First,", "Second,",
"Third,", and "Finally,". A long list may run to "Seventh,". The device is one
of his signatures.
Examples: "This is surprising for three reasons." (JM 2015) "We performed
three robustness checks." (JM 2015) "Four critical aspects of our study shed
further light on this relationship." (JMR 2020)

B6. **Link sentences and paragraphs with a repeated key term, an ordinal, a
connective, or a demonstrative that carries a noun.**
Example: "This increased bankruptcy risk can weaken a firm's ability to enter
into implicit or explicit contracts with nonfinancial stakeholders (Titman
1984)." (JM 2015)

B7. **Use a one-sentence paragraph only for a lead-in or a pointer.** A lead-in
introduces an equation or a hypothesis. A pointer sends the reader to a table,
an appendix, or the next section.

B8. **Stack evidence sentences when several studies support one claim.** Three
or four sentences in a row may each report one study, with the authors as the
subject. Join the later ones with "Similarly,", "Furthermore,", "More
recently,", or "Finally,".

B9. **State scope in a short, plain paragraph.** Say what a construct or a
measure covers and what it leaves out. Use declarative sentences of 10 to 20
words, with no hedges and few citations.

B10. **Point across sections inside a sentence.** He writes "as we discussed
previously", "which we describe in the following section", and "We elaborate
on this counterintuitive result in the "Discussion" section". He does not
write a transition paragraph.

### C. Sentences

C1. **Follow his length profile.** The mean is 21 to 22 words and the median
is 20 to 21. About one sentence in eight has 10 words or fewer. About one in
20 has more than 40 words. Go beyond 45 words only for the "where" sentence
after an equation, for a formal hypothesis, or for a sentence that lists
several cited studies. The mean is about the same in every section.

C2. **Use a short sentence for one of five jobs.** The jobs are a claim that
opens a paragraph, a verdict on a hypothesis, a lead-in, a pointer, and a flat
definition. Do not write three short sentences in a row.
Examples: "However, debt has its costs as well." (JM 2015) "Thus, H1c is fully
supported." (JMR 2020)

C3. **Vary the way sentences start.** About one sentence in three starts with
a connective or an ordinal and a comma. About one in eight starts with "We".
The rest start with the subject or with one of the fronted elements in rule
C4.

C4. **Front the purpose, the reason, the concession, the condition, or the
precedent when it frames the main clause.** The forms are "To [purpose], we",
"Because [reason],", "Although [concession],", "When [condition],",
"Following [source],", "Using [data],", "By [action],", and "Consistent with
[source],".
Examples: "Estimating a system of five equations, we find that higher leverage
leads to reductions in advertising, which in turn results in lower customer
satisfaction." (JM 2015) "Because customers are allowed to be indifferent,
customer satisfaction and dissatisfaction measures are not merely the
mathematical inverse of each other." (JMR 2020)

C5. **Build a sentence from one main clause and at most two more clauses.**
Extend the main clause with "because" in the middle of the sentence, with a
", which" clause, with "which in turn", with "thereby" and an "-ing" verb, or
with one trailing "-ing" phrase that states a consequence or the reading of a
number, e.g., "suggesting that", "indicating that", and "leading to". Use one
trailing phrase per sentence, and do not use one to claim importance.
Example: "The issuance of equity reduces financial leverage, thereby
increasing the firm's financial flexibility and enabling it to pursue a more
aggressive marketing strategy." (JM 2015)

C6. **A series of three parallel items is normal.** Use the serial comma. Each
item may carry its own citation.

C7. **State a contrast in one sentence with "Whereas", "while", or
"Although", or in two sentences with "However," or "In contrast,".**
Example: "Whereas long investors seek positive stock returns by buying a stock
at a low price and selling it at a higher price, short sellers bet on stock
price declines." (JMR 2020)

C8. **Use the same sentence frame for parallel ideas.** Hypotheses of one
family, conditions of one test, and definitions of sibling constructs repeat
the frame and change only the terms.

C9. **Use mirrored parentheses only when both directions are meant.** The form
"higher (lower)" states a symmetric claim in one sentence. The JMR 2020 paper
uses the form often, and the current manuscript uses it once.

C10. **Use the passive voice for measures, data, and definitions.** The
passive fits what a data provider does, how a variable is measured, and when
data are available. He uses about five passives per 1,000 words. Use the
active voice everywhere else.
Example: "Short selling activity is empirically measured by short interest,
calculated as the ratio of the number of firm's shares shorted to the firm's
total number of shares outstanding." (JMR 2020)

C11. **Put a citation at the end of the clause that it supports.** Make the
authors the subject of the sentence only when one study carries the argument.
About one citation in five is in that narrative form.

C12. **Attach a noun to every demonstrative.** Write "This finding suggests",
"These results support", and "Such markets". Do not write "This suggests" or
"This is". The current manuscript follows the rule in 15 of 16 cases.

C13. **Ask questions only as numbered research questions.** A manuscript has
no rhetorical questions. One direct question that the next sentence answers
may appear in a paper, and no more.

C14. **Define a term inside the sentence that introduces it.** Use an
appositive after a comma, "is defined as", or a gloss in parentheses that
starts with "i.e.,".

C15. **Introduce an example with "For example," at the start of a sentence,
with "such as" inside a sentence, or with "e.g.," inside parentheses.**

C16. **End the sentence on the new information.** The last words name the
outcome, the number, or the construct that the next sentence picks up.

C17. **Do not write fragments, one-word sentences, or exclamations, and do not
start a sentence with "And", "But", or "So" in a manuscript.**

### D. Word choice

D1. **Use one term for each construct, and repeat it.** Choose the label once,
define it, and use the same label every time. He writes "customer
satisfaction" in full about 160 times in one paper. When you declare an
abbreviation or a short label, use that exact form in every later mention, and
do not alternate between the long form and the short form.

D2. **Name units and actors with his words.** Write "firm" and not "company"
in a manuscript. Write "customers" or "consumers" as the construct requires,
and keep the choice. Name the role that acts, e.g., managers, executives,
marketers, CMOs, CFOs, investors, and regulators.

D3. **Use "We argue that" for your own reasoning.** Use "we posit" for the
thesis of the paper, and "we expect", "we propose", and "we anticipate" for
predictions.

D4. **Use plain verbs for procedures.** After "we", write use, estimate,
include, control for, model, measure, operationalize, obtain, collect, compute,
calculate, specify, and test. Write "use" and not "utilize" or "employ".

D5. **Report results with "We find that" or with the construct as the
subject.** Other forms are "Our results show that", "Our results indicate
that", "The results support H1a", and "is consistent with". Keep "show" and
"demonstrate" for summary claims in the introduction and the discussion.

D6. **Report other researchers with neutral verbs in the present tense.** Use
find, show, report, argue, document, note, demonstrate, suggest, and propose.
A theory suggests, posits, or explains.

D7. **Choose the word for a relation by its status.** Use "relationship" for a
theorized link, "association" for a tested one, and "effect" or "impact" for
the framing of the paper. Other words in his range are "moderates",
"mediates", "mechanism", "channel", "through", "more pronounced", "stronger",
and "weaker".

D8. **Mark a conclusion with "Therefore," or "Thus,".** The published papers
prefer "Thus,", and the current manuscript prefers "Therefore,". The
alternates are "Accordingly,", "Consequently,", "As such,", "In summary,", and
"Overall,". Do not write "Hence", "In sum,", or "In conclusion,".

D9. **Mark addition with "In addition,", "Furthermore,", "Similarly,", or
"Additionally,", and contrast with "However,", "In contrast,", "By contrast,",
or "Nonetheless,".** Use "Moreover," at most twice in a paper. "Yet" opens a
gap sentence in his published papers.

D10. **Give a reason with "because".** He does not use "since" for cause. The
current manuscript also uses "as" for a short reason.

D11. **Hedge with may, can, should, likely, could, potential, and suggest.**
Do not hedge with "perhaps", "arguably", "somewhat", or "seems".

D12. **The vocabulary of the field is fine.** He writes extant, posit,
antecedent, exacerbate, attenuate, and value relevance. Do not use the words
that Part 2 rule 1 lists, and do not use pivotal, realm, foster, underscore,
showcase, seamless, intricate, testament, harness, unlock, or navigate. Keep
"leverage" for the finance noun, and write "use", "exploit", or "capitalize
on" for the verb.

D13. **Define each technical term and each abbreviation at first use.** Give
the full term and then the abbreviation in parentheses. Keep the number of
abbreviations small.

D14. **Keep Latin abbreviations inside parentheses.** Write "e.g.," and
"i.e.," only in parentheses, and "for example" and "that is" in the running
sentence. Do not write "etc.".

D15. **Vary only the label for earlier work.** He rotates "previous research",
"prior research", "previous studies", "prior literature", and "extant
research". The rotation is the one exception to rule D1.

D16. **State a limit with a plain negative.** Write "does not", "cannot", and
"no association".

### E. Punctuation and formatting in manuscripts

The full rules, with examples, are in `references/reporting-and-phrases.md`.

E1. **Use the serial comma.**

E2. **Use a closed em dash only to set off a short definition or a short list
inside a sentence.** The limit is about one per 1,000 words. Do not use a dash
for a pause or for emphasis.

E3. **Use an en dash for a relation between two constructs and for a range.**
Examples are "the customer satisfaction–firm value link" and "1994–2010".

E4. **Use a colon before a numbered list, numbered research questions, a
formal hypothesis, or an equation.** Do not join two clauses with a colon.

E5. **Use semicolons between citations and between list items that contain
commas.** A semicolon may join two parallel clauses now and then.

E6. **Use parentheses for citations, statistics, abbreviations, examples that
start with "e.g.,", and short glosses.**

E7. **Do not use bullet lists in the body of a manuscript.** Use an inline
list numbered (1), (2), and (3), a sequence of ordinal sentences, or a table.

E8. **Use quotation marks for a direct quotation, with its page number, and
for a term in a special sense on its first use.**

E9. **Use italics for a newly named mechanism, for statistical symbols, and
for run-in headings.** Do not use bold in body text.

E10. **Use title case for first-level and second-level headings, and run-in
headings for the third level.** Word every heading as a noun phrase.

### F. Evidence and numbers

F1. **Support every claim about prior work with a citation.** A claim about a
stream of work gets two to five citations.

F2. **Give exact numbers with their units.** State the sample as the number
of observations, the number of firms, and the period. Use "approximately" for
a rounded statistic.

F3. **Keep a number and its comparison in one sentence.** A mean is followed
by the benchmark, and an effect is followed by what it is compared with.

F4. **Report statistics in his formats.** A coefficient and its p-value go in
parentheses right after the claim. See reporting rules 1 to 11.

F5. **Translate the headline effect into a magnitude that a manager can
read.** See reporting rule 10 and playbook rule 76.

F6. **Use a quotation from a named practitioner as evidence for a claim about
practice.** The JMR 2020 paper quotes interviews with industry experts in the
theory section. Introduce the speaker with name and role, and set a long
quotation as a block.

### G. Manuscript structure

Read `references/manuscript-playbook.md` before you draft a section. The map
below is a summary.

G1. **Title.** A short phrase, a colon, and a literal subtitle that names the
constructs.

G2. **Abstract.** One paragraph of 150 to 180 words in the present tense, with
the gap or the aim first and the magnitudes last.

G3. **Introduction.** Seven or eight paragraphs: the standing of the topic,
what prior research shows, the gap in one "Yet" or "Although" sentence, the
counted reasons or aspects, the research questions, the empirical preview with
sample facts, the findings, and the counted contributions.

G4. **Theory.** One claim per paragraph, evidence from cited studies, a
concrete example, and a first-person sentence that marks the step to the
paper's own argument.

G5. **Hypotheses.** A chain of reasoning with hedged verbs, the opposing
argument resolved, a short lead-in, and one declarative sentence per
hypothesis in associational wording.

G6. **Method.** Data, measures, model, and identification. Every choice
carries a precedent or a reason in the sentence that introduces it.

G7. **Results.** For each test: restate, show the estimate, and give the
verdict. Unsupported and unexpected results are named as such.

G8. **Discussion.** Theoretical implications, managerial implications for
named roles, and limitations that are paired with future research. The papers
have no separate conclusion.

### H. Practitioner register

Section H comes from his two coauthored Harvard Business Review articles.
Magazine editors shaped the surface of those articles, so section H keeps what
the authors chose: the structure, the evidence, and the way of giving advice.
For the surface, apply Part 2.

H1. **Open on the manager's situation.** Start with a current trend and the
risk that it carries. Do not open with the literature or with a research gap.

H2. **Give the main finding early, in one sentence.** The finding comes right
after the opening and before the description of the study.

H3. **Introduce the study in one sentence.** The sentence has a purpose
phrase, "we", a plain verb, and who and how many took part. Do not name the
design, the model, or the measures.
Example: "To better understand how political polarization affects brands, we
surveyed 5,881 retail customers with strong political ideologies (Democrats
and Republicans) and rated their likelihood to engage in positive and negative
word-of-mouth for 45 retail brands." (HBR, Partisanship)

H4. **Report a finding with "we found that" in the past tense.** Use the
present tense for a summary claim, with the study as the subject, e.g., "Our
survey shows" and "Our data suggest".

H5. **State each finding as a plain number with its comparison.** Use a count,
a percentage, or a group mean, and pair it with its contrast: perceived
against actual, before against after, or one group against another. Do not
report a p-value, a coefficient, a test statistic, or a model name.
Example: "From 1994 to 2017, the average partisan gap increased from 15 points
to 36 points." (HBR, Partisanship)

H6. **Follow each finding with a named company and one dated action or one
number.**

H7. **Give each construct an everyday label, and define it by what was
observed.** Keep the labels fixed once you define them.

H8. **Name each source in the sentence.** The articles have no parenthetical
citations and no footnotes.
Example: "A 2023 review of 245 academic papers found that firms that
prioritize customer satisfaction perform better across a wide variety of
metrics, including sales, profits, cash flows, stock price, and more." (HBR,
Alignment)

H9. **Organize advice as a counted set of steps.** Give each step a subhead
that starts with a verb. In the running text, state the advice about a
third-person subject with "must", "should", or "cannot". Use "you" only for a
direct instruction.
Example: "Leaders cannot simply announce a strategy and assume it has
permeated the rest of the organization." (HBR, Alignment)

H10. **Hedge only at the step from data to advice.** Use "suggests", "likely",
"may", and "might".
Example: "Actions that push brands into vulnerable or dissonant territory are
likely to hurt revenue and growth." (HBR, Partisanship)

H11. **Write sentences of 20 to 25 words on average and paragraphs of about
three sentences.** About one sentence in ten has 10 words or fewer.

H12. **Use everyday connectives.** Write "For example,", "Next,",
"Similarly,", "Instead,", "Specifically,", "First,", and "Finally,". Do not
write "However,", "Therefore,", "Thus,", "Moreover,", or "Furthermore,".

H13. **Ask at most one question at a time, and answer it in the next
sentence.**

H14. **End on the advice.** A practitioner article has no limitations section
and no call for future research.

H15. **Put a comparison across categories in a short list of label and
value.** Introduce the list with a sentence that ends in a colon.

H16. **Let a named executive state a lesson in a direct quotation.** Give the
name, the title, and the company. Use only quotations that the user supplies.

## Part 2. Plain writing (secondary)

Part 2 repeats the 25 rules of the plain-writing skill by Shreya Shankar. The
rules apply in full in the working register. A note that starts with "In
manuscripts" says how the author's style changes a rule for the manuscript
register. A rule without a note applies to manuscripts as written.

There are four groups of rules: word choice and tone, sentences and
paragraphs, punctuation and formatting, and patterns to avoid. Each rule has a
before and after.

### Word choice and tone

1. **Use simple, everyday words.** Don't pick a fancy synonym when a plain word
   works. Also avoid words AI tools overuse, e.g., "delve", "tapestry",
   "landscape", "robust", "leverage", and "reach".
   Before: We leverage the cache to unlock a more robust query experience.
   After: We use the cache to make repeated queries faster.
   In manuscripts: the vocabulary of the field is allowed, e.g., "extant",
   "posit", "antecedent", "moderate", and "mediate" (rule D12). "Robust" is
   allowed in its statistical sense, as in "robustness checks". Keep
   "leverage" for the finance noun.

2. **No jargon.** Always use human-understandable language, the way two people
   talk to each other. Don't invent jargon or shorthand (that is, if a word or
   phrase is not in the Merriam Webster dictionary, don't use it). Use
   established technical terms only when they are most precise, and briefly
   define them when readers may not know them.
   Before: The score is a calibrated proxy for whether the property holds.
   After: The score estimates how likely the property is to hold.
   In manuscripts: technical terms are expected. Define each term in the
   sentence that introduces it, and define each abbreviation at first use
   (rule D13).

3. **No puffery or empty emphasis.** Drop words that add emphasis but no
   information, e.g., "really", "real", "matters", "worth", "carries weight",
   "boasts", "a testament to", "pivotal", "renowned", and "quietly". State the
   actual point, or cut the sentence.
   Before: This result matters, and it carries weight for the design.
   After: The scores barely moved, so we can skip the model on most documents.
   In manuscripts: the rule holds. He writes "important" or "critical" a few
   times in a paper, and each time the same sentence or the next one gives the
   reason (rule A4).

4. **Use consistent terminology and constrain your vocabulary.**
   Before: Upload the document. The file is parsed, and the record is saved.
   After: Upload the document. The document is parsed and saved.
   In manuscripts: the rule holds and is stricter (rule D1). The one exception
   is the label for earlier work (rule D15).

5. **It's ok to use contractions.** They match everyday speech, so use them
   freely.
   Before: Do not worry, it is not going to overwrite your file.
   After: Don't worry, it's not going to overwrite your file.
   In manuscripts: do not use contractions (rule A2). In practitioner writing,
   a few contractions are fine.

6. **Do not invent hyphenated adjectives.** Avoid a phrase you make up by
   joining words with a hyphen to sound compact or clever. If you would not find
   it in a dictionary, don't use it. A common compound adjective that people
   already use is fine, e.g., "well-crafted".
   Before: We added a reveal-style colon to the output.
   After: We added a colon that shows the schema.
   In manuscripts: a compound modifier built from a defined construct or from
   a number is standard, e.g., "firm-quarter observations", "high-leverage
   firms", and "one-standard-deviation increase". Do not coin a compound for
   effect.

7. **Keep the writing boring, descriptive, and explanatory.** Do not use a
   catchy phrase, slogan, clever label, or wording meant to sound memorable.
   This rule applies everywhere; to headings, topic sentences, callouts,
   labels, summaries, and ordinary prose.
   Before: Legal requirements as a floor.
   After: Applicable legal constraints.
   Before: # The alignment loop
   After: # Iterative refinement using development disagreements
   In manuscripts: the rule holds for headings, topic sentences, labels, and
   body text. The one exception is the title of a paper, which may open with a
   short phrase before the colon (rule G1).

### Sentences and paragraphs

8. **Write complete sentences.** Each sentence should have a subject and a
   verb. Do not write fragments, and do not stitch unrelated ideas together with
   colons or semicolons. But it is ok to join closely related ideas with plain
   conjunctions, like "and", "because", or "so".
   Before: The agent polls the file and reacts to changes, and the team meets on
   Tuesdays.
   After: The agent polls the file and reacts to changes. The team meets on
   Tuesdays.
   In manuscripts: the rule holds. A run-in heading such as "Sales growth." is
   a heading and not a sentence. A semicolon may join two parallel clauses now
   and then (rule E5).

9. **When you present a workflow or sequence, walk through it in order.** Use
   "First", "Second", "Third", and give each step its own sentence so the
   reader can follow it, or break up steps with semicolons.
   Before: The groups the features were sorted into were the authors' own
   reading, the example posts were written by hand, and finer detail meant
   training extra small models and labeling again.
   After: First, the authors sorted the features into groups themselves, based on
   their own reading of the outputs. Second, they wrote the example posts by
   hand. Third, when they wanted finer detail, they trained another small
   model, and they labeled the posts again.
   In manuscripts: the rule holds. He also writes "Fourth," and "Finally,",
   and he announces the count before the sequence (rule B5).

10. **Organize a paragraph as a topic sentence and then support.** Start each
   paragraph or section with a topic sentence that states the main point. Then,
   the next sentence should be a supporting example or fact, with an extra
   sentence about it if it needs one. Then, introduce more support with a plain
   connective like "For example", "Moreover", or "Or".
   Before: The parser skips files with no changes. The cache holds the previous
   output. Most renders are fast.
   After: Most renders are fast. For example, the parser skips files with no
   changes, so the server returns early. Moreover, the cache keeps the previous
   output, so a repeated render does no work.
    In manuscripts: the rule holds. Add a last sentence that states the
    consequence or leads into the next element (rule B4).

11. **Never write three or more clauses in one sentence, or three or more
    example sentences in a row.** In ordinary prose, a sentence may have one or
    two related clauses. Do not pack three or more clauses into one prose
    sentence. If you need that many points, use a numbered First / Second / Third
    sequence under rule 9, or short bullet points when you are writing a
    brief. If list points are examples and you want to inline them, introduce
    with "e.g.". Also do not give three or more example sentences back to back
    to support the same point.
    Before: The parser reads the file, the validator checks the fields, and the
    writer saves the record.
    After: The parser reads the file, and the validator checks the fields. The
    writer then saves the record.
    In manuscripts: a sentence may hold a series of three parallel items, and
    each item may carry its own citation (rule C6). Three or four evidence
    sentences may stand in a row when each reports a different study (rule
    B8). For every other sentence, keep to one main clause and at most two
    more clauses (rule C5).

12. **Prefer long, explanatory sentences over short, punchy ones.** In ordinary
    prose, write the way people explain things out loud: longer sentences with
    commas, and the simplest way to say the point. Do not break one thought into
    a stack of short sentences, and don't write catchy short phrases. Short
    lines are fine only in labeled briefs, bullets, or a First / Second / Third
    sequence, e.g., "To do: validate recall on long queries."
    Before: The gate runs on every merge. It blocks regressions. Nobody
    bypasses it.
    After: The gate runs on every merge, and it blocks changes that fail a
    regression case. A regression cannot make it to production, unless someone
    deliberately overrides the check.
    Before: Search ranking now uses a scored model instead of heuristics. The
    change reduced p95 latency from 900 ms to 220 ms. We still need to validate
    recall on long queries.
    After: Search ranking now uses a scored model instead of heuristics, and
    p95 latency fell from 900 ms to 220 ms. To do: validate recall on long
    queries.
    In manuscripts: follow his length profile (rule C1). A short sentence is
    right for a claim that opens a paragraph, a verdict on a hypothesis, a
    lead-in, a pointer, and a flat definition (rule C2).

13. **Be precise and unambiguous, and cut unnecessary clauses.** Say exactly
    what changes, who does what, or by what mechanism. Prefer a concrete
    statement over an evocative abstraction, e.g., don't say things like
    "improvement stops being guesswork". Also drop trailing or side clauses
    that add no fact, e.g., "before we call the work done", "as we move
    forward", or "for the time being". Keep the sentence long when the content
    needs it, but do not pad it.
    Before: With trusted scores, improvement stops being guesswork.
    After: With trusted scores, you can measure whether each change helped,
    so you keep or revert each change based on the measured result.
    Before: We still need to validate recall on long queries before we call
    the work done.
    After: To do: validate recall on long queries.

14. **In chat, give context on the problem.** When you are chatting back and
    forth, write for a smart reader who does not have context on the problem,
    or who forgot it. Give context on the problem and on what was happening
    before. Then say what changed. Keep the setup short. Do not dump the whole
    history. Ignore this rule if you are writing an essay.
    Before: The exporter now waits on the reset header, and `dotnet test` is
    green.
    After: The Okta System Log exporter was rereading whole hours, so a retry
    could write the same event twice. It now waits using the response reset
    header, and the six acceptance tests pass.
    In manuscripts: the rule does not apply.

### Punctuation and formatting

15. **No dashes or middle dots.** Do not use em dashes or en dashes, including in
    number ranges. Join clauses with a period or "and", and write ranges with
    "to". Do not use the middle dot (·) as a separator; use a comma, "and", or
    separate lines instead.
    Before: The build is fast — it finishes in 10 to 20 seconds.
    After: The build is fast. It finishes in 10 to 20 seconds.
    In manuscripts: use an en dash for a relation between two constructs and
    for a range, as the journals do (rule E3). A closed em dash may set off a
    short definition or a short list inside a sentence, at most about once per
    1,000 words (rule E2). Do not use a dash for a pause or for emphasis.

16. **Don't use colons to join clauses in ordinary prose.** Do not use a colon
    to glue two clauses or to set up a point in essay-like writing. A colon is
    fine when you introduce a list. A colon is also fine as a short label in
    updates, briefs, status notes, and PR descriptions, e.g., "Summary:",
    "Changes:", or "Remaining work:".
    Before: Read for the schema: the feature fires.
    After: Read for the schema. The feature fires.
    Before (allowed in a PR or update): Summary: Replace em dashes in
    generated docs.
    After (same text is fine): Summary: Replace em dashes in generated docs.
    In manuscripts: the rule holds. A colon also introduces numbered research
    questions, a formal hypothesis, and an equation (rule E4).

17. **Use straight quotes, not curly quotes.**
    Before: The system logs each “event” as it happens.
    After: The system logs each "event" as it happens.
    In manuscripts: use the quotation marks that the document format produces.
    Word files and typeset articles use curly quotes, and plain text and
    Markdown use straight quotes.

18. **Keep the formatting plain.** Use sentence case in headings. Do not use
    bold for decoration.
    Before: ## How To Install The Skill
    After: ## How to install the skill
    In manuscripts: use title case for first-level and second-level headings
    and run-in headings for the third level, or the format of the target
    journal (rule E10). Do not use bold in body text.

19. **You can use lists, but do not overuse them.** Keep a list to three or
    four points, and nest extra points if you need more. When you are writing
    an essay, use lists and tables very sparingly.
    Before: Shipped this week:
    - dark mode
    - an invite link fix
    - a schema mismatch that blocked analytics export
    - renderer cleanup
    - copy edits
    - a scored ranking model
    - a p95 drop from 900 ms to 220 ms
    - untested recall on long queries
    After: Search ranking now uses a scored model, and p95 latency fell from
    900 ms to 220 ms. The old heuristic path is still in the repo as a
    fallback.
    - Shipped
      - Dark mode
      - Invite link fix
    - Still open
      - Test recall on long queries
      - Unblock analytics export
    In manuscripts: do not use bullet lists in the body. Use an inline
    numbered list, a sequence of ordinal sentences, or a table (rule E7).

### Patterns to avoid

20. **Do not give inanimate things fake agency.** Do not write as if a system
    or object transforms, decides, or intends on its own when a person or
    process is the real actor. Ordinary factual verbs for tools and systems are
    fine, e.g., "The API returns JSON", "The job writes the file", or "The
    paper argues". Prefer a human or process subject when that is clearer.
    Before: The logs become searchable records, once the job finishes.
    After: You can search the logs, once the job finishes.
    In manuscripts: a construct, a result, a table, or a study may be the
    subject of a factual verb, e.g., "Leverage reduces customer satisfaction",
    "Our results show", and "Table 2 shows". Do not give an abstraction a
    wish, a goal, or a plan.

21. **No analogies or imagery.** Do not explain by comparing to something else,
    and do not use metaphor. Describe the actual thing in literal terms. Write
    in a boring way.
    Before: The feature index is like a card catalog that the optimizer can flip
    through.
    After: The feature index is a list of named features. The optimizer can look
    up which feature matches a request.
    In manuscripts: the rule holds. Explain with a worked example or a named
    firm (rule A7). His papers contain a few stock phrases such as "shed light
    on", at a rate of under one per 2,000 words. Do not add more than that,
    and do not build an analogy.

22. **Never use negative parallelism of the form "not just X, it is Y" or
    "not only X, but Y".** State what the thing is. A plain refusal or
    correction is fine, including a short quote of a customer's hype phrase
    when you replace it with a concrete fact.
    Before: It is not just a parser, it is a full toolchain.
    After: It is a parser and a formatter.
    Before: We do not describe the API as "enterprise-grade robust," because
    that phrase can mean different things.
    After: The API has a 99.9% monthly uptime SLO.
    In manuscripts: the additive form "not only X but also Y" is allowed when
    X and Y are both findings of the paper, at most twice in a paper. He uses
    the form to state a dual effect. The reframing form "it is not X, it is Y"
    stays banned.

23. **Do not stack rhetorical questions.** AI writing often asks two or three
    rhetorical questions in a row to sound thoughtful. Don't do this. Just state
    the problem directly.
    Before: Does the tool keep the writer's voice? Does it make the argument
    stronger or weaker?
    After: We do not yet know whether the tool keeps the writer's voice, or
    whether it makes the argument stronger or weaker.
    In manuscripts: the rule holds. Numbered research questions are real
    questions and are fine (rule C13).

24. **Do not use vague demonstrative pronouns.** Do not use "This", "That",
    "These", or "Those", especially do not start a sentence with a demonstrative
    pronoun, and never begin a paragraph with a sentence that contains a
    demonstrative anywhere in it.
    Before: That context carries into the next turn.
    After: The agent applies the rules you saved on the next turn.
    In manuscripts: "This", "These", and "Such" may start a sentence or a
    paragraph when a noun follows at once, e.g., "This finding suggests" and
    "These results support H3" (rule C12). He uses the form 10 to 20 times in
    a paper. Do not leave the demonstrative bare, as in "This suggests".

25. **Do not open with a count of things.** Never start by announcing how many
    points are coming, e.g., "Two cautions." or "Three things to keep in mind."
    State the first point directly. If you absolutely must present many things,
    use a bullet list instead.
    Before: Two cautions. First, the section can drift out of date. Second,
    it can balloon if every item gets a sentence.
    After: The section can drift out of date, because it duplicates facts
    that live elsewhere. It can also balloon if every item gets a sentence.
    In manuscripts: announce the count, and then list the items with ordinals,
    e.g., "This is surprising for three reasons." (rule B5). In practitioner
    writing, a counted set of steps is fine (rule H9).

## Part 3. Where the author's style overrides plain writing

The table lists every plain-writing rule that changes outside the working
register. A rule that is not in the table applies in all three registers.

| Rule | Working register | Manuscript register | Practitioner register |
|---|---|---|---|
| 1. Simple words | Applies | Field vocabulary allowed (D12) | Applies |
| 2. No jargon | Applies | Technical terms allowed when defined (D13) | Everyday labels (H7) |
| 5. Contractions | Allowed | Not allowed (A2) | Allowed, a few |
| 6. Hyphenated adjectives | Applies | Compounds from constructs and numbers allowed | Applies |
| 7. Boring wording | Applies | Applies, except the main title (G1) | Applies |
| 11. Three clauses, three examples | Applies | Series of three and stacked evidence allowed (C5, C6, B8) | Applies |
| 12. Long sentences | Applies | His length profile (C1, C2) | 20 to 25 words (H11) |
| 14. Context in chat | Applies | Does not apply | Does not apply |
| 15. No dashes | Applies | En dash allowed, em dash rare (E2, E3) | Applies |
| 17. Straight quotes | Applies | Quotes of the document format | Applies |
| 18. Sentence-case headings | Applies | Title case and run-in headings (E10) | Subheads that start with a verb (H9) |
| 19. Lists | Applies | No bullet lists in the body (E7) | Short label and value lists (H15) |
| 20. Fake agency | Applies | Constructs, results, tables, and studies may act (D5, D6) | Applies |
| 22. Negative parallelism | Applies | "not only X but also Y" allowed, twice per paper | Applies |
| 23. Rhetorical questions | Applies | Numbered research questions only (C13) | One question at a time (H13) |
| 24. Demonstratives | Applies | Allowed with a noun (C12) | Allowed with a noun |
| 25. Count of things | Applies | Announce the count (B5) | Counted steps allowed (H9) |

## Part 4. The deslopify command

When the user says `/malshe-plain-writing deslopify`, rewrite the previous
agent response, or the text after the command, for a sharp CEO or technical
reader who has no project context. Return only the rewrite.

Start with the main conclusion, then cover the background, how it works, and
present all information logically and sequentially. Include technical details
the reader needs (standardize on existing well-known terminology, not new
terminology), and define unfamiliar terms.

Follow the rules of the working register. When the text is a passage from a
manuscript, follow the rules of the manuscript register.

## Part 5. Check before you return the text

For every register:

1. Every fact, number, citation, and quotation comes from the user or from a
   source that you read. Each gap is a placeholder in square brackets.
2. Each construct has one label, and the label is the same everywhere.
3. No sentence uses a word that rule D12 or Part 2 rule 1 bans.
4. No analogy, slogan, or stacked question is in the text.

For a manuscript:

5. No contraction, no "I", no "you", and no exclamation mark.
6. Sentence length follows rule C1, and no three short sentences stand in a
   row.
7. Each paragraph opens with its claim or its action and ends on a sentence
   that does a job.
8. Every demonstrative carries a noun.
9. Hypotheses, results, and robustness checks use associational wording when
   the data are observational.
10. Each list of reasons, steps, contributions, or limitations has an
    announced count and ordinals.
11. Statistics, numbers, citations, and cross-references follow
    `references/reporting-and-phrases.md` or the style of the target journal.
12. Em dashes number at most one per 1,000 words, and no colon joins two
    clauses.

For the working register:

13. All 25 rules of Part 2 hold as written, with no dashes, no bare
    demonstratives, and no opening count.
