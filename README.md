pgAdmin III README
==================

**NOTE!** This is a fork of https://github.com/Symbiatch/pgAdmin3, which supports
PostgreSQL 11 and newer. The addition of this fork is, that it gets compiled
on Linux systems smoothly and has few more fixes:

- uses the latest version of wxWidgets
- contains some fix regarding plugins factory
- contains fix of .gitignore and improved desktop integration
- contains markdown versions of README and INSTALL

#### The original note from Symbiatch:  
This is a fork of the official pgAdmin3 due to it no longer being
maintained. This fork is meant to provide support for new PostgreSQL server
versions to users who want to use pgAdmin3 rather than pgAdmin4. If you have
issues with this version do NOT contact the original developers, rather post
an issue or a pull request on Github.

The binaries are available at https://tokavuh.com/pgadmin3redux/
Note! The application is in debug mode and will show some warnings. I am
trying to get it to compile and work in release mode so these would go away
as well as fixing the underlying issues (newer wxWidgets libraries).


Introduction
------------

pgAdmin III is the most popular and feature rich Open Source administration and
development platform for PostgreSQL, the most advanced Open Source database in
the world. The application may be used on Linux, FreeBSD, Solaris, Mac OS X and 
Windows platforms to manage PostgreSQL 8.2 and above running on any platform,
as well as commercial versions of PostgreSQL such as Mammoth PostgreSQL, 
EnterpriseDB Postgres Plus Advanced Server and Greenplum Database.

pgAdmin III is designed to answer the needs of all users, from writing simple 
SQL queries to developing complex databases. The graphical interface supports 
all PostgreSQL features and makes administration easy. The application also 
includes a syntax highlighting SQL editor, a server-side code editor, an 
SQL/batch/shell job scheduling agent, support for the Slony-I replication 
engine and much more. Server connection may be made using TCP/IP or Unix Domain
Sockets (on *nix platforms), and may be SSL encrypted for security. No 
additional drivers are required to communicate with the database server.

pgAdmin III is developed by a community of PostgreSQL experts around the world 
and is available in more than a dozen languages. It is Free Software released 
under the PostgreSQL License.

Compilation
-----------

Please see the [INSTALL](INSTALL.md) file for compilation and installation instructions.

Translation
-----------

Translation into your preferred language is easily possible even for 
non-programmers. Please see http://www.pgadmin.org/translation/ for 
further details.
