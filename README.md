# Italy

## What's `football.db`?

A free open public domain football database & schema
for use in any (programming) language
(e.g. uses datasets in plain text).
More [`football.db` Project Site »](http://openfootball.github.io)


## Intro

Free open public domain football data for Italy / Europe.
Events include:

| Level |                             |           |
| ----: | --------------------------- | --------- |
|     I | Serie A                     | 20 Clubs  |


Example:

<!--
```
### Serie A Clubs

AC Milan | Associazione Calcio Milan, MIL
Internazionale | FC Internazionale Milano, INT
AS Roma | Associazione Sportiva Roma, ROM
Juventus FC |Juventus Football Club | Juventus Torino, JUV
...
```
-->

```
1^ Giornata

[24.8.]
  Hellas Verona  2-1  AC Milan
  Sampdoria      0-1  Juventus
[25.8.]
  Inter          2-0  Genoa CFC
  AS Livorno     0-2  AS Roma
  SSC Napoli     3-0  Bologna FC
...
```


## Build Your Own `italy.db` Copy

Use the `sportdb` command line tool to build your own `italy.db` copy
from the plain text fixtures. [More »](https://github.com/openfootball/datafile)


### Alternative I - Use the Quick Starter Templates

Use the quick starter datafile templates to start from scratch. Examples:

Build the database for all Italian clubs, leagues and seasons:

    $ sportdb new it

Build the database for the 2020/21 season:

    $ sportdb new it2020-21

[More »](https://github.com/openfootball/quick-starter)



### Alternative II - Do-It-Yourself (DIY) - Downlad and Unpack Zip Archive or Git Clone

Download and unpack the zip archive with the datasets or if you have git installed use the `git clone` command to
get a local copy.

Try in your working folder (that is, `/italy`):

```
$ sportdb build
$ sportdb --verbose build     # or for more (verbose) details incl. debug info
```

This will

- setup a new single-file SQLite database e.g. `./sport.db` and
- read in all datasets in plain text (`.txt`)

That's it.


## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!
