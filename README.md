dotify
======

An open source OMR for Android and iOS.

An app to support teachers in marking multiple choice exams with a super simple interface.

Goal
====

Mark assignments live on screen as you point your phone's camera at the paper.

Show live annotations, with green ticks, red crosses and highlighting of expected answers.

Automatically generate a report when finished, with a simple interface for capturing student names and stepping through
the workflow.

A desktop app for bulk marking of assignments with a scanner.

Design
======

Machine Learning Ideas
----------------------

- Train on dots
  - Application figures out question/answer structure and ordering by their relative and overall positioning
- Train on question 'sections'
  - Application only needs to work out ordering of questions
- Train on 'sheet'
  - Application identifies the whole structure and everything by just looking at a sheet
- Hybrid - layers of information with more detail going down:
  - Train on dots
  - Train on questions, using the dot recognition concept
  - Train on pages, using the section recognition concept

Implementation
==============

Prototypes!

Look at OpenCV and Tensorflow.
