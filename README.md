# Migrating_to_Synergy_9<br />
**Created Date:** 5/1/2008<br />
**Last Updated:** 5/20/2008<br />
**Description:** This CodeExchange entry contains a collection of programs which highlight many
of the changes between the Synergy/DE V9 compiler, and earlier versions of the
compiler.<br />
**Platforms:** Windows<br />
**Products:** Synergy DBL<br />
**Minimum Version:** 9.1<br />
**Author:** Steve Ives
<hr>

**Additional Information:**
Each of the included programs compiles without errors or warnings under the
Synergy V8.3 compiler, but results in compiler errors or warnings when compiled
with the V9 compiler. Each source file includes comments which discuss the
reason for the change, and suggest how to address the issue.

The changes highlighted by the various programs are typical of the changes that
some developers may need to make to their applications when migrating to
Synergy/DE V9 for the first time.

Although all of the programs included will COMPILE with the V8.3 compiler,
several may have the possibilities of runtime errors. Typically the changes
required to make the code compile with the V9 compiler also removes the
possibility of these runtime errors.

Instructions:

Use Workbench to open the Workspace MigratingToSyerngy9.vpw

For each source file in the project

1). Open the file in the editor
2). Compile with the V8 compiler (Build menu, Compile With V8)
3). Compile with the V9 compiler (Build menu, Compile With V9)
4). Review the compiler errors or warnings
5). Review and implement the suggested solution
6). Compile with the V9 compiler (Build menu, Compile With V9)
