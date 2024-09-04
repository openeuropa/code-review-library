# Conventions

Information about conventions for OpenEuropa projects and components.

## Available conventions

These conventions can be used in your projects:

* [Library](dist/library-conventions.yml) for generic PHP projects.

## PHP Code Sniffer

- [PSR-12 coding standards](https://www.php-fig.org/psr/psr-12)
  with the following additions:
  - Comments, array declarations and code that is split over multiple lines also
    need to be indented with 4 characters.

## PHP Stan

- PHPStan default config, more info about available configuration: https://phpstan.org/user-guide/getting-started

## Commit messages

Valid default commit messages: `Issue #123: My commit.` or `OPENEUROPA-123: My commit.`

- Must start with GitHub issue reference or a Jira-like ticket ID.
- Must have a colon followed by a space after the issue reference.
- Must start with capital letter and end with a period.
