# Reporting formats and recurring phrases

Read the reporting file when you write results, methods, citations, or any
sentence that reports a number in an academic manuscript. It gives the formats
the author uses and the phrases that recur in his papers.

Quoted sentences carry a source tag: JM 2015 or JMR 2020. Patterns with slots
in square brackets are templates. Several formats come from journal house
style, and the file marks them with "Journal style". For those points, follow
the target journal. His accepted manuscript for the Journal of the Academy of
Marketing Science was not copyedited, so it shows what he and his coauthors
type themselves. The file calls it the JAMS manuscript.

## Statistics in running text

1. **Put the estimate and its p-value in parentheses right after the claim
   they support.** Add the table and the column to the first estimate in each
   paragraph. When you do not know them, write "Table [number], Column
   [number]". Name both variables each time you report an interaction. Use the
   coefficient symbol of the tables in the paper. The default is β.
   Examples: "We find that customer satisfaction has a positive impact on
   Tobin's q (b = .021, p ≤ .01; Table 3, Column 4)." (JM 2015) "The natural
   log of sales in Equation 4 is statistically significant (.348, p < .01),
   indicating that firms with higher sales have a higher probability of YouGov
   coverage." (JMR 2020)
   Template: "[X] is positively associated with [Y] (β = [value], p <
   [threshold]; Table [number], Column [number])."

2. **Report p-values as thresholds.** Write p < .01, p < .05, and p < .10, and
   p > .10 for a null result. The JM 2015 paper prints "p ≤", which is the
   earlier practice. Do not print an exact p-value unless the user's tables
   report one.

3. **Leading zero. Journal style.** JM and JMR drop the leading zero before a
   decimal, e.g., ".47", "p < .05", and "r = –.31". His
   current manuscript does the same for coefficients, p-values, and confidence
   limits. The JAMS manuscript keeps the zero, e.g., "p < 0.05". Follow the
   target journal. Without a target, drop the zero.

4. **Use the following words for significance.** Write "significant",
   "marginally significant" for a result between .05 and .10, and
   "statistically nonsignificant", "not significant", or "does not reach
   statistical significance" for a null result. Write "nonsignificant" and not
   "insignificant".

5. **State the sign and the significance together.**
   Examples: "The interaction of customer satisfaction and competition is
   significant and positive" (JMR 2020). "must be negative and significant"
   (JM 2015).

6. **Give a chi-square statistic with its degrees of freedom, and give t and r
   without them.**
   Templates: "(χ2([df]) = [value], p > .10)", "(t = [value], p < .05)", and
   "(r = [value], p < .01)".

7. **Report a confidence interval with its level and its method, and say
   whether it includes zero.**
   Template: "([estimate], 95% bootstrap CI = [[lower], [upper]])".
   Example of the method sentence: "Following Preacher and Hayes (2004), we
   draw 1,000 bootstrap samples with replacement to obtain the 95% confidence
   intervals for the indirect effect." (JMR 2020)

8. **Report model fit in one sentence and say what it suggests.**
   Example: "The R2 values range from .30 to .89, suggesting excellent model
   fit." (JM 2015)
   The word "excellent" is the earlier practice. Leave it out in new text, and
   say what the fit statistic shows.

9. **Report a product of coefficients by showing the product when the user
   gives both coefficients.** When the user gives only the indirect effect,
   report it in the format of rule 7, and do not write placeholders for the
   two coefficients.
   Template: "(β = [product] = [first coefficient] × [second coefficient])".

10. **Translate the headline effect into a magnitude.** Give the translation
    in the abstract, in the introduction, and in the discussion, and keep the
    results section in the units of the model. Use one of the templates below.
    "a one-standard-deviation increase in [X] from the average level results
    in a [n] point decrease in [Y], which is equivalent to an estimated loss of
    $[n] million in [metric] ([citation])".
    "a one-unit increase in [X] is associated with a [n] percentage point
    increase in [Y]".
    "[effect A] is [n] times larger than [effect B]".
    When the variables are in logs, use "a 1% change in [X] is associated with
    a [n]% change in [Y]".
    Example: "Specifically, a one-unit increase in customer satisfaction is
    associated with a .56 percentage point increase in abnormal returns, while
    a one-unit increase in customer dissatisfaction is associated with a 1.34
    percentage point decrease in abnormal returns." (JMR 2020)

11. **Say plainly what a specification test means.**
    Templates: "suggesting that the instruments are valid", "which further
    confirms that multicollinearity is not an issue in this analysis", and
    "indicating that [plain statement]".

12. **Test a difference between two effects, and report the test in
    parentheses after the comparison.** Give the test statistic and a
    threshold p-value.

13. **Statistical symbols.** In a Word file, set p, t, r, b, F, N, and n in
    italics. Do not italicize Greek letters, "CI", or numbers. Write a
    negative value with a minus sign and no space. In Markdown or plain text,
    write the symbols without markup unless the user asks for italics.

## Numbers

14. **Spell out one through nine when you count things, and use numerals from
    10 up.** He writes "five equations", "three robustness checks", and "two
    related questions", and he writes "171 firms", "17 years", and "23
    industries".

15. **Always use numerals with units, percentages, money, sample sizes, and
    statistics.** He writes "5%", "$26 million", "100 million shares", and
    "2 SDs".

16. **Use the percent sign, not the word.** He writes "80%" and "(20.58%)".

17. **Use a comma in numbers of four digits or more.** He writes "1,346
    firm-year observations" and "7,383 firm-quarter observations".

18. **Hyphenate a number phrase that modifies a noun.** He writes
    "one-standard-deviation increase", "one-unit increase", "17-year period",
    "one-year sales growth", "four-factor model", and "firm-quarter
    observations".

19. **Mark a rounded number with "approximately", "more than", or
    "almost".** The JM 2015 paper writes "approximately 80%". The JMR 2020
    paper writes "more than 1,800 U.S. brands" and "almost two decades". Do
    not write "around" or "about" with a statistic, and do not use a tilde.

20. **Give a period as a span of years.** In typeset articles the span has an
    en dash, e.g., "1994–2010". In running text he also writes "spanning 2007
    to 2017" and "from Q2 2007 to Q4 2017".

21. **Do not start a sentence with a numeral.** Reword the sentence or start
    with the unit of analysis.

## Citations

The citation format follows the target journal. The points below describe JM
and JMR style, which is also what he types in his own drafts.

22. **Use author and year with no comma between them.** "(Kurt and Hulland
    2013)".

23. **Order multiple citations alphabetically and separate them with
    semicolons.** "(Gupta 2009; Myers 1977; Srivastava, Shervani, and Fahey
    1998)".

24. **Name all authors for up to three, and use "et al." from four. Journal
    style.** "Anderson, Fornell, and Mazvancheryl (2004)" and "Fornell et al.
    2006". In his own drafts, a parenthetical citation of a three-author work
    may have "et al.".

25. **Put "e.g.," inside the parentheses when the citation is one example
    among many.** "(e.g., Kurt and Hulland 2013)". Do not write "e.g." outside
    parentheses. Outside parentheses, write "for example" or "such as".

26. **Point to a review with "for a review, see".** "(for a review, see
    Graham and Leary 2011)". He also writes "(see, e.g., [citation])" and
    "(cf. [citation])".

27. **Give the page for a direct quotation.** "Anderson and Sullivan (1993,
    p. 125) note that".

28. **Use a possessive for a named model or method.** "Carhart's (1997)
    four-factor model" and "Sobel's test".

29. **Support every claim about prior work with a citation.** About three
    parenthetical citations in four hold one source. A claim about a set of
    related studies gets a string of two to five.

30. **For a journal that uses APA style, switch the format and keep the
    habits.** His typeset JAMS and Elsevier articles have commas and
    ampersands, e.g., "(Angrist & Pischke, 2008)". The journal applies that
    form in production. Rules 23 and 25 to 29 still apply.

## Cross-references

31. **Capitalize "Table", "Figure", "Web Appendix", and hypothesis labels.**
    The capital in "Equation 4", "Column 2", "Model 1", and "Panel A" is
    journal style for JM and JMR. In the JAMS manuscript he types "equation
    (2)" and "column (4)".

32. **Cite an exhibit in one of the following forms.**
    "In Table 3, we report [content]."
    "Table 2 shows [content]."
    "[claim] (Table 3, Column 4)."
    "as shown in Table 8"
    "As Tables 4 and 5 show, [claim]."
    "(see Web Appendix Table W8)"

33. **Refer to equations by number and to sections by name.** "in Equation 2
    (Equation 3)" and "in the "Discussion" section".

## Abbreviations and terms

34. **Define an abbreviation at first use, in parentheses after the full
    term.** "research and development (R&D)", "American Customer Satisfaction
    Index (ACSI)", "chief marketing officers (CMOs)", and "seemingly unrelated
    regression (SUR)". Use the abbreviation from then on (rule D13 in
    SKILL.md).

35. **Spell out the term when it starts a sentence. Journal style.** JM
    prints "Research and development has been shown to" at the start of a
    sentence, after the abbreviation is defined.

36. **Introduce a method or a package with its citation.** "the conditional
    mixed process (CMP; Roodman 2011)".

37. **Put quotation marks around a term on first use when the term is used in
    a special sense.** He does so for "discipline", "option value", "real
    options", "underinvestment problem", "slack", and "information
    intermediary". Do not repeat the quotation marks on later uses.

38. **Keep one word per concept.** See rules D1 and D2 in SKILL.md.

39. **Name variables in equations with short capital labels and define them
    in the "where" sentence.** Examples are CS, ADV, LEV, SI, and COMP. When a
    variable name
    appears in running text, capitalize it, e.g., "Higher values of
    Competition".

40. **Write "dataset" as one word.** He types "dataset" in his own drafts.
    JM and JMR print "data set", which is journal style.

## Lists inside sentences

41. **Number the items of an inline list with (1), (2), and (3).** Use the
    form for conditions and for the parts of an argument. Research questions
    follow the introduction part of the playbook.
    Example: "In this section, we propose three potential moderators that can
    influence the leverage–customer satisfaction link: (1) service versus
    manufacturing firms, (2) competitive intensity in the industry, and (3)
    sales growth." (JM 2015)

42. **Use (a) and (b) for the parts of one hypothesis.**

## Punctuation in manuscripts

Rules E2 to E7 in SKILL.md are the short form of the rules below. Rules 13,
27, and 37 cover the symbols and the quotation marks of rules E8 and E9, and
the last part of the playbook covers the headings of rule E10.

43. **Em dash.** Use a closed em dash, with no spaces, to set off a definition
    or a list of up to about ten words inside a sentence. Use at most one em
    dash, or one pair of em dashes, per 1,000 words. His first-author papers
    have no dash for a pause or for emphasis. Two coauthored papers that
    another author led have a spaced en dash for a pause. Do not copy that.
    Example: "Second, the dependent variable in the selection equation is
    dichotomous, while the other two dependent variables—short interest and
    abnormal returns—are continuous." (JMR 2020)

44. **En dash. Journal style.** JM and JMR print a closed en dash for a
    relation between two constructs, for a range, and for a method named after
    two people. Examples are "the customer satisfaction–firm value link", "the
    marketing–finance interface", "1994–2010", "H2a–c", "Equations 1–3", and
    "the Durbin–Wu–Hausman test". In his own drafts he types a hyphen or a
    spaced en dash. Use the closed en dash for a JM or JMR manuscript, and
    follow the target journal elsewhere.

45. **Colon.** Use a colon before a numbered list, before a short list after
    a counted noun, before numbered research questions, before a formal
    hypothesis, and before an equation. The JM 2015 paper also joins a claim
    to its elaboration with a colon four times. The later papers do not. Do
    not join two clauses with a colon.

46. **Semicolon.** Use semicolons between citations, between the items of a
    list that have commas inside them, and now and then between two parallel
    clauses.
    Example of parallel clauses: "H3a proposes that the association of
    unexpected changes in customer satisfaction and short interest is more
    (less) negative for firms with lower (higher) capital intensity; H3b
    posits that the association of unexpected changes in customer
    dissatisfaction and short interest is more (less) positive for firms with
    lower (higher) capital intensity." (JMR 2020)

47. **Parentheses.** Use parentheses for abbreviations, for short lists of
    examples that start with "e.g.,", for statistics, for a short gloss, and
    for paired alternatives such as "higher (lower)".

48. **Slash.** Use a slash rarely, for a ratio or for a fixed pair, e.g.,
    "customer satisfaction/dissatisfaction".

49. **Do not use exclamation marks, ellipses for effect, bold for emphasis,
    or bullet lists in the body of a manuscript.**

## Recurring phrases

The phrases below recur in his papers. Use them where they fit. Do not use the
same phrase twice in one paragraph. The ordinals are the one exception.

### Stating what prior work has done

- "A large body of research in marketing has demonstrated that"
- "Previous research shows that" and "Previous research has shown that"
- "Extant research has demonstrated that"
- "Prior literature has suggested"
- "A stream of finance literature has argued that"
- "Research in finance has confirmed that"
- "Marketing scholars have argued that"
- "it is well documented in finance literature that"
- "Research shows that"
- "In a survey of [n] [respondents], [Authors] ([year]) find that"
- "Several studies have also examined"

### Stating the gap and the position of the paper

Use "has not been investigated" and "To the best of our knowledge," only when
the user confirms the claim.

- "Yet little research investigates"
- "research is unclear on"
- "is an open issue and has not been investigated"
- "most previous studies explore only"
- "prior studies have assumed"
- "To the best of our knowledge,"
- "We build on their study by arguing that"
- "In contrast to these studies, the current study uses"
- "this research fits with recent studies that investigate"

### Moving to the paper's own argument

- "We argue that"
- "we posit the following:" and "we expect the following:" before a formal
  hypothesis
- "we propose that"
- "we expect"
- "we do not anticipate"
- "Our core argument is that"
- "Our logic is that"
- "Along similar lines,"
- "In a similar vein,"
- "Correspondingly,"
- "Consistent with this logic,"
- "Following this discussion,"

### Agreement and disagreement with prior work

- "consistent with"
- "in line with"
- "In support of this notion,"
- "Our result substantiates previous research showing that"
- "Our results lend support to the findings of"
- "Our results are consistent with [Author] ([year]), who argues that"
- "Echoing their work,"
- "Contrary to expectations,"
- "in contrast to"

### Cause and consequence inside a sentence

- "because" in the middle of a sentence, and "Because" at the start
- ", which" with a verb
- "which in turn"
- "thereby"
- "leading to"
- "resulting in"
- "due to"
- "such that"
- "in that"

### Starting a sentence that concludes

- "Thus,"
- "Therefore,"
- "Accordingly,"
- "Consequently,"
- "As such,"
- "In summary,"
- "Overall,"
- "Taken together,"

### Starting a sentence that adds, contrasts, or narrows

- Adds: "In addition,", "Furthermore,", "Similarly,", "Additionally,", and
  "Finally," for the last item. Use "Moreover," at most twice in a paper.
- Contrasts: "However,", "In contrast,", "By contrast,", "Yet",
  "Nonetheless,", "Whereas", "Although", and "While". The JM 2015 paper uses
  "However," 23 times. The JMR 2020 paper uses it once and prefers "In
  contrast,".
- Narrows: "Specifically,", "For example,", "As an example,", and "Indeed,".
  "More generally," widens a claim.
- Orders: "First,", "Second,", "Third,", "Fourth,", "Finally,", and "Next,".

### Reporting findings

- "We find that"
- "We also find that"
- "In support of H1a and H1b,"
- "Consistent with this expectation, we find that"
- "However, in contrast to H2c, we find that"
- "contrary to our conjecture"
- "The results support H1a."
- "We find support for [H1] in that [finding]"
- "Therefore, we find partial support for [H1] in that"
- "more pronounced for"
- "economically significant"
- "We find that our results continue to hold."

### Limits and future work

- "Our findings are limited by"
- "Data limitations do not allow us to"
- "It is possible that"
- "A potential explanation for this puzzling result is that"
- "Although this is not the focus of our research,"
- "Future research should examine", "Future research could explore", and
  "Future studies should examine". The JM 2015 paper writes "Further
  research". The later papers write "Future research", which is the default.

### Words and phrases to leave out

- The following words are in none of his first-author papers: "delve",
  "tapestry", "landscape", "pivotal", "realm", "foster", "underscore",
  "showcase", "seamless", "intricate", "testament", "harness", "unlock", and
  "navigate".
- Do not write "insignificant" for a statistical result, "since" for cause,
  "Hence", "In sum,", "In conclusion,", "etc.", or "and so on".
- Do not use contractions, the first person singular, or exclamation marks in
  a manuscript.
- Do not write "Clearly,", "Importantly,", "Interestingly,", or
  "Reassuringly," at the start of a sentence. The published papers have a few
  of them.

## Changes in his wording over time

- **From "impact" to "association".** The JM 2015 paper writes "impact",
  "effect", and "link" for the main relations. The JMR 2020 paper and the
  current manuscript write "association" and "is associated with" for
  hypotheses and estimates. Follow the later practice (rule A5 in SKILL.md).
- **From past to present tense in methods.** The JM 2015 paper reports
  procedures in the past tense. The later papers use the present tense for the
  model and the measures.
- **From "Thus," to "Therefore,".** The published papers prefer "Thus,". The
  current manuscript prefers "Therefore,". See rule D8 in SKILL.md.
- **Fewer intensifiers.** "very", "highly", "extremely", and "Clearly," appear
  in the JM 2015 paper and almost never in the current manuscript. Leave them
  out.
- **Fewer bare demonstratives.** The published papers sometimes start a
  sentence with "This is" or "This suggests". The current manuscript attaches
  a noun in 15 of 16 cases, e.g., "This finding suggests". Attach the noun.
- **No priority claims.** The published papers write "we are among the first"
  and "our study is the first". The current manuscript makes no such claim.
