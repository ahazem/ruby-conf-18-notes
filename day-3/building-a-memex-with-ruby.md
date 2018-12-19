## Building a Memex (with Ruby!)

Andrew Louis (@[hyfen](https://twitter.com/hyfen))<br />Track: [General](https://rubyconf.org/program#track-general)

### About (extracted from RubyConf website)

Andrew is a software developer from Toronto. After learning about the Memex, he asked the dangerous question of “why do we still not have this?” and foolishly decided to start building one himself. Previously, he was the co-founder and CTO of ShopLocket, an ecommerce startup which was acquired in 2014.

### Intro

Introduces himself, and the talk. What's memex and all. Starting with history.

![Vannevar Bush](https://pbs.twimg.com/media/DsEz_YGVYAADXTW.jpg:large)
_Image courtesy of [@lsegal](https://twitter.com/lsegal/status/1063188175177211904)._

### Notes

1930s - Talks about Vannevar Bush and his work on computers.

1940s - WWII happened. Everything changed.

Quotes Vannevar:

>  "We are being buried under our own product".

Basically that technology allows us to create information more that we can analysis/understand.

Vannevar came up with a device called The Memex.

Explains the memex.

The memex was never built.

Talks about how he used to save every little piece of information about himself.

Shows post-stamps, reports from school, among many other things.

Decided to build a memex for himself.

[Live demo of his memex].

Amazing!

Gives an overview of the application he built.

Talks about importers: ETL (Extract, Transform, Load).

Discusses problems with gathering data for the memex:

- There might not be an API for what I need.
- Even if there's an API, it might not be designed for me to use.
- Even if there's a public API, it might not be a good one.
- Even if there's a good API available, it might not last forever.
- GDPR exports: not very useful for humans; not very useful for machines.

Talks about the things the first memex did wrong.

More demo.

Will open source the project.

### Video

Video can be found [here](http://confreaks.tv/videos/rubyconf2018-building-a-memex-with-ruby).

More info about the project: https://hyfen.net/memex/.

### Q&A:

1. **Q**: How does the system know what you ate?

   **A**: In general everything on the demo was automated. Some things he manually types like food.

2. **Q**: How often do you use the system? How has it changed you?

   **A**: 1) All the time. 2) Relates that to a having a personal journal. A supercharged journal.

3. **Q**: Mentions it is super cool. Her question is: are there any negative side effects?

   **A**: He said he leads a pretty normal life, but he also tries to ensure he always get data.

4. **Q**: Have you read the Laundry Files by Charles Stross?

   **A**: Talks about the book series, and Charles' depiction of the Memex.

5. **Q**: Have you been able to identify things like in your current habits that you wanted to change?

   **A**: Yes, explains how he changed using the data he gets from the memex at times.

6. **Q**: Where's the code run?

   **A**: The demo is running on his laptop (probably said the database is on personal cloud).

7. **Q**: Data growth over time?

   **A**: Fitbit and GPS data are like thousands of events every day, he think it's probably tens of thousands of events a day for all events.

8. Didn't get the question or the answer.

9. **Q**: Are you worried if this becomes open source, a company uses it to aggregate info about people?
   **A**: Didn't get the answer.

10. **Q**: How often do you import the data?
   **A**: Importers are running constantly!
