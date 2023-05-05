Awesome Series @ Planet Open Data

[World (Countries, Cities, Codes, ...)](https://github.com/planetopendata/awesome-world) • 
[Football (Clubs, Players, Stadiums, ...)](https://github.com/planetopendata/awesome-football) •
[SQLite (Tools, Books, Schemas, ...)](https://github.com/planetopendata/awesome-sqlite)


# SQLite

A collection of awesome (open source) sqlite tools, scripts, books, etc.


**Contributions welcome. Anything missing? Send in a pull request. Thanks.**

Note:  For closed source / proprietary free or non-free sqlite tools & services, see the [**COMMERCIAL page »**](COMMERCIAL.md)




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

- **sqlean** (github: https://github.com/nalgeon/sqlean) by nalgeon
- **Text File Reader for SQLite (TFR4SQLite)** (github: [elau1004/TFR4SQLite](https://github.com/elau1004/TFR4SQLite)) by Edward Lau  -- read any structured text file according to your parsing spec into SQLite


## SQLite Derivates

- **sql.js** (github: [sql-js/sql.js](https://github.com/sql-js/sql.js)) -- SQLite compiled to JavaScript (using asm.js) through Emscripten

Talks

-  [**Inside Punkbase - SQLite (SQL.js) In Action**](https://github.com/cryptopunksnotdead/punkbase/tree/master/insidepunkbase) 

Breaking News 

**SQLite Gets Offical "First-Class" WebAssembly & JavaScript Support**

see [**sqlite.org/wasm »**](https://sqlite.org/wasm)

Announced in October 2022 the about page reads:

> About the sqlite3 WASM/JS Subproject
> WebAssembly, a.k.a. WASM, is a standard defining a low-level programming language suitable
> (A) as a target for cross-compilation from many other languages and 
> (B) for running via a virtual machine in a browser.
> Designed with scriptability via JavaScript in mind, it provides a way to compile C code (among others) to WASM and script 
> it via JavaScript with relatively little friction despite the vast differences between JavaScript and C.
>
> Folks have been building sqlite3 for the web since as far back as 2012
> but this subproject is the first effort "officially" associated with the SQLite project, 
> created with the goal of making WASM builds of the library first-class members of the family of supported SQLite deliverables.



## SQLite-based Distributed Database

- **rqlite** (github: [rqlite/rqlite](https://github.com/rqlite/rqlite)) by Philip O'Toole et al -- The lightweight, distributed relational database built on SQLite


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

Swift

- **Lighter.swift** (github: [lighter-swift/lighter](https://github.com/lighter-swift), pkg: [Lighter](https://github.com/Lighter-swift/Lighter)) -- SQLite code generator and db packager for Swift

and many more 


## SQLite Admin Tools

### Web

- **sqlite-web** ★217 (github: [coleifer/sqlite-web](https://github.com/coleifer/sqlite-web)) by Charles Leifer -- a web-based SQLite database browser written in Python
- **sqliteweb** ★46 (github: [hypebeast/sqliteweb](https://github.com/hypebeast/sqliteweb)) by Sebastian Ruml -- a web-based SQLite database browser written in Go
- **phpliteadmin** ★31  (web: [phpliteadmin.org](https://www.phpliteadmin.org), github: [phpLiteAdmin/pla](https://github.com/phpLiteAdmin/pla)) -- a web-based SQLite database admin tool written in PHP
- **web gui for sqlite** (web: [extendsclass.com](https://extendsclass.com/sqlite-browser.html), github: [hautdefrance/Web-GUI-for-SQLite](https://github.com/hautdefrance/Web-GUI-for-SQLite) by Cyril Bois -- a web-based SQLite database browser written in JavaScript

### Desktop

Major

- **SQLiteStudio** (web: [sqlitestudio.pl](http://sqlitestudio.pl)) - Linux, Windows, Mac OS X
- **DB Browser for SQLite** ★3,718 (web: [sqlitebrowser.org](http://sqlitebrowser.org), github: [sqlitebrowser/sqlitebrowser](https://github.com/sqlitebrowser/sqlitebrowser)) -- formerly known as SQLite Database Browser
- [**SQLite Toolbox**](https://visualstudiogallery.msdn.microsoft.com/0e313dfd-be80-4afb-b5e9-6e74d369f7a1) (codeplex: [sqlcetoolbox] (http://sqlcetoolbox.codeplex.com)) -- Visual Studio extension (add-in); coded by Erik Ejlskov Jensen
- [DataStation](https://github.com/multiprocessio/datastation) - Easily query, script, and visualize data from every database, file, and API.




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
- **csvs-to-sqlite** (github: [simonw/csvs-to-sqlite](https://github.com/simonw/csvs-to-sqlite), pypi: [csvs-to-sqlite](https://pypi.org/project/csvs-to-sqlite/)) -- Python command-line tool for loading one or more CSV files and converting them into a SQLite database

## PostgreSQL-to-SQLite

- **pg2sqlite** (codeberg: [louis77/pg2sqlite](https://codeberg.org/louis77/pg2sqlite)) -- Go command-line tool for automatically migrating tables from PostgreSQL to SQLite incl. generating DDL

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
- **Northwind.db** (github: [jpwhite3/northwind-SQLite3](https://github.com/jpwhite3/northwind-SQLite3), Swift pkg: [NorthwindSQLite.swift](https://github.com/Lighter-swift/NorthwindSQLite.swift)) - food store (customers, products, orders, employees, suppliers, ...) with sample data; port of the "classic" Microsoft Northwind database


## SQLite Web Service (JSON API) Publishers / Containers

_Turn your Database into Ready-to-Use (Instant) Online Web Services (JSON APIs) w/ Query Language (QL)_

- **Datasette** (github: [simonw/datasette](https://github.com/simonw/datasette)) by Simon Willison - an instant JSON API for your SQLite databases



## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the sqlite-users mailing list. Thanks!
