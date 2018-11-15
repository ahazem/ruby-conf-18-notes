Cache is King: Get the Most Bang for Your Buck From Ruby
Molly Struve

### Intro

Went in a few minutes late.

Gives a life example of caching. Talks about her company.

### Notes

Talks about their setup: Mysql -> ActiveModelSerializers -> ElasticSearch.

Gives an example about how they had a lot of fast queries but they were making so many of them.

Bulk Serialization.

Lots of talking about how they are optimising and caching, especially using bulk serialization.

Shows a graph where the curve goes down sharply after deploying those optimisations.

Explains how fixing one part of the problem moved the load to another part: Redis.

Talks about sharding their database.

Moves on to other optimisation techniques to ensure not doing unnecessary database hits.

Goes on to the last point. Bumping up the number of Resque workers from 45 to 70. Redis was overwhelmed as a result.

Recommendations:

- Process in bulk
- Hash Cache is always going to be faster than Redis.
- Framework cache (know your gems: octopus sharding)
- Database Guards
- Remove data store hits

### Q&A:

1. **Q**: Did your team has any issues with caching invalidation?

   **A**: Make sure when you're adding something to a cache, everything has an invalidation.

2. **Q**: Are you keeping a local cache on every instance (on a load-balanced environment)?

   **A**: Didn't catch the answer.

3. **Q**: Is there a way you can automatically detect where you ...

   **A**: [...]

4. Couldn't catch the question or the answer.
