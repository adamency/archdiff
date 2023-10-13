## Usage

### Help

```
`$basename -h`                Print usage
`$basename --help` 
```
### Single File

```
`$basename <file>`            Display diff for managed file
`$basename <file> -v`         Display diff for managed file in vim
```
### Single Package

#### List Modified Files

```
`$basename <package> -l`      List all modified files owned by <package>
`$basename <package> -l -q`   IDEM Machine-Readable
`$basename <package> -l -v`   IDEM Verbose
```
#### Diffs

```
`$basename <package>`         Display all diffs for package
`$basename <package> -v`      Display each diff for package in vim successively
```
### All Packages

```
`$basename -l`                List ALL modified managed files sorted by packages
`$basename -l -q`             IDEM Machine-Readable
`$basename -l -v`             IDEM Verbose
```
