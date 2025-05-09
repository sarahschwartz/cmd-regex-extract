# Command Regex Extract

Extracts strings from a command output using regex inputs, and returns a list of matches.

```yml
- uses: sarahschwartz/regex-action@main
  with:
   command: 'echo "Version: 1.2.3-beta"'
    regex-inputs: |
        ([0-9]+\.[0-9]+\.[0-9]+(-[a-z]+)?)
```
