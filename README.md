<picture>
  <source media="(prefers-color-scheme: dark)" srcset="bad-apple-128x96-dark.svg">
  <img src="bad-apple-128x96.svg" width="832" alt="Bad Apple!! played on a contribution graph">
</picture>

```text
      __              __                     __     ____
     / /_  ____ _____/ /  ____ _____  ____  / /__  / / /
    / __ \/ __ `/ __  /  / __ `/ __ \/ __ \/ / _ \/ / /
   / /_/ / /_/ / /_/ /  / /_/ / /_/ / /_/ / /  __/_/_/
  /_.___/\__,_/\__,_/   \__,_/ .___/ .___/_/\___(_|_)
                            /_/   /_/
                                   commit graph edition
                                         by mightsleep

  .------------------------------------------------------.
  |  type ........ animated SVG in a profile README      |
  |  grid ........ 128 x 96 contribution cells, 4:3      |
  |  frames ...... 6572 + greetz, 30 fps, 4:05           |
  |  size ........ 4.7 MB raw, 789 KB gzip               |
  |  javascript .. none were harmed                      |
  |  sound ....... bring your own                        |
  `------------------------------------------------------'

  how it works
    The whole video is a single <path fill-rule="evenodd">.
    Even-odd fill is addition over GF(2), so a frame is
    nothing but its outline. SMIL swaps the path 30 times
    a second, in short chained runs with explicit keyTimes,
    because browsers disagree on how to divide time and
    long value lists are slow. Cell centers sit on halves
    and the outline on integers, so a stroke two cells
    wide covers exactly the edge band. The band shows noise
    in GitHub's own greens.

  credits
    Bad Apple!! PV ......... Anira
    song ................... Alstroemeria Records feat. nomico
    original melody ........ ZUN (Touhou)

  greetz
    ryg * the demoscene * HAKMEM * Hacker's Delight
```
