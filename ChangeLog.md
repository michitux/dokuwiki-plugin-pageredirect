# Dokuwiki pageredirect plugin change log

When writing entries, refer to [Keep a CHANGELOG](http://keepachangelog.com/) for guidelines.

All notable changes to this project will be documented in this file.

## [20160924]

  - add French translations. [#14]
  - display pagename if heading is undefined. [#15], [#9], [#13]
  - preserve `GET` parameters when redirecting. [#16]
  - add Russian translations. [#17]
  - update Korean translations. [#21]
  - fix test which is not passing with new version of Dokuwiki. [#22]

## [20140414]

  - add `<br/>` tag to the redirect note to avoid being covered by page TOC. [#4]
  - add Japanese translations. [#7]
  - make `~~REDIRECT` pattern non-greedy. [#5], [#8]
  - honour `conf['useheading']` for redirect note. [#6], [#8]
  - basic support for external redirects. [#8]
  - fix access to protected variable after [dokuwiki#555]. [#10], [#11]

## [20120816]

  - allow `#redirect` syntax to be lowercase, but it must be start on line. [1362442]

## [20120612]

  - match anything in page name, to wiki path it is converted internally. [f423934]
  - preserve `#section` anchors on redirect. [c31b525]
  - make redirects 301 redirect permanently to be SEO friendly, [9796335]
  - apply prevent conflict patch from wiki comments. [87145da]
  - add alternative `#REDIRECT namespace/pagename` syntax. [01efce2]
  - add zh-tw translations. [82539ae]
  - add Korean translations. [6aa688d]
  - add portugese translations. [e22f33a]
  - fix matching page with `#REDIRECT` syntax. [4dca632]

## [20070124]

  - Build 2

[20160924]: https://github.com/glensc/dokuwiki-plugin-pageredirect/compare/20140414...20160924
[20140414]: https://github.com/glensc/dokuwiki-plugin-pageredirect/compare/20120816...20140414
[20120816]: https://github.com/glensc/dokuwiki-plugin-pageredirect/compare/20120612...20120816
[20120612]: https://github.com/glensc/dokuwiki-plugin-pageredirect/compare/20070124...20120612
[20070124]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commits/20070124
[1362442]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/1362442
[f423934]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/f423934
[c31b525]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/c31b525
[9796335]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/9796335
[87145da]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/87145da
[01efce2]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/01efce2
[82539ae]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/82539ae
[6aa688d]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/6aa688d
[e22f33a]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/e22f33a
[4dca632]: https://github.com/glensc/dokuwiki-plugin-pageredirect/commit/4dca632
[#4]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/4
[#5]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/5
[#6]: https://github.com/glensc/dokuwiki-plugin-pageredirect/issues/6
[#7]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/7
[#8]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/8
[#9]: https://github.com/glensc/dokuwiki-plugin-pageredirect/issues/9
[#10]: https://github.com/glensc/dokuwiki-plugin-pageredirect/issues/10
[#11]: https://github.com/glensc/dokuwiki-plugin-pageredirect/issues/11
[#13]: https://github.com/glensc/dokuwiki-plugin-pageredirect/issues/13
[#14]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/14
[#15]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/15
[#16]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/16
[#17]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/17
[#21]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/21
[#22]: https://github.com/glensc/dokuwiki-plugin-pageredirect/pull/22
[dokuwiki#555]: https://github.com/splitbrain/dokuwiki/pull/555