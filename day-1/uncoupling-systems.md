## Uncoupling Systems

Jeremy Hanna ([@almosyjeremy](https://twitter.com/almostjeremy))<br />
Track: [Taming Services](https://rubyconf.org/program#track-taming-services)

### About the speaker (extracted from RubyConf website)

Lifelong learner and student. Passionate about computers and systems and computer systems. I read too much and dislike heights.

The past 3 years I've worked at Kenna Security in Chicago, scaling and building out our back-end data pipeline platform. I'm currently heading up the effort to split out services and migrate to containers.

### Intro

Talk is about systems design.

### Notes

Talks about Sandi Metz's book (Practical Object-Oriented Design in Ruby).

Going through an example of code and how complicated it is.

The slides (code examples and drawings) can hardly be read on the projector.

Feels a little unprepared. I think he was very stressed out.

Lists three anti-patterns when designing a system (mostly around communication):

1) Not talking about design.

2) Let so and so design it.

3) Not discussing trade-offs.

Gives one more code example. I can hardly see the code.

Recommends two books for further reading:

- [Designing data-intensive applications](https://dataintensive.net/)
- [Distributed systems](https://www.distributed-systems.net/index.php/books/distributed-systems-3rd-edition-2017/)

Shows some topics and code examples from the books.

Lost interest at this point.

Lists a few tips on how to design your data:

- Communicate through queues
- Retryable, idempotent workers
- Pre-compute work
- Identify derived data
- Determine consistency costs

Not sure what is he talking about anymore!

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">&quot;When turning DB data into an API you lose transactions, joins and coupled state. Now you need to implement Sagas&quot; - Jeremy Hanna <a href="https://twitter.com/hashtag/RubyConf?src=hash&amp;ref_src=twsrc%5Etfw">#RubyConf</a> <a href="https://twitter.com/hashtag/RubyConf18?src=hash&amp;ref_src=twsrc%5Etfw">#RubyConf18</a> <a href="https://t.co/tX88xlx21i">https://t.co/tX88xlx21i</a></p>&mdash; elg0nz (@elg0nz) <a href="https://twitter.com/elg0nz/status/1062485893833867265?ref_src=twsrc%5Etfw">November 13, 2018</a></blockquote>

Feels like a little cryptic to be honest, the talk wasn't very interesting or engaging. As if he didn't prepare the slides himself or just put together some ideas from different books with no genuine contribution from him.

I regret choosing this one, now that I'm reading how interesting is the other talks (Waffle Maker / Fakes News Psychology) on Twitter:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Waffles! <a href="https://twitter.com/hashtag/rubyconf?src=hash&amp;ref_src=twsrc%5Etfw">#rubyconf</a> <a href="https://twitter.com/thejonanshow?ref_src=twsrc%5Etfw">@thejonanshow</a> <a href="https://t.co/d5yO50JnGF">pic.twitter.com/d5yO50JnGF</a></p>&mdash; Valerie Woolard Srinivasan (@valeriecodes) <a href="https://twitter.com/valeriecodes/status/1062480247910686720?ref_src=twsrc%5Etfw">November 13, 2018</a></blockquote>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/Waffles?src=hash&amp;ref_src=twsrc%5Etfw">#Waffles</a> in the making  <a href="https://twitter.com/hashtag/Rubyconf?src=hash&amp;ref_src=twsrc%5Etfw">#Rubyconf</a> <a href="https://t.co/p7NPrYyyaS">pic.twitter.com/p7NPrYyyaS</a></p>&mdash; Vipul A M (@vipulnsward) <a href="https://twitter.com/vipulnsward/status/1062487246677233664?ref_src=twsrc%5Etfw">November 13, 2018</a></blockquote>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I&#39;m learning about fake news from the 1930s that has been immortalized as truth 😮<a href="https://twitter.com/hashtag/RubyConf?src=hash&amp;ref_src=twsrc%5Etfw">#RubyConf</a> <a href="https://twitter.com/cecycorrea?ref_src=twsrc%5Etfw">@cecycorrea</a></p>&mdash; jtu (@jtu) <a href="https://twitter.com/jtu/status/1062482832478498816?ref_src=twsrc%5Etfw">November 13, 2018</a></blockquote>

### Slides & Video

The video can be found [here](https://confreaks.tv/videos/rubyconf2018-uncoupling-systems). Slides not available online.

### Q&A

I don't remember if there was any questions asked after the talk.
