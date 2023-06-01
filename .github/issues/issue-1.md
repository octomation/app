---
code: null
id: I_kwDOHe4lws5MkiRy
databaseId: 1284646002
number: 1
url: https://github.com/octomation/app/issues/1
title: "env: activate: add node_modules/.bin and vendor/bin to path"
issueType: null
labels: []
assignees:
  - kamilsk
milestone: null
parent: null
issueFields: {}
state: OPEN
stateReason: null
duplicateOf: null
createdAt: 2022-06-25T16:05:30Z
updatedAt: 2022-06-25T16:05:30Z
lastEditedAt: null
closedAt: null
---

# env: activate: add node_modules/.bin and vendor/bin to path

**Motivation:** the application is multi-lingual, and "bin/os/arch" is not enough.

`node_modules/.bin` is required for the frontend part, `vendor/bin` for the backend on PHP.

**Source:** https://github.com/octomation/go-tool/blob/f59cf8b6efb783cc90ebf4752f3557afc76c4894/bin/activate#L106.
