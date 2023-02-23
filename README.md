# hz.tools

Hello! You've found [@paultag](https://github.com/paultag)'s radio code!

Interested in future updates? Follow me on mastodon at
[@paul@soylent.green](https://soylent.green/@paul) Posts about hz.tools will be
tagged [#hztools](https://soylent.green/@paul/tagged/hztools).

I've been working on learning about SDRs for a few years, and this organization
contains code that I've been working on to try and learn about radios by building
everything from start to finish.

It's been a ton of fun, and 4 years (at the time of writing, since 2019) of
learning, which has been incredibly rewarding.

I've decided, after a few years that it's time to make a number of them public,
and to start working on them in the open, as I’ve built up a bit of confidence
around it, and feel confident that the repo doesn’t contain overt lies.

## Expectations within this Organization

  - I do want this library to be used to learn with. Please go through it all and use it to learn about radios and how software can control them!
  - I am interested in bugs if there’s a problem you discover. Such bugs are likely a great chance for me to fix something I’ve misunderstood or typoed.
  - I am interested in PRs fixing bugs you find. I may need a bit of a back and forth to fully understand the problem if I do not understand the bug and fix yet. I hope you may have some grace if it’s taking a long time.

However,

  - I do not want this library to become a critical dependency of an important project, since I do not have the time to deal with the maintenance burden. Putting me in that position is going to make me very uncomfortable.
  - I am not interested in feature requests, the features have grown as I’ve hit problems, I’m not interested in building or maintaining features for features sake. The API surface should be exposed enough to allow others to experiment with such things out-of-tree.
  - I’m not interested in clever code replacing clear code without a very compelling reason.
  - I use GNU/Linux (specifically Debian), and from time-to-time I’ve made sure that my code runs on OpenBSD  too. Platforms beyond that will likely not be supported at the expense of either of those two. I’ll take fixes for bugs that fix a problem on another platform, but not damage the code to work around issues / lack of features on other platforms (like Windows).

## API Stabilty

I can make no promises about the stability of the API and it's subject to
complete and total breakage in a single commit. I need this freedom to continue
to learn and refine my understanding of software defined radios without having
to coordinate changes with a wider ecosystem. Perhaps one day we'll get there,
but for now, this is the standing policy.

## LICENSE

Currently, all code is MIT/Expat licensed. Ensure proper attribution is
maintained if you copy code. Email me if you have any questions.
