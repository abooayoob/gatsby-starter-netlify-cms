---
templateKey: blog-post
path: /ali
title: Ali Tries some cms fu
date: 2017-12-22T05:31:24.275Z
description: Just a test of how this works. Bam!
---
```
function durationFormatter(value) {            if (value > 3600) {                const hours = Math.floor(value / 3600)                const secondsLeft = Math.floor(value % 3600)                let minutes = Math.floor(secondsLeft / 60)                if (minutes < 10) minutes = `0${minutes}`                let seconds = Math.floor(secondsLeft % 60)                if (seconds < 10) seconds = `0${seconds}`                return `${hours}:${minutes}:${seconds}`            } else {                let minutes = Math.floor(value / 60)                if (minutes < 10) minutes = `0${minutes}`                let seconds = Math.floor(value % 60)                if (seconds < 10) seconds = `0${seconds}`                return `${minutes}:${seconds}`            }        }
```

* Hmmm, not totally convinced yet.
* But it is pretty cool anyways!
* Will investigate further.

## New section:

I do _actually_ like it though....

![The new video page](/img/screen shot 2017-12-20 at 15.40.06.png)

Well, it now says unsaved changes, there is no save button, only publish button. Guess I have to choose to delete all my work, or just publish this thing.
