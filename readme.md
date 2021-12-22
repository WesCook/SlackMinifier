# Slack Minifier

Slack on the web includes many navigation bars, seldom-used icons, and other visual clutter.  This userstyle cleans it up to help you reclaim some screen real estate.

While this has been released publicly, it's only been tested within a single organization.  Feel free to submit any bugs/PRs, but I can't promise widespread support.  I will try to fix any broken changes caused by a Slack update however.

Designed for use with [Stylus][https://add0n.com/stylus.html].


## Changes

Slack Minifier will remove the large search bar at the top, as well as the bookmarks bar.  Important features like user avatar,  search input box, and the Pinned dropdown will be moved safely into the top-right corner.

The Help and History icons have been hidden completely.  To access these, you'll need to briefly disable the userstyle.


## Compatibility

|                                           | Chrome             | Firefox               | Opera               | Safari                |
|-------------------------------------------|--------------------|-----------------------|---------------------|-----------------------|
| [Stylus][stylus-home]<sup>1</sup>         | [✔][stylus-ch]     | [✔][stylus-fx]        | [✔][stylus-op]     |                       |
| [Stylish][stylish-home]<sup>2</sup>       | [✔][stylish-ch]    | [✔][stylish-fx]       | [✔][stylish-op]    |                       |
| [FreeStyler][freestyler-home]<sup>3</sup> | [✔][freestyler-ch] |                       | [✔][freestyler-op] | [✔][freestyler-multi] |

<sup>1. Stylus can auto-install the userstyle by viewing the [raw file](https://raw.githubusercontent.com/WesCook/SlackMinifier/main/slackminifier.user.css) and installing at the prompt.</sup>  
<sup>2. Stylish won't import the userstyle directly, but can be imported into a new style using the "Mozilla Format Import" feature.</sup>  
<sup>3. FreeStyler requires the `@-moz-document` rule be removed.</sup>


[stylus-home]: https://add0n.com/stylus.html
[stylus-ch]: https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en
[stylus-fx]: https://addons.mozilla.org/en-US/firefox/addon/styl-us/
[stylus-op]: https://addons.opera.com/en/extensions/details/stylus/

[stylish-home]: https://github.com/stylish-userstyles/stylish
[stylish-ch]: https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en
[stylish-fx]: https://addons.mozilla.org/en-US/firefox/addon/stylish/
[stylish-op]: https://addons.opera.com/en/extensions/details/stylish/

[freestyler-home]: http://freestyler.ws/
[freestyler-ch]: https://chrome.google.com/webstore/detail/freestyler/hihigldmabkodfpehkgdemjklmaebmca?hl=en
[freestyler-op]: https://addons.opera.com/en/extensions/details/freestyler/?display=en
[freestyler-multi]: https://freestyler.ws/plugin-page
