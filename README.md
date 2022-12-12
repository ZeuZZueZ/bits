Bitcoin Core integration/staging tree
=====================================

https://bitcoincore.org
<img src="https://raw.githubusercontent.com/wiki/epezent/implot/screenshots3/tables.gif" width="270">

For an immediately usable, binary version of the Bitcoin Core software, see
https://bitcoincore.org/en/download/.

What is Bitcoin Core?
---------------------

Bitcoin Core connects to the Bitcoin peer-to-peer network to download and fully
validate blocks and transactions. It also includes a wallet and graphical user
interface, which can be optionally built.

Further information about Bitcoin Core is available in the [doc folder](/doc).

License
-------

Bitcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process

<a href="https://github.com/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=ZeuZZueZ&repo=github-readme-stats" />
</a>

  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"> 
  
<a href="https://github.com/Pepyn0/github-readme-stats">
  <img width=450 height=170 align="center" src="https://github-readme-stats.vercel.app/api?username=anuraghazra&theme=midnight-purple&show_icons=true&bg_color=0D1117&hide_border=true" />
</a>
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&theme=midnight-purple&layout=compact&bg_color=0D1117&hide_border=true" />
</a>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"> 

<div>
  <img src="https://github.com/Pepyn0/Pepyn0/raw/output/github-contribution-grid-snake.svg" alt="snake"></center>
</div>

<br/>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)

## Stack
![Bitcoin](https://img.shields.io/badge/anuraghazra?style=for-the-badge&logo=bitcoin&logoColor=white)
-------------------

The `master` branch is regularly built (see `doc/build-*.md` for instructions) and tested, but it is not guaranteed to be
completely stable. [Tags](https://github.com/bitcoin/bitcoin/tags) are created
regularly from release branches to indicate new official, stable release versions of Bitcoin Core.

The https://github.com/bitcoin-core/gui repository is used exclusively for the
development of the GUI. Its master branch is identical in all monotree
repositories. Release branches and tags do not exist, so please do not fork
that repository unless it is for development reasons.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md)
and useful hints for developers can be found in [doc/developer-notes.md](doc/developer-notes.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing


Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The CI (Continuous Integration) systems make sure that every pull request is built for Windows, Linux, and macOS,
and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing


Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Changes to translations as well as new translations can be submitted to
[Bitcoin Core's Transifex page](https://www.transifex.com/bitcoin/bitcoin/).

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.







<table cellspacing="0" style="height: 300px; width: 300px;"><tr><td style="padding: 0px;"></td><td style="padding: 0px; position: relative; width: 226px; height: 274px;"><div style="width: 100%; height: 100%; position: relative; overflow: hidden;"><canvas width="678" height="822" style="width: 226px; height: 274px; position: absolute; z-index: 1; left: 0px; top: 0px;"></canvas><canvas width="678" height="822" style="width: 226px; height: 274px; position: absolute; z-index: 2; left: 0px; top: 0px;"></canvas></div></td><td style="padding: 0px;"><div style="height: 274px; overflow: hidden; width: 74px; left: 0px; position: relative; min-width: 74px;"><canvas width="222" height="822" style="width: 74px; height: 274px; position: absolute; z-index: 1; left: 0px; top: 0px;"></canvas><canvas width="222" height="822" style="width: 74px; height: 274px; position: absolute; z-index: 2; left: 0px; top: 0px;"></canvas></div></td></tr><tr><td style="padding: 0px;"></td><td style="height: 26px; padding: 0px; width: 226px;"><div style="width: 100%; height: 100%; position: relative; overflow: hidden;"><canvas width="678" height="78" style="width: 226px; height: 26px; position: absolute; z-index: 1; left: 0px; top: 0px;"></canvas><canvas width="678" height="78" style="width: 226px; height: 26px; position: absolute; z-index: 2; left: 0px; top: 0px;"></canvas></div></td><td style="padding: 0px;"><div style="width: 74px; height: 26px; overflow: hidden; min-width: 74px;"><canvas width="222" height="78" style="width: 74px; height: 26px;"></canvas></div></td></tr></table>


<z/> bitcoin> [div] "amanciojsilvjr"












