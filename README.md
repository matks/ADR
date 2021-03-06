# ADR

Architecture Decision Records for the PrestaShop project

## What is this?

The purpose of this repository is to track the history of design choices on the PrestaShop project.

To learn more about ADRs, read [this article][adr]

[adr]: http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions

## How do I propose a subject?

Use [ADR tools](https://github.com/npryce/adr-tools/) to build your proposal, add it to the status table below, then submit a Pull Request.

New proposals initial status is "In discussion". If the subject is accepted for discussion, it is assigned an ID and added to the table below.

Once the discussion is over and after all necessary ADR modifications, a vote is cast in the related Pull Request. All project maintainers vote, and their vote is registered. Decisions are accepted by simple majority. Discussed ADRs are merged even if they are not accepted.

## ADR status

ADR ID | Date | Discussion | Title | Status
------ | ---- | ---------- | ----- | ------
0001   | 2019-01-22 | ~ | [Record architecture decisions](0001-record-architecture-decisions.md) | ✅ Accepted
0002   | 2019-02-15 | ~ | [Mixed use of composer and zip modules](0002-mixed-use-of-composer-and-zip-modules.md) | ✅ Accepted
0003   | 2019-10-15 | ~ | [Use of autowiring](0003-use-of-autowiring.md) | ❌ Rejected
0004   | 2020-04-17 | ~ | [Keep QA and Devs HTML selectors separate](0004-keep-qa-and-devs-html-selectors-separate.md) | ❌ Rejected
0005   | 2019-01-22 | [Pull Request](https://github.com/PrestaShop/ADR/pull/1) | Define ACL rules for Symfony pages | 💬 In discussion
0006   | 2020-02-13 | [Pull Request](https://github.com/PrestaShop/ADR/pull/7) | Registration of a bundle-like module | 💬 In discussion
0007   | 2020-03-09 | [Pull Request](https://github.com/PrestaShop/ADR/pull/8) | Module advanced installation | 💬 In discussion
0008   | 2020-03-23 | [Pull Request](https://github.com/PrestaShop/ADR/pull/9) | Ajax error handling | 💬 In discussion
0009   | 2020-08-20 | ~ | [Expose js components using window variable](https://github.com/PrestaShop/ADR/blob/master/0009-expose-js-components-using-window-variable.md) | ✅ Accepted
0010   | 2020-12-15 | [Pull Request](https://github.com/PrestaShop/ADR/pull/14) | Module version bump convention when Core is updated | 💬 In discussion

