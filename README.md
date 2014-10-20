## wkhtmltopdf_binary_gem

This gem is a clone of the
[wkhtmltopdf-binary gem](https://github.com/zakird/wkhtmltopdf_binary_gem), with
the git history entirely erased.

The purpose of this repository is simple: to allow the inclusion of wkhtmltopdf
binaries on both local and production environments, without having to wait on
the original gem to be pushed up to Rubygems, and without incurring the massive
space overhead (from the binaries stored in the git history) that comes from
cloning the gem directly from the original gem's GitHub repo.

## Updating

In keeping with the spirit of this repository, updates should not update the git
history. Instead, `rm -rf .git` and then `git init` again, to avoid any git
history.

The `wkhtmltopdf-binary` gem is a real git repository. This is merely a
small-footprint clone, and should be treated as such.
