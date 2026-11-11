# malshe-plain-writing

A writing skill for Claude Code and Codex. It makes the agent write and edit
prose the way Ashwin Malshe writes, and it applies the plain-writing rules
wherever his own style is silent.

The rules in Part 1 of `SKILL.md` were learned from his own writing: two
first-author papers (Journal of Marketing 2015 and Journal of Marketing
Research 2020), a current working manuscript, five coauthored journal
articles, and two Harvard Business Review articles. Part 2 of `SKILL.md`
repeats all 25 rules of the plain-writing skill by Shreya Shankar and says how
each one applies to his manuscripts.

His style is the primary source, and plain writing is the secondary source.

## What the skill covers

The skill treats manuscripts, practitioner writing, and working text
differently.

- Manuscripts: journal articles, working papers, web appendices, conference
  abstracts, grant text, and responses to reviewers. His own style governs.
- Practitioner writing: articles for managers, executive summaries, and posts
  about research for a business audience. The structure and the evidence
  follow his Harvard Business Review articles, and the wording and the
  formatting follow the plain-writing rules.
- Working text: chat replies, emails, reports, READMEs, slides, documentation,
  commit messages, and PR descriptions. The 25 plain-writing rules govern in
  full.

The skill also keeps the `deslopify` command of the plain-writing skill.

## Files

```
skills/malshe-plain-writing/
  SKILL.md                              the rules
  references/manuscript-playbook.md     steps and sentence patterns for each
                                        section of an empirical paper
  references/reporting-and-phrases.md   formats for statistics, numbers,
                                        citations, and punctuation, and a list
                                        of recurring phrases
  references/other-genres.md            review articles, methodological
                                        commentaries, and responses to
                                        reviewers
  references/plain-writing-original.md  the plain-writing skill as published
  agents/openai.yaml                    display name and default prompt for
                                        Codex
.claude-plugin/                         plugin and marketplace files for
                                        Claude Code
.codex-plugin/ and .agents/plugins/     plugin and marketplace files for Codex
```

`SKILL.md` has about 1,180 lines. The usual advice is to keep the file under
500 lines. The file is longer on purpose, because it holds every rule of both
sources. The detail that only a manuscript needs is in the reference files,
and the agent reads those files when it drafts a manuscript section.

## Install in Claude Code

The repository is private, so every method below needs Git access to it on
your machine, e.g., through `gh auth login` or an SSH key.

### Method 1: personal skill (recommended)

A personal skill works in all your projects, and you call it with the short
name `/malshe-plain-writing`.

```bash
git clone https://github.com/ashgreat/malshe-plain-writing.git
```

```bash
mkdir -p ~/.claude/skills
```

```bash
cp -R malshe-plain-writing/skills/malshe-plain-writing ~/.claude/skills/
```

To receive updates with `git pull`, link the folder and do not copy it:

```bash
ln -s "$(pwd)/malshe-plain-writing/skills/malshe-plain-writing" ~/.claude/skills/malshe-plain-writing
```

Claude Code picks up a new or changed skill in a running session. If
`~/.claude/skills` did not exist when the session started, run
`/reload-skills` once.

### Method 2: project skill

A project skill works only in one repository, and everyone who clones the
repository gets it. Run the commands from the root of that repository.

```bash
mkdir -p .claude/skills
```

```bash
cp -R /path/to/malshe-plain-writing/skills/malshe-plain-writing .claude/skills/
```

Commit the `.claude/skills/malshe-plain-writing` folder.

### Method 3: plugin

The repository is also a plugin marketplace with one plugin. Inside a Claude
Code session, run:

```
/plugin marketplace add ashgreat/malshe-plain-writing
```

```
/plugin install malshe-plain-writing@malshe-plain-writing
```

Run the same steps from a terminal:

```bash
claude plugin marketplace add ashgreat/malshe-plain-writing
```

```bash
claude plugin install malshe-plain-writing@malshe-plain-writing
```

A skill from a plugin has a longer name. Call it with
`/malshe-plain-writing:malshe-plain-writing`.

Update the plugin with the commands below.

```bash
claude plugin marketplace update malshe-plain-writing
```

```bash
claude plugin update malshe-plain-writing@malshe-plain-writing
```

Remove the plugin with the commands below.

```bash
claude plugin uninstall malshe-plain-writing@malshe-plain-writing
```

```bash
claude plugin marketplace remove malshe-plain-writing
```

The install was tested with Claude Code 2.1.322.

### Method 4: the skills command line tool

The `skills` tool installs a skill folder into the right place for each agent.
It needs Node.js 22.20 or later.

```bash
npx skills add ashgreat/malshe-plain-writing --skill malshe-plain-writing -g -a claude-code
```

The `-g` flag installs for your user account, in `~/.claude/skills/`. Leave it
out to install into the current project.

### Claude desktop app and claude.ai

Upload the skill as a zip file. The skill folder must be the top level of the
archive.

```bash
cd malshe-plain-writing/skills
```

```bash
zip -r malshe-plain-writing.zip malshe-plain-writing/
```

Then upload the zip file and turn the skill on under Customize > Skills.

### Use it in Claude Code

- Call it directly: `/malshe-plain-writing revise the introduction in
  manuscript.docx`.
- Ask in plain words: "Write the results paragraph for H2 in my style." Claude
  loads the skill when the request matches its description.
- Rewrite the last reply for a reader with no context:
  `/malshe-plain-writing deslopify`.

To make Claude use the skill for all prose in a project, add one line to the
project's `CLAUDE.md`, or to `~/.claude/CLAUDE.md` for all projects:

```
Use the malshe-plain-writing skill for all prose that you write or edit.
```

Claude reads `CLAUDE.md` as context. The line asks Claude to use the skill by
default, and Claude may still decide not to use it.

## Install in Codex

### Method 1: user skill (recommended)

Codex reads user skills from `~/.agents/skills`.

```bash
git clone https://github.com/ashgreat/malshe-plain-writing.git
```

```bash
mkdir -p ~/.agents/skills
```

```bash
cp -R malshe-plain-writing/skills/malshe-plain-writing ~/.agents/skills/
```

Codex follows a linked folder, so you can link the folder to receive updates
with `git pull`:

```bash
ln -s "$(pwd)/malshe-plain-writing/skills/malshe-plain-writing" ~/.agents/skills/malshe-plain-writing
```

The skill is available on your next message. If the skill does not appear when
you type `$`, start a new Codex session.

Codex also still reads the older folder `~/.codex/skills`.

### Method 2: repository skill

Codex reads `.agents/skills` in every folder from the root of the repository
down to the working folder. Run the commands from the root of the repository.

```bash
mkdir -p .agents/skills
```

```bash
cp -R /path/to/malshe-plain-writing/skills/malshe-plain-writing .agents/skills/
```

### Method 3: the built-in skill installer

Codex ships with a skill named `skill-installer`. In a Codex session, write:

```
$skill-installer install the skill at https://github.com/ashgreat/malshe-plain-writing/tree/main/skills/malshe-plain-writing
```

Codex asks for approval to use the network. The installer puts the skill in
`~/.codex/skills/malshe-plain-writing`. For a private repository, the installer
uses your Git credentials or the `GITHUB_TOKEN` variable. The installer stops
if the destination folder exists, so delete the old folder before you update.

### Method 4: plugin

```bash
codex plugin marketplace add ashgreat/malshe-plain-writing
```

```bash
codex plugin add malshe-plain-writing@malshe-plain-writing
```

A skill from a plugin has a longer name. Mention it as
`$malshe-plain-writing:malshe-plain-writing`.

Update the plugin with the commands below.

```bash
codex plugin marketplace upgrade malshe-plain-writing
```

Remove the plugin with the commands below.

```bash
codex plugin remove malshe-plain-writing@malshe-plain-writing
```

```bash
codex plugin marketplace remove malshe-plain-writing
```

The install was tested with Codex CLI 0.167.1. Codex copies the whole
repository into its plugin cache, so keep large files out of the repository.

### Method 5: the skills command line tool

```bash
npx skills add ashgreat/malshe-plain-writing --skill malshe-plain-writing -g -a codex
```

The `-g` flag installs in `~/.agents/skills/`. To install for both agents in
one step, pass both names:

```bash
npx skills add ashgreat/malshe-plain-writing --skill malshe-plain-writing -g -a claude-code -a codex
```

### Use it in Codex

- Mention the skill with a dollar sign anywhere in the message:
  `$malshe-plain-writing tighten the discussion section in manuscript.docx`.
- Type `/skills` to list the skills and to turn a skill on or off.
- Ask in plain words. Codex chooses the skill when the request matches its
  description.

To make Codex use the skill for all prose, add one line to `~/.codex/AGENTS.md`
for all projects, or to `AGENTS.md` at the root of one repository:

```
When you write or edit prose, use the malshe-plain-writing skill.
```

To turn the skill off without removing it, add the following lines to
`~/.codex/config.toml`:

```toml
[[skills.config]]
name = "malshe-plain-writing"
enabled = false
```

## How the rules were derived

- Each document was converted to text. A script computed the sentence and
  paragraph statistics and counted words, phrases, and punctuation marks.
- The two first-author papers, the current manuscript, and one coauthored
  paper were each read for structure and for the steps of the argument.
- Independent checkers then tested the draft rules. One recomputed every
  number and tested every "do not" rule against the two first-author papers.
  One tested the rules on four coauthored papers. One judged four pieces that
  a fresh writer produced with only the skill. The rules were corrected from
  their reports.
- The 181 examples in the skill that carry a source tag are verbatim quotes
  from the published papers and from the two Harvard Business Review articles,
  and a script checks them against the source text. The unpublished manuscript
  informed
  the rules. The skill takes short templates from it and does not quote its
  arguments or its findings.
- The install steps for Claude Code come from its current documentation. The
  install steps for Codex come from the Codex source code. Both plugin
  installs were run with the Claude Code and Codex command line tools.

The rules have limits.

- Every rule is an instruction for new text. His published papers do not
  follow every rule, and the skill says so where the difference is large.
- Journal copyeditors set some formats in the published papers, such as the
  leading zero, the en dash, and the citation format. The reference files mark
  those points as journal style, and the target journal decides them.
- Coauthors wrote part of every paper. The skill gives most weight to the two
  first-author papers and the current manuscript.
- His practice has changed since 2015. Where the papers differ, the skill
  follows the current practice and names the earlier one.
- The parts on review articles and commentaries each rest on one coauthored
  article.

## License and credits

The skill is released under the MIT License. See `LICENSE`.

The plain-writing rules in Part 2 of `SKILL.md` are by Shreya Shankar and are
used under the MIT License. The style rules in Part 1 and in the reference
files describe the writing of Ashwin Malshe.
