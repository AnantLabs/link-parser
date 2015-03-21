The Link Grammar Parser http://www.link.cs.cmu.edu/link/ is a syntactic parser of English. Given a sentence, the system assigns to it a syntactic structure, which consists of a set of labeled links connecting pairs of words. It is written in the C programming language, and is under the GNU GPL license.

The current project updates this parser with assorted fixes and enhancements. These include:

  * Dictionary updates
  * Java bindings
  * Bug fixes
  * Improved build system

Currently, the source code and the latest source code is at

http://www.abisource.com/projects/link-grammar/

Source fixes include:
  * Use of automake/autoconf/configure build system, to make building easier.
  * Move of dictionaries to en directory, enabling inclusion of other languages.
  * Placeholders for entities, allowing entity detection software to be used.

Dictionary fixes include:
  * New link types for comparatives, so as to link relative clauses.
  * Fixes for "Expresso is a coffee drink"
  * "Teach me fetch"
  * "I am pooped" as synonym for "I am tired"
  * "Mother likes her." "Mommy loves me." and related.
  * "Go play ball." "Go take a walk." "You and Rover go play with the ball."