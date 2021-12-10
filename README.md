# Guild Wars template code parser
Parse skill template codes for Guild Wars

Last part of output is for use on wikidot, where we embed images crawled from wiki.guildwars.com

## Usage
```go run main.go TEMPLATECODE```

Warning: frequent/rapid use will make too many calls to wiki, be nice.
If needed this code could be extended to crawl all skill image urls once and store them.
