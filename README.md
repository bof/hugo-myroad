# hugo-myroad - my own hugo theme

This is a work in progress. I'm getting started using hugo for some personal
blog usage, and as it is with us programmers, there's always stuff to fiddle
with and change which upstreams probably won't want, things to incorporate
from different sources, yadda yadda. So, that's why.

If I ever get around to feeling somewhat "finished" with this theme, I'll
take some time to extract or write anew some documentation, too. For now,
see "Attribution" below with links to the places I shamelessly stole from,
and read *their* documentation.

## config.toml Settings

 Setting       | Default | Usage
---------------+---------+----------------------------------------------------
authorbox      | false   | globally enable authorbox for single pages

## Frontmatter Settings

In addition to the usual frontmatter stuff, this theme gives you several
additional degrees of freedom to influence what is or is not shown on
certain single and/or list pages.

 Setting       | Default | Pagetype | Usage
---------------+---------+----------+-----------------------------------------
authorbox      | false   | single   | enable authorbox, if globally disabled
no_authorbox   | false   | single   | disable authorbox, if globally enabled
no_header      | false   | single   | suppress title-and-date header

## Attribution

The theme is based on [vimux/Mainroad](https://github.com/vimux/Mainroad).
Right now pretty much all html, js, css is from there. I've been reworking
the template structure a bit, trying to make sense of baseof/block/define...

The gallery / figure shortcodes are integrated from
[hugo-easy-gallery](https://github.com/liwenyip/hugo-easy-gallery)

Regarding license, I'm putting this work under GPLv2, as that is what
vimux uses for his Mainroad theme.

