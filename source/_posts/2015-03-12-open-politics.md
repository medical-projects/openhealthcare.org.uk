---
layout: post
title: "Open Politics"
date: 2015-03-12 15:42:20 +0000
comments: true
categories:
author: Nick
author_link: ntoll
image: assets/images/posts/open.jpg
---
<i>This is a guest post by [Nicholas Tollervey](http://ntoll.org)</i>

The purpose of this post is to explore openness in government
technology. I've been asked to advise on this subject for 
[NHS England](http://www.england.nhs.uk/).
I shall be directing the civil servants I have been working with to this
article.

To many people much of this post will be old news. Unfortunately
we are in the minority. Hence the need for this summary.

As always, feedback and comments are most welcome; in fact, comments
will be quite useful given the readership will include civil
servants who can make changes within NHS England. Think of it as an
unofficial opportunity for engagement with the unelected arm of the
government.

The moral argument for openness in government is simple: it is a
fundamental requirement for a democratic society. Without the ability to
observe what and how the government is doing, how are citizens to
evaluate politicians come polling day?

Yet openness is too broad a term - in this sense it is perhaps a virtue
of a good political system. Therefore I will simply state three
practical embodiments of the virtue of openness:

1. **Open data** - data should be freely available without restrictions of
   copyright, patents or other controls;
2. **Open media** - data generated by the government should be in a format
   that is accessible to everyone;
3. **Open processes** - what the government does should be transparent,
   recorded and accountable.

The UK Government has been 
[vocal in the promotion of open data](https://www.gov.uk/government/publications/open-data-white-paper-unleashing-the-potential) 
(point 1). Yet it is not good enough to simply publish data. The format
and structure of the data is critical (point 2), as is its provenance
(point 3).

Regarding point 2: what's the point of publishing data if there's no way
for people to make use of it? After all, when data is read, analysed and
interpreted it becomes useful information. Publishing data in a medium
that only works with a single piece of software (such as releasing
tabular data that can only be read by Excel) makes it frustratingly
difficult use. While I welcome the publication of data I'd much
rather it were in a friendly open format (such as [releasing tabular data
as a CSV](http://data.okfn.org/doc/csv)).

Regarding point 3: what's the point of publishing data if there's no way
to  discover how it was compiled, by whom and with what intention? It
should be possible to independently check the reports published by
government through access to the raw data and (crucially) the
algorithms, processes and pipelines used to aggregate, transform and
generate the end result. Furthermore, an open process allows people to
examine, test and improve the methodology involved in generating data.
It will no longer be the case that compiling some-report-or-other is
only understood by a couple of government statisticians - this essential
organisational information would be available to all.

While this sounds like an onerous task for civil servants it is
important to note that these three practices actually make life easier
for all involved, including civil servants.

From a technical point of view, it's impossible to work effectively in
digital walled gardens where opaque solutions don't quite work
properly and are too expensive to migrate away from. Open standards
allow anyone (including civil servants) the flexibility to use their own
choice of tool for the job in hand as illustrated by the diagram
below.

<img
src="https://assets.digital.cabinet-office.gov.uk/government/uploads/system/uploads/image_data/file/8854/open_formats_standards_960x640.png"/>

As the Cabinet Office minister [Francis Maud states](https://www.gov.uk/government/publications/open-standards-principles/open-standards-principles),

<blockquote class="custom-quote"><p><i class="fa fa-quote-left"></i>

Government IT must be open - open to the people and organisations that
use our services and open to any provider, regardless of their size.
<br />
We currently have many small, separate platforms operating across
disconnected departments and IT that is tied into monolithic contracts.
We need to have a platform for government that allows us to share
appropriate data effectively and that gives us flexibility and choice.
</p></blockquote>


Contrast this vision with the incumbant alternative (based on real life
experiences working with statisticians within NHS England):

- No-one wants to work in a world where the data they need
for their report is held within a complex Excel spreadsheet with
meaningless column names generated by a team who never
answers email.

- No-one wants to work with a spreadsheet that is subtly different each
time it gets published causing doubts about its reliability and
provenance.

- No-one wants to work with a spreadsheet hosted on a website created in
2005 where the only way to get at it is to download a Java applet (the
technical equivalent of the [ruins of Ozymandias](http://en.wikipedia.org/wiki/Ozymandias)
) and manually press a
button on a computer logged into the very special VPN that never works
when you need it to.

Such a chain of opaque technology comes at great cost in terms of
time, efficiency and job satisfaction. Highly trained NHS
statisticians do not enjoy spending hours downloading, revising,
copying, pasting and re-uploading shonky spreadsheets.

They want to **work with data**, not push it around.

They want to **access the data**, not spend hours clicking buttons.

They want to **understand** their colleagues' work and know who to contact
if there's a problem.

<img src="/assets/images/posts/hope.jpg" />

Happily, there are signs of hope.

In the first instance civil servants should be following the 
[Open Standards Principles](https://www.gov.uk/government/publications/open-standards-principles/open-standards-principles)
from the Cabinet Office

It is a simple and easy to understand guide for using open
standards in government. If you're a civil servant working with data
you should be following this checklist:

 1. We place the needs of our users at the heart of our standards choices
 2. Our selected open standards will enable suppliers to compete on alevel playing field
 3. Our standards choices support flexibility and change
 4. We adopt open standards that support sustainable cost
 5. Our decisions about standards selection are well informed
 6. We select open standards using fair and transparent processes
 7. We are fair and transparent in the specification and implementation of open standards

It is no longer acceptable to say things like, "but the needs of our
legacy system mean you should use &lt;closed technology X&gt;". If you hear
such a remark, point the perpetrator at the checklist above. If they
claim it would be too expensive to migrate, explain that it's because it
is so expensive to migrate that such a system needs changing (such
expense only ever grows over time, change things sooner rather than
later). If they assert that it's not organisational policy to use
open process Y ask them to justify themselves within the framework
described in the policy document above (that became active on 1st
November 2012). Cabinet Office advice when 
[choosing technologies](https://www.gov.uk/service-manual/making-software/choosing-technology.html)
is that one should express requirements in terms of user needs and capabilities
not incumbent institutional needs. Furthermore, when considering the choice
of technology, they state,

<blockquote class="custom-quote"><p><i class="fa fa-quote-left"></i>
All things being equal, picking technologies that developers and operations staff like will typically result in improved productivity.
</blockquote>

A second positive is that there appear to be politicians of all
affiliations who understand and have the political will to promote open
standards.

Consider the following exchange between myself and Meg Hillier MP:

<blockquote class="twitter-tweet" lang="en"><p>.<a href="https://twitter.com/Meg_HillierMP">@Meg_HillierMP</a>, given ubiquity of closed formats (MS Office etc), will Parliament switch to publish w/open data formats? <a href="https://twitter.com/hashtag/digitaldemocracy?src=hash">#digitaldemocracy</a></p>&mdash; Nicholas Tollervey (@ntoll) <a href="https://twitter.com/ntoll/status/575253094663122944">March 10, 2015</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" lang="en"><p>.<a href="https://twitter.com/ntoll">@ntoll</a> yes..that&#39;s the plan. New head of Parliament Digital Service <a href="https://twitter.com/Rob_Greig">@Rob_Greig</a> is already working on this</p>&mdash; MegHillierMP (@Meg_HillierMP) <a href="https://twitter.com/Meg_HillierMP/status/575258270706892800">March 10, 2015</a></blockquote>

<blockquote class="twitter-tweet" lang="en"><p>.<a href="https://twitter.com/Meg_HillierMP">@Meg_HillierMP</a> motivation for my q is current work w/<a href="https://twitter.com/NHSEngland">@NHSEngland</a> stats / data in messy, non-machine readable Excel spreadsheets &amp; PDFs. :-(</p>&mdash; Nicholas Tollervey (@ntoll) <a href="https://twitter.com/ntoll/status/575257864454995969">March 10, 2015</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" lang="en"><p><a href="https://twitter.com/ntoll">@ntoll</a> <a href="https://twitter.com/Meg_HillierMP">@Meg_HillierMP</a> <a href="https://twitter.com/NHSEngland">@NHSEngland</a> &quot;non-machine readable Excel spreadsheets&quot; --&gt; cold shiver in my spine</p>&mdash; Giovanni Idili (@John_Idol) <a href="https://twitter.com/John_Idol/status/575261025395720192">March 10, 2015</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" lang="en"><p>.<a href="https://twitter.com/John_Idol">@John_Idol</a> <a href="https://twitter.com/ntoll">@ntoll</a> <a href="https://twitter.com/NHSEngland">@NHSEngland</a> and that&#39;s not the worst of it! sometimes they are not even readable in paper form</p>&mdash; MegHillierMP (@Meg_HillierMP) <a href="https://twitter.com/Meg_HillierMP/status/575261373304803330">March 10, 2015</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" lang="en"><p><a href="https://twitter.com/Meg_HillierMP">@Meg_HillierMP</a> <a href="https://twitter.com/John_Idol">@John_Idol</a> <a href="https://twitter.com/NHSEngland">@NHSEngland</a> good point - demonstrates accountability/evidence: confusing data=confused understanding perhaps?</p>&mdash; Nicholas Tollervey (@ntoll) <a href="https://twitter.com/ntoll/status/575261775446306817">March 10, 2015</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" lang="en"><p>.<a href="https://twitter.com/ntoll">@ntoll</a> <a href="https://twitter.com/John_Idol">@John_Idol</a> <a href="https://twitter.com/NHSEngland">@NHSEngland</a> yes. We are coming from same place on this issue. Open Up! <a href="https://twitter.com/hashtag/digitaldemocracy?src=hash">#digitaldemocracy</a></p>&mdash; MegHillierMP (@Meg_HillierMP) <a href="https://twitter.com/Meg_HillierMP/status/575262116405460992">March 10, 2015</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" lang="en"><p><a href="https://twitter.com/Meg_HillierMP">@Meg_HillierMP</a> <a href="https://twitter.com/John_Idol">@John_Idol</a> <a href="https://twitter.com/NHSEngland">@NHSEngland</a> quite... so having evidence is one thing - but how does a citizen hold publisher accountable?</p>&mdash; Nicholas Tollervey (@ntoll) <a href="https://twitter.com/ntoll/status/575272422582132736">March 10, 2015</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" lang="en"><p>.<a href="https://twitter.com/ntoll">@ntoll</a> <a href="https://twitter.com/John_Idol">@John_Idol</a> <a href="https://twitter.com/NHSEngland">@NHSEngland</a> we need to make it either embarrassing for them or in case of Govt manke it mandatory</p>&mdash; MegHillierMP (@Meg_HillierMP) <a href="https://twitter.com/Meg_HillierMP/status/575301644272996352">March 10, 2015</a></blockquote>



<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Here's hoping NHS England leads the way in open standards. After all,
they were born from a disparate collection of
existing governmental organisations, each of whom did things differently. Openness is
a way for NHS England to integrate, collaborate and work more effectively towards making
the NHS the world class healthcare system it needs to be.

This is an opportunity that applies to the whole public sector. The cost of inaction would
be to deny the government tools and processes essential for working effectively in a world
in constant flux.

Panta rhei!

<small>
Photo credits: <br />
[Opensourceway](http://www.flickr.com/photos/opensourceway/)<br />
[Pol Sifter](http://www.flickr.com/photos/polsifter/)
</small>
