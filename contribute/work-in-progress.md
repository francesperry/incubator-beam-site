---
layout: default
title: 'In Progress Work in Beam'
permalink: /contribute/work-in-progress/
---

# Work In Progress in the Apache Beam Project

As mentioned in the [Contribution Guide](/contribute/contribution-guide/), all work in Beam is tracked in our [Apache JIRA](https://issues.apache.org/jira/browse/BEAM). In addition, the following types of work may be of particular interest to the Beam community.

* TOC
{:toc}


## Starter Tasks

The community regular tags good getting started tasks with the label `newbie` or `starter`. Use a quick [JIRA search](https://issues.apache.org/jira/issues?jql=project%20%3D%20BEAM%20AND%20resolution%20%3D%20Unresolved%20AND%20labels%20in%20(newbie%2C%20starter)) to identify ways you can get started [contributing](/contribute/contribution-guide/) to Beam.

## Beam Proposals

Larger contributions use the JIRA issue type `proposal` to make the easier to identify and track, particularly during the [design](/contribute/contribution-guide#design) phase.

You can use JIRA searches on this issue type to identify proposals that are initial [ideas](TODO), [under discussion](TODO), [in implementation](TODO), and [completed](TODO).

## Feature Branches

Larger features with multiple active developers may be developed on a [feature branch](/contribute/contribution-guide/#feature-branches) before being merged in the master branch. In particular, this is often used for initial development of new components like SDKs or runners.

Current branches include:

| Feature | Branch | JIRA Component | More Info |
| ---- | ---- | ---- | ---- |
| Apache Gearpump Runner | [gearpump-runner](https://github.com/apache/incubator-beam/tree/gearpump-runner) | [runner-gearpump](https://issues.apache.org/jira/browse/BEAM/component/12330829) | [README](https://github.com/apache/incubator-beam/blob/gearpump-runner/runners/gearpump/README.md) |
| Python SDK | [python-sdk](https://github.com/apache/incubator-beam/tree/python-sdk) | [sdk-py](https://issues.apache.org/jira/browse/BEAM/component/12328910) | [README](https://github.com/apache/incubator-beam/blob/python-sdk/sdks/python/README.md) |
| Apache Spark 2.0 Runner | [runners-spark2](https://github.com/apache/incubator-beam/tree/runners-spark2) | - | [thread](https://lists.apache.org/thread.html/e38ac4e4914a6cb1b865b1f32a6ca06c2be28ea4aa0f6b18393de66f@%3Cdev.beam.apache.org%3E) |
{:.table}
