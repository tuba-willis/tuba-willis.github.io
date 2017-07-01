---
layout: default
title: What Is Big Data?
---

<div id="contact">
  <h1 class="pageTitle">Big Data</h1>
  <h3>What Is Big Data?</h3>
 An exact definition of "big data" is difficult to nail down because projects, vendors, practitioners, and business professionals use it quite differently. With that in mind, generally speaking, big data is:
<ul>
<li>large datasets</li>
<li>the category of computing strategies and technologies that are used to handle large datasets</li>
In this context, "large dataset" means a dataset too large to reasonably process or store with traditional tooling or on a single computer. This means that the common scale of big datasets is constantly shifting and may vary significantly from organization to organization.

<h3>Why Are Big Data Systems Different?</h3>
The basic requirements for working with big data are the same as the requirements for working with datasets of any size. However, the massive scale, the speed of ingesting and processing, and the characteristics of the data that must be dealt with at each stage of the process present significant new challenges when designing solutions. The goal of most big data systems is to surface insights and connections from large volumes of heterogeneous data that would not be possible using conventional methods.

In 2001, Gartner's Doug Laney first presented what became known as the "three Vs of big data" to describe some of the characteristics that make big data different from other data processing:
<ol>
<li>Volume</li>

The sheer scale of the information processed helps define big data systems. These datasets can be orders of magnitude larger than traditional datasets, which demands more thought at each stage of the processing and storage life cycle.

Often, because the work requirements exceed the capabilities of a single computer, this becomes a challenge of pooling, allocating, and coordinating resources from groups of computers. Cluster management and algorithms capable of breaking tasks into smaller pieces become increasingly important.

<li>Velocity</li>

Another way in which big data differs significantly from other data systems is the speed that information moves through the system. Data is frequently flowing into the system from multiple sources and is often expected to be processed in real time to gain insights and update the current understanding of the system.

This focus on near instant feedback has driven many big data practitioners away from a batch-oriented approach and closer to a real-time streaming system. Data is constantly being added, massaged, processed, and analyzed in order to keep up with the influx of new information and to surface valuable information early when it is most relevant. These ideas require robust systems with highly available components to guard against failures along the data pipeline.

<li>Variety</li>

Big data problems are often unique because of the wide range of both the sources being processed and their relative quality.

Data can be ingested from internal systems like application and server logs, from social media feeds and other external APIs, from physical device sensors, and from other providers. Big data seeks to handle potentially useful data regardless of where it's coming from by consolidating all information into a single system.

The formats and types of media can vary significantly as well. Rich media like images, video files, and audio recordings are ingested alongside text files, structured logs, etc. While more traditional data processing systems might expect data to enter the pipeline already labeled, formatted, and organized, big data systems usually accept and store data closer to its raw state. Ideally, any transformations or changes to the raw data will happen in memory at the time of processing.
</ol>
<img src="{{ 'assets/img/vs.jpg' | prepend: site.baseurl }}" alt="">
<h5>Other Characteristics</h5>

Various individuals and organizations have suggested expanding the original three Vs, though these proposals have tended to describe challenges rather than qualities of big data. Some common additions are:
<ul>
<li>Veracity:</li> The variety of sources and the complexity of the processing can lead to challenges in evaluating the quality of the data (and consequently, the quality of the resulting analysis)
<li>Variability:</li> Variation in the data leads to wide variation in quality. Additional resources may be needed to identify, process, or filter low quality data to make it more useful.
<li>Value:</li> The ultimate challenge of big data is delivering value. Sometimes, the systems and processes in place are complex enough that using the data and extracting actual value can become difficult.
</ul>

<h4>Why Is Big Data Important?</h4>

The importance of big data doesn’t revolve around how much data you have, but what you do with it. You can take data from any source and analyze it to find answers that enable:
<ol>
<li> cost reductions,</li><li> time reductions, </li><li> new product development and optimized offerings, and </li><li> smart decision making.</li> When you combine big data with high-powered analytics, you can accomplish business-related tasks such as:
<ul>
<li>Determining root causes of failures, issues and defects in near-real time.</li>
<li>Generating coupons at the point of sale based on the customer’s buying habits.</li>
<li>Recalculating entire risk portfolios in minutes.</li>
<li>Detecting fraudulent behavior before it affects your organization.
</ul>
</ol>
