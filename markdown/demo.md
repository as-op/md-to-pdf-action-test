# Demo

```mermaid
quadrantChart
    title Reach and engagement of campaigns
    x-axis Low Reach --> High Reach
    y-axis Low Engagement --> High Engagement
    quadrant-1 We should expand
    quadrant-2 Need to promote
    quadrant-3 Re-evaluate
    quadrant-4 May be improved
    Campaign A: [0.3, 0.6]
    Campaign B: [0.45, 0.23]
    Campaign C: [0.57, 0.69]
    Campaign D: [0.78, 0.34]
    Campaign E: [0.40, 0.34]
    Campaign F: [0.35, 0.78]
```

```mermaid
gantt
    title A Gantt Diagram
    dateFormat YYYY-MM-DD
    section Section
        A task          :a1, 2014-01-01, 30d
        Another task    :after a1, 20d
    section Another
        Task in Another :2014-01-12, 12d
        another task    :24d
```

<br-page/>

> [!NOTE]
> Useful information that users should know, even when skimming content.


> [!TIP]
> Helpful advice for doing things better or more easily.


> [!IMPORTANT]
> Key information users need to know to achieve their goal.


> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

<br-page/>

## HTML comment tags

Code:

```
Here's a paragraph that will be visible.

<!-- This is a comment that will be hidden. -->

<!-- 

This is a comment that will
be hidden.

-->

```

Here's a paragraph that will be visible.

<!-- This is a comment that will be hidden. -->

<!-- 

This is a comment that will
be hidden.

-->

And here's another paragraph that's visible.


## Markdown comments

Code:

```
Here's a paragraph that will be visible.

[This is a comment that will be hidden.]: #

And here's another paragraph that's visible.
```

Rendered:

Here's a paragraph that will be visible.

[This is a comment that will be hidden.]: #

And here's another paragraph that's visible.

## Weird comments

Code:

```
[//]: # (This syntax works like a comment, and won't appear in any output.)
[//]: # (It’s a little bizarre, but it works with MacDown and Pandoc.)
```

Rendered:

[//]: # (This syntax works like a comment, and won't appear in any output.)
[//]: # (It’s a little bizarre, but it works with MacDown and Pandoc.)
