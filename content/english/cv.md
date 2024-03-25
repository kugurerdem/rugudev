---
title: CV
layout: cv
---

{{< center >}}
[Summary](/en/cv/#summary) |
[Education](/en/cv/#education) |
[Experience](/en/cv/#experience) |
[Philosophy](/en/cv/#philosophy) |
[Stack](/en/cv/#stack)

**Uğur Erdem Seyfi** ([GitHub](https://github.com/kugurerdem))
{{< /center >}}

{{< center >}}
# Summary
{{< /center >}}

I am a **full-stack software developer** with an academic background of
**Mathematics** and **Computer Science**. I have been professionally building
Software Products for **since 2021**, yet my first introduction to Software
Development can be traced back to my high school years in 2015.

I mainly have [experience](#experience) working with
financial tech apps, from their early stages to their more
stable phases. I've primarily used **NodeJS and its
ecosystem libraries/frameworks**, in addition to databases
like **PostgreSQL, Redis, LevelDB, and MongoDB**. I'm quite
familiar with tools such as **git** and I've been using the
**a Linux Distribution** as my primary operating system
since 2021. I feel comfortable building apps from scratch
with these tools. However, I am not strictly confined to
using this [stack](#stack) and I am always open to learning
new technologies. I believe that my understanding of the
fundamentals makes it easier for me to learn the right
tools when necessary.

To give you a more idea about me, I am your typical software developer with a
hacker's mindset. I delve deeper into the technologies I use and their
underlying philosophies. I use **Arch Linux** as my desktop computer, use
**Vim** to edit and write text, spend time on [Hacker
News](https://news.ycombinator.com/user?id=kugurerdem), and write regularly. I
highly value **philosophy**, particularly **rational
thinking**. **I think having a proper understanding of the
fundamentals of this industry is a way more valuable skill
than to know XYZ framework**. I find it a requirement for
success to have a [philosophy](#philosophy) of doing things
for delivering products.

{{< center >}}
# Education
{{< /center >}}

I studied **Mathematics** between **2018 and 2022** at **Bilkent University**,
one of the most prestigious universities in Turkey. During my major, I
completed the entire **Computer Science** curriculum through electives except
for two courses I did not enroll - Operating Systems and Algorithms I.


{{< center >}}
# Experience
{{< /center >}}

---

> {{< center >}} **Freelance Software Developer** at [Sphera
Engineering](https://www.spheraeng.com/) (**2023-12-13 / 2024-04**)

> Sphera is an engineering company with crossover expertise in structural
> design and software development.
{{< /center >}}

> Our job was to construct a **backend infrastructure** and create a simple,
> functional **frontend** that enables global and local administrators to
> manage designers, products, catalogs, etc. The most challenging part of the
> project was to make the authentication process to be SAML-compatible. In
> other words, **we designed our backend to act as a SAML Service Provider**
> and then integrated our app with  **Salesforce and Azure SAML IdP Services**.

> **Stack**: Postgres, SAML Protocol, Javascript, React, Fastify, Heroku,
> Cloudflare Pages

---

> {{< center >}} **Freelance Software Developer** at [Blackwater Information Services](https://www.borsaistanbul.com/tr/sayfa/453/servis-saglayicilar) (**2023-02-13 / 2023-12-29**)

> BlackWater Information Services is a trading company located in Turkey.
{{< /center >}}

> During my involvement in this project, I have made significant contributions
> in the process of developing **NodeJS adaptors** for [ITCH,
> GLIMPSE](https://www.borsaistanbul.com/en/sayfa/2537/itch-protocol), and
> [OUCH](https://www.borsaistanbul.com/en/sayfa/2535/ouch-protocol) Socket
> Protocols, protocols which are commonly used in central exchanges such as
> Nasdaq and Borsa Istanbul (BIST) for facilitating high-frequency trading and
> market data transmission.

> **We have successfully passed the BIST's OUCH Certification Exam using the
> adaptors we have developed**, and as a result, the company was listed as one
> of the few [OUCH Certified
> Applications](https://www.borsaistanbul.com/en/sayfa/2557/service-vendors).

> I have also made many important contributions regarding the clarifications of
> the **trading algorithms** which are built as well as **building the
> infrastructure in which those algorithms could be easily implemented and put
> into practice**. Unfortunately, I cannot talk much about the trading
> algorithms part itself as it is subject to NDA.

> I have developed a **REPL program** to make it easier for users to test the
> algorithms and interface that we are building by easily placing orders and
> initiating trading algorithms.

> I have also contributed to the process of building a **desktop application**
> which is supposed to be used as a replacing front-end alternative to the REPL
> program I mentioned above. The UI is designed so that it fits the specific
> needs of the traders.

> **Stack**: NodeJS, Sockets, ITCH, GLIMPSE and OUCH Protocols, SoupbinTCP, MoldUDP, Electron, React

---


> {{< center >}}**Freelance Software Developer** at [Referencehood](https://referencehood.com) (**2023-01-20 / 2023-10-10**)

> Referencehood is a referral platform that is founded by [Efe
> Bulduk](https://twitter.com/thebullduck?lang=en). It provides advantageous
> features for its users such as discounted fees or fee returns to those who
> register cryptocurrency exchanges using the site. {{< /center >}}

> I am familiar with all parts of the system which we have built as a team.
> This is not just limited to the frontend or backend but also
> administration, maintenance operations, and customer support. I have made
> significant contributions to the project to assist the team in enhancing all
> these aspects. These contributions include:

> - Developing **a system for Automatic Withdrawal**, where withdrawal jobs are
>   put into a **Redis-based message queue** as soon as the user creates a
>   withdrawal request, and are handled by consumer processes. I have also
>   implemented **a notification system where GitHub issues are created** in
>   case programmatically unrecoverable errors occur (such as the balance of the
>   wallet becoming insufficient).
> - Developing an **Admin Panel** that operators and the support team can use
>   for looking at certain statistics as well as seeing user details.
> - Implementing the first version of the **frontend** which is now present in
>   Referencehood, but modified a lot after.
> - Developing scripts and insfrastructure used for automatically **parsing the
>   reports** obtained from the crypto exchanges. This includes a panel for
>   operators to put the reports they obtained from exchanges as well as the
>   scripts that parse those reports on the backend side.
> - **Migrating the database** for improved balance calculation
> - Helping to improve some of the endpoints that are used in the **public
>   API**.
> - **Developing generic exchange adaptors** for different crypto exchanges
>   such as Binance, Okex, and Bybit, to be later used in a **sweeping process**.

> I have also helped the Referencehood team with tasks which require soft skills
> as well, including:
> - Helping the **e-mail support team** on their way to answer customers, as
>   well as answering stuff by myself from time to time.
> - Improving some of the **FAQ entries**.
> - Interacting with some of the exchange representatives during the
>   integration periods.


> **Stack**: Postgres, LevelDB, Redis, bullMQ, NodeJS, Fastify, React, Heroku, Cloudflare Pages

---

> {{< center >}} Part-time **Full-Stack Developer** at [Metavest](https://linktr.ee/metavestapp) (**2021-10 / 2022-08**)

> Metavest was a project backed by [BiLira](https://www.bilira.co/), the
> company which issued the first stable coin (TRYB) in Turkey. The project
> intended to become a cryptobank providing a high-quality mobile finance
> experience for all. {{< /center >}}

> My major responsibility in this project was to build a monitoring system
> called “DefiTracker” which esentially aggregates data from different kinds of
> DeFi platforms, later to be served on a panel built on Retool.
>
> I was also involved in the process of onboarding new members to DeFi
> ecosystem.

> **Stack**: NodeJS, Redis, MongoDB, Web3 Libraries (such as ethers.js), Grafana, Retool, Docker


---

> {{< center >}} **Software Developer Intern** at [Meteksan Defense](https://www.meteksan.com/en) (2021-06 / 2021-07)

> Meteksan Savunma is a Turkish defense technology company, specializing in
> radar systems, perimeter surveillance systems, laser and electro-optic
> systems, communication systems, underwater acoustic systems and simulators. {{< /center >}}

> I spent my time during my internship period at Meteksan by mostly focusing on
> learning certain areas and concepts such as **C++**, **socket programming**,
> **multi-threading**, **machine-learning** and **computer vision**. I have
> created a simple multi-client server network insfracture incorporating the
> things I learned about sockets and threads. On later periods of my
> internship, I delved into **Machine Learning**, with a particular emphasis on
> **Computer Vision**, **built a simple AI program which recognizes the MNIST
> numbers.**

> **Stack**: C++, Socket Programming, Threads, Python, PyTorch



{{< center >}}
# Philosophy
{{< /center >}}

## No Silver Bullet

Most problems of software development occur because developers not being
able to distinguish essential complexity from accidental complexity. Try to
oversimplify a problem, and you fail. Solve problems by favoring complex
tools and patterns, and you create technical debt for the future.


Software Developers frequently find themselves at a point where they are no
longer trying to solve the essential complexities regarding a particular
problem but the problems arise from accidental complexities created by
others, and sometimes themselves. The important thing to note here is that
there is [No Silver
Bullet](https://en.wikipedia.org/wiki/No_Silver_Bullet).


## Keep it Simple, Stupid!


No, using frameworks and tools without properly understanding the essential
complexities which they are supposed to solve is not going to help as they
often introduce problems on their own. **What is lacking in the industry is not
people being able to use XYZ framework but rather having a good understanding
of the fundamentals.** This is not to say that we should never use frameworks,
but rather we should know when to [put that framework down before someone gets
hurt](https://blog.boot.dev/webdev/put-that-framework-down/) as well as when to
use them so that we are not building [stupid light
software](https://www.arp242.net/stupid-light.html) in the pursuit of being
suckless.

Understanding the fundamentals is essential. But it is never enough by
itself for avoiding accidental complexities. It is quite common for smart
individuals to create and solve complex problems not because it benefit the
business, but simply because they enjoy it. This is why I see a great value
in reminding ourselves the principles such as
[KISS](https://en.wikipedia.org/wiki/KISS_principle) or [Less is
More](https://en.wikipedia.org/wiki/Less_is_more). Sometimes, being not so
smart, or [being a stupid progammer](https://antonz.org/stupid/) can lead
to a more understandable code. Remember Tony Hoare saying 'Premature
optimization is the root of all evil in programming.'


## Choosing Boring Technology

There is another lesson which I think is very important regarding this
matter. That is the ability to distinguish non-perishable knowledge from
[perishable
knowledge](https://www.lesswrong.com/posts/L6iFpR9ZyTmzHvYci/perishable-knowledge).
In many cases, 'smart' software developers lean towards using fancy tools
which are new and cutting edge when there are already technologies which
are battle tested for long periods of time, and known to be working well
for many cases. Most of the time it's just a better investment for your
business to [choose boring
technology](https://mcfunley.com/choose-boring-technology) over the
ones which are fancy (and marketed well) but not battle-tested enough.
See [Lindy Effect](https://en.wikipedia.org/wiki/Lindy_effect).

There also seem to be great amount of acumulated knowledge which are
available with 'boring technologies' which we could benefit from a lot.

## UNIX Philosophy

Hackers from previous generations accumulated a vast amount of knowledge of
many things. One such example that we could greatly benefit from is the [UNIX
philosophy](https://en.wikipedia.org/wiki/Unix_philosophy). Understanding that
most of the problems we face today in computer use have already been discussed
and often solved can influence how we use our computers.

## Mindful Communication

While working on projects, it's important to apply your soft skills as much as
your technical abilities. It's quite common for developers to face problems
that could easily be overcome by communicating with customers, product
managers, and team members. But they often prefer not to do so. This is often
the reason why product managers find themselves in a place where they need to
force developers to attend meetings in order to sync with them. The key thing
to understand here is that both situations could essentially be avoided simply
by developers learning to become a [radiating
programmer](https://dev.37signals.com/the-radiating-programmer/), a programmer
which radiates information as a habit.

{{< center >}}
# Stack
{{< /center >}}

I am always open to learning and adding new technologies to my stack. But, here
are the technologies which I am most familiar with.

---

### Programming Languages

**Javascript** is the programming language which I am most familiar with. I’ve
been using it since high school, both for recreational and professional tasks.
Having said this, I have also used programming languages such as **Python,
Java, C++, C** in the past, both for university projects as well as
recreational purposes. So, I have some familiarity with them to some extent as
well.

I use **Bash** pretty much regularly on my own operating system as well as the
systems I administrate.

I am also familiar with descriptive languages such as **SQL** and am interested
in functional programming languages such as **Haskell** and **Clojure**.

---

### Frameworks and Libraries

You can view the frameworks and libraries I've worked with for each language.
Click on the collapsible sections below corresponding to the programming
language you're interested in:

> {{< details "Javascript" >}}
**Frontend**

- The frontend framework I am familiar the most is **React**. I have used
  react with complementary libraries such as **React Query, React Router5**
  and **Zustand**.

- As a more lightweight alternative to React for simpler frontends, I use
**hyperscript, hyperscript-helpers** libraries.

- To build statistics charts, I opt for victory if I am using React. If not, a
  lightweight library such as shown will suffice.

**Backend**:

- For backend, I have used **Fastify** as a web framework with plugins such as
  **fastify-cors, fastify-rate-limit, fastify-swagger**.

- **jsonwebtoken**, is a very well known npm package used for handling JWT
  tokens. So, I use this as well.

- I have also used **formidable** to parse HTTP request form datas that
  especially contain file uploads.

- As a Database client library for Postgres, I have tried the following ones:
  **pg, postgres, massiveJS** and found **pg** the one which provides the most
  power whereas **massiveJS** makes the process of writing code more
  convenient.

- If using a database such as Postgres, or even SQLite becomes an overkill, and
  saving stuff in a key/value structure is sufficient, using **classic-level**
  npm package for using LevelDB might be a good idea.

- I have used **bullMQ** when I needed a message queue. It met my needs.

**Developer Dependencies**:

- My favorite choice of javascript linter is **Eslint**.

- I have also used the following developer dependencies from time to time for
  different purposes: **parcel, vite, heroku, wrangler, nodemon, patch,
  pino-pretty**

**Other Libraries**:

- **Lodash** is one of the utility libraries that I find pretty usefull,
  especially for transforming data from one form into another.

- I strongly prefer libraries such as **bignumber.js** for dealing with
  arithmetic operations for critical tasks rather than using JavaScript’s own
  methods.

- The library **minimist** is a good option for building CLI programs with
  simple argument mechanisms.

- I use **nanoid** to create unique identifiers in the same process.

- **async-retry** is another library that I find very helpful for implementing
  asynchronous retry logic, which is sometimes needed.

- I have also used libraries such as **csv-parse, csv-stringify, unzipper,
  xlsx** for parsing different files. They were fine, overall.

- I have used both **ethers.js** and **web3.js** for interacting with EVM
  Compatible Blockchains. I found the interface, documentation and the ease of
  use of ethers.js much better than web3.js. For the Tron blockchain,
  **tronweb** library worked fine for me.
{{< /details >}}

---

### Databases

For storing business critical data, I opt for relational databases such as
**PostgreSQL** over the ones that force you to implement the business logic in
the application layer (such as **MongoDB**).

I have also used databases such as **Redis**, **LevelDB** and **Prometheus** in
the past as well.

---

### Version Control System

I am familiar with **git** to the point that I do everything related to git via
its CLI.

---

### Cloud

I have used **Heroku** as a Cloud Application Platform. **I also configured and
maintained servers by myself to host applications.**

---

### UNIX Tools

Thanks to my daily exposure to consequences of using a minimal Linux distro as
a desktop computer, I am quite familiar with lots of different UNIX tools. :)
