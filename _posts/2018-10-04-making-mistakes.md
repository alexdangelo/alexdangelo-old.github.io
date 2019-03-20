---
layout: post
title: Making Mistakes
subtitle: Let's be kind to ourselves
---

When a bug is found, how does the team react? Finding the person to blame is the easiest, especially when it happens in production. But is that the most important thing? The author of the bug already feels bad enough, shaming them won't help much, other than to instill dread.

We treat it like this:
We don't point fingers. Instead we just fix the bug. The person with most familiarity or bug author is likely the one to fix the bug, but it's the tone that is set. It's not "Esteban broke this feature. Great job, Esteban." but rather "This feature is broken. Esteban, can you take a look? Let me know if I can help."

We want to create a supportive environment where it's ok to make mistakes. We all make mistakes. We all introduce bugs of varying severity. Getting down on each other doesn't help.

So what's the consequence? Bugs should be minimized, not laughed away. Bugs can be expensive to fix, especially if it impacts a paying customer. Look at the root problem. Was the code ever tested? Was it running against the same data that is in production? Would a unit test have caught it? Was it missed in code review? What conditions existed at the time, e.g. was the feature rushed out due to other deadlines?

Are bugs consistently seen in a person's code? That opens up a different discussion.
