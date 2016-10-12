# Test Variables

## Fix characters

### Lower
```
tolower()
```

### Upper
```
toupper()
```

### Split
```
strsplit(x, splitChar)
```

### Substitute
Once:
```
sub(pattern, replace, x)
```
All:
```
gsub(pattern, replace, x)
```
### Search
Positions:
```
grep(pattern, x)
```
```
grep(pattern, x, value=TRUE)
```
Boolean Vector:
```
grepl(pattern, x)
```

## stringr

```
library(stringr)
nchar(x)
substr(x, min, max)
paste(x, y)
paste0(x, y) // No spaces
```

## Important
### Variable Names
- Lowercase when possible
- Descriptive
- Unique
- No underscores, dots or white spaces

### Char Values
- Made into factor variables
- Descriptive (TRUE/FALSE is better than 0/1)
