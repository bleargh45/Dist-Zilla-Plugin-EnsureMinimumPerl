# NAME

Dist::Zilla::Plugin::EnsureMinimumPerl - Ensure that you have specified a minimum version of Perl

# SYNOPSIS

```
# In your dist.ini
[EnsureMinimumPerl]
```

# DESCRIPTION

This `Dist::Zilla` plugin checks to ensure that you have specified a minimum
required version of Perl, before allowing you to perform a release.

I kept forgetting to be explicit about this in my own releases, and so I
whipped this up to force me to do it.

# AUTHOR

Graham TerMarsch (cpan@howlingfrog.com)

# COPYRIGHT

Copyright (C) 2021-, Graham TerMarsch.  All Rights Reserved.

This is free software; you can redistribute it and/or modify it under the same
license as Perl itself.

# SEE ALSO

- [Dist::Zilla](https://metacpan.org/pod/Dist%3A%3AZilla)
