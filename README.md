# Hi, I'm Matt!
I'm a father of three, husband, and software engineering leader. I have a lot of interests, but I primarily take interest in the topics of technology, science, parenting, software engineering, leadership, business management, entrepreneurship, and gaming!

I've worked in tech in Vancouver, British Columbia, Canada since 2011. The first five years of my career were spent in Technical Support, the majority of which was in enterprise B2B software focused on endpoint security. In 2016, I changed disciplines and started focusing on software engineering and leadership.

# Links
You can find some of my relevant links in the list below:

- [Twitter](https://twitter.com/mattwoodtech)
- [LinkedIn](www.linkedin.com/in/matt-wood-40380550)

# Work
I'm currently working as an Engineering Manager at [Plenty of Fish](https://pof.com) and [Match Group](https://mtch.com/). I joined the POF brand at Match Group in January 2022.

I have a strong track record as a builder and leader of teams that build platform services, payments systems, monetization and other domains.

# Side Projects
I have worked on several side projects over the years. Some info about them is below.

## Kore Tools (2022-Current)
Towards the end of 2022 I solo-founded [Kore Tools](https://www.kore-tools.com/), a developer tools platform built to help make software development faster. I felt that there was a gap in some core technologies that developers need to build scalable, reliable solutions to real-world problems. 

I started with the basics: I am self-bootstrapping, in an indie hacker style, a product called [Kore Cache](https://blog.kore-tools.com/blog/20221108_AnnouncingKoreCache). Kore Cache is a distributed cache which you can setup and get started with in production in <5 minutes. My goal is to spread that ease of use and reliability to other areas of development in the future. I want people to be able to leverage core technologies in a few minutes without having to sell their souls, customer data or life savings to Amazon, Google or Facebook for the pleasure of doing so.

Kore Tools is being built in public. You can read the trials and tribulations on the [KT blog](https://blog.kore-tools.com) or on [Twitter](https://twitter.com/koretools).

This project uses a bunch of technologies in a microservice-style architecture. I'll blog more about it, but it's primarily built with C# and .Net 6, backed by a PostgreSQL data store, and TypeScript, NextJS and Tailwind for frontend work.

## OpenHouseTrader (2019-2020)
In 2019, my wife and I co-founded OpenHouseTrader. OHT was a SaaS marketplace intended to be used by real estate brokerages to swap open house appointments with other realtors at the same brokerage. Unfortunately, our timing couldn't have been worse and the COVID-19 pandemic started just before our closed beta began. We weren't sure how long the pandemic would last, so we cut our losses and moved on from OpenHouseTrader after 3 months of building.

This project was built with C#, .Net Core, Angular and Bootstrap.

## Data Exporter (2016-2021)
Internal tool I built at [Absolute](https://absolute.com) for job scheduling and execution. It had an immense number of features, including a client tool to help users (even non-technical ones) produce and publish jobs for Data Exporter. It did a lot of tasks, but it's greatest strengths were in ETL (data transfer to and from SQL Server, PostgreSQL, and REST APIs), batch job scheduler (an advanced replacement for Windows Scheduled Tasks, Windows Services, and cron jobs), and in automated report deivery (daily reports delivered via email, SFTP, S3, and more). It had many advanced features that I personally miss: very flexible scheduling options, automatic job failure retries, retry backoff, automated failure detection and alerting, execution history and performance monitoring, real-time alerts for job feailures, advanced logging features, and a highly productive UI built in WinForms to build and publish new jobs in just a few minutes.

Data Exporter was built with C# and .Net Framework (it just missed the boat on .Net Core and we had no need yet to port it), and backed by PostgreSQL as its primary data store (though it had integration points into many data stores to support various job types). At the time that I left Absolute, Data Exporter had executed more than 1.5 million jobs in its lifetime and managed over 250 active internal and customer jobs. It was originally intended to run 1 job for 1 customer and then... Kinda just organically went crazy and took over most of our automated/scheduled workload.

## Quick Query (2014-2021)
Another internal tool I built at [Absolute](https://absolute.com) for querying and displaying data. I built this as part of my work, but I'll count it as a side project. It was one of the projects that justified and allowed me to switch into Software Engineering in 2016. It was built in VB.Net and SQL Server, with SQLite for usage tracking and integrations with REST APIs to collect next generation service data.
