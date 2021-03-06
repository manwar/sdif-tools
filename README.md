# NAME

sdif-tools - sdif and family tools, cdif and watchdiff

# SYNOPSIS

sdif f1 f2

diff f1 f2 | cdif

git diff | sdif --cdif -n

watchdiff df

# DESCRIPTION

**sdif-tools** are composed by **sdif** and related tools including
**cdif** and **watchdiff**.

**sdif** prints diff output in side-by-side format.

**cdif** adds visual effect for diff output, comparing lines in
word-by-word, or character-by-character bases.

**watchdiff** calls specified command repeatedly, and print the output
with visual effect to emphasize modified part.

See individual manual of each command for detail.

# SEE ALSO

[sdif](https://metacpan.org/pod/sdif), [cdif](https://metacpan.org/pod/cdif), [watchdiff](https://metacpan.org/pod/watchdiff)

# LICENSE

Copyright (C) Kaz Utashiro.

These commands and libraries are free software; you can redistribute
it and/or modify it under the same terms as Perl itself.

# AUTHOR

Kaz Utashiro <kaz@utashiro.com>
