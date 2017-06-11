---
layout: post
title:  "Introduction to SQLite"
date:   2017-06-11 22:51:07 +0000
---


**SQLite** is a software library that implements a self-contained, serverless, zero-configuration, transactional SQL database engine. SQLite is one of the fastest-growing database engines around, but that's growth in terms of popularity, not anything to do with its size. The source code for SQLite is in the public domain.

**What is SQLite?**

SQLite is an in-process library that implements a self-contained, serverless, zero-configuration, transactional SQL database engine. It is a database, which is zero-configured, which means like other databases you do not need to configure it in your system.

SQLite engine is not a standalone process like other databases, you can link it statically or dynamically as per your requirement with your application. SQLite accesses its storage files directly.

**Why SQLite?**

SQLite does not require a separate server process or system to operate (serverless).

SQLite comes with zero-configuration, which means no setup or administration needed.

A complete SQLite database is stored in a single cross-platform disk file.

SQLite is very small and light weight, less than 400KiB fully configured or less than 250KiB with optional features omitted.

SQLite is self-contained, which means no external dependencies.

SQLite transactions are fully ACID-compliant, allowing safe access from multiple processes or threads.

SQLite supports most of the query language features found in SQL92 (SQL2) standard.

SQLite is written in ANSI-C and provides simple and easy-to-use API.

SQLite is available on UNIX (Linux, Mac OS-X, Android, iOS) and Windows (Win32, WinCE, WinRT).

**SQLite A Brief History**

2000 - D. Richard Hipp designed SQLite for the purpose of no administration required for operating a program.

2000 - In August, SQLite 1.0 released with GNU Database Manager.

2011 - Hipp announced to add UNQl interface to SQLite DB and to develop UNQLite (Document oriented database).
