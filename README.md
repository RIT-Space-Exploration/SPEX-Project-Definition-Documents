# SPEX Standard - Project Definition Document
This is an RIT Space Exploration Standard defining guidelines for content and
formatting of project definition documents (PDDs).

This repository includes [the IEEE Conference Proceedings LaTeX formatting
template](https://www.ieee.org/conferences_events/conferences/publishing/templates.html)
(the SPEX internal standard), a sample document with style guidelines, and an
archive of reviewed and approved PDDs.

# What is a Project Definition Document?
The intent of a Project Definition Document (PDD) is to organize and document a
project idea and its objectives. In the ideal project life cycle, an idea
undergoes an initial research phase where an individual or a small team
develops the primary objectives and requirements. The PDD is a snapshot of the
known challenges, risks, and anticipated areas for research at the very start
of a project.

# How do I use this template?
This document is intended for a member of RIT Space Exploration to bring
forward an idea for a project to be conducted under the RIT SPEX banner.

## Write
1. Read this Readme in its entirety.
2. Read [the template PDD](COPY_THIS/SPEXpdd.pdf). This document is an example
   that also explains the intent behind writing a PDD.
3. Create a branch from `master` to start working on your own document.
```
git branch -d my-new-pdd
```
4. Copy the `COPY_THIS` directory, then gut the `.tex` file and replace its
   contents with your own ideas!
5. Use a LaTeX compiler to build a PDF from the `.tex` source file. To learn
   how to do this, [read our
   tutorial](https://github.com/RIT-Space-Exploration/SPEX-Standard-Proposal/wiki/Creating-a-PDD-from-the-Template).
6. When you're ready to have your PDD archived in the `master` branch, [create
   a Pull
   Request](https://github.com/RIT-Space-Exploration/SPEX-Project-Definition-Documents/compare)
   and ask others to review your work!

## Review
A PDD is reviewed by a panel of peers (any current or alumni member of SPEX) in
order to refine the document into the best that it can be. This usually
includes feedback regarding grammar, wording, or areas where the wording is
confusing. Reviewers may also request additional detail is needed to fully
explain the project idea or justifications for certain assumptions and
estimates made in the PDD. However, this peer review feedback loops should
_not_ be a review of the concept itself.

A [pull
request](https://github.com/RIT-Space-Exploration/SPEX-Project-Definition-Documents/compare)
is created for the new PDD to bring in the `.tex`, PDF and other supporting
files into the repository. GitHub’s pull request review interface allows
reviewers to make line-by-line comments on the document source file, and tracks
changes as the author addresses those comments. Once reviewers have "approved"
the pull request, the document is archived in the master branch of the
repository.

# FAQ
## Are all the sections in the template required?
Short answer: No.

Long answer: **The template was written as a functional example. Read it!** One
reason to write a PDD is to guide you to focus and refine your project concept.
Writing this document will hopefully guide you to think about how your project
will benefit SPEX in the future and and what major obstacles will be in your
way. While many sections of the template are specific to the template as a PDD
itself, I expect many of the same discussions to appear in your project as
well.

## Who should write a PDD?
Anyone is welcome to write about a project and present it using the PDD format.
If any SPEX member, university faculty member, or enthusisastic individual has
an idea for a SPEX project, writing a PDD is a great way to document their
concept, archive it, and perhaps present it to SPEX. The project "Champion" is
the primary author of the definition document and, similar to a Principal
Investigator, leads a preliminary team in developing a project idea. The
Champion is not necessarily the project manager for a project they propose.
Faculty recommendations, advice, and support for a project is not necessary but
is strongly encouraged. The Champion is the main point of contact for the PDD.
The project's Champion be handed off over time, but a project must always have
a Champion.

## Will my PDD be rejected?
PDDs are not approved nor rejected. PDDs are archived, so a definition document
that doesn't initially take off may be picked up by a new team somewhere down
the line.

## Is my definition document binding?
In the ideal project life cycle, a PDD defines a set of objectives or
deliverables which are fulfilled and discussed in a final report or paper. In
practice, this is not always the case but an PDD should guide a project such
that "feature creep" is avoided and good science is achieved.

## I wrote my PDD. Now what?
You need to submit it for review so we can make it the best that it can be.
This is also covered in the [the
tutorial](https://github.com/RIT-Space-Exploration/SPEX-Standard-Proposal/wiki/Creating-a-PDD-from-the-Template#make-a-new-pull-request-pr)
as well.

## Should I rewrite my PDD?
Probably not. The purpose of a design document is to capture and preserve the
essence of your original idea. In reality, ideas may grow and change over time.
If this is the case, it is better to use your old PDD as a template for a new
one than to go for a rewrite. On the other hand, it is acceptable to polish and
edit a PDD for the sake of clarity and concision, but usually this is done
before work has begun on that project. This question lies squarely in the
_spirit_ of a PDD, and is thus up to interpretation. Use your best judgement, I
trust you.

## Why use LaTeX instead of a regular word processor?
LaTeX is not a word processor. It allows you to write content without worrying
about formatting or typesetting -- LaTeX handles all the organization,
placement of text, spacing, headings, and so on. It is the de facto standard
for technical and scientific documents, and it is beneficial for you to be at
least somewhat familiar with using it, especially if you plan to do research in
the future. For more about LaTeX, [visit their
homepage](https://www.latex-project.org/about/).

## But I don't know how to write LaTeX code!
Fear not, my apprentice. LaTeX can be tricky to work with, especially when
starting out. Lucky for you there is a vibrant TeX community on [stack
exchange](https://tex.stackexchange.com/) and across the web. I recommend new
users to modify templates, ask lots of questions, and experiment.

Answers to frequently asked questions are found at the [end of this
Readme](#how-to-latex).

## The template is broken or missing something important!
Let us know in the [Issue
Tracker](https://github.com/RIT-Space-Exploration/SPEX-Standard-Proposal/issues)
so we can fix it!

# Writing tips
This advice goes for PDDs, Readmes, Wiki pages, conference papers, or even
theses.

1. **READ.** Read a lot of technical writing, good AND bad. This will help you
   refine your skill while giving you goal posts to shoot for and pitfalls to
   avoid.

2. **WRITE.** You don't get better without practice. Personal projects are a
   good safe place to do this because nobody sees the writing unless you share
   it. If you think it's good, its an amazing feeling to share a well
   documented project--it makes the project itself look that much better.

3. **DON'T OVERTHINK IT.** With technical writing, the goal is to convey your
   ideas as completely yet as concisely as possible. Sometimes sharing too much
   detail can obstruct the main idea you're trying to convey. Likewise, not
   enough detail and the main idea gets lost or misunderstood. It's a balance
   that you'll discover with tips 1 and 2.

4. **DON'T TAKE IT PERSONALLY.** Even if your words are written well, they can
   still be confusing. If someone reads your words and is confused, there is
   probably a good reason for that. Take mental notes of the way you explain it
   to them verbally and see if you can work that in to the original confusing
   bit. Every time you explain what you meant to say, that means there is an
   opportunity to improve what you wrote. Iteration is necessary 99.9% of the
   time. Don't let it get to you and keep writing. But don't let it get to your
   head--you can _always_ write something better.

5. **FORMATTING COMES FIRST AND LAST.** This one is tricky. What I mean is that
   when you block out your ideas just starting out a piece of writing, organize
   it in a way that makes the most sense for your mental model of what you
   intend to write. Build the scaffolding. For me, this includes lots of
   subheadings or bulleted lists. The framework usually lingers as comments.
   When writing the meat of it, don't get hung up on formatting. At that point
   your goal is to get the words out and into your scaffold. Finally, take some
   time to format things well. How words are arranged can have a significant
   impact on how they are received or understood. In short: Put up the frame,
   lay the pipes, electrical, and lights. Then put up the drywall and buy your
   furniture. Then paint the walls and rearrange the furniture. Then keep
   repainting and rearranging for the next 20 years.

# LaTeX tips
[LaTeX Quickstart
Tutorial](https://github.com/RIT-Space-Exploration/SPEX-Standard-Proposal/wiki/LaTeX-Quickstart-Tutorial)
☕️

[Begin LaTeX in minutes](https://github.com/LewisVo/Begin-Latex-in-minutes)
:fire:

## How to LaTeX on PC?
[Setting up your computer to work with
LaTeX](https://github.com/RIT-Space-Exploration/SPEX-Standard-Proposal/wiki/Setting-up-your-computer-to-work-with-LaTeX)
☕️ 👌

## My bibliography won't show up!
* Make sure you've created a `.bib` file and it's properly formatted! There are
  examples in the COPY_THIS folder.
  [sample-formats.bib](https://github.com/RIT-Space-Exploration/SPEX-Standard-Proposal/blob/master/COPY_THIS/sample-formats.bib)
  [sample-with-examples](https://github.com/RIT-Space-Exploration/SPEX-Standard-Proposal/blob/master/COPY_THIS/sample-with-examples.bib)
* Have you made any citations? Whenever you reference an external work such as
  a textbook or research paper, you must use the `\cite{your-reference}`
  command to insert a citation. No matter how many references you have in your
  `.bib` file, LaTeX only shows the ones you have cited.
* Are you telling LaTeX to make the bibliography? Insert the following commands
  after your acknowledgements and before your appendix:
```tex
\bibliographystyle{IEEEtran}
\bibliography{YOUR-BIB}
```
(in this example, I have a file called `YOUR-BIB.bib` in the same directory as
my `.TeX` file.)

## How do I make nice looking tables?
I'm so glad you asked! [Here's a great style guide to effective and beautiful
LaTeX
tables](https://www.inf.ethz.ch/personal/markusp/teaching/guides/guide-tables.pdf).

The package `booktabs` is highly recommended. Its usage is also described in
the style guide.

## Why is my linter yelling at me over periods and dashes?
Because it matters!
* `-` (hyphen), `--` (en-dash) and `---` (em-dash) are actually different
  characters and have different uses.
    * Hyphens (`-`) are used for word breaks and hyphenated words like
      "noise-canceling headphones." Don't worry about this one too much. LaTeX
      automatically hyphenates word breaks and there's no real "proper" rule
      for hyphenating words.
    * En-dashes (`--`) are used to delineate ranges like "1991--1995" or "2--3
      weeks." Looks goofy in code, but really nice in print.
    * Em-dashes (`---`) are used to place things like interjections---an
      uncommon grammar device in research papers---in among other parts of a
      sentence.
    * More info: https://tex.stackexchange.com/questions/3819/dashes-vs-vs
* Spacing is actually handled differently with periods that appear between
  letters of an abbreviation, after a word like "etc.", or, of course, at the
  end of a sentence. There are only a couple special cases to worry about, and
  even then this is only the "proper" usage (but it's optional).
    * [READ THIS
      FIRST](https://tex.stackexchange.com/questions/99543/exhaustive-list-of-use-cases-for-the-interword-space).
    * Non-breaking space (`~`) - This is used when you don't want two words to
      be separated if LaTeX wants to push one of them to a new line. It will
      appear as a space in text, but `these~words` will be handled like one
      "chunk." Use this one in between first and last names, or between titles
      and names like `Dr.~John~Smith`
    * Interword space (`\ `) - The Guide to LaTeX (4e) states that \␣ is a
      "[n]ormal space between words after a command without arguments or after
      a period that is not the end of a sentence" (p. 467).
    * Intersentence space (`\@`) - [Read
      this](https://tex.stackexchange.com/questions/55105/when-should-i-use-intersentence-spacing/55112#55112).
