# My Alfred Workflows

This is a collection of Alfred workflows I've written that are particularly
useful to me.

## Official Workflows

The following workflows are officially-maintained projects of mine, and
represent some of my most useful Alfred workflows. They are all MIT-licensed
and free to use.

### YouVersion Suggest

Allows you to quickly search the Bible for a specific topic or verse/chapter from Alfred.

https://github.com/caleb531/youversion-suggest-alfred

### Play Song

Allows you to play a song, artist, album, and more in only a few keystrokes. It
is significantly faster to use than Alfred's built-in Mini Player.

https://github.com/caleb531/play-song

### Open Conference URL

Launches your next Zoom/Meet/Teams/etc. meeting in no time at all

https://github.com/caleb531/open-conference-url.

## Unofficial Workflows

The following workflows are personal to me and not published as official
projects. They are completely free and unlicensed, so you may do with them as
you please.

**These workflows are unversioned and may change at any time.**

### Suggestion Workflows

A number of these workflows are designated as my "Suggest" workflows, which
significantly improve upon the web searches you can already build in Alfred.
Those native web searches lack autocomplete suggestions, whereas my Suggest
workflows provide relevant autocomplete suggestions according to the service
you are using.

Now, while there are already Google Suggest and Amazon Suggest example
workflows bundled with Alfred, these workflows suffer from the side-effect that
you must wait for the suggestions to load before you can submit the search. If
you have poor internet connectivity, or no connection at all, the suggestions
might fail to load, and therefore those workflows will prohibit you from
searching for even your typed query. These workflows aim to solve this problem
by cleverly lazy-loading the autocomplete suggestions below the first result
for your typed query (which can always be submitted immediately).

The available Suggest workflows include:

- Amazon Suggest (keyword: `az`)
- Google Suggest (keyword: `g`)
- Google Images Suggest (keyword: `gi`)
- Wikipedia Suggest (keyword: `w`)
- YouTube Suggest (keyword: `yt`)

### Open Directory in Terminal

Keyword: `cd`

Allows you to filter to a specific directory and open said directory in the
Terminal.

### Find Contacts

Keyword: `who`

By default, Alfred allows you to search contacts, but as part of the global
search results rather than scoped via keyword. This workflow was created to
replace this global functionality by allowing you to search contacts via the
`who` keyword within Alfred. In other words, you can restrict your search to
contacts _only_.

### Find Directories

Keyword: `d`

By default, Alfred shows directories only as part of the global search results
rather than scoped via keyword. This workflow was created so that you could
limit your search to only directories via the `d` keyword (i.e. if you know
you're looking for a directory specifically).

### Get IP Address

Keyword: `ip`

Displays the local IPv4 address of the machine, as well as the IPv4 address of
the router (using https://ifconfig.me).

### Flush DNS

Keywords: `dnsflush` or `flushdns`

Flushes the local DNS cache. You can use either keyword to invoke the workflow.

### Copy Contents to Clipboard

A file action that allows you to copy the contents of the selected file to the
clipboard.
