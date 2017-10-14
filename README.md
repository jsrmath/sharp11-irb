# sharp11-irb

The [iRb Jazz Corpus](https://musiccog.ohio-state.edu/home/index.php/iRb_Jazz_Corpus) is a corpus of over a thousand jazz standards.  It was assembled by the Cognitive and Systematic Musicology Laboratory at The Ohio State University and has been made freely available for music research.  This module contains a parsed and serialized version of this corpus for use with [Sharp11](https://github.com/jsrmath/sharp11).

# Usage

```
var s11 = require('sharp11');
var irb = require('sharp11-irb');

var irbCorpus = s11.corpus.load(irb); // A Sharp11 corpus object
```
