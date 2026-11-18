# Data, Analytics & Applied AI Leader

I build and lead data teams that turn complex information into better business decisions. Over 17+ years in music, media, and consumer internet businesses, I've helped organizations grow revenue, reduce costs, improve reporting, and make better use of their data.

I combine executive leadership with hands-on work in SQL, Python, R, and applied AI. My most recent public build is [dbt-honest-data](https://github.com/hi-jason/dbt-honest-data), a tested dbt package.

## Selected accomplishments

- **Built and developed high-performing teams.** Grew a global data organization from 14 to 27 people across analytics, data engineering, data science, and technical program management, including three managers leading their own teams.
- **Avoided $900K in external consulting costs.** Led an Oracle-to-PostgreSQL migration in eight months against a twelve-month estimate. First used a controlled AI-assisted test to establish feasibility and secure organizational support; the project also documented and version-controlled previously undocumented data pipelines and SQL.
- **Generated $700K in additional revenue.** Audited partner-reported consumption against independent third-party sources, finding discrepancies that routine reporting, including the partner's own, had missed.
- **Cut call-platform costs by 25%.** Identified critical inefficiencies in a Twilio-based call platform and led its cross-functional redevelopment with Product and Engineering, without direct authority. Worked with the team to rearchitect the data side end to end, from the reworked software through ETL pipelines and finished tables to the Tableau dashboards the business used, so call and lead data became reliable.

## Featured project

### [dbt-honest-data](https://github.com/hi-jason/dbt-honest-data)

A dbt package of 16 data tests for errors that pass ordinary `not_null` and `unique` checks, built from a ten-day audit of 83,965 snapshots from five public job-listing feeds. The audit found 18,536 estimated posting dates that looked exact, 41.8% of records treated as open without confirmation, and one listing's real 17% pay rise hidden by a noise filter. In CI, every test must pass on clean synthetic data and fail on planted errors, on DuckDB and PostgreSQL.

- **Hiring managers:** start with the case study, [*When clean data lies*](https://github.com/hi-jason/dbt-honest-data/blob/main/docs/when-clean-data-lies.md) (about 8 minutes).
- **Engineers:** see [the core checks](https://github.com/hi-jason/dbt-honest-data#the-eight-core-checks), [how they attach to a model](https://github.com/hi-jason/dbt-honest-data#how-the-checks-attach-to-a-model), and [how the tests are tested](https://github.com/hi-jason/dbt-honest-data/blob/main/integration_tests/README.md).

Built with AI coding assistance (Claude Code); the design decisions and audit findings are mine.

## Featured research

### The Application of a Markov Chain to Album Listening

**UCLA Master's thesis, Applied Statistics and Data Science (2023)** · [Read the published thesis on UC eScholarship](https://escholarship.org/uc/item/16b612nw)

**The question:** How do people move through an album, song by song, and where do they stop listening?

I used a statistical model called an **absorbing Markov chain** to study how listeners move between tracks or end a session. I independently prepared **133 GB of raw listening data** from the open LFM-2b research dataset (approximately two billion Last.fm plays) in BigQuery and built the model in R.

For one album over 90 days (**654 listeners; 29,925 plays**):

- **Engagement varied widely:** The most engaged quarter of listeners averaged **141.9 album plays per person**, compared with **1.9** for the least engaged quarter.
- **Track 3 stood out:** Listeners were more likely to end a session there than on neighboring tracks.

**Why it matters:** The order of consumer actions can reveal patterns that totals and averages miss, helping teams ask better questions about content, engagement, and experience.

## Expertise

- **Analytics and engineering:** SQL, Python, R, [dbt](https://github.com/hi-jason/dbt-honest-data), BigQuery, PostgreSQL, DuckDB, Tableau, statistical modeling, data governance
- **Applied AI:** AI-enabled analytics, Model Context Protocol (MCP), automation, predictive modeling, [AI-assisted development](https://github.com/hi-jason/dbt-honest-data)

This profile highlights selected professional outcomes and my public work: [dbt-honest-data](https://github.com/hi-jason/dbt-honest-data) and the thesis above. Employer code and internal datasets are not published here.

## Let's connect

I'm interested in opportunities where I can combine data and analytics leadership, hands-on technical work, and applied AI to solve meaningful business problems.

If you're building a data organization, exploring AI opportunities, or looking for an experienced leader who still builds, I'd welcome a conversation.

[Connect with me on LinkedIn](https://www.linkedin.com/in/jasonsyi/)
