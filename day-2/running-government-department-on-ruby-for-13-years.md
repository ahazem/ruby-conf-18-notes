Running a Government Department on Ruby for over 13 Years
Jeremy Evans ([jeremyevans0](https://twitter.com/jeremyevans0))

### About (extracted from Rubyconf website)

Jeremy Evans is the lead developer of the Sequel database library, the Roda web toolkit, the Rodauth authentication framework, and many other ruby libraries. He has contributed to CRuby and JRuby, as well as many popular ruby libraries. He is the maintainer of ruby ports for the OpenBSD operating system.

### Intro

Talk about using Ruby for the last 13 years in goverment projects.

Maintainer of Sequel, Roda, RodAuth.

### Notes

Talks about why he's maintaining these libraries and how they are being used in his work at the California State Auditor.

The talk is not about typical government software development (in other states / countries).

Usually large projects, they need approval processes, the median time is over a year.

After approval, they start by preparing a request for proposal.

After reviewing proposals and accepting one, they give the contract to one of the contractors.

Talks about different types of testing done:

- "no unit testing of any kind, good integration testing coverage but performed manually via checklist".

Levels of oversight in a project is multiple, huge.

That's how not they are doing things:

- Avoids building large systems: starting simple.
- Scope reduction: getting rid of things unnecessary.
- No contractors: all work done by government employees.
- Ruby-only: all internal customer development is done in Ruby.

Typical projects they work on:

- Transforming paper-based forms to electronic forms.

More details into what systems and projects they're internally working on. Lost interest.

Talks about authentication system.

More slides about the things they do with Ruby. Nothing about how they do that in specific though.

Discusses his journey learning Rails/Sinatra and Coda, using them in work, and now talks about different tools and technologies they are using.

Javascript is avoided.

Talks about recruiting and then about his role as an information security officer at the department.

Defense in Depth approach:

- Reduced database privileges
- Separate users
- Security definer database functions
- Ingress/Egress/Loopback Filtering
- Chroot priv-drop (chroot doesn't work will with autoload)
- System call filtering

Gave some security recommendations, felt a bit unorganized, all related to previous points.



### Q&A:

1. **Q**: How did you get everybody to buy in?

   **A**: Convincing him to use Ruby, giving comparison of how the code looked: php vs rails.

2. **Q**: Number of applications in one cycle (9 months)?

   **A**: Not really a high volume of applications.

3. **Q**: How do you handle version upgrades in multiple applications?

   **A**: Done once a year: upgrade version, run tests, and see if something breaks, fix them and go to production.

4. **Q**: Is there any restricts on open sourcing the applications you're building?

   **A**: Replies about the stack being open source (the tools themselves used, not the applications, I think he got the question wrong).
