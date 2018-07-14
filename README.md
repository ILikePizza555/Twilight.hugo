# Twilight.hugo
The hugo theme I use for my personal site

## Usage

### Title and subtitle

Set `Params.title` and `Params.tagline` as strings in `config.toml`.

Example:
```
[Params]
    title = "My Title"
    tagline = "My tagline"
```

### Navbar Links

Set the `Params.links` variable as a table in in `config.toml`. It should consist of other tables containing the variables `text` and `href`.

Example:
```
[Params.links]
    [Params.links.tags]
        text = "Tags" 
        href="/tags"
    [Params.links.categories]
        text = "Categories" 
        href="/categories"
    [Params.links.about]
        text = "About Me" 
        href="/aboutme"
```

### Profile Links

This is similar to normal links. Set the `Params.profile.links` variable as a table in `config.toml`. It should consists of other tables containing the variables `text` and `href`.