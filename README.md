Run `rustfmt --write-mode=diff src/lib.rs` against this library. Only sometimes
will it pick up the formatting error.

The problem seems to be due to the macro in src/alpha/mod.rs.

Note that this code does not compile, but it is a severely cut-down version of
a project which does.
