# GitHub-Action-Test-Negation
https://github.com/github/docs/pull/20883

# Both work but `${{ }}` is required.
## if: ${{ !contains('Hello world', 'moon') }}
## if: ${{ ! contains('Hello world', 'moon') }}
