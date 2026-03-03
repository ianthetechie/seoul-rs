# seoul.rs

## How to write your content

1. Add your author info at config/author.toml
```
[extra.author.johnsmith]
name = "John Smith"
bio = "I am John Smith"
github = "jsmith"
```

2. Run justfile
```
	$ just prebuild
```

3. Write your content  
Make sure you have 'title', 'date' and 'authors' section available.
```
+++
title = "Joah Smith's first blog"
date = "2026-03-02"
authors = ["johnsmith"]
+++
```

3. Preview with zola
```
	$ zola serve
```

4. Commit and PR

