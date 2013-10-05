scripts-misc
============

Miscellaneous scripts accumulated over the years, not as central as the ones in
http://github.com/johnkerl/scripts.

Windows workalikes for familiar Unix tools, from back in my NT days:
* grep.pl
* head.pl
* tail.pl
* uniq.pl
* wc.pl,
* whereis.pl,
* My_win_glob.pm,
* w.pl,
* notes about Perl and Windows file associations: perl-on-windows-notes.txt,
* toc.pl which works around the Windows association/redirection bug.

fixrlinks.pl:
When I rsync -rtlz between hosts on which the spelling of my home directory
differs (e.g. /u5/kerl on one and /home/kerl on the other), rsync doesn't
change the symlink referents.  This script can be run after an rsync to fix
that.

finddang.pl: Reports on dangling symlinks.

Substitute for makeindex which correctly handles alphabetization of text including \mathbb etc. in LaTeX files:
* kmkidx [kmkidx].
