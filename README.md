# 02purl.details.txt

**!!! EXPERIMENTAL PROJECT !!!**

Converts `02packages.details.txt`, adds PURL strings, and creates `02purl.details.txt` file.

`02purl.details.txt` file may be useful for CPAN clients that support PURL strings.

`02packages.details.txt`

```
[...]
URI::PackageURL                    2.23  G/GD/GDT/URI-PackageURL-2.23.tar.gz
URI::PackageURL::App               2.23  G/GD/GDT/URI-PackageURL-2.23.tar.gz
URI::PackageURL::CLI               2.04  G/GD/GDT/URI-PackageURL-2.04.tar.gz
URI::PackageURL::Util              2.23  G/GD/GDT/URI-PackageURL-2.23.tar.gz
URI::VersionRange                  2.23  G/GD/GDT/URI-PackageURL-2.23.tar.gz
URI::VersionRange::App             2.23  G/GD/GDT/URI-PackageURL-2.23.tar.gz
URI::VersionRange::Constraint      2.23  G/GD/GDT/URI-PackageURL-2.23.tar.gz
URI::VersionRange::Version        undef  G/GD/GDT/URI-PackageURL-2.23.tar.gz
[...]
```

`02purl.details.txt`

```
[...]
URI::PackageURL                     2.23  pkg:cpan/GDT/URI-PackageURL@2.23
URI::PackageURL::App                2.23  pkg:cpan/GDT/URI-PackageURL@2.23
URI::PackageURL::CLI                2.04  pkg:cpan/GDT/URI-PackageURL@2.04
URI::PackageURL::Util               2.23  pkg:cpan/GDT/URI-PackageURL@2.23
URI::VersionRange                   2.23  pkg:cpan/GDT/URI-PackageURL@2.23
URI::VersionRange::App              2.23  pkg:cpan/GDT/URI-PackageURL@2.23
URI::VersionRange::Constraint       2.23  pkg:cpan/GDT/URI-PackageURL@2.23
URI::VersionRange::Version         undef  pkg:cpan/GDT/URI-PackageURL@2.23
[...]
```

## Copyright

- Copyright 2025 © Giuseppe Di Terlizzi
