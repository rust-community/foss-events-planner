# Implementation Notes

The FOSS events planner is a plan to bring a physical workshop into the digital space. The workshop was run on RustFest 2018. You can find impressions here:

https://twitter.com/Argorak/status/1001029123899260928

All orange cards on the images are *features*, all green ones are *tasks*.

Most of the [issues](https://github.com/rust-community/foss-events-planner/issues) are transcriptions of the cards derived back then.

We based the planning on the following elements

## Features

Features are something that you would like to have at an event. Features are important, but not actionable. "I want to have food" or "I want to have speakers" is ultimately the goal. An event does not have to have all features - for example, a conference without speaker selection and CFP is an unconference. Still, features might come with experiences (e.g. "drinks are easy, food is hard"), which are not immediately obvious. The planner wants to help newcomers to find these hidden dangers or tricks.

## Tasks

Tasks are directly bound to features. The are the *tiny, actionable* steps to implement a feature. For example, providing drinks requires you to find a vendor, order the drinks and finally pay them. Tasks might also be interconnected, even cross-referenced! For example, you need to know how many people actually attend before buying drinks! This cross-references to ticket sales!

## Cards

A (feature) card is a combination of both of the above. For example, the feature "drinks" can be found [here](/cards/drinks.md). It documents how hard the feature is (in terms of effort), how plannable it is (how likely random things happen) and what the tasks that need to be done for it. 