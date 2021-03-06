<!-- omit in toc -->
# Awesome Game of Life [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Conway's Game of Life resources and tools.

<!-- omit in toc -->
## Contents

- [Introduction](#introduction)
- [Pattern Collections](#pattern-collections)
- [Simulation](#simulation)
  - [Downloadable](#downloadable)
  - [Online](#online)
  - [Library](#library)
- [Searching](#searching)
  - [Soup search](#soup-search)
  - [Row-by-row](#row-by-row)
  - [Cell-by cell](#cell-by-cell)
  - [SAT](#sat)
  - [Catalyst](#catalyst)
  - [Miscellaneous](#miscellaneous)
- [Blogs and News](#blogs-and-news)
  - [News](#news)
  - [Blogs](#blogs)
  - [Personal Life Pages](#personal-life-pages)
- [Links](#links)

## Introduction

- [LifeWiki page](https://www.conwaylife.com/wiki/Conway%27s_Game_of_Life)
- [Wikipedia page](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
- [Wolfram MathWorld page](http://mathworld.wolfram.com/GameofLife.html)

## Pattern Collections

- [LifeWiki](https://www.conwaylife.com/wiki/Main_Page) - The wiki for Conway's Game of Life.
- [Life Lexicon](https://www.conwaylife.com/ref/lexicon/lex_home.htm) - A lexicon of terms relating to John Horton Conway's Game of Life.
- [jslife](http://entropymine.com/jason/life/#collections) -  Jason Summers' pattern collections.
- [Catagolue](https://catagolue.appspot.com/home) - An ongoing distributed census of naturally occurring ash objects.
- [Gliders in Life-Like Cellular Automata](https://www.conwaylife.com/gliders/golly-index.html) - An online database of gliders in 2D cellular automaton rules such as Conway's Life.
- [Golly Online Archives](http://golly.sourceforge.net/Help/archives.html) -  Golly can download patterns, rules and scripts from these online archives.
- [Shinjuku](https://gitlab.com/parclytaxel/Shinjuku) - A database of glider syntheses.

## Simulation

### Downloadable

- [Golly](http://golly.sourceforge.net/) - An an open source, cross-platform application for exploring Conway's Game of Life and many other types of cellular automata.
- [LifeViewer](https://lazyslug.com/lifeview/) - A scriptable pattern viewer and editor used to simulate Life and other Life-like cellular automata. Written in Javascript/HTML5.
- [Mirek's Cellebration (MCell)](http://www.mirekw.com/ca/index.html) - A 32-bit Windows program whose main purpose is exploring existing and creating new rules and patterns of 1-D and 2-D Cellular Automata.
- [Life32](https://github.com/JBontes/Life32) - A player/editor for conway's game of life and related CA's. Will run on any Windows version from XP to 10.

### Online

- [copy.sh/life/](http://copy.sh/life/) - A JavaScript version of Conway's Game of Life, based on the Hashlife-algorithm.
- [Golly for the Web](http://golly.sourceforge.net/webapp/golly.html) - A web version of Golly.
- [Golgi](http://mame.github.io/golgi/) - A "Cellular" Viewer for Conwey's Game of Life

### Library

- [lifelib](https://gitlab.com/apgoucher/lifelib) - A fast C++ library for simulation and manipulation of patterns in cellular automata.

## Searching

See also: [Tutorials/Software on LifeWiki](https://www.conwaylife.com/wiki/Tutorials/Software).

### Soup search

- [apgsearch](https://gitlab.com/apgoucher/apgmera) - A program for searching random initial configurations in cellular automata and reporting to a centralised server ([Catagolue](https://catagolue.appspot.com/home)).
- [Random Agar](http://www.gabrielnivasch.org/fun/life/) - A program intended to look for new Life oscillators, wicks, and agars.

### Row-by-row

- [gfind](https://www.ics.uci.edu/~eppstein/ca/gfind.c) - A breadth-first search program for spaceships using de Bruijn graphs.
- [knights](https://github.com/Matthias-Merzenich/knightt-results)
- [afind](https://github.com/conwaylife/afind)
- [zfind](https://github.com/rokicki/ntzfind)
- [qfind](https://github.com/Matthias-Merzenich/qfind)
- [ofind](https://www.ics.uci.edu/~eppstein/ca/ofind.c) - A breadth first search program for low-period oscillators using an algorithm similar to gfind.

### Cell-by cell

- [lifesrc](http://members.tip.net.au/~dbell/programs/lifesrc-3.8.tar.gz) - A depth-first backtracking search program for low-period spaceships, oscillators, still lifes, puffers, or predecessors of a given pattern.
- [WinLifeSearch (WLS)](http://entropymine.com/jason/life/software/) - A graphical Windows port of lifesrc.
- [JavaLifeSearch (JLS)](https://www.conwaylife.com/forums/viewtopic.php?f=9&t=990) - A platform-independent Java version of lifesrc.
- [Rust Life Search (rlifesrc)](https://alephalpha.github.io/rlifesrc/) - A Rust and WebAssembly version of lifesrc.

### SAT

- [Logic Life Search (LLS)](https://github.com/OscarCunningham/logic-life-search) - A program to search for patterns in Conway's Game of Life (and other cellular automata) by use of a SAT solver.
- [LifeFind](https://github.com/AlephAlpha/LifeFind) - A simple and naïve Game of Life pattern searcher written in Wolfram Language.

### Catalyst

- [Bellman](https://sourceforge.net/projects/bellman/) - A
program for searching for catalytic interactions in Conway's Game of Life and potentially other similar cellular automata.
- [Catalyst](http://www.gabrielnivasch.org/fun/life/) - A program that finds ways of modifying the evolution of an input pattern by placing catalysts that react with it, by a backtracking search.
- [CatForce](https://github.com/simsim314/CatForce) - A catalyst search utility using brute force space search.
- [CollisionsSearch](https://www.conwaylife.com/forums/viewtopic.php?f=9&t=2246)
- [ptbsearch](https://github.com/conwaylife/ptbsearch)

### Miscellaneous

- [drifter (dr)](https://www.conwaylife.com/forums/viewtopic.php?f=9&t=4247) - Finds patterns consisting of a small perturbation "drifting" across a still-life background.
- [HoneySearch](https://gitlab.com/apgoucher/slmake/) - A parallelised search program to find simple slow-salvos for moving, converting, and copying objects.
- [slmake](https://gitlab.com/apgoucher/slmake/) - A program for assembling slow salvo syntheses of stable constellations by tail recursion.
- [ikpx](https://gitlab.com/apgoucher/metasat) - A search program for oblique spaceships in Conway's Life, combining gfind's row-by-row search and LLS's usage of SAT solvers.
- [life slice ship search](https://gitlab.com/andrew-j-wade/life_slice_ship_search) - A depth first spaceship search for Conway's life, using divide and conquer strategies.
- [gencol](https://conwaylife.com/ref/lifepage/gencols.txt) - A program that searches for pattern interactions in Conway's Game of Life by generating interactions between pairs of patterns.

## Blogs and News

### News

- [LifeWiki:News archive](https://www.conwaylife.com/wiki/LifeWiki:News_archive)
- [Game of Life News](http://pentadecathlon.com/lifeNews/)

### Blogs

- [Conway's Life: Work in Progress](https://b3s23life.blogspot.com/)
- [MathematRec](https://mathematrec.wordpress.com/)
- [Complex Projective 4-Space](https://cp4space.wordpress.com/) - The blog of Adam P. Goucher.

### Personal Life Pages

- [Achim Flammenkamp](http://wwwhomes.uni-bielefeld.de/achim/gol.html)
- [David Bell](http://members.tip.net.au/~dbell/)
- [David Eppstein](https://www.ics.uci.edu/~eppstein/ca/)
- [Dean Hickerson](https://conwaylife.com/ref/DRH/)
- [Gabriel Nivasch](http://www.gabrielnivasch.org/fun/life)
- [Jason Summer](http://entropymine.com/jason/life/)
- [Mark D. Niemiec](http://codercontest.com/mniemiec/lifepage.htm/)
- [Paul Callahan](https://conwaylife.com/ref/lifepage/)

## Links

- [LifeWiki:Life links](https://www.conwaylife.com/wiki/LifeWiki:Life_links)
- [Golly References](http://golly.sourceforge.net/Help/refs.html)
