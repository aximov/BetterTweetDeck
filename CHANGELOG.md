:tada: 3.1 :tada:
===============
- [Feature] Better TweetDeck now speaks Japanese! :jp: (thanks to [@shuuji3](https://github.com/shuuji3)) ([#111](https://github.com/eramdam/BetterTweetDeck/pull/111))
- [Feature] You can now paste images inside the tweet composer!           
  :rotating_light: **Due to a browser limitation, it will not work with GIFs** :rotating_light:
- [Fix] Verified badges in mentions should display correctly (as of 29/12/2016)
- Fix various little crashes (that were not disrupting the UI but still annoying me)

3.0.23
===============
- [Fix] Fix a glitch with verified badges on "XXX added you to a list" notifications

3.0.22
===============
- [Fix] Fix some UI shenanigans because of last TweetDeck update (6th December 2016)


3.0.21
===============
- [Feature] You can now collapse read DMs in the Messages column for a cleaner look and more privacy (GG [@pixeldesu](https://github.com/pixeldesu)) ([#105](https://github.com/eramdam/BetterTweetDeck/pull/105))
- [Fix] Fix a bug where valid "thumbnails" URLs would not get a preview because of the search query ([#104](https://github.com/eramdam/BetterTweetDeck/issues/104))


3.0.20
===============
- [Fix] Fix display of verified badge because of TweetDeck update on 9th of October 2016 FOR REAL THIS TIME
- [Fix] Gfycat iframes in modals should be correctly resized now (due to technical weirdness on Gfycat end, they won't resize dynamically though)
- [Fix] Fixing the display of avatars in conversations because TweetDeck still didn't fix it smh
- [Improvement] BTD changes the usernames correctly inside quoted tweets inside retweets and inside the "in reply to" block inside quoted tweets
- [Improvement] The "in reply to" part in quoted tweets is a little darker than the rest so it doesn't blend too much while in Dark + Minimal mode

3.0.19
===============
- [Fix] Remove the heart button animation when the stars are displayed
- [Fix] Slim scrollbars are also slim in detailed tweet view
- [Fix] Fix display of verified badge because of TweetDeck update on 9th of October 2016
- [Fix] Images/iframes in modals should be correctly resized now
- [Improvement] Desaturate some colors in minimal + dark mode

3.0.18
===============
- [Feature] You can specify a custom width for columns using any CSS value
- [Fix] The verified icon won't display on top on the "like" icon. Even though a heart should always be checked. :white_check_mark: :heart:
- [Fix] The "replace hearts by stars" feature is fixed after TweetDeck broke it.
- [Fix] The Esc key should close the lightboxes


3.0.17
===============
- [Fix] Horizontal scrollbars are also thin when "slim scrollbars" is enabled ([#96](https://github.com/eramdam/BetterTweetDeck/issues/96))
- [Fix] Dribbble/Imgur thumbnails work again
- [Fix/Improvement] hide the link related to a thumbnail only if it ends the tweet ([#97](https://github.com/eramdam/BetterTweetDeck/issues/97))

3.0.16
===============
- [Fix] Fix a bug where tweet actions would not work on custom modals.
- [Fix] Fix a bug where icons of accounts in Compose panel would be mis-placed.
- [Fix] Fix a bug where usernames would wrongly gets changed in some edge cases.
- [Improvement] Made some improvements to the way BTD stores its settings to handle future Edge/Firefox ports properly.
- [Improvement] Revert back the gradient on the modal's background.

3.0.15
===============
- [Feature] Added a setting to "stop" GIFs in profile pictures in columns
- [Fix] Gfycat embed players were too small, it's now fixed
- [Fix] Twitch clips should now actually work
- [Improvement] Username formatting should be more reliable/more performant
- [Improvement] The "no bg" background of modal now has a black to transparent gradient for improve readability

3.0.14
===============
- [Fix] Slimmer scrollbars are bigger and it's now an option

3.0.13
===============
- [Fix] GIFs should not stop anymore when the option "Stop gif autoplay" is unchecked
- [Fix] Streamable embed players were too small and mis-placed, it's now fixed
- [Improvement] The option "hide links relative to thumbnails" should work more reliably
- [Improvement] Better French translation (Thanks [LeoColomb](https://github.com/LeoColomb))
- [Improvement] Verified badge is better positioned (Thanks [LeoColomb](https://github.com/LeoColomb))
- [Feature] Twitch clips (clips.twitch.tv) are now supported ![](https://static-cdn.jtvnw.net/emoticons/v1/41/1.0)

3.0.12
===============
- [Fix] Verified badges should display correctly when relevant
- [Fix] Bring back the like/RT indicator on tweets because TweetDeck killed it
- [Improvement] Verified badges should display in modals and in the DM columns

3.0.11
===============
- [Fix] Choice of activating a provider or not is correctly taken into account in settings
- [Improvement] Universal preview is re-enabled by default
- [Improvement] The code don't use Embed.ly anymore

3.0.7 => 3.0.10
===============
- [Improvement] Removal of "tabs" permissions
- [Improvement] More reliable way of showing verified badges
- [Fix] Fix flashing of tweets
- [Fix] Links won't be hidden if a column has its media size on "off"
- [Fix] Modal should not have a scrollbar anymore
- [Improvement] The code don't rely on Embed.ly anymore for most services (except Giphy, cloudapp, bandcamp and twitch)

3.0.5
===============
- [Improvement] Option to hide bg of modals

3.0.3
===============
- [Fix] Share item is correctly added or not
- [Improvement] Settings button is back in TD
- [Improvement] Settings to hide scrollbars or not

3.0.1
===============
- [Fix] The play glyph is aligned on the "play icon"
- [Fix] Modal previews open for tweets in notifications
- [Fix] The "bubble" in minimal mode actually depends on the "show context" setting
- [Improvement] Another "save" button has been added in options page

3.0.0 Codename "Half-Life 3"
===============
- [Meta] Completely re-written in ES2015 with modules for a more maintainable code
- [Meta] Faster than 2.x, more reliable and nicer on resources
- [Feature] Modals/thumbnails work in DMs
- [Feature] Stop the autoplay of GIFs
- [Feature] Verified badge in the columns
- [Feature] Updated Minimal theme for dark/white + more reliable support of it
- [Feature] Can change hearts back to stars
- [Feature] Emoji picker now has a search and diversity support
- [Feature] Every thumbnail is powered by [Embed.ly](http://embed.ly/) and added thumbnails providers:
  - Gfycat
  - Giphy
  - Mixcloud
  - Skitch
  - Spotify
  - Streamable
  - TinyGrab
  - Twitch
  - Vidme
  - youtu.be
- [Feature] Custom format for timestamps
- [Feature] Bigger emojis in tweets
