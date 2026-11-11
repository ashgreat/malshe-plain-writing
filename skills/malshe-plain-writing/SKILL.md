---
name: malshe-plain-writing
description: >-
  Writes and edits prose in Ashwin Malshe's own style, learned from his
  published marketing papers and current manuscript, and applies the
  plain-writing rules where his style is silent. Use when drafting or revising
  his journal
  manuscripts (abstract, introduction, theory, hypotheses, methods, results,
  discussion, web appendix), responses to reviewers, practitioner articles,
  reports, summaries, emails, READMEs, slides, commit messages, or PR
  descriptions. Use when the user asks to write in his style or voice, or to
  simplify, tighten, reword, or clean up writing. Use when the user invokes
  /malshe-plain-writing deslopify or asks to deslopify a response. Do not
  apply to code, only to the words around it.
license: MIT
metadata:
  version: "1.1.0"
---

# Malshe plain writing

The skill draws on the author's own writing and on the plain-writing skill.
The author's own writing is two first-author papers in Journal of Marketing
(JM 2015) and Journal of Marketing Research (JMR 2020), a current working
manuscript, five coauthored journal articles, and two Harvard Business Review
articles. The plain-writing skill is a set of 25 rules for plain and literal
prose.

The author's style is the primary source, and plain writing is the secondary
source. Part 1 holds the rules of the author's style. Part 2 holds all 25
plain-writing rules and says how each one applies to his manuscripts. Part 3
is a lookup table for the places where the two sources disagree. Part 4 is the
deslopify command. Part 5 is the check to run before you return the text.

Every rule is an instruction for new text. Where a rule also describes his
papers, it names the paper. His published papers do not follow every rule, and
the rules say so where the difference is large. When a published paper and a
rule disagree, follow the rule.

## How to apply the skill

1. **Decide which register the text belongs to.**
   - Manuscript register: journal articles, working papers, web appendices,
     conference abstracts, grant text, and responses to reviewers.
   - Practitioner register: articles for managers, executive summaries, and
     posts about research for a business audience.
   - Working register: chat replies, emails, reports, READMEs, slides,
     documentation, commit messages, and PR descriptions.

   When the text is not in a list, choose by the reader. Text that an editor,
   a reviewer, or a scholar will judge as research is in the manuscript
   register, e.g., a book chapter, a dissertation, and a referee report. Text
   for managers or the public is in the practitioner register, e.g., a
   teaching case and a post on LinkedIn. All other text is in the working
   register, e.g., a cover letter to an editor, a recommendation letter, a
   syllabus, and slides for a talk. When a document mixes registers, apply the
   register of each part. When the choice is not obvious, say in one line
   which register you used.

2. **Apply the rules that govern the register.**
   - Manuscript register: Part 1 governs. Part 2 applies wherever Part 1 is
     silent, in the form that the "In manuscripts" notes give.
   - Practitioner register: section H of Part 1 governs, then Part 2. From the
     rest of Part 1, keep rules A3, A5, A7, D1, F2, and F3. Write "company"
     and not "firm".
   - Working register: Part 2 governs in full. From Part 1, keep rules D1,
     F2, and F3. In a chat reply or a status message, give the earlier problem
     first and then what changed (Part 2 rule 14). Part 2 rule 10 applies to
     each paragraph of a longer text.

3. **Read the reference file that fits the task before you write.**
   - `references/manuscript-playbook.md`: read the part for the section that
     you write, and the last part when the text has headings, tables, or
     footnotes. The playbook gives the steps and the sentence patterns for
     each section of an empirical paper.
   - `references/reporting-and-phrases.md`: read it before you write results,
     methods, citations, or numbers. It gives the formats for statistics,
     numbers, citations, cross-references, and punctuation, and a list of
     recurring phrases.
   - `references/other-genres.md`: read it for a review or conceptual
     article, a methodological commentary, or a response to reviewers.
   - `references/plain-writing-original.md`: the plain-writing skill as
     published. Part 2 repeats its rules, so you rarely need the file.

4. **Follow the order of authority.** The user's instruction for the task
   comes first. The style guide of the target journal comes second, and it
   decides citation format, heading format, the person of the abstract, the
   leading zero, and spelling. The rules of the skill come third. A word limit
   from the user comes before the statistics of rules B2 and C1. To meet a
   limit,
   drop the optional steps of the playbook first, and say which steps you
   dropped. Use American spelling unless the journal asks for another.

5. **Do not invent content.** Do not make up a citation, a number, a result,
   a quotation, a sample fact, a definition, a finding of prior work, a named
   firm, or a benchmark. When a sentence needs one of them and you do not have
   it, write a placeholder in square brackets that names what is missing,
   e.g., [citation], [number of firms], [definition of advertising intensity],
   and [opposing argument and its resolution]. You may write reasoning that
   links the user's facts, such as a step in a mechanism, a contrast between
   two conditions, or advice that follows from a finding. Hedge the reasoning
   under rule A3, and do not attach a citation placeholder to it unless the
   user says that a source exists. When the playbook requires a step and you
   lack the content, write the step as a template with placeholders, and do
   not drop it without telling the user. At the end of your reply, list the
   placeholders and the sentences of your own reasoning, so that the user can
   confirm them.

6. **When you edit an existing draft, keep what already follows the rules.**
   Keep the meaning, the numbers, the citations, and the hedges. Change a
   sentence only when it breaks a rule or when the user's request requires the
   change, e.g., a word limit. Keep the conventions that the draft already
   uses for the labels of predictions, the conclusion connective, the tense of
   the method section, and the citation format, and apply one convention to
   the whole draft. Do not add a step, a claim, or an example that the draft
   lacks. When the draft makes a claim that the facts you have do not support,
   do not repeat the claim as a fact. After the text, list the steps that are
   missing, the claims that you left out, and the changes you made by rule
   id, unless the user asks for the text only.

7. **Match the format of the file you write.** In a Word file, use the
   heading styles, the italics, and the curly quotes of the document. In
   Markdown or chat, use "#" headings in the case that rule E10 or Part 2 rule
   18 gives, straight quotes, and no italics unless the user asks. Set a
   formal hypothesis on its own line. When you write one section or one
   paragraph, assume that the rest of the paper exists. Define a term again
   only when the user says that the text stands alone.

8. **Check the text against Part 5 before you return it.**

## Part 1. The author's style (primary)

Examples are quoted from his published papers and carry a source tag. The
rates describe a whole paper. Use a rate as a check only on a text of 500
words or more, and accept a text that is within one quarter of the rate. Do
not add or cut words in a short text to meet a rate.

### A. Voice and stance

A1. **Write in the first person plural and the active voice.** Use "we" for
what the authors argue, do, and find, and "our" for the study, the sample, and
the results. He uses "we" 10 to 15 times per 1,000 words across a paper. The
method and results sections have the most, at 16 to 25 per 1,000 words. An
introduction has 5 to 15, and a hypothesis argument has almost none. Do not
write "I". Write "the authors" only in an abstract for a journal that wants
the third person. Refer to the work as "our study", "our research", or "this
research". "This article" is in the published papers and may stay in his
draft. Do not write "this paper".
Example: "We argue that leverage affects customer satisfaction through two
mediating observable expenditures: R&D and advertising." (JM 2015)

A2. **Do not use contractions in a manuscript.** His empirical papers have
none outside direct quotations.

A3. **Match the strength of the verb to the evidence.** State a cited finding
and your own estimate without a hedge. Hedge a mechanism, a prediction, an
explanation of a surprising result, and advice. Use "may" for how actors may
react, "can" for what a factor is able to do, "should" for a predicted relation
or for advice, "likely" for a probable outcome, and "could" for future
research. He uses "may" two to four times per 1,000 words, almost all of it in
the theory section and the discussion. Use one hedge per claim, and do not
stack two, as in "may potentially".
Examples: "Higher debt can also change the firm's incentives to honor implicit
contracts (Maksimovic and Titman 1991)." (JM 2015) "In such markets, the
marginal benefits to increasing customer satisfaction are likely to be lower."
(JM 2015)

A4. **Keep evaluation rare, and give the reason at once.** When you call a
finding important, the same sentence or the next one must give the reason or
the number. The words "important", "critical", "key", and "crucial" may appear
at most once per 1,000 words in total, in the introduction and the discussion.
Do not use an intensifier to praise or to stress, and do not write "clearly",
"novel", "interestingly", "notably", "importantly", or "reassuringly". The
words "highly" and "very" are allowed only when they name a level on a measured
scale, e.g., "highly leveraged" and "highly correlated". His published papers
contain intensifiers, so do not take them as a model, and remove them when you
edit.
Example: "The finding that leverage moderates the customer satisfaction–firm
value link is important. Previous research has found a wide variation in this
link across industries (Anderson, Fornell, and Mazvancheryl 2004)." (JM 2015)

A5. **Use associational words for estimates from observational data, and
causal words for theory.** Every sentence that predicts or reports an estimate
takes associational wording: research questions, the preview of findings,
hypotheses, results, robustness checks, and contribution statements. Write "is
positively associated with", "the association between", and "the association
is weaker for". Sentences that state the theory may use causal words: the core
argument, the mechanism in the hypothesis development, and the implications in
the discussion. There the verbs "affects", "reduces", and "leads to" are fine.
The noun "effect" stays in fixed terms such as "indirect effect", "moderating
effect", and "fixed effects". Treat every estimate as associational unless the
user says that the data come from an experiment or a natural experiment.
Describe identification as reducing a concern, with "to address", "to
alleviate", or "to account for". The rule follows the JMR 2020 paper and the
current manuscript. The JM 2015 paper and his coauthored papers write "impact"
and "effect" in hypotheses and results, so keep those words when the user's
draft uses them throughout.

A6. **Say plainly when a result is unexpected, unsupported, or limited.** The
JM 2015 paper uses "unexpected", "counterintuitive", "puzzling", and "contrary
to our conjecture". When "unexpected" names a construct in the paper, write
"counterintuitive" or "contrary to our expectation". In the results section,
name the result and point to the discussion. In the discussion, offer one
possible explanation, mark it as possible, and say what stops the paper from
testing it. When the user gives no explanation, write [possible explanation
for the result] and do not invent one.
Example: "A potential explanation for this puzzling result is that
high-sales-growth firms might have achieved the sales growth by offering price
promotions and shrinking the profit margins." (JM 2015)

A7. **Explain with literal, concrete material.** Use a worked example with
round numbers, a named firm, or a named industry. Do not explain with an
analogy.

A8. **Position the paper against prior work by coverage, not by fault.** Say
what earlier studies examined, used, or assumed, and then what the present
study does. Credit the exception by name. Do not write that earlier authors
ignored, overlooked, or failed to see something. A sentence may say that
studies "fail to consistently find" an effect, because the sentence reports a
result and does not fault the authors.
Example: "Luo, Homburg, and Wieseke (2010) is one exception, and they show
that the dispersion in financial analysts' recommendations partially mediates
the association of customer satisfaction and firm financial outcomes." (JMR
2020)

A9. **Choose the tense by the kind of statement.** Use the present tense for
a general claim, for what one study finds, for your own argument, and for your
results. Use the present perfect for a set of related studies, e.g., "Previous
research
has shown". Use the present tense for the model and the measures, and the past
tense for a one-time step on the data. Use "could" and "should" for future
research.

A10. **Do not address the reader.** The body text of a manuscript has no "you"
and no advice in the imperative, outside direct quotations. "Recall that" may
open a reminder once in a paper. Open a worked example with "As an example,"
or "For example,". A cell of an implications table may start with a verb.

A11. **Cite your own earlier papers in the third person, as you cite any
source.**
Example: "Following Malshe and Agarwal (2015), we use the Herfindahl–Hirschman
index (HHI) to calculate industry concentration." (JMR 2020)

### B. Paragraphs

B1. **Give each paragraph one job, and state it in the first sentence.** Most
paragraphs open with the construct or the topic as the subject, and the
sentence states the claim at once. The other common opening is "We" or "Our"
with a verb that says what the paragraph does or claims, e.g., "We argue
that", "We use", and "We find". About one paragraph in three opens in that way
in the current manuscript, and about one in eight in the published papers. The
first sentence may carry a citation when the claim comes from the literature.
The first paragraph of a construct subsection opens with the definition of the
construct, and the claim follows in the second sentence.

B2. **Write paragraphs of five to six sentences and about 120 words on
average.** Most paragraphs have three to eight sentences. A paragraph may have
ten sentences or more for a hypothesis argument or a numbered procedure.
Paragraphs in an introduction have five to seven sentences and 110 to 230
words, so give each step of rule G3 its own paragraph, and do not merge the
summary of prior research, the gap, and the thesis into one paragraph. Results
paragraphs are the shortest, at about 90 to 110 words.

B3. **Order the support as claim, evidence, example, consequence.** The
evidence sentences carry the citations. The example is a named firm or a
named industry.

B4. **End the paragraph on a sentence that does a job.** The last sentence
states the consequence, leads into a hypothesis or an equation, or points to a
table or an appendix. A consequence sentence with "Thus," or "Therefore,"
closes an argument block, in about four theory paragraphs in ten in the JM
2015 paper. Do not add "Thus," to every paragraph. Do not end a paragraph on a
slogan or on a restatement for effect.

B5. **Announce the count before you list reasons, steps, contributions,
checks, or limitations.** Then mark each item with "First,", "Second,",
"Third,", and "Finally,". A number is the default when the list has two to
five items. He also writes "several" and "a few", most often when the items
run over several paragraphs, so keep those words when you edit his draft. A
list runs to "Fifth," in the two first-author papers and to "Seventh," in the
current manuscript and in his coauthored review article. He uses the device in
both published first-author papers.
Examples: "This is surprising for three reasons." (JM 2015) "We performed
three robustness checks." (JM 2015) "Four critical aspects of our study shed
further light on this relationship." (JMR 2020)
The first example is from 2015. Write "This gap is surprising for three
reasons." in new text (rule C12).

B6. **Link sentences and paragraphs with a repeated construct label, an
ordinal, a connective, or a demonstrative that carries a noun.** Rule D1
covers construct labels only. When the link is a phrase of four words or more
that is not a construct label, do not repeat it as the next subject. Use a
demonstrative with a summary noun of one or two words, e.g., "These actions"
and "This approach", or join the two steps in one sentence with ", which in
turn".
Example: "These actions are likely to harm customer satisfaction by negatively
influencing some of its key determinants such as perceived quality and
perceived value." (JM 2015)

B7. **Use a one-sentence paragraph only for a formal hypothesis, for a
one-sentence summary that leads into a hypothesis, for the lead-in to an
equation, or for the attribution before a block quotation.** Put any other
lead-in or pointer at the end of the paragraph that it closes.

B8. **Put evidence sentences in a row when several studies support one
claim.** Two or three sentences in a row may each report one study, with the
authors as the subject. Join the later ones with "Similarly,",
"Furthermore,", or "Echoing their work,". When more studies support the claim,
put them in one parenthetical string.

B9. **State scope in a short, plain paragraph.** Say what a construct or a
measure covers and what it leaves out. Use declarative sentences of 10 to 20
words, with no hedges and few citations.
Template: "[Construct] covers [what is inside]. [Construct] does not cover
[what is outside]. Our measure cannot show [limit]."

B10. **Point across sections inside a sentence.** He writes "as we discussed
previously", "which we describe in the following section", and "We elaborate
on this counterintuitive result in the "Discussion" section". Do not write a
transition paragraph in an empirical paper. The JM 2015 paper has one roadmap
paragraph at the end of its introduction, and the playbook marks it as
optional.

### C. Sentences

C1. **Follow his length profile.** Across a paper, the mean is 21 to 23 words
and the median is 20 to 21. About one sentence in eight has 10 words or fewer,
and about one in 20 has more than 40 words. The mean differs by section.
Introductions and theory sections have a mean of 22 to 28 words, because the
sentences carry citation strings. Results sections have a mean of 18 to 22
words, because verdicts and pointers are short. Method sections and
discussions have a mean of 21 to 24 words. Two to four sentences in 100
run past 45 words, and most of them are argument sentences with a "because"
clause or a citation string. His coauthored papers have longer sentences, with
means of 23 to 27 words. Do not use them as the target.

C2. **Use a sentence of 10 words or fewer only for a claim that opens a
paragraph, a verdict on a hypothesis, a lead-in, a pointer, or a flat
definition.** Do not write three short sentences in a row. In an introduction,
write one short sentence in each paragraph that states a gap or a count.
Examples: "However, debt has its costs as well." (JM 2015) "Thus, H1c is fully
supported." (JMR 2020)

C3. **Vary the way sentences start.** Between one sentence in three and one in
five starts with a connective or an ordinal and a comma. About one in ten
starts with "We". The rest start with the subject or with one of the fronted
elements in rule C4.

C4. **Front the purpose, the reason, the concession, the condition, or the
precedent when it frames the main clause.** The purpose form, "To [purpose],
we", is the most common. The other forms are "Because [reason],", "Although
[concession],", "When [condition],", "Following [source],", and "Consistent
with [source],". The forms "Using [data],", "Estimating [model],", and "By
[action]," appear once or twice in a paper. Use each fronted form at most once
in a paragraph, and do
not open two paragraphs in a row with the same form. When the research
questions end with a "To" sentence, open the empirical preview with
"Empirically,".
Examples: "Estimating a system of five equations, we find that higher leverage
leads to reductions in advertising, which in turn results in lower customer
satisfaction." (JM 2015) "Because customers are allowed to be indifferent,
customer satisfaction and dissatisfaction measures are not merely the
mathematical inverse of each other." (JMR 2020)

C5. **Build a sentence from one main clause and at most two more clauses.**
Extend the main clause with "because" in the middle of the sentence or with a
", which" clause. The forms "which in turn", "thereby" with an "-ing" verb,
and a trailing "-ing" phrase are occasional, at one to three uses each in a
published paper. A trailing "-ing" phrase states a consequence or the reading
of a number, e.g., "suggesting that", "indicating that", and "leading to". Use
at most one per sentence and about one per paragraph, and do not use one to
claim importance. Count as one clause each: a "because", "when", or "although"
clause, a ", which" clause, and a trailing "-ing" phrase. Do not count the
"that" clause after "we find", "we argue", or "H1 posits".
Example: "The issuance of equity reduces financial leverage, thereby
increasing the firm's financial flexibility and enabling it to pursue a more
aggressive marketing strategy." (JM 2015)

C6. **A series of three parallel items is normal.** Each item may carry its
own citation.

C7. **State a contrast in one sentence with "Whereas", "while", or
"Although", or in two sentences with "However," or "In contrast,".**
Example: "Whereas long investors seek positive stock returns by buying a stock
at a low price and selling it at a higher price, short sellers bet on stock
price declines." (JMR 2020)

C8. **Use the same sentence frame for parallel ideas.** Hypotheses of one
family, conditions of one test, and definitions of sibling constructs repeat
the frame and change only the terms.
Example: "H2a: The association between unexpected increase (decrease) in
customer satisfaction and unexpected decrease (increase) in short interest is
weaker for firms operating in industries with higher competitive intensity."
(JMR 2020) H2b repeats the frame and changes "satisfaction" to
"dissatisfaction" and the directions.

C9. **Use paired alternatives in parentheses, as in "higher (lower)", only
when both directions are meant.** The JMR 2020 paper uses the form often, and
the current manuscript uses it once.

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
"This is". The current manuscript follows the rule in 15 of 16 cases. His
published papers often write "This suggests" and "This is", so do not take
those sentences as models.

C13. **Ask questions as numbered research questions in the introduction.** A
manuscript has no rhetorical questions, and he does not ask a question and
then answer it. One direct question may state a topic for future research in
the limitations.

C14. **Define a term inside the sentence that introduces it.** Use an
appositive after a comma, "is defined as", or a short gloss in parentheses.

C15. **Introduce an example with "For example," at the start of a sentence,
with "such as" inside a sentence, or with "e.g.," inside parentheses.**

C16. **End the sentence on the new information.** The last words name the
outcome, the number, or the construct that the next sentence picks up. The
first example under rule C4 ends on the outcome. Do not end a sentence on a
phrase such as "in our sample" or "as we show next" when the outcome can go
last.

C17. **Do not write fragments, one-word sentences, or exclamations, and do not
start a sentence with "And", "But", or "So" in a manuscript.**

### D. Word choice

D1. **Use one term for each construct, and repeat it.** Choose the label once,
define it, and use the same label every time. When you declare an abbreviation
or a short label, use that exact form in every later mention. A construct may
have a level form and a change form, e.g., "complaint volume" and "an
unexpected increase in complaint volume". Define both, and do not write a
third form. A variable name for a model term may appear only in equations, in
table labels, and in the name of an interaction, after you define it. When the
user's notes use several labels for one outcome, use the label of the measure,
say once which construct it measures, and tell the user which labels you
merged. His published papers depart from the rule about one time in ten, e.g.,
"satisfaction" for "customer satisfaction". Do not copy the departures.

D2. **Name units and actors with his words.** Write "firm" and not "company"
in a manuscript. Write "customers" or "consumers" as the construct requires,
and keep the choice. Name the role that acts, e.g., managers, executives,
marketers, CMOs, CFOs, investors, and regulators.

D3. **Use "We argue that" for your own reasoning and "we expect" for a
prediction.** Use "we posit the following:" or "we expect the following:" to
lead into a formal hypothesis, and "[H2b] posits that" to restate it in the
results. State the thesis of the paper with "Our core argument is that".
Example: "Our core argument is that an increase in customer satisfaction
(dissatisfaction) lowers (elevates) short selling intensity in a firm's stock,
which affects abnormal stock returns." (JMR 2020)

D4. **Use plain verbs for procedures.** After "we", write use, estimate,
include, control for, model, measure, operationalize, obtain, collect, compute,
calculate, specify, and test. Write "use" and not "utilize" or "employ" in new
text. The JMR 2020 paper has "utilize" five times. Do not copy it.

D5. **Report results with "We find that" or with the construct as the
subject.** In the results section, the other forms are "The results support
H1a", "In support of H1,", and "is consistent with". Write "Our results show
that", "Our results indicate that", and "we demonstrate" only for summary
claims in the abstract, the introduction, and the discussion.

D6. **Report other researchers with neutral verbs in the present tense.** Use
find, show, report, argue, document, note, demonstrate, suggest, and propose.
A theory suggests, posits, or explains.

D7. **Choose the word for a relation by its status.** Use "association" for a
relation that the paper hypothesizes or estimates (rule A5). Use "link" in a
heading and after two constructs that an en dash joins, e.g., "the customer
satisfaction–firm value link". Use "relationship" as the general word in the
theory. He also uses "moderates", "mediates", "mechanism", "channel",
"through", "more pronounced", "stronger", and "weaker".

D8. **Mark a conclusion with "Thus," or "Therefore,".** Use "Thus," for a
verdict on a hypothesis and for the last sentence of a contribution. For a
step in an argument and in the lead-in to a hypothesis, use "Therefore," in
new text, and keep "Thus," when the draft already uses it. The published
papers prefer "Thus,", and the current manuscript prefers "Therefore,". The
alternates are "Accordingly,", "Consequently,", "As such,", "In summary,",
"Overall,", and "Taken together,". Do not write "Hence", "In sum,", or "In
conclusion,".

D9. **Mark addition with "In addition,", "Furthermore,", "Similarly,", or
"Additionally,", and contrast with "However,", "In contrast,", "By contrast,",
or "Nonetheless,".** Use "Moreover," at most twice in a paper. "Yet" opens a
sentence that turns the argument, a few times in a paper.

D10. **Give a reason with "because".** His first-author papers do not use
"since" for cause outside direct quotations. The current manuscript also uses
"as" for a short reason.

D11. **Hedge with may, might, can, should, likely, could, potential, and
suggest.** Do not hedge with "perhaps", "arguably", "somewhat", or "seems".

D12. **The vocabulary of the field is fine.** He writes extant, posit,
antecedent, exacerbate, attenuate, and value relevance. Do not use the words
that Part 2 rule 1 lists, except as its note allows, and do not use pivotal,
realm, foster, underscore,
showcase, seamless, intricate, testament, harness, unlock, or navigate. None
of the words from "pivotal" to "navigate" is in his first-author papers, and
"delve", "tapestry", and "landscape" are not in them either. Write "use",
"exploit", or
"capitalize on" and not "leverage" as a verb, and never use "leverage" as a
verb in a paper in which leverage is a construct.

D13. **Define each technical term and each abbreviation at first use.** Give
the full term and then the abbreviation in parentheses. Abbreviate a term only
when it appears five times or more, or when it is the standard name of a data
source or a method.

D14. **Keep Latin abbreviations inside parentheses.** Write "e.g.," and
"i.e.," only in parentheses, with a comma after each, and write "for example"
and "that is" in the running sentence. Do not close a list with "etc." or "and
so on". Close the list with its last item.

D15. **Vary only the label for earlier work.** He rotates "previous research",
"prior research", "previous studies", "prior literature", and "extant
research". The rotation is the one exception to rule D1.

D16. **State a limit with a plain negative.** Write "does not", "cannot", and
"no association".

### E. Punctuation and formatting in manuscripts

The longer rules for dashes, colons, semicolons, and parentheses, with
examples, are in the punctuation part of
`references/reporting-and-phrases.md`. The heading rules are in the last part
of `references/manuscript-playbook.md`. The target journal decides the points
that the reference files mark as journal style.

E1. **Use the serial comma.**

E2. **Use a closed em dash only to set off a definition or a list of up to
about ten words inside a sentence.** Use at most one em dash, or one pair of
em dashes, per 1,000 words. Do not use a dash for a pause or for emphasis.

E3. **Use an en dash for a relation between two constructs and for a range in
a manuscript for an American Marketing Association journal.** Examples are
"the customer satisfaction–firm value link" and "1994–2010". Follow the target
journal elsewhere.

E4. **Use a colon before a list, numbered research questions, a formal
hypothesis, or an equation.** The list may be a short list after a counted
noun. Do not join two clauses with a colon.
Example: "The empirical model has three equations: abnormal returns, short
interest, and selection." (JMR 2020)

E5. **Use semicolons between citations and between list items that contain
commas.** A semicolon may join two parallel clauses now and then.

E6. **Use parentheses for citations, statistics, abbreviations, examples that
start with "e.g.,", and short glosses.**

E7. **Do not use bullet lists in the body of a manuscript.** Use an inline
list numbered (1), (2), and (3), a sequence of ordinal sentences, or a table.
The one exception is the research questions, which are set off as a numbered
list.

E8. **Use quotation marks for a direct quotation, with its page number, and
for a term in a special sense on its first use.**

E9. **Use italics for statistical symbols and for run-in headings.** The
current manuscript also sets a newly named mechanism in italics on its first
use. Do not use bold in body text.

E10. **Use title case for first-level and second-level headings, and run-in
headings for the third level, in a manuscript for an American Marketing
Association journal.** Some journals print sentence-case or numbered headings,
so follow the target journal. Word every heading as a noun phrase.

### F. Evidence and numbers

F1. **Support every claim about prior work with a citation.** Most claims
carry one citation. A claim about a set of related studies gets a string of
two to five. When the citations are missing, write one placeholder that states
the
count and the topic, e.g., [citations: two to five studies on customer metrics
and stock returns].

F2. **Give exact numbers with their units.** State the sample as the number
of observations, the number of firms, and the period. Mark a rounded number
with "approximately", "more than", or "almost". In a manuscript, do not write
"around" or "about" with a statistic.

F3. **Keep a number and its comparison in one sentence.** A mean is followed
by the benchmark, and an effect is followed by what it is compared with. When
the comparison is missing, write a placeholder, e.g., [sample mean of the loan
spread].
Example: "The average short interest for our sample is 5.2%, similar to the
4.9% average in Rapach, Ringgenberg, and Zhou (2016)." (JMR 2020)

F4. **Report statistics in his formats.** A coefficient and its p-value go in
parentheses right after the claim. See the statistics part of the reporting
file.

F5. **Translate the headline effect into a magnitude that a manager can
read.** Give the translation in the abstract, in the preview of findings in
the introduction, and in the discussion, in the same sentence frame. Keep the
results section in the units of the model. When the user gives no standard
deviation and no unit for the variable, write [magnitude of the headline
effect].

F6. **Use a quotation from a named practitioner as evidence for a claim about
practice.** The JMR 2020 paper quotes interviews with industry experts in the
theory section. Introduce the speaker with name and role, and set a long
quotation as a block. Use only quotations that the user supplies.

### G. Manuscript structure

Read the part of `references/manuscript-playbook.md` for the section before
you draft it. The rules below are a summary.

G1. **Title.** Write a short phrase, a colon, and a literal subtitle that
names the constructs.

G2. **Abstract.** Write one paragraph of 150 to 180 words in the present
tense, in one of the two sentence orders that the playbook gives.

G3. **Introduction.** Write seven paragraphs in the following order: the
standing of the topic, what prior research shows, the gap, the counted reasons
or the counted aspects of the study, the research questions, the empirical
preview with sample facts and findings, and the counted contributions. The
introduction takes a tenth to an eighth of the body text. When the
introduction follows the aspects of the study, each aspect has its own
paragraph, and the paragraphs for the reasons and the research questions drop
out.

G4. **Theory.** Give each paragraph one claim, evidence from cited studies,
and a concrete example, and mark the step to the paper's own argument with a
first-person sentence.

G5. **Hypotheses.** Build a sequence of linked steps with hedged verbs and the
construct as the subject, resolve the opposing argument, add a short lead-in,
and state each hypothesis in one declarative sentence with associational
wording.

G6. **Method.** Cover the data, the measures, the model, and identification.
Every choice carries a precedent or a reason in the sentence that introduces
it.

G7. **Results.** For each test, restate the hypothesis, show the estimate, and
give the verdict. Give one combined verdict for a group of tests. Name an
unsupported or unexpected result as such.

G8. **Discussion.** Cover the theoretical implications, the managerial
implications for named roles, and the limitations paired with future research.
His empirical papers have no separate conclusion.

G9. **Budget.** Give the theory and the hypotheses 28% to 35% of the body
text, the method 23% to 28%, the results 13% to 17%, and the discussion 14% to
18%.

### H. Practitioner register

Section H comes from his two coauthored Harvard Business Review articles.
Magazine editors changed the wording, the punctuation, and the headings of
those articles, so section H keeps only what the authors chose: the structure,
the evidence, and the way of giving advice. For wording, punctuation, and
formatting, apply Part 2.

H1. **Open on the manager's situation.** Start with a current trend and the
risk that it carries. Do not open with the literature or with a research gap.
When the user gives no trend, open on the decision that the manager faces, and
add [current trend with source] to the list of placeholders.

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
survey shows" and "Our data suggest". For an estimate from observational data,
write "was followed by", "went along with", or "was linked to", and do not
write "caused" or "led to".

H5. **State each finding as a plain number with its comparison.** Use a count,
a percentage, or a group mean, and pair it with its contrast: perceived
against actual, before against after, or one group against another. Do not
report a p-value, a coefficient, a test statistic, or a model name, and do not
write "standard deviation". Convert a statistical unit into an everyday unit
when the conversion is arithmetic, e.g., write "about 0.06 percentage points"
for 6.2 basis points. Describe a one-standard-deviation change in words, e.g.,
"a typical unexpected increase in complaints", and write [size of a typical
increase] when the user does not give its size. When the comparison is
missing, write [comparison].
Example: "From 1994 to 2017, the average partisan gap increased from 15 points
to 36 points." (HBR, Partisanship)

H6. **Follow each finding with a named company and one dated action or one
number.** Use only companies and actions that the user supplies. When the user
supplies none, write one placeholder after the main finding, [company example:
name, date, and action].

H7. **Give each construct an everyday label, and define it by what was
observed.** Keep the labels fixed once you define them. When the user gives no
definition, write [plain definition of the term] at its first use.

H8. **Name each source in the sentence.** The articles have no parenthetical
citations and no footnotes. When the user names no source for a claim about
prior work, leave the claim out.
Example: "A 2023 review of 245 academic papers found that firms that
prioritize customer satisfaction perform better across a wide variety of
metrics, including sales, profits, cash flows, stock price, and more." (HBR,
Alignment)
The example has "firms". Write "companies" in new text.

H9. **Organize advice as a counted set of steps.** Give each step a subhead
that starts with a verb. In a piece of under 300 words, give the steps as
sentences that start with "First," and "Second,", without subheads. In the
running text, state the advice about a third-person subject with "must",
"should", or "cannot". Use "you" only for a direct instruction.
Example: "Leaders cannot simply announce a strategy and assume it has
permeated the rest of the organization." (HBR, Alignment)

H10. **Hedge only at the step from data to advice.** Use "suggests", "likely",
"may", and "might". A mechanism that the study does not test is also hedged,
with "may".
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
   allowed in its statistical sense, as in "robustness checks". Do not use
   "leverage" as a verb (rule D12).

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
   In manuscripts: the rule holds as an instruction (rule A4). His published
   papers contain intensifiers such as "very" and "Importantly,", so do not
   take them as a model. When he writes "important", the same sentence or the
   next one gives the reason.

4. **Use consistent terminology and constrain your vocabulary.**
   Before: Upload the document. The file is parsed, and the record is saved.
   After: Upload the document. The document is parsed and saved.
   In manuscripts: the rule holds and is stricter (rule D1). The one licensed
   exception is the label for earlier work (rule D15). His published papers
   depart from the rule about one time in ten, and the departures are not
   models.

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
   short phrase before the colon (rule G1). The JM 2015 paper has one catchy
   phrase in its body, "a double whammy". Do not copy it.

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
   After: First, the authors sorted the features into groups themselves, based
   on
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
    In manuscripts: the rule holds. End the paragraph on a sentence that does
    a job (rule B4).

11. **Never write three or more clauses in one sentence, or three or more
    example sentences in a row.** In ordinary prose, a sentence may have one or
    two related clauses. Do not pack three or more clauses into one prose
    sentence. If you need that many points, use a numbered First / Second /
    Third
    sequence under rule 9, or short bullet points when you are writing a
    brief. If list points are examples and you want to inline them, introduce
    with "e.g.". Also do not give three or more example sentences back to back
    to support the same point.
    Before: The parser reads the file, the validator checks the fields, and the
    writer saves the record.
    After: The parser reads the file, and the validator checks the fields. The
    writer then saves the record.
    In manuscripts: a sentence may hold a series of three parallel items, and
    each item may carry its own citation (rule C6). Two or three evidence
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
    In manuscripts: follow his length profile (rule C1). Use a short sentence
    only for the jobs that rule C2 lists.

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

15. **No dashes or middle dots.** Do not use em dashes or en dashes, including
    in
    number ranges. Join clauses with a period or "and", and write ranges with
    "to". Do not use the middle dot (·) as a separator; use a comma, "and", or
    separate lines instead.
    Before: The build is fast — it finishes in 10 to 20 seconds.
    After: The build is fast. It finishes in 10 to 20 seconds.
    In manuscripts: use an en dash for a relation between two constructs and
    for a range when the target journal does (rule E3). A closed em dash may
    set off a definition or a list of up to about ten words, with at most one
    em dash, or one pair of em dashes, per 1,000 words (rule E2). Do not use a
    dash for a pause or for emphasis.

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
    In manuscripts: the rule holds for new text. A colon also introduces
    numbered research questions, a formal hypothesis, an equation, and a short
    list after a counted noun (rule E4). The JM 2015 paper joins a claim to
    its elaboration with a colon four times, which is the earlier practice.

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
    numbered list, a sequence of ordinal sentences, or a table. The research
    questions may be set off as a numbered list (rule E7).

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
    firm (rule A7). The stock phrases in his papers are "shed light on", "in
    light of", "a stream of literature", "in a similar vein", and "lend
    support to". Use at most one of them per 2,000 words, and no other figure
    of speech.

22. **Never use negative parallelism of the form "not just X, it is Y" or
    "not only X, but Y".** State what the thing is. A plain refusal or
    correction is fine, including a short quote of a customer's hype phrase
    when you replace it with a concrete fact.
    Before: It is not just a parser, it is a full toolchain.
    After: It is a parser and a formatter.
    Before: We do not describe the API as "enterprise-grade robust," because
    that phrase can mean different things.
    After: The API has a 99.9% monthly uptime SLO.
    In manuscripts: the additive form "not only X but also Y" is allowed two
    or three times in a paper, for a dual effect, a dual contribution, or a
    dual benefit. The reframing form "it is not X, it is Y" stays banned.

23. **Do not stack rhetorical questions.** AI writing often asks two or three
    rhetorical questions in a row to sound thoughtful. Don't do this. Just state
    the problem directly.
    Before: Does the tool keep the writer's voice? Does it make the argument
    stronger or weaker?
    After: We do not yet know whether the tool keeps the writer's voice, or
    whether it makes the argument stronger or weaker.
    In manuscripts: the rule holds. Numbered research questions are not
    rhetorical and are fine, and one direct question may state a topic for
    future research (rule C13).

24. **Do not use vague demonstrative pronouns.** Do not use "This", "That",
    "These", or "Those", especially do not start a sentence with a demonstrative
    pronoun, and never begin a paragraph with a sentence that contains a
    demonstrative anywhere in it.
    Before: That context carries into the next turn.
    After: The agent applies the rules you saved on the next turn.
    In manuscripts: "This", "These", and "Such" may start a sentence or a
    paragraph when a noun follows at once, e.g., "This finding suggests" and
    "These results support H3" (rule C12). He uses the form 10 to 20 times in
    a paper. Do not leave the demonstrative bare, as in "This suggests". His
    published papers have some bare ones, and the instruction overrides them.

25. **Do not open with a count of things.** Never start by announcing how many
    points are coming, e.g., "Two cautions." or "Three things to keep in mind."
    State the first point directly. If you absolutely must present many things,
    use a bullet list instead.
    Before: Two cautions. First, the section can drift out of date. Second,
    it can balloon if every item gets a sentence.
    After: The section can drift out of date, because it duplicates facts
    that live elsewhere. It can also balloon if every item gets a sentence.
    In manuscripts: announce the count, and then list the items with ordinals,
    e.g., "This gap is surprising for three reasons." (rule B5). In
    practitioner writing, a counted set of steps is fine (rule H9).

## Part 3. Where the author's style overrides plain writing

The table lists the plain-writing rules that change outside the working
register. A rule that is not in the table applies in all three registers, with
the additions that its note gives.

| Rule | Working register | Manuscript register | Practitioner register |
|---|---|---|---|
| 1. Simple words | Applies | Field vocabulary allowed (D12) | Applies |
| 2. No jargon | Applies | Technical terms allowed when defined (D13) | Everyday labels (H7) |
| 5. Contractions | Allowed | Not allowed (A2) | Allowed, a few |
| 6. Hyphenated adjectives | Applies | Compounds from constructs and numbers allowed | Applies |
| 7. Boring wording | Applies | Applies, except the main title (G1) | Applies |
| 8. Complete sentences | Applies | A semicolon may join two parallel clauses (E5) | Applies |
| 10. Topic sentence and support | Applies | Add a closing sentence that does a job (B4) | Applies, without "Moreover," (H12) |
| 11. Three clauses, three examples | Applies | Series of three and evidence sentences in a row allowed (C5, C6, B8) | Applies |
| 12. Long sentences | Applies | His length profile (C1, C2) | 20 to 25 words (H11) |
| 14. Context in chat | Applies | Does not apply | Does not apply |
| 15. No dashes | Applies | En dash allowed, em dash rare (E2, E3) | Applies |
| 16. Colons | Applies | Also before research questions, a hypothesis, and an equation (E4) | Also before a label and value list (H15) |
| 17. Straight quotes | Applies | Quotes of the document format | Applies |
| 18. Sentence-case headings | Applies | Title case and run-in headings, or the journal's format (E10) | Subheads that start with a verb (H9) |
| 19. Lists | Applies | No bullet lists in the body (E7) | Short label and value lists (H15) |
| 20. Fake agency | Applies | Constructs, results, tables, and studies may be the subject of a factual verb (note to rule 20) | Applies |
| 21. Analogies | Applies | Applies, with a stock phrase at most once per 2,000 words | Applies |
| 22. Negative parallelism | Applies | "not only X but also Y" allowed, two or three times in a paper | Applies |
| 23. Rhetorical questions | Applies | Numbered research questions, and one direct question for future research (C13) | One question at a time (H13) |
| 24. Demonstratives | Applies | Allowed with a noun (C12) | Allowed with a noun |
| 25. Count of things | Applies | Announce the count (B5) | Counted steps allowed (H9) |

## Part 4. The deslopify command

When the user says `/malshe-plain-writing deslopify`, rewrite the previous
agent response, or the text after the command, for a sharp CEO or technical
reader who has no project context. Return only the rewrite. When the rewrite
has placeholders, list them after it.

Start with the main conclusion, then cover the background, how it works, and
present all information logically and sequentially. Include technical details
the reader needs (standardize on existing well-known terminology, not new
terminology), and define unfamiliar terms.

Follow the rules of the working register. When the text is a passage from a
manuscript, follow the rules of the manuscript register.

## Part 5. Check before you return the text

For every register:

1. Every fact, number, citation, and quotation comes from the user or from a
   source that you read. Each gap is a placeholder in square brackets, and the
   placeholders are listed after the text.
2. Each construct has one label, and the label is the same everywhere.
3. No sentence uses a word that Part 2 rules 1 and 3 ban. In a manuscript, the
   uses that the notes to those rules allow are fine, e.g., "robustness checks"
   and "leverage" as a noun.
4. No analogy, slogan, or stacked question is in the text.

For a manuscript:

5. The text has no contraction, no "I", no "you", and no exclamation mark.
6. In a text of 500 words or more, the mean sentence length is inside the
   range that rule C1 gives for the section, with the tolerance that the start of
   Part 1 gives. In any text of 300 words or more, at least one sentence has 10
   words or fewer, and no three short sentences stand in a row.
7. Each paragraph opens with its claim, its action, or a definition, and ends
   on a sentence that does a job.
8. Every demonstrative carries a noun.
9. Research questions, hypotheses, results, robustness checks, and
   contribution statements use associational wording when the data are
   observational.
10. Each list of reasons, steps, contributions, checks, or limitations has an
    announcing sentence and ordinals.
11. Statistics, numbers, citations, and cross-references follow
    `references/reporting-and-phrases.md` or the style of the target journal.
12. The text has at most one em dash, or one pair of em dashes, per 1,000
    words, and no colon joins two clauses.
13. Each technical term and each abbreviation is defined at first use. Each
    claim about prior work has a citation or a placeholder.
14. No sentence has a word that rules A4, D4, D8, D11, D12, or D14 ban, and no
    sentence has "since" for cause.

For practitioner writing:

15. The first paragraph gives the manager's situation and the main finding.
16. No p-value, coefficient, test statistic, model name, parenthetical
    citation, or "standard deviation" is in the text.
17. Each finding has a number in an everyday unit and a comparison.
18. Each company, source, and quotation comes from the user.
19. Each piece of advice follows from a finding that the text reports, and
    the text ends on the advice.

For the working register:

20. All 25 rules of Part 2 hold as written, with no dashes, no bare
    demonstratives, and no opening count.
