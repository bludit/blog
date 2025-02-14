# Bludit v4 Road map
<!-- date: 2021-01-15 18:00:00 -->

After some time without posting on the blog, I decided to show some progress of Bludit v4. I will try to update this post with some highlights in the changelog.

## 07/06/2021
Release of Bludit v4.0.0 Alpha 2. [Download from Github](https://github.com/bludit/bludit/releases/tag/4.0.0-alpha2).
### Highlights
- Setting for themes based on plugins, check the theme and plugin "popeye"
- UI improvemnets for Admin panel
- Dark mode for Admin panel
- Dark mode for PopEye theme
- Remove pages from the content page
- Include cover images in RSS plugin
- Improve HTTPs detection behind proxy
- Comments standars based on https://symfony.com/doc/current/contributing/code/standards.html
## Dark mode for Admin panel and PopEye theme

<a href="https://ibb.co/7yc0Bpx"><img src="https://i.ibb.co/ThXNJ0D/popeye-darkmode-bludit-v4.png" alt="popeye-darkmode-bludit-v4" border="0"></a>
<a href="https://ibb.co/7S990q5"><img src="https://i.ibb.co/ZfZZb0P/Screenshot-2021-06-07-at-20-34-20.png" alt="admin-panel-darkmode-bludit-v4" border="0"></a>

## 24/04/2021

### Highlights
- New default theme PopEye
- Automatic install and configure API plugin for the admin area
- Improved related pages function
- Improved Login class for authentication through API
- More changes in Bludit core for v4.0

## New default theme PopEye

<a href="https://ibb.co/XStKTSz"><img src="https://i.ibb.co/t8Dv58b/Screenshot-2021-04-24-at-19-58-40.png" alt="Screenshot-2021-04-24-at-19-58-40" border="0"></a>
<a href="https://ibb.co/f2y6YJP"><img src="https://i.ibb.co/G08Yvmb/Screenshot-2021-04-24-at-19-58-34.png" alt="Screenshot-2021-04-24-at-19-58-34" border="0"></a>
<a href="https://ibb.co/qp0V8qB"><img src="https://i.ibb.co/RchdKr2/Screenshot-2021-04-24-at-19-58-50.png" alt="Screenshot-2021-04-24-at-19-58-50" border="0"></a>

## 19/03/2021

### Highlights
- Plugins settings show the description by default.
- "Simple stats" now is "Visits Stats", and only shows visits and unique visitors, I will create new plugins to show more stats such as disk space, number of pages, etc.
- EasyMDE updated for Bludit v4.
- TinyMCE updated for Bludit v4.
- Welcome message now is a plugin for the dashboard, you can disable it.
- New branch for Documentation in English for Bludit v4, https://github.com/bludit/documentation-english/tree/v4.0
- Move frameworks to a proper folder `/bl-kernel/vendors/`
- `Theme::` helper replaced by `HTML::` helper.
- API feature, activate/deactivate plugins.
- API feature, configure plugins throug the API.
- API feature, upload and remove site logo.

### Plugins for Dashboard
A simple way to add plugins to the dashboard and order them.

<a href="https://ibb.co/5sNjzWY"><img src="https://i.ibb.co/ygwkMnh/Screenshot-2021-03-19-at-15-43-43.png" alt="Screenshot-2021-03-19-at-15-43-43" border="0" /></a>

<a href="https://ibb.co/qmwqRCz"><img src="https://i.ibb.co/h2vQKck/Screenshot-2021-03-19-at-15-43-31.png" alt="Screenshot-2021-03-19-at-15-43-31" border="0" /></a>

## 23/01/2021

### Highlights
- API feature, upload/delete profile picture
- Included new library for manage images [SimpleImages](https://github.com/claviska/SimpleImage)
- Warn user before leaving web page with unsaved changes
- Refactor as usual of Bludit's core
- Handle errors and alerts for the user
- Improvements in logs

You can check the commits here: https://github.com/bludit/bludit/tree/v4.0

### Refresh UI: User picture profile

<a href="https://ibb.co/hfvRwsF"><img src="https://i.ibb.co/JQPRgnj/Screenshot-2021-01-21-at-19-13-10.png" alt="Screenshot-2021-01-21-at-19-13-10" border="0"></a>

### Logos
We have new ideas for the logo.

Thank lodria, please check the post in the forum, https://forum.bludit.org/viewtopic.php?f=6&t=1969
<a href='https://postimg.cc/ZBbw5BHc' target='_blank'><img src='https://i.postimg.cc/ZBbw5BHc/Bludit-01a.png' border='0' alt='Bludit-01a'/></a>

Thanks to Claquettes Bleues, please check the following Tweet, https://twitter.com/bludit/status/1344364223682502660
<a href="https://ibb.co/7R0SF61"><img src="https://i.ibb.co/gPcrCBR/Es-QX9rl-W8-AMv3le.jpg" alt="Es-QX9rl-W8-AMv3le" border="0"></a>

<hr/>

## 15/01/2021

### Highlights
- API feature, upload files
- API feature, get files related to a page
- API feature, generate a friendly URL for a page
- API feature, create/edit/delete categories
- API feature, create/edit/delete users

### Refresh UI: Editor area
- Bootstrap v5
- Boostrap icons
- Editor area via AJAX, you don't need to refresh the page to save your changes

<a href="https://ibb.co/zZjzmXp"><img src="https://i.ibb.co/5LtP1rm/Screenshot-2021-01-15-at-17-48-59.png" alt="Bludit v4 - Admin panel" border="0"></a>

### Refresh UI: File manager
Allow upload any kind of type of file.

<a href="https://ibb.co/sWTpr9S"><img src="https://i.ibb.co/5KQXVhD/bludit-v4-file-manager.png" alt="bludit-v4-file-manager" border="0"></a>

### Logo
I would like to do a refresh of the current logo or change it for a new one, any help is welcome!

Thank to Multicolor by [Mateusz Skrzypczak](https://www.facebook.com/multicolorstargard) for the following logo.

<img src="https://github.com/bludit/logos/raw/master/multicolor/yello.png" alt="alternative-logo-by-mulicolor">
