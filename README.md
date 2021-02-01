# LabGo theme

A theme for hugo work mad with labs in mind.

## Built With

[![Hugo](https://img.shields.io/badge/Hugo-%5E0.80.0-ff4088?style=flat-square&logo=hugo)](https://gohugo.io/)

## How to Use

###### Install [hugo](https://gohugo.io)

```
brew install hugo
```

###### Create Site

```
hugo new site sitename
```

##### Add theme submodule

```
git submodule add https://gitlab.com/thesimplekid/labgo.git themes/labgo
```

#### Images

This theme assumes you're hostinf images on [Cloudinary](https://cloudinary.com/) with the `image:` in the front matter of content beinf the image id from cloudinary.

#### Netlify CMS

If you would like to use [netlifycms](https://www.netlifycms.org/) to mange the content the of your site set `useNetlifyCMS = true` in your `config.toml` for the [Netlify.com](https://www.netlify.com/) to be included on the homepage. Addital set up information can be found [here](https://www.netlifycms.org/docs/start-with-a-template/)

##### Set `sitename/config.toml`

```
Example config.toml

baseURL = "https://www.sitename.com"
languageCode = "en-us"
DefaultContentLanguage = "en"
title = "site title"
theme = "labgo"
enableGitInfo = true
enableRobotsTXT = true

summaryLength = 10

disableKinds = ['taxonomyTerm', 'term']


[params]
    useNetlifyCMS = true
    cloudinary_id= ""
    email = ""
    google_scholar = ""
    copyright = ""
    description = ""
```

## This is new

This is new and my first go at a hugo theme so hopefully some updates to come.

## In the Wild

You can view this theme being used for [www.deanlab.com](www.deanlab.com)

## License

This project is distributed under the MIT License

## Built and Maintained By

Brendan Murphy | [www.brendanmurphy.xyz](www.brendanmurphy.xyz) | brendan@thesimpelkid.com

Feel free to contact me with and comments or questions

Hosted on gitlab but maybe mirrored to github
