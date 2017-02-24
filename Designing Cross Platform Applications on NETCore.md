# Designing Cross Platform Applications on .NET Core

If you have been developing .NET applications within the past 15 years, you have traditionally been supporting only Windows.  Because, of course, the .NET Framework was designed to only run on Windows.  

If you were adventurous, you could attempt to run your application on Linux or Mac using the Mono compiler.  However, some inconsistencies in the implementation of common libraries meant you had to target one environment or another -- never both.  

With the release of .NET Core, the prophecy of being able to build true cross-platform applications using .NET is coming true!  However, it isn't as easy as File, New.  Design decisions you make can impact your ability to easy work across platforms.  In this presentation, attendees will learn how to create cross platform .NET Core applications and how to avoid the pitfalls that will land them back into Windows-only mode.

In this presentation, attendees will:
- Learn about .NET Standard versus the .NET Framework
- Learn the anatomy of a .NET Core application versus a full .NET framework application
- Build the scaffold for an application that will work on Windows, Linux, Mac, and even in Docker!