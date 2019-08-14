# Theatertechniek

Branch|[![Travis CI logo](pics/TravisCI.png)](https://travis-ci.org)
---|---
`master`|[![Build Status](https://travis-ci.org/richelbilderbeek/theatertechniek.svg?branch=master)](https://travis-ci.org/richelbilderbeek/theatertechniek)
`develop`|[![Build Status](https://travis-ci.org/richelbilderbeek/theatertechniek.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/theatertechniek)

These stagecraft videos are created by Richel Bilderbeek as course material for the course 'Stagecraft'.

Originally the movies were shot in WMV. Goals of this project is
 * to convert these to OGV without losing (even more) resolution
 * add the license to the movie

The movies are licensed under CC-BY-NC-SA, which is not yet explicitly visible in the movies.

## Videos

 * [De Drie Theaterwetten](https://github.com/richelbilderbeek/DeDrieTheaterwetten)

## Conversie

The conversion from WMV to OGV tried (but with terrible results):
<code>
for x in *.wmv; do avconv -i "$x" -flags +ilme+ildct+alt "`basename "$x" .wmv`.ogv"; done
</code>


