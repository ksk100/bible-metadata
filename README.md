# bible-metadata

Metadata for various aspects of the Biblical text (and potenially other ancient texts, one day) in `JSON` format.  

Currently data is provided for the Lexham Hebrew Bible and the Nestle-Almond 27 Greek New Testament text, and for each book the following fields are available:

* Total number of words
* Number of chapters
* Mean number of words per chapter
* Book number in entire Bible
* Book number in the relevant testament

Three `JSON` files are available (in the `dist/json` directory): one containing a hash of the books indexed by book name, one containing an array of the books in bibliographic order, and one containing both the hash and the array.

Data was sourced from Jeffrey and Laura Kranz's _The Overview Bible Project_ and is used with permission.  See Jeffrey's blog post on [the longest book of the bible](http://overviewbible.com/longest-book-of-the-bible/) for more information.
