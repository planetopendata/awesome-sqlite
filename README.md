Awesome Series @ Planet Open Data

[World (Countries, Cities, Codes, ...)](https://github.com/planetopendata/awesome-world) • 
[Football (Clubs, Players, Stadiums, ...)](https://github.com/planetopendata/awesome-football) •
[SQLite (Tools, Books, Schemas, ...)](https://github.com/planetopendata/awesome-sqlite)


# SQLite

A collection of awesome sqlite tools, scripts, books, etc.

---

[ANNOUNCEMENT] Looking for awesome SQLite libraries in Ruby? See the [Awesome ActiveRecord List @ Planet Ruby](https://github.com/planetruby/awesome-activerecord). 

---

#### _Contributions welcome. Anything missing? Send in a pull request. Thanks._


## SQLite Headquarters (HQ)

_Small. Fast. Reliable. Choose any three._

- **SQLite** (web: [sqlite.org](http://www.sqlite.org)) by D. Richard Hipp et al
  - [Versions / Release History](http://www.sqlite.org/changes.html)
    - 2013: 3.8.0 (Aug/26) 
    - 2010: 3.7.0 (Jul/22)
  - [Talk](http://mailinglists.sqlite.org/cgi-bin/mailman/listinfo/sqlite-users) - sqlite-users mailing list

Articles

- [SQLite As An Application File Format](https://www.sqlite.org/appfileformat.html)
- [In-Memory Databases](http://www.sqlite.org/inmemorydb.html)


## SQLite Documentation / History

- [Article: SQLite @ Wikipedia](http://en.wikipedia.org/wiki/SQLite)

## SQLite Books

- [The Definitive Guide to SQLite (2nd Edition)](http://www.apress.com/9781430232254) - by Mike Owens and Grant Allen; 2010; Apress; 368 pages
- [Using SQLite](http://shop.oreilly.com/product/9780596521196.do) - by Jay A. Kreibich; 2010, O'Reilly; 530 pages
- [Getting Started with SQL - A Hands-On Approach for Beginners](http://shop.oreilly.com/product/0636920044994.do) - by Thomas Nield; 2016; O'Reilly; 134 pages -- learn SQL with SQLite and SQLiteStudio

## SQLite Modules / Extensions

- **Text File Reader for SQLite (TFR4SQLite)** (github: [elau1004/TFR4SQLite](https://github.com/elau1004/TFR4SQLite)) by Edward Lau  -- read any structured text file according to your parsing spec into SQLite


## SQLite Derivates

- **sql.js** (github: [kripken/sql.js](https://github.com/kripken/sql.js)) -- SQLite compiled to JavaScript (using asm.js) through Emscripten 


## Middleware

Microsoft ODBC

- [SQLite ODBC Driver](http://www.ch-werner.de/sqliteodbc) - coded by Christian Werner

Java JDBC

- [SQLite JDBC Driver (sqlite.jar)](http://www.ch-werner.de/javasqlite) - a Java wrapper includes a basic JDBC driver for SQLite; coded by Christian Werner
- [SQLite JDBC Driver (sqlite-jdbc.jar)](https://bitbucket.org/xerial/sqlite-jdbc) - a library for accessing SQLite databases through the JDBC API; coded by Taro L. Saito


## Language Bindings

R Language

- **RSQLite** (github: [rstats-db/RSQLite](https://github.com/rstats-db/RSQLite), cran: [RSQLite](http://cran.r-project.org/web/packages/RSQLite)) -- SQLite interface for R 

Ruby

- **sqlite3** (github: [sparklemotion/sqlite3-ruby](https://github.com/sparklemotion/sqlite3-ruby), gem: [sqlite3](https://rubygems.org/gems/sqlite3)) -- SQLite interface for Ruby

Microsoft .NET

- **System.Data.SQLite** (web: [system.data.sqlite.org](http://system.data.sqlite.org)) --  a SQLite ActiveX Data Objects (ADO).NET driver with Language-Integrated Query (LINQ) and Entity Framework support; official support by SQLite HQ

Visual Basic for Applications (VBA)

- **SQLite for Excel** (codeplex: [sqliteforexcel](https://sqliteforexcel.codeplex.com)) -- SQLite wrapper for VBA

and many more 


## SQLite Admin Tools

### Web

- **sqlite-web** ★217 (github: [coleifer/sqlite-web](https://github.com/coleifer/sqlite-web)) by Charles Leifer -- a web-based SQLite database browser written in Python
- **sqliteweb** ★46 (github: [hypebeast/sqliteweb](https://github.com/hypebeast/sqliteweb)) by Sebastian Ruml -- a web-based SQLite database browser written in Go
- **phpliteadmin** ★31  (web: [phpliteadmin.org](https://www.phpliteadmin.org), github: [phpLiteAdmin/pla](https://github.com/phpLiteAdmin/pla)) -- a web-based SQLite database admin tool written in PHP


### Desktop

Major

- **SQLiteStudio** (web: [sqlitestudio.pl](http://sqlitestudio.pl)) - Linux, Windows, Mac OS X
- **DB Browser for SQLite** ★3,718 (web: [sqlitebrowser.org](http://sqlitebrowser.org), github: [sqlitebrowser/sqlitebrowser](https://github.com/sqlitebrowser/sqlitebrowser)) -- formerly known as SQLite Database Browser
- [**SQLite Toolbox**](https://visualstudiogallery.msdn.microsoft.com/0e313dfd-be80-4afb-b5e9-6e74d369f7a1) (codeplex: [sqlcetoolbox] (http://sqlcetoolbox.codeplex.com)) -- Visual Studio extension (add-in); coded by Erik Ejlskov Jensen


Minor

- [SQLite Expert](http://www.sqliteexpert.com) - note: free personal edition and commercial "professional" edition
- [SQLiteSpy](http://www.yunqa.de/delphi/doku.php/products/sqlitespy/index)
- [SQLite Administrator](http://sqliteadmin.orbmu2k.de)


## SpatiaLite 

_A spatial SQLite extension for vector geodata functionality_

- [SpatiaLite](http://www.gaia-gis.it/gaia-sins)
    - [libspatialite](https://www.gaia-gis.it/fossil/libspatialite/index)
    - [SpatiaLite Command Line Tools](https://www.gaia-gis.it/fossil/spatialite-tools/index)
    - [SpatiaLite Admin Tool](https://www.gaia-gis.it/fossil/spatialite_gui/index)
- [Article: SpatiaLite @ Wikipedia](http://en.wikipedia.org/wiki/SpatiaLite)


## Text-to-SQLite

- **datapak** (github: [textkit/datapak](https://github.com/textkit/datapak), gem: [datapak](https://rubygems.org/gems/datapak)) -- Ruby tool and library for working with tabular data packages (.csv files w/ .json) using SQLite (via ActiveRecord)
- **q command line tool** (github: [harelba/q](https://github.com/harelba/q) -- Python script; lets you run SQL directly on CSV files

## Misc

- **R-Package sqldf** (github: [ggrothendieck/sqldf](https://github.com/ggrothendieck/sqldf), cran: [sqldf](http://cran.r-project.org/web/packages/sqldf)) -- perform SQL selects on R data frames


## Schema Documentation Generators

- **schemadoc** (github: [rubylibs/schemadoc](https://github.com/rubylibs/schemadoc), gem: [schemadoc](https://rubygems.org/gems/schemadoc)) -- documents your database schemas (tables, columns, etc.); uses SQLite (via ActiveRecord)
- **sqleton** (github: [inukshuk/sqleton](https://github.com/inukshuk/sqleton)) by Sylvester Keil -- ['skelɪtən]; visualizes your SQLite database schema (requires graphviz)



## SQLite Schemas

_Ready-to-Use (Instant) Database Schemas_

<!-- do be done
- [world.db :octocat:]()  - countries, states, cities, counties, munis, districts, places, names, etc.
-->

- **football.db** (github: [openfootball/schema.sql](https://github.com/openfootball/schema.sql)) - teams, competitions, seasons, matches, goals, rounds, groups, etc.
- **beer.db** (github: [openbeer/schema.sql](https://github.com/openbeer/schema.sql))  - beer, brand, brewery, etc.
- **Chinook Database** (codeplex: [chinookdatabase](http://chinookdatabase.codeplex.com)), [(chinook.sqlite Download)](http://chinookdatabase.codeplex.com/releases/view/55681) -  online music store (artists, albums, genres, playlists, media tracks, customers, invoices, employees) with sample data; inspired by the "classic" Microsoft Northwind database


## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the sqlite-users mailing list. Thanks!
