Gaana-Dl
========
Its fun listening to your favourite Bollywood songs on <a href='http://gaana.com'>gaana.com</a>.

Double up the fun by downloading the whole album from gaana.com directly to your computer for free.

Search your favorite songs in the terminal and listen it all day long even without internet.

Just Clone this Repo.

Installation
============
* `git clone git@github.com:tusharbabbar/gaana-dl.git`
* `pip install -r requirements.txt`

Usage
=====
* usage: gaana-dl.py&nbsp;[-h] [-a [ALBUM]] [-s [SONG]]
* optional arguments:

  + -h, --help            show this help message and exit


  + -a [ALBUM], --album [ALBUM]
                        choose this to search albums. Space seperated query
                        must be enclosed in quotes('')


  + -s [SONG], --song [SONG]
                        choose this to search songs. Space seperated query
                        must be enclosed in quotes('')

  + -d [DIR], --dir [DIR]
                        can be used to specify directory to download songs to
  
  + -p [dummy], --playlist [DIR]
                        specify that you want to download existing playlists.
