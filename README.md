# api documentation for  [youtube-api (v2.0.8)](https://github.com/IonicaBizau/youtube-api)  [![npm package](https://img.shields.io/npm/v/npmdoc-youtube-api.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-youtube-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-youtube-api.svg)](https://travis-ci.org/npmdoc/node-npmdoc-youtube-api)
#### A Node.JS module, which provides an object oriented wrapper for the Youtube v3 API.

[![NPM](https://nodei.co/npm/youtube-api.png?downloads=true)](https://www.npmjs.com/package/youtube-api)

[![apidoc](https://npmdoc.github.io/node-npmdoc-youtube-api/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-youtube-api_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-youtube-api/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-youtube-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-youtube-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ionică Bizău",
        "email": "bizauionica@gmail.com",
        "url": "https://ionicabizau.net"
    },
    "blah": {
        "show_jsdocs": false,
        "documentation": [
            "The [official Youtube documentation](https://developers.google.com/youtube/v3/docs/) is a very useful resource.",
            {
                "ul": [
                    "[Activities](https://developers.google.com/youtube/v3/docs/activities)",
                    "[ChannelBanners](https://developers.google.com/youtube/v3/docs/channelBanners)",
                    "[Channels](https://developers.google.com/youtube/v3/docs/channels)",
                    "[GuideCategories](https://developers.google.com/youtube/v3/docs/guideCategories)",
                    "[PlaylistItems](https://developers.google.com/youtube/v3/docs/playlistItems)",
                    "[Playlists](https://developers.google.com/youtube/v3/docs/playlists)",
                    "[Search](https://developers.google.com/youtube/v3/docs/search)",
                    "[Subscriptions](https://developers.google.com/youtube/v3/docs/subscriptions)",
                    "[Thumbnails](https://developers.google.com/youtube/v3/docs/thumbnails)",
                    "[VideoCategories](https://developers.google.com/youtube/v3/docs/videoCategories)",
                    "[Videos](https://developers.google.com/youtube/v3/docs/videos)"
                ]
            },
            "If you have any questions, please [ask them on **Stack Overflow**](https://stackoverflow.com/questions/ask) and eventually [open an issue](https://github.com/IonicaBizau/youtube-api/issues/new) and link your question there.",
            "",
            {
                "h3": "Authentication"
            },
            "",
            {
                "h4": "OAuth (Access Token)"
            },
            {
                "code": {
                    "language": "js",
                    "content": [
                        "Youtube.authenticate({",
                        "    type: \"oauth\"",
                        "  , token: \"your access token\"",
                        "});"
                    ]
                }
            },
            {
                "h4": "OAuth (Refresh Token)"
            },
            {
                "code": {
                    "language": "js",
                    "content": [
                        "Youtube.authenticate({",
                        "    type: \"oauth\"",
                        "  , refresh_token: \"your refresh token\"",
                        "  , client_id: \"your client id\"",
                        "  , client_secret: \"your client secret\"",
                        "  , redirect_url: \"your refresh url\"",
                        "});"
                    ]
                }
            },
            {
                "h4": "Server Key"
            },
            "Only for requests that don't require [user authorization](https://developers.google.com/youtube/v3/guides/authentication) (certain list operations)",
            {
                "code": {
                    "language": "js",
                    "content": [
                        "Youtube.authenticate({",
                        "    type: \"key\"",
                        "  , key: \"your server key\"",
                        "});"
                    ]
                }
            }
        ]
    },
    "bugs": {
        "url": "https://github.com/IonicaBizau/youtube-api/issues"
    },
    "contributors": [
        {
            "name": "Ionică Bizău",
            "email": "bizauionica@gmail.com"
        },
        {
            "name": "Adam",
            "email": "aaschodd@asu.edu",
            "url": "brutalhonesty"
        },
        {
            "name": "Michael Scharl",
            "email": "developeme@gmail.com"
        },
        {
            "name": "Vels",
            "email": "velshome@yahoo.com",
            "url": "velsa"
        },
        {
            "name": "Rasmus Karlsson",
            "email": "pajlada@bithack.se"
        },
        {
            "name": "Brad Oyler",
            "email": "bradoyler@gmail.com"
        }
    ],
    "dependencies": {
        "googleapis": "^5.2.1"
    },
    "description": "A Node.JS module, which provides an object oriented wrapper for the Youtube v3 API.",
    "devDependencies": {
        "bug-killer": "^4.2.2",
        "lien": "^1.0.1",
        "opn": "^4.0.1",
        "pretty-bytes": "^3.0.1",
        "r-json": "^1.2.2"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "6f9ac0b3c4cfe110b100330ea404aa0ad885501f",
        "tarball": "https://registry.npmjs.org/youtube-api/-/youtube-api-2.0.8.tgz"
    },
    "files": [
        "bin/",
        "app/",
        "lib/",
        "dist/",
        "src/",
        "scripts/",
        "resources/",
        "menu/",
        "cli.js",
        "index.js"
    ],
    "gitHead": "427d667f461c1121a83b041c9e3ed08c9b6f8f17",
    "homepage": "https://github.com/IonicaBizau/youtube-api",
    "keywords": [
        "youtube",
        "api",
        "v3",
        "node"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "ionicabizau",
            "email": "bizauionica@yahoo.com"
        }
    ],
    "name": "youtube-api",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/IonicaBizau/youtube-api.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "2.0.8"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module youtube-api](#apidoc.module.youtube-api)
1.  [function <span class="apidocSignatureSpan">youtube-api.</span>authenticate (options)](#apidoc.element.youtube-api.authenticate)
1.  [function <span class="apidocSignatureSpan">youtube-api.</span>getConfig ()](#apidoc.element.youtube-api.getConfig)
1.  [function <span class="apidocSignatureSpan">youtube-api.</span>google.GoogleApis (options)](#apidoc.element.youtube-api.google.GoogleApis)
1.  object <span class="apidocSignatureSpan">youtube-api.</span>_options
1.  object <span class="apidocSignatureSpan">youtube-api.</span>activities
1.  object <span class="apidocSignatureSpan">youtube-api.</span>captions
1.  object <span class="apidocSignatureSpan">youtube-api.</span>channelBanners
1.  object <span class="apidocSignatureSpan">youtube-api.</span>channelSections
1.  object <span class="apidocSignatureSpan">youtube-api.</span>channels
1.  object <span class="apidocSignatureSpan">youtube-api.</span>commentThreads
1.  object <span class="apidocSignatureSpan">youtube-api.</span>comments
1.  object <span class="apidocSignatureSpan">youtube-api.</span>fanFundingEvents
1.  object <span class="apidocSignatureSpan">youtube-api.</span>google
1.  object <span class="apidocSignatureSpan">youtube-api.</span>google.GoogleApis.prototype
1.  object <span class="apidocSignatureSpan">youtube-api.</span>google.auth
1.  object <span class="apidocSignatureSpan">youtube-api.</span>google.auth.ComputeClient.prototype
1.  object <span class="apidocSignatureSpan">youtube-api.</span>google.auth.JWTClient.prototype
1.  object <span class="apidocSignatureSpan">youtube-api.</span>guideCategories
1.  object <span class="apidocSignatureSpan">youtube-api.</span>i18nLanguages
1.  object <span class="apidocSignatureSpan">youtube-api.</span>i18nRegions
1.  object <span class="apidocSignatureSpan">youtube-api.</span>liveBroadcasts
1.  object <span class="apidocSignatureSpan">youtube-api.</span>liveChatBans
1.  object <span class="apidocSignatureSpan">youtube-api.</span>liveChatMessages
1.  object <span class="apidocSignatureSpan">youtube-api.</span>liveChatModerators
1.  object <span class="apidocSignatureSpan">youtube-api.</span>liveStreams
1.  object <span class="apidocSignatureSpan">youtube-api.</span>playlistItems
1.  object <span class="apidocSignatureSpan">youtube-api.</span>playlists
1.  object <span class="apidocSignatureSpan">youtube-api.</span>search
1.  object <span class="apidocSignatureSpan">youtube-api.</span>sponsors
1.  object <span class="apidocSignatureSpan">youtube-api.</span>subscriptions
1.  object <span class="apidocSignatureSpan">youtube-api.</span>thumbnails
1.  object <span class="apidocSignatureSpan">youtube-api.</span>videoAbuseReportReasons
1.  object <span class="apidocSignatureSpan">youtube-api.</span>videoCategories
1.  object <span class="apidocSignatureSpan">youtube-api.</span>videos
1.  object <span class="apidocSignatureSpan">youtube-api.</span>watermarks

#### [module youtube-api.activities](#apidoc.module.youtube-api.activities)
1.  [function <span class="apidocSignatureSpan">youtube-api.activities.</span>insert (params, callback)](#apidoc.element.youtube-api.activities.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.activities.</span>list (params, callback)](#apidoc.element.youtube-api.activities.list)

#### [module youtube-api.captions](#apidoc.module.youtube-api.captions)
1.  [function <span class="apidocSignatureSpan">youtube-api.captions.</span>delete (params, callback)](#apidoc.element.youtube-api.captions.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.captions.</span>download (params, callback)](#apidoc.element.youtube-api.captions.download)
1.  [function <span class="apidocSignatureSpan">youtube-api.captions.</span>insert (params, callback)](#apidoc.element.youtube-api.captions.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.captions.</span>list (params, callback)](#apidoc.element.youtube-api.captions.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.captions.</span>update (params, callback)](#apidoc.element.youtube-api.captions.update)

#### [module youtube-api.channelBanners](#apidoc.module.youtube-api.channelBanners)
1.  [function <span class="apidocSignatureSpan">youtube-api.channelBanners.</span>insert (params, callback)](#apidoc.element.youtube-api.channelBanners.insert)

#### [module youtube-api.channelSections](#apidoc.module.youtube-api.channelSections)
1.  [function <span class="apidocSignatureSpan">youtube-api.channelSections.</span>delete (params, callback)](#apidoc.element.youtube-api.channelSections.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.channelSections.</span>insert (params, callback)](#apidoc.element.youtube-api.channelSections.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.channelSections.</span>list (params, callback)](#apidoc.element.youtube-api.channelSections.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.channelSections.</span>update (params, callback)](#apidoc.element.youtube-api.channelSections.update)

#### [module youtube-api.channels](#apidoc.module.youtube-api.channels)
1.  [function <span class="apidocSignatureSpan">youtube-api.channels.</span>list (params, callback)](#apidoc.element.youtube-api.channels.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.channels.</span>update (params, callback)](#apidoc.element.youtube-api.channels.update)

#### [module youtube-api.commentThreads](#apidoc.module.youtube-api.commentThreads)
1.  [function <span class="apidocSignatureSpan">youtube-api.commentThreads.</span>insert (params, callback)](#apidoc.element.youtube-api.commentThreads.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.commentThreads.</span>list (params, callback)](#apidoc.element.youtube-api.commentThreads.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.commentThreads.</span>update (params, callback)](#apidoc.element.youtube-api.commentThreads.update)

#### [module youtube-api.comments](#apidoc.module.youtube-api.comments)
1.  [function <span class="apidocSignatureSpan">youtube-api.comments.</span>delete (params, callback)](#apidoc.element.youtube-api.comments.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.comments.</span>insert (params, callback)](#apidoc.element.youtube-api.comments.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.comments.</span>list (params, callback)](#apidoc.element.youtube-api.comments.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.comments.</span>markAsSpam (params, callback)](#apidoc.element.youtube-api.comments.markAsSpam)
1.  [function <span class="apidocSignatureSpan">youtube-api.comments.</span>setModerationStatus (params, callback)](#apidoc.element.youtube-api.comments.setModerationStatus)
1.  [function <span class="apidocSignatureSpan">youtube-api.comments.</span>update (params, callback)](#apidoc.element.youtube-api.comments.update)

#### [module youtube-api.fanFundingEvents](#apidoc.module.youtube-api.fanFundingEvents)
1.  [function <span class="apidocSignatureSpan">youtube-api.fanFundingEvents.</span>list (params, callback)](#apidoc.element.youtube-api.fanFundingEvents.list)

#### [module youtube-api.google](#apidoc.module.youtube-api.google)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>GoogleApis (options)](#apidoc.element.youtube-api.google.GoogleApis)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>adexchangebuyer ()](#apidoc.element.youtube-api.google.adexchangebuyer)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>adexchangebuyer2 ()](#apidoc.element.youtube-api.google.adexchangebuyer2)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>adexchangeseller ()](#apidoc.element.youtube-api.google.adexchangeseller)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>admin ()](#apidoc.element.youtube-api.google.admin)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>adsense ()](#apidoc.element.youtube-api.google.adsense)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>adsensehost ()](#apidoc.element.youtube-api.google.adsensehost)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>analytics ()](#apidoc.element.youtube-api.google.analytics)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>analyticsreporting ()](#apidoc.element.youtube-api.google.analyticsreporting)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>androidenterprise ()](#apidoc.element.youtube-api.google.androidenterprise)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>androidpublisher ()](#apidoc.element.youtube-api.google.androidpublisher)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>appengine ()](#apidoc.element.youtube-api.google.appengine)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>appsactivity ()](#apidoc.element.youtube-api.google.appsactivity)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>appstate ()](#apidoc.element.youtube-api.google.appstate)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>autoscaler ()](#apidoc.element.youtube-api.google.autoscaler)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>bigquery ()](#apidoc.element.youtube-api.google.bigquery)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>blogger ()](#apidoc.element.youtube-api.google.blogger)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>books ()](#apidoc.element.youtube-api.google.books)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>calendar ()](#apidoc.element.youtube-api.google.calendar)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>civicinfo ()](#apidoc.element.youtube-api.google.civicinfo)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>classroom ()](#apidoc.element.youtube-api.google.classroom)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudbilling ()](#apidoc.element.youtube-api.google.cloudbilling)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudbuild ()](#apidoc.element.youtube-api.google.cloudbuild)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>clouddebugger ()](#apidoc.element.youtube-api.google.clouddebugger)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>clouderrorreporting ()](#apidoc.element.youtube-api.google.clouderrorreporting)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudlatencytest ()](#apidoc.element.youtube-api.google.cloudlatencytest)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudmonitoring ()](#apidoc.element.youtube-api.google.cloudmonitoring)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudresourcemanager ()](#apidoc.element.youtube-api.google.cloudresourcemanager)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudtrace ()](#apidoc.element.youtube-api.google.cloudtrace)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>clouduseraccounts ()](#apidoc.element.youtube-api.google.clouduseraccounts)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>compute ()](#apidoc.element.youtube-api.google.compute)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>consumersurveys ()](#apidoc.element.youtube-api.google.consumersurveys)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>container ()](#apidoc.element.youtube-api.google.container)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>content ()](#apidoc.element.youtube-api.google.content)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>coordinate ()](#apidoc.element.youtube-api.google.coordinate)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>customsearch ()](#apidoc.element.youtube-api.google.customsearch)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>dataflow ()](#apidoc.element.youtube-api.google.dataflow)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>dataproc ()](#apidoc.element.youtube-api.google.dataproc)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>datastore ()](#apidoc.element.youtube-api.google.datastore)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>deploymentmanager ()](#apidoc.element.youtube-api.google.deploymentmanager)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>dfareporting ()](#apidoc.element.youtube-api.google.dfareporting)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>discovery ()](#apidoc.element.youtube-api.google.discovery)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>dns ()](#apidoc.element.youtube-api.google.dns)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>doubleclickbidmanager ()](#apidoc.element.youtube-api.google.doubleclickbidmanager)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>doubleclicksearch ()](#apidoc.element.youtube-api.google.doubleclicksearch)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>drive ()](#apidoc.element.youtube-api.google.drive)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>fitness ()](#apidoc.element.youtube-api.google.fitness)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>freebase ()](#apidoc.element.youtube-api.google.freebase)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>fusiontables ()](#apidoc.element.youtube-api.google.fusiontables)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>games ()](#apidoc.element.youtube-api.google.games)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>gamesConfiguration ()](#apidoc.element.youtube-api.google.gamesConfiguration)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>gamesManagement ()](#apidoc.element.youtube-api.google.gamesManagement)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>gan ()](#apidoc.element.youtube-api.google.gan)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>genomics ()](#apidoc.element.youtube-api.google.genomics)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>gmail ()](#apidoc.element.youtube-api.google.gmail)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>groupsmigration ()](#apidoc.element.youtube-api.google.groupsmigration)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>groupssettings ()](#apidoc.element.youtube-api.google.groupssettings)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>iam ()](#apidoc.element.youtube-api.google.iam)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>identitytoolkit ()](#apidoc.element.youtube-api.google.identitytoolkit)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>kgsearch ()](#apidoc.element.youtube-api.google.kgsearch)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>licensing ()](#apidoc.element.youtube-api.google.licensing)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>logging ()](#apidoc.element.youtube-api.google.logging)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>manager ()](#apidoc.element.youtube-api.google.manager)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>mirror ()](#apidoc.element.youtube-api.google.mirror)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>monitoring ()](#apidoc.element.youtube-api.google.monitoring)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>oauth2 ()](#apidoc.element.youtube-api.google.oauth2)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>pagespeedonline ()](#apidoc.element.youtube-api.google.pagespeedonline)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>partners ()](#apidoc.element.youtube-api.google.partners)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>people ()](#apidoc.element.youtube-api.google.people)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>playmoviespartner ()](#apidoc.element.youtube-api.google.playmoviespartner)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>plus ()](#apidoc.element.youtube-api.google.plus)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>plusDomains ()](#apidoc.element.youtube-api.google.plusDomains)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>prediction ()](#apidoc.element.youtube-api.google.prediction)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>proximitybeacon ()](#apidoc.element.youtube-api.google.proximitybeacon)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>pubsub ()](#apidoc.element.youtube-api.google.pubsub)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>qpxExpress ()](#apidoc.element.youtube-api.google.qpxExpress)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>replicapool ()](#apidoc.element.youtube-api.google.replicapool)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>replicapoolupdater ()](#apidoc.element.youtube-api.google.replicapoolupdater)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>reseller ()](#apidoc.element.youtube-api.google.reseller)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>resourceviews ()](#apidoc.element.youtube-api.google.resourceviews)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>script ()](#apidoc.element.youtube-api.google.script)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>serviceregistry ()](#apidoc.element.youtube-api.google.serviceregistry)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>siteVerification ()](#apidoc.element.youtube-api.google.siteVerification)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>spectrum ()](#apidoc.element.youtube-api.google.spectrum)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>sqladmin ()](#apidoc.element.youtube-api.google.sqladmin)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>storage ()](#apidoc.element.youtube-api.google.storage)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>storagetransfer ()](#apidoc.element.youtube-api.google.storagetransfer)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>tagmanager ()](#apidoc.element.youtube-api.google.tagmanager)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>taskqueue ()](#apidoc.element.youtube-api.google.taskqueue)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>tasks ()](#apidoc.element.youtube-api.google.tasks)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>toolresults ()](#apidoc.element.youtube-api.google.toolresults)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>translate ()](#apidoc.element.youtube-api.google.translate)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>urlshortener ()](#apidoc.element.youtube-api.google.urlshortener)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>vision ()](#apidoc.element.youtube-api.google.vision)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>webfonts ()](#apidoc.element.youtube-api.google.webfonts)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>webmasters ()](#apidoc.element.youtube-api.google.webmasters)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>youtube ()](#apidoc.element.youtube-api.google.youtube)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>youtubeAnalytics ()](#apidoc.element.youtube-api.google.youtubeAnalytics)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>youtubereporting ()](#apidoc.element.youtube-api.google.youtubereporting)
1.  object <span class="apidocSignatureSpan">youtube-api.google.</span>_options
1.  object <span class="apidocSignatureSpan">youtube-api.google.</span>auth

#### [module youtube-api.google.GoogleApis](#apidoc.module.youtube-api.google.GoogleApis)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.</span>GoogleApis (options)](#apidoc.element.youtube-api.google.GoogleApis.GoogleApis)

#### [module youtube-api.google.GoogleApis.prototype](#apidoc.module.youtube-api.google.GoogleApis.prototype)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.GoogleApis.prototype.</span>addAPIs (apis)](#apidoc.element.youtube-api.google.GoogleApis.prototype.addAPIs)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.GoogleApis.prototype.</span>discover (url, callback)](#apidoc.element.youtube-api.google.GoogleApis.prototype.discover)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.GoogleApis.prototype.</span>discoverAPI (path, options, callback)](#apidoc.element.youtube-api.google.GoogleApis.prototype.discoverAPI)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.GoogleApis.prototype.</span>options (options)](#apidoc.element.youtube-api.google.GoogleApis.prototype.options)

#### [module youtube-api.google.auth](#apidoc.module.youtube-api.google.auth)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.</span>ComputeClient ()](#apidoc.element.youtube-api.google.auth.ComputeClient)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.</span>JWTClient (email, keyFile, key, scopes, subject)](#apidoc.element.youtube-api.google.auth.JWTClient)
1.  object <span class="apidocSignatureSpan">youtube-api.google.auth.</span>_cachedCredential

#### [module youtube-api.google.auth.ComputeClient.prototype](#apidoc.module.youtube-api.google.auth.ComputeClient.prototype)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.ComputeClient.prototype.</span>_injectErrorMessage (err, result, response, callback)](#apidoc.element.youtube-api.google.auth.ComputeClient.prototype._injectErrorMessage)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.ComputeClient.prototype.</span>createScopedRequired ()](#apidoc.element.youtube-api.google.auth.ComputeClient.prototype.createScopedRequired)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.ComputeClient.prototype.</span>refreshToken_ (ignored_, opt_callback)](#apidoc.element.youtube-api.google.auth.ComputeClient.prototype.refreshToken_)

#### [module youtube-api.google.auth.JWTClient.prototype](#apidoc.module.youtube-api.google.auth.JWTClient.prototype)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>_createGToken (callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype._createGToken)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>authorize (opt_callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.authorize)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>createScoped (scopes)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.createScoped)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>createScopedRequired ()](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.createScopedRequired)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>fromJSON (json, opt_callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.fromJSON)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>fromStream (stream, opt_callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.fromStream)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>getRequestMetadata (opt_uri, metadataCb)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.getRequestMetadata)
1.  [function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>refreshToken_ (ignored_, opt_callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.refreshToken_)

#### [module youtube-api.guideCategories](#apidoc.module.youtube-api.guideCategories)
1.  [function <span class="apidocSignatureSpan">youtube-api.guideCategories.</span>list (params, callback)](#apidoc.element.youtube-api.guideCategories.list)

#### [module youtube-api.i18nLanguages](#apidoc.module.youtube-api.i18nLanguages)
1.  [function <span class="apidocSignatureSpan">youtube-api.i18nLanguages.</span>list (params, callback)](#apidoc.element.youtube-api.i18nLanguages.list)

#### [module youtube-api.i18nRegions](#apidoc.module.youtube-api.i18nRegions)
1.  [function <span class="apidocSignatureSpan">youtube-api.i18nRegions.</span>list (params, callback)](#apidoc.element.youtube-api.i18nRegions.list)

#### [module youtube-api.liveBroadcasts](#apidoc.module.youtube-api.liveBroadcasts)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>bind (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.bind)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>control (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.control)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>delete (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>insert (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>list (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>transition (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.transition)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>update (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.update)

#### [module youtube-api.liveChatBans](#apidoc.module.youtube-api.liveChatBans)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveChatBans.</span>delete (params, callback)](#apidoc.element.youtube-api.liveChatBans.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveChatBans.</span>insert (params, callback)](#apidoc.element.youtube-api.liveChatBans.insert)

#### [module youtube-api.liveChatMessages](#apidoc.module.youtube-api.liveChatMessages)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveChatMessages.</span>delete (params, callback)](#apidoc.element.youtube-api.liveChatMessages.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveChatMessages.</span>insert (params, callback)](#apidoc.element.youtube-api.liveChatMessages.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveChatMessages.</span>list (params, callback)](#apidoc.element.youtube-api.liveChatMessages.list)

#### [module youtube-api.liveChatModerators](#apidoc.module.youtube-api.liveChatModerators)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveChatModerators.</span>delete (params, callback)](#apidoc.element.youtube-api.liveChatModerators.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveChatModerators.</span>insert (params, callback)](#apidoc.element.youtube-api.liveChatModerators.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveChatModerators.</span>list (params, callback)](#apidoc.element.youtube-api.liveChatModerators.list)

#### [module youtube-api.liveStreams](#apidoc.module.youtube-api.liveStreams)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveStreams.</span>delete (params, callback)](#apidoc.element.youtube-api.liveStreams.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveStreams.</span>insert (params, callback)](#apidoc.element.youtube-api.liveStreams.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveStreams.</span>list (params, callback)](#apidoc.element.youtube-api.liveStreams.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.liveStreams.</span>update (params, callback)](#apidoc.element.youtube-api.liveStreams.update)

#### [module youtube-api.playlistItems](#apidoc.module.youtube-api.playlistItems)
1.  [function <span class="apidocSignatureSpan">youtube-api.playlistItems.</span>delete (params, callback)](#apidoc.element.youtube-api.playlistItems.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.playlistItems.</span>insert (params, callback)](#apidoc.element.youtube-api.playlistItems.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.playlistItems.</span>list (params, callback)](#apidoc.element.youtube-api.playlistItems.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.playlistItems.</span>update (params, callback)](#apidoc.element.youtube-api.playlistItems.update)

#### [module youtube-api.playlists](#apidoc.module.youtube-api.playlists)
1.  [function <span class="apidocSignatureSpan">youtube-api.playlists.</span>delete (params, callback)](#apidoc.element.youtube-api.playlists.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.playlists.</span>insert (params, callback)](#apidoc.element.youtube-api.playlists.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.playlists.</span>list (params, callback)](#apidoc.element.youtube-api.playlists.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.playlists.</span>update (params, callback)](#apidoc.element.youtube-api.playlists.update)

#### [module youtube-api.search](#apidoc.module.youtube-api.search)
1.  [function <span class="apidocSignatureSpan">youtube-api.search.</span>list (params, callback)](#apidoc.element.youtube-api.search.list)

#### [module youtube-api.sponsors](#apidoc.module.youtube-api.sponsors)
1.  [function <span class="apidocSignatureSpan">youtube-api.sponsors.</span>list (params, callback)](#apidoc.element.youtube-api.sponsors.list)

#### [module youtube-api.subscriptions](#apidoc.module.youtube-api.subscriptions)
1.  [function <span class="apidocSignatureSpan">youtube-api.subscriptions.</span>delete (params, callback)](#apidoc.element.youtube-api.subscriptions.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.subscriptions.</span>insert (params, callback)](#apidoc.element.youtube-api.subscriptions.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.subscriptions.</span>list (params, callback)](#apidoc.element.youtube-api.subscriptions.list)

#### [module youtube-api.thumbnails](#apidoc.module.youtube-api.thumbnails)
1.  [function <span class="apidocSignatureSpan">youtube-api.thumbnails.</span>set (params, callback)](#apidoc.element.youtube-api.thumbnails.set)

#### [module youtube-api.videoAbuseReportReasons](#apidoc.module.youtube-api.videoAbuseReportReasons)
1.  [function <span class="apidocSignatureSpan">youtube-api.videoAbuseReportReasons.</span>list (params, callback)](#apidoc.element.youtube-api.videoAbuseReportReasons.list)

#### [module youtube-api.videoCategories](#apidoc.module.youtube-api.videoCategories)
1.  [function <span class="apidocSignatureSpan">youtube-api.videoCategories.</span>list (params, callback)](#apidoc.element.youtube-api.videoCategories.list)

#### [module youtube-api.videos](#apidoc.module.youtube-api.videos)
1.  [function <span class="apidocSignatureSpan">youtube-api.videos.</span>delete (params, callback)](#apidoc.element.youtube-api.videos.delete)
1.  [function <span class="apidocSignatureSpan">youtube-api.videos.</span>getRating (params, callback)](#apidoc.element.youtube-api.videos.getRating)
1.  [function <span class="apidocSignatureSpan">youtube-api.videos.</span>insert (params, callback)](#apidoc.element.youtube-api.videos.insert)
1.  [function <span class="apidocSignatureSpan">youtube-api.videos.</span>list (params, callback)](#apidoc.element.youtube-api.videos.list)
1.  [function <span class="apidocSignatureSpan">youtube-api.videos.</span>rate (params, callback)](#apidoc.element.youtube-api.videos.rate)
1.  [function <span class="apidocSignatureSpan">youtube-api.videos.</span>reportAbuse (params, callback)](#apidoc.element.youtube-api.videos.reportAbuse)
1.  [function <span class="apidocSignatureSpan">youtube-api.videos.</span>update (params, callback)](#apidoc.element.youtube-api.videos.update)

#### [module youtube-api.watermarks](#apidoc.module.youtube-api.watermarks)
1.  [function <span class="apidocSignatureSpan">youtube-api.watermarks.</span>set (params, callback)](#apidoc.element.youtube-api.watermarks.set)
1.  [function <span class="apidocSignatureSpan">youtube-api.watermarks.</span>unset (params, callback)](#apidoc.element.youtube-api.watermarks.unset)



# <a name="apidoc.module.youtube-api"></a>[module youtube-api](#apidoc.module.youtube-api)

#### <a name="apidoc.element.youtube-api.authenticate"></a>[function <span class="apidocSignatureSpan">youtube-api.</span>authenticate (options)](#apidoc.element.youtube-api.authenticate)
- description and source-code
```javascript
authenticate = function (options) {
    if (!options) {
        config.auth = undefined;
        return;
    }

    var authObj = null;
    switch (options.type) {
        case "oauth":
            authObj = new Google.auth.OAuth2(options.client_id, options.client_secret, options.redirect_url);
            authObj.setCredentials({
                access_token: options.access_token || options.token,
                refresh_token: options.refresh_token
            });
            break;
        case "key":
            authObj = options.key;
            break;
    }

    Google.options({ auth: authObj });
    config.auth = options;

    return authObj;
}
```
- example usage
```shell
...
    host: "localhost"
  , port: 5000
});

// Authenticate
// You can access the Youtube resources via OAuth2 only.
// https://developers.google.com/youtube/v3/guides/moving_to_oauth#service_accounts
let oauth = Youtube.authenticate({
    type: "oauth"
  , client_id: CREDENTIALS.web.client_id
  , client_secret: CREDENTIALS.web.client_secret
  , redirect_url: CREDENTIALS.web.redirect_uris[0]
});

opn(oauth.generateAuthUrl({
...
```

#### <a name="apidoc.element.youtube-api.getConfig"></a>[function <span class="apidocSignatureSpan">youtube-api.</span>getConfig ()](#apidoc.element.youtube-api.getConfig)
- description and source-code
```javascript
getConfig = function () {
    return config;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.GoogleApis"></a>[function <span class="apidocSignatureSpan">youtube-api.</span>google.GoogleApis (options)](#apidoc.element.youtube-api.google.GoogleApis)
- description and source-code
```javascript
function GoogleApis(options) {
  this.options(options);
  this.addAPIs(apis);

<span class="apidocCodeCommentSpan">  /**
   * A reference to an instance of GoogleAuth.
   *
   * @name GoogleApis#auth
   * @type {GoogleAuth}
   */
</span>  this.auth = new GoogleAuth();

  /**
   * A reference to the GoogleApis constructor function.
   *
   * @name GoogleApis#GoogleApis
   * @type {Function}
   */
  this.GoogleApis = GoogleApis;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.activities"></a>[module youtube-api.activities](#apidoc.module.youtube-api.activities)

#### <a name="apidoc.element.youtube-api.activities.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.activities.</span>insert (params, callback)](#apidoc.element.youtube-api.activities.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/activities',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.activities.list"></a>[function <span class="apidocSignatureSpan">youtube-api.activities.</span>list (params, callback)](#apidoc.element.youtube-api.activities.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/activities',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.captions"></a>[module youtube-api.captions](#apidoc.module.youtube-api.captions)

#### <a name="apidoc.element.youtube-api.captions.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.captions.</span>delete (params, callback)](#apidoc.element.youtube-api.captions.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/captions',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.captions.download"></a>[function <span class="apidocSignatureSpan">youtube-api.captions.</span>download (params, callback)](#apidoc.element.youtube-api.captions.download)
- description and source-code
```javascript
download = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/captions/{id}',
      method: 'GET'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: ['id'],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.captions.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.captions.</span>insert (params, callback)](#apidoc.element.youtube-api.captions.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/captions',
      method: 'POST'
    },
    params: params,
    mediaUrl: 'https://www.googleapis.com/upload/youtube/v3/captions',
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.captions.list"></a>[function <span class="apidocSignatureSpan">youtube-api.captions.</span>list (params, callback)](#apidoc.element.youtube-api.captions.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/captions',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part', 'videoId'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.captions.update"></a>[function <span class="apidocSignatureSpan">youtube-api.captions.</span>update (params, callback)](#apidoc.element.youtube-api.captions.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/captions',
      method: 'PUT'
    },
    params: params,
    mediaUrl: 'https://www.googleapis.com/upload/youtube/v3/captions',
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.channelBanners"></a>[module youtube-api.channelBanners](#apidoc.module.youtube-api.channelBanners)

#### <a name="apidoc.element.youtube-api.channelBanners.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.channelBanners.</span>insert (params, callback)](#apidoc.element.youtube-api.channelBanners.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/channelBanners/insert',
      method: 'POST'
    },
    params: params,
    mediaUrl: 'https://www.googleapis.com/upload/youtube/v3/channelBanners/insert',
    requiredParams: [],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```



# <a name="apidoc.module.youtube-api.channelSections"></a>[module youtube-api.channelSections](#apidoc.module.youtube-api.channelSections)

#### <a name="apidoc.element.youtube-api.channelSections.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.channelSections.</span>delete (params, callback)](#apidoc.element.youtube-api.channelSections.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/channelSections',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.channelSections.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.channelSections.</span>insert (params, callback)](#apidoc.element.youtube-api.channelSections.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/channelSections',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.channelSections.list"></a>[function <span class="apidocSignatureSpan">youtube-api.channelSections.</span>list (params, callback)](#apidoc.element.youtube-api.channelSections.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/channelSections',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.channelSections.update"></a>[function <span class="apidocSignatureSpan">youtube-api.channelSections.</span>update (params, callback)](#apidoc.element.youtube-api.channelSections.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/channelSections',
      method: 'PUT'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.channels"></a>[module youtube-api.channels](#apidoc.module.youtube-api.channels)

#### <a name="apidoc.element.youtube-api.channels.list"></a>[function <span class="apidocSignatureSpan">youtube-api.channels.</span>list (params, callback)](#apidoc.element.youtube-api.channels.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/channels',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.channels.update"></a>[function <span class="apidocSignatureSpan">youtube-api.channels.</span>update (params, callback)](#apidoc.element.youtube-api.channels.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/channels',
      method: 'PUT'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.commentThreads"></a>[module youtube-api.commentThreads](#apidoc.module.youtube-api.commentThreads)

#### <a name="apidoc.element.youtube-api.commentThreads.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.commentThreads.</span>insert (params, callback)](#apidoc.element.youtube-api.commentThreads.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/commentThreads',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.commentThreads.list"></a>[function <span class="apidocSignatureSpan">youtube-api.commentThreads.</span>list (params, callback)](#apidoc.element.youtube-api.commentThreads.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/commentThreads',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.commentThreads.update"></a>[function <span class="apidocSignatureSpan">youtube-api.commentThreads.</span>update (params, callback)](#apidoc.element.youtube-api.commentThreads.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/commentThreads',
      method: 'PUT'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.comments"></a>[module youtube-api.comments](#apidoc.module.youtube-api.comments)

#### <a name="apidoc.element.youtube-api.comments.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.comments.</span>delete (params, callback)](#apidoc.element.youtube-api.comments.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/comments',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.comments.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.comments.</span>insert (params, callback)](#apidoc.element.youtube-api.comments.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/comments',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.comments.list"></a>[function <span class="apidocSignatureSpan">youtube-api.comments.</span>list (params, callback)](#apidoc.element.youtube-api.comments.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/comments',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.comments.markAsSpam"></a>[function <span class="apidocSignatureSpan">youtube-api.comments.</span>markAsSpam (params, callback)](#apidoc.element.youtube-api.comments.markAsSpam)
- description and source-code
```javascript
markAsSpam = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/comments/markAsSpam',
      method: 'POST'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.comments.setModerationStatus"></a>[function <span class="apidocSignatureSpan">youtube-api.comments.</span>setModerationStatus (params, callback)](#apidoc.element.youtube-api.comments.setModerationStatus)
- description and source-code
```javascript
setModerationStatus = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/comments/setModerationStatus',
      method: 'POST'
    },
    params: params,
    requiredParams: ['id', 'moderationStatus'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.comments.update"></a>[function <span class="apidocSignatureSpan">youtube-api.comments.</span>update (params, callback)](#apidoc.element.youtube-api.comments.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/comments',
      method: 'PUT'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.fanFundingEvents"></a>[module youtube-api.fanFundingEvents](#apidoc.module.youtube-api.fanFundingEvents)

#### <a name="apidoc.element.youtube-api.fanFundingEvents.list"></a>[function <span class="apidocSignatureSpan">youtube-api.fanFundingEvents.</span>list (params, callback)](#apidoc.element.youtube-api.fanFundingEvents.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/fanFundingEvents',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.google"></a>[module youtube-api.google](#apidoc.module.youtube-api.google)

#### <a name="apidoc.element.youtube-api.google.GoogleApis"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>GoogleApis (options)](#apidoc.element.youtube-api.google.GoogleApis)
- description and source-code
```javascript
function GoogleApis(options) {
  this.options(options);
  this.addAPIs(apis);

<span class="apidocCodeCommentSpan">  /**
   * A reference to an instance of GoogleAuth.
   *
   * @name GoogleApis#auth
   * @type {GoogleAuth}
   */
</span>  this.auth = new GoogleAuth();

  /**
   * A reference to the GoogleApis constructor function.
   *
   * @name GoogleApis#GoogleApis
   * @type {Function}
   */
  this.GoogleApis = GoogleApis;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.adexchangebuyer"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>adexchangebuyer ()](#apidoc.element.youtube-api.google.adexchangebuyer)
- description and source-code
```javascript
adexchangebuyer = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.adexchangebuyer2"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>adexchangebuyer2 ()](#apidoc.element.youtube-api.google.adexchangebuyer2)
- description and source-code
```javascript
adexchangebuyer2 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.adexchangeseller"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>adexchangeseller ()](#apidoc.element.youtube-api.google.adexchangeseller)
- description and source-code
```javascript
adexchangeseller = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.admin"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>admin ()](#apidoc.element.youtube-api.google.admin)
- description and source-code
```javascript
admin = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.adsense"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>adsense ()](#apidoc.element.youtube-api.google.adsense)
- description and source-code
```javascript
adsense = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.adsensehost"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>adsensehost ()](#apidoc.element.youtube-api.google.adsensehost)
- description and source-code
```javascript
adsensehost = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.analytics"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>analytics ()](#apidoc.element.youtube-api.google.analytics)
- description and source-code
```javascript
analytics = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.analyticsreporting"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>analyticsreporting ()](#apidoc.element.youtube-api.google.analyticsreporting)
- description and source-code
```javascript
analyticsreporting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.androidenterprise"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>androidenterprise ()](#apidoc.element.youtube-api.google.androidenterprise)
- description and source-code
```javascript
androidenterprise = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.androidpublisher"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>androidpublisher ()](#apidoc.element.youtube-api.google.androidpublisher)
- description and source-code
```javascript
androidpublisher = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.appengine"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>appengine ()](#apidoc.element.youtube-api.google.appengine)
- description and source-code
```javascript
appengine = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.appsactivity"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>appsactivity ()](#apidoc.element.youtube-api.google.appsactivity)
- description and source-code
```javascript
appsactivity = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.appstate"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>appstate ()](#apidoc.element.youtube-api.google.appstate)
- description and source-code
```javascript
appstate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.autoscaler"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>autoscaler ()](#apidoc.element.youtube-api.google.autoscaler)
- description and source-code
```javascript
autoscaler = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.bigquery"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>bigquery ()](#apidoc.element.youtube-api.google.bigquery)
- description and source-code
```javascript
bigquery = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.blogger"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>blogger ()](#apidoc.element.youtube-api.google.blogger)
- description and source-code
```javascript
blogger = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.books"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>books ()](#apidoc.element.youtube-api.google.books)
- description and source-code
```javascript
books = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.calendar"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>calendar ()](#apidoc.element.youtube-api.google.calendar)
- description and source-code
```javascript
calendar = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.civicinfo"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>civicinfo ()](#apidoc.element.youtube-api.google.civicinfo)
- description and source-code
```javascript
civicinfo = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.classroom"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>classroom ()](#apidoc.element.youtube-api.google.classroom)
- description and source-code
```javascript
classroom = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.cloudbilling"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudbilling ()](#apidoc.element.youtube-api.google.cloudbilling)
- description and source-code
```javascript
cloudbilling = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.cloudbuild"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudbuild ()](#apidoc.element.youtube-api.google.cloudbuild)
- description and source-code
```javascript
cloudbuild = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.clouddebugger"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>clouddebugger ()](#apidoc.element.youtube-api.google.clouddebugger)
- description and source-code
```javascript
clouddebugger = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.clouderrorreporting"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>clouderrorreporting ()](#apidoc.element.youtube-api.google.clouderrorreporting)
- description and source-code
```javascript
clouderrorreporting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.cloudlatencytest"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudlatencytest ()](#apidoc.element.youtube-api.google.cloudlatencytest)
- description and source-code
```javascript
cloudlatencytest = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.cloudmonitoring"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudmonitoring ()](#apidoc.element.youtube-api.google.cloudmonitoring)
- description and source-code
```javascript
cloudmonitoring = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.cloudresourcemanager"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudresourcemanager ()](#apidoc.element.youtube-api.google.cloudresourcemanager)
- description and source-code
```javascript
cloudresourcemanager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.cloudtrace"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>cloudtrace ()](#apidoc.element.youtube-api.google.cloudtrace)
- description and source-code
```javascript
cloudtrace = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.clouduseraccounts"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>clouduseraccounts ()](#apidoc.element.youtube-api.google.clouduseraccounts)
- description and source-code
```javascript
clouduseraccounts = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.compute"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>compute ()](#apidoc.element.youtube-api.google.compute)
- description and source-code
```javascript
compute = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.consumersurveys"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>consumersurveys ()](#apidoc.element.youtube-api.google.consumersurveys)
- description and source-code
```javascript
consumersurveys = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.container"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>container ()](#apidoc.element.youtube-api.google.container)
- description and source-code
```javascript
container = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.content"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>content ()](#apidoc.element.youtube-api.google.content)
- description and source-code
```javascript
content = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.coordinate"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>coordinate ()](#apidoc.element.youtube-api.google.coordinate)
- description and source-code
```javascript
coordinate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.customsearch"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>customsearch ()](#apidoc.element.youtube-api.google.customsearch)
- description and source-code
```javascript
customsearch = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.dataflow"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>dataflow ()](#apidoc.element.youtube-api.google.dataflow)
- description and source-code
```javascript
dataflow = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.dataproc"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>dataproc ()](#apidoc.element.youtube-api.google.dataproc)
- description and source-code
```javascript
dataproc = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.datastore"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>datastore ()](#apidoc.element.youtube-api.google.datastore)
- description and source-code
```javascript
datastore = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.deploymentmanager"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>deploymentmanager ()](#apidoc.element.youtube-api.google.deploymentmanager)
- description and source-code
```javascript
deploymentmanager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.dfareporting"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>dfareporting ()](#apidoc.element.youtube-api.google.dfareporting)
- description and source-code
```javascript
dfareporting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.discovery"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>discovery ()](#apidoc.element.youtube-api.google.discovery)
- description and source-code
```javascript
discovery = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.dns"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>dns ()](#apidoc.element.youtube-api.google.dns)
- description and source-code
```javascript
dns = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.doubleclickbidmanager"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>doubleclickbidmanager ()](#apidoc.element.youtube-api.google.doubleclickbidmanager)
- description and source-code
```javascript
doubleclickbidmanager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.doubleclicksearch"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>doubleclicksearch ()](#apidoc.element.youtube-api.google.doubleclicksearch)
- description and source-code
```javascript
doubleclicksearch = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.drive"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>drive ()](#apidoc.element.youtube-api.google.drive)
- description and source-code
```javascript
drive = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.fitness"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>fitness ()](#apidoc.element.youtube-api.google.fitness)
- description and source-code
```javascript
fitness = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.freebase"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>freebase ()](#apidoc.element.youtube-api.google.freebase)
- description and source-code
```javascript
freebase = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.fusiontables"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>fusiontables ()](#apidoc.element.youtube-api.google.fusiontables)
- description and source-code
```javascript
fusiontables = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.games"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>games ()](#apidoc.element.youtube-api.google.games)
- description and source-code
```javascript
games = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.gamesConfiguration"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>gamesConfiguration ()](#apidoc.element.youtube-api.google.gamesConfiguration)
- description and source-code
```javascript
gamesConfiguration = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.gamesManagement"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>gamesManagement ()](#apidoc.element.youtube-api.google.gamesManagement)
- description and source-code
```javascript
gamesManagement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.gan"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>gan ()](#apidoc.element.youtube-api.google.gan)
- description and source-code
```javascript
gan = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.genomics"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>genomics ()](#apidoc.element.youtube-api.google.genomics)
- description and source-code
```javascript
genomics = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.gmail"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>gmail ()](#apidoc.element.youtube-api.google.gmail)
- description and source-code
```javascript
gmail = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.groupsmigration"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>groupsmigration ()](#apidoc.element.youtube-api.google.groupsmigration)
- description and source-code
```javascript
groupsmigration = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.groupssettings"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>groupssettings ()](#apidoc.element.youtube-api.google.groupssettings)
- description and source-code
```javascript
groupssettings = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.iam"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>iam ()](#apidoc.element.youtube-api.google.iam)
- description and source-code
```javascript
iam = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.identitytoolkit"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>identitytoolkit ()](#apidoc.element.youtube-api.google.identitytoolkit)
- description and source-code
```javascript
identitytoolkit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.kgsearch"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>kgsearch ()](#apidoc.element.youtube-api.google.kgsearch)
- description and source-code
```javascript
kgsearch = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.licensing"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>licensing ()](#apidoc.element.youtube-api.google.licensing)
- description and source-code
```javascript
licensing = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.logging"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>logging ()](#apidoc.element.youtube-api.google.logging)
- description and source-code
```javascript
logging = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.manager"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>manager ()](#apidoc.element.youtube-api.google.manager)
- description and source-code
```javascript
manager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.mirror"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>mirror ()](#apidoc.element.youtube-api.google.mirror)
- description and source-code
```javascript
mirror = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.monitoring"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>monitoring ()](#apidoc.element.youtube-api.google.monitoring)
- description and source-code
```javascript
monitoring = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.oauth2"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>oauth2 ()](#apidoc.element.youtube-api.google.oauth2)
- description and source-code
```javascript
oauth2 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.pagespeedonline"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>pagespeedonline ()](#apidoc.element.youtube-api.google.pagespeedonline)
- description and source-code
```javascript
pagespeedonline = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.partners"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>partners ()](#apidoc.element.youtube-api.google.partners)
- description and source-code
```javascript
partners = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.people"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>people ()](#apidoc.element.youtube-api.google.people)
- description and source-code
```javascript
people = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.playmoviespartner"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>playmoviespartner ()](#apidoc.element.youtube-api.google.playmoviespartner)
- description and source-code
```javascript
playmoviespartner = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.plus"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>plus ()](#apidoc.element.youtube-api.google.plus)
- description and source-code
```javascript
plus = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.plusDomains"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>plusDomains ()](#apidoc.element.youtube-api.google.plusDomains)
- description and source-code
```javascript
plusDomains = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.prediction"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>prediction ()](#apidoc.element.youtube-api.google.prediction)
- description and source-code
```javascript
prediction = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.proximitybeacon"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>proximitybeacon ()](#apidoc.element.youtube-api.google.proximitybeacon)
- description and source-code
```javascript
proximitybeacon = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.pubsub"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>pubsub ()](#apidoc.element.youtube-api.google.pubsub)
- description and source-code
```javascript
pubsub = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.qpxExpress"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>qpxExpress ()](#apidoc.element.youtube-api.google.qpxExpress)
- description and source-code
```javascript
qpxExpress = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.replicapool"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>replicapool ()](#apidoc.element.youtube-api.google.replicapool)
- description and source-code
```javascript
replicapool = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.replicapoolupdater"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>replicapoolupdater ()](#apidoc.element.youtube-api.google.replicapoolupdater)
- description and source-code
```javascript
replicapoolupdater = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.reseller"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>reseller ()](#apidoc.element.youtube-api.google.reseller)
- description and source-code
```javascript
reseller = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.resourceviews"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>resourceviews ()](#apidoc.element.youtube-api.google.resourceviews)
- description and source-code
```javascript
resourceviews = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.script"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>script ()](#apidoc.element.youtube-api.google.script)
- description and source-code
```javascript
script = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.serviceregistry"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>serviceregistry ()](#apidoc.element.youtube-api.google.serviceregistry)
- description and source-code
```javascript
serviceregistry = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.siteVerification"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>siteVerification ()](#apidoc.element.youtube-api.google.siteVerification)
- description and source-code
```javascript
siteVerification = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.spectrum"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>spectrum ()](#apidoc.element.youtube-api.google.spectrum)
- description and source-code
```javascript
spectrum = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.sqladmin"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>sqladmin ()](#apidoc.element.youtube-api.google.sqladmin)
- description and source-code
```javascript
sqladmin = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.storage"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>storage ()](#apidoc.element.youtube-api.google.storage)
- description and source-code
```javascript
storage = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.storagetransfer"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>storagetransfer ()](#apidoc.element.youtube-api.google.storagetransfer)
- description and source-code
```javascript
storagetransfer = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.tagmanager"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>tagmanager ()](#apidoc.element.youtube-api.google.tagmanager)
- description and source-code
```javascript
tagmanager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.taskqueue"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>taskqueue ()](#apidoc.element.youtube-api.google.taskqueue)
- description and source-code
```javascript
taskqueue = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.tasks"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>tasks ()](#apidoc.element.youtube-api.google.tasks)
- description and source-code
```javascript
tasks = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.toolresults"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>toolresults ()](#apidoc.element.youtube-api.google.toolresults)
- description and source-code
```javascript
toolresults = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.translate"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>translate ()](#apidoc.element.youtube-api.google.translate)
- description and source-code
```javascript
translate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.urlshortener"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>urlshortener ()](#apidoc.element.youtube-api.google.urlshortener)
- description and source-code
```javascript
urlshortener = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.vision"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>vision ()](#apidoc.element.youtube-api.google.vision)
- description and source-code
```javascript
vision = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.webfonts"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>webfonts ()](#apidoc.element.youtube-api.google.webfonts)
- description and source-code
```javascript
webfonts = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.webmasters"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>webmasters ()](#apidoc.element.youtube-api.google.webmasters)
- description and source-code
```javascript
webmasters = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.youtube"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>youtube ()](#apidoc.element.youtube-api.google.youtube)
- description and source-code
```javascript
youtube = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.youtubeAnalytics"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>youtubeAnalytics ()](#apidoc.element.youtube-api.google.youtubeAnalytics)
- description and source-code
```javascript
youtubeAnalytics = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.youtubereporting"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>youtubereporting ()](#apidoc.element.youtube-api.google.youtubereporting)
- description and source-code
```javascript
youtubereporting = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.google.GoogleApis"></a>[module youtube-api.google.GoogleApis](#apidoc.module.youtube-api.google.GoogleApis)

#### <a name="apidoc.element.youtube-api.google.GoogleApis.GoogleApis"></a>[function <span class="apidocSignatureSpan">youtube-api.google.</span>GoogleApis (options)](#apidoc.element.youtube-api.google.GoogleApis.GoogleApis)
- description and source-code
```javascript
function GoogleApis(options) {
  this.options(options);
  this.addAPIs(apis);

<span class="apidocCodeCommentSpan">  /**
   * A reference to an instance of GoogleAuth.
   *
   * @name GoogleApis#auth
   * @type {GoogleAuth}
   */
</span>  this.auth = new GoogleAuth();

  /**
   * A reference to the GoogleApis constructor function.
   *
   * @name GoogleApis#GoogleApis
   * @type {Function}
   */
  this.GoogleApis = GoogleApis;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.google.GoogleApis.prototype"></a>[module youtube-api.google.GoogleApis.prototype](#apidoc.module.youtube-api.google.GoogleApis.prototype)

#### <a name="apidoc.element.youtube-api.google.GoogleApis.prototype.addAPIs"></a>[function <span class="apidocSignatureSpan">youtube-api.google.GoogleApis.prototype.</span>addAPIs (apis)](#apidoc.element.youtube-api.google.GoogleApis.prototype.addAPIs)
- description and source-code
```javascript
addAPIs = function (apis) {
  for (var apiName in apis) {
    this[apiName] = apis[apiName].bind(this);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.GoogleApis.prototype.discover"></a>[function <span class="apidocSignatureSpan">youtube-api.google.GoogleApis.prototype.</span>discover (url, callback)](#apidoc.element.youtube-api.google.GoogleApis.prototype.discover)
- description and source-code
```javascript
discover = function (url, callback) {
  var self = this;

  discovery.discoverAllAPIs(url, function (err, apis) {
    if (err) {
      return callback(err);
    }
    self.addAPIs(apis);
    callback();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.GoogleApis.prototype.discoverAPI"></a>[function <span class="apidocSignatureSpan">youtube-api.google.GoogleApis.prototype.</span>discoverAPI (path, options, callback)](#apidoc.element.youtube-api.google.GoogleApis.prototype.discoverAPI)
- description and source-code
```javascript
discoverAPI = function (path, options, callback) {
  var self = this;
  if (typeof options === 'function') {
    callback = options;
    options = {};
  }
  if (!options) {
    options = {};
  }
  discovery.discoverAPI(path, function (err, Endpoint) {
    if (err) {
      return callback(err);
    }
    var ep = new Endpoint(options);
    ep.google = self; // for drive.google.transporter
    return callback(null, Object.freeze(ep)); // create new & freeze
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.GoogleApis.prototype.options"></a>[function <span class="apidocSignatureSpan">youtube-api.google.GoogleApis.prototype.</span>options (options)](#apidoc.element.youtube-api.google.GoogleApis.prototype.options)
- description and source-code
```javascript
options = function (options) {
  this._options = options || {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.google.auth"></a>[module youtube-api.google.auth](#apidoc.module.youtube-api.google.auth)

#### <a name="apidoc.element.youtube-api.google.auth.ComputeClient"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.</span>ComputeClient ()](#apidoc.element.youtube-api.google.auth.ComputeClient)
- description and source-code
```javascript
function Compute() {
  Compute.super_.call(this);
  // Start with an expired refresh token, which will automatically be refreshed
  // before the first API call is made.
  this.credentials = {
    refresh_token: 'compute-placeholder',
    expiry_date: 1
  };

  // Hook the post request method so we can provide better error messages.
  this._postRequest = this._injectErrorMessage;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.JWTClient"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.</span>JWTClient (email, keyFile, key, scopes, subject)](#apidoc.element.youtube-api.google.auth.JWTClient)
- description and source-code
```javascript
function JWT(email, keyFile, key, scopes, subject) {
  JWT.super_.call(this);
  this.email = email;
  this.keyFile = keyFile;
  this.key = key;
  this.scopes = scopes;
  this.subject = subject;
  this.gToken = gToken;

  this.credentials = {
    refresh_token: 'jwt-placeholder',
    expiry_date: 1
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.google.auth.ComputeClient.prototype"></a>[module youtube-api.google.auth.ComputeClient.prototype](#apidoc.module.youtube-api.google.auth.ComputeClient.prototype)

#### <a name="apidoc.element.youtube-api.google.auth.ComputeClient.prototype._injectErrorMessage"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.ComputeClient.prototype.</span>_injectErrorMessage (err, result, response, callback)](#apidoc.element.youtube-api.google.auth.ComputeClient.prototype._injectErrorMessage)
- description and source-code
```javascript
_injectErrorMessage = function (err, result, response, callback) {
  if (response && response.statusCode) {
    var helpfulMessage = null;
    if (response.statusCode === 403) {
      helpfulMessage = 'A Forbidden error was returned while attempting to retrieve an access ' +
        'token for the Compute Engine built-in service account. This may be because the Compute ' +
        'Engine instance does not have the correct permission scopes specified.';
    } else if (response.statusCode === 404) {
      helpfulMessage = 'A Not Found error was returned while attempting to retrieve an access' +
        'token for the Compute Engine built-in service account. This may be because the Compute ' +
        'Engine instance does not have any permission scopes specified.';
    }
    if (helpfulMessage) {
      if (err && err.message) {
        helpfulMessage += ' ' + err.message;
      }

      if (err) {
        err.message = helpfulMessage;
      } else {
        err = new Error(helpfulMessage);
        err.code = response.statusCode;
      }
    }
  }
  callback(err, result, response);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.ComputeClient.prototype.createScopedRequired"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.ComputeClient.prototype.</span>createScopedRequired ()](#apidoc.element.youtube-api.google.auth.ComputeClient.prototype.createScopedRequired)
- description and source-code
```javascript
createScopedRequired = function () {
  // On compute engine, scopes are specified at the compute instance's creation time,
  // and cannot be changed. For this reason, always return false.
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.ComputeClient.prototype.refreshToken_"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.ComputeClient.prototype.</span>refreshToken_ (ignored_, opt_callback)](#apidoc.element.youtube-api.google.auth.ComputeClient.prototype.refreshToken_)
- description and source-code
```javascript
refreshToken_ = function (ignored_, opt_callback) {
  var uri = this.opts.tokenUrl || Compute.GOOGLE_OAUTH2_TOKEN_URL_;
  // request for new token
  this.transporter.request({
    method: 'GET',
    uri: uri,
    json: true
  }, function(err, tokens, response) {
    if (!err && tokens && tokens.expires_in) {
      tokens.expiry_date = ((new Date()).getTime() + (tokens.expires_in * 1000));
      delete tokens.expires_in;
    }

    if (opt_callback) {
      opt_callback(err, tokens, response);
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.google.auth.JWTClient.prototype"></a>[module youtube-api.google.auth.JWTClient.prototype](#apidoc.module.youtube-api.google.auth.JWTClient.prototype)

#### <a name="apidoc.element.youtube-api.google.auth.JWTClient.prototype._createGToken"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>_createGToken (callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype._createGToken)
- description and source-code
```javascript
_createGToken = function (callback) {
  if (this.gtoken) {
    return callback(null, this.gtoken);
  } else {
    this.gtoken = this.gToken({
      iss: this.email,
      sub: this.subject,
      scope: this.scopes,
      keyFile: this.keyFile,
      key: this.key
    });
    return callback(null, this.gtoken);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.JWTClient.prototype.authorize"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>authorize (opt_callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.authorize)
- description and source-code
```javascript
authorize = function (opt_callback) {
  var that = this;
  var done = opt_callback || noop;

  that.refreshToken_(null, function(err, result) {
    if (!err) {
      that.credentials = result;
      that.credentials.refresh_token = 'jwt-placeholder';
      that.key = that.gtoken.key;
      that.email = that.gtoken.iss;
    }
    done(err, result);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.JWTClient.prototype.createScoped"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>createScoped (scopes)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.createScoped)
- description and source-code
```javascript
createScoped = function (scopes) {
  return new JWT(this.email, this.keyFile, this.key, scopes, this.subject);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.JWTClient.prototype.createScopedRequired"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>createScopedRequired ()](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.createScopedRequired)
- description and source-code
```javascript
createScopedRequired = function () {
  // If scopes is null, always return true.
  if (this.scopes) {
    // For arrays, check the array length.
    if (this.scopes instanceof Array) {
      return this.scopes.length === 0;
    }

    // For others, convert to a string and check the length.
    return String(this.scopes).length === 0;
  }

  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.JWTClient.prototype.fromJSON"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>fromJSON (json, opt_callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.fromJSON)
- description and source-code
```javascript
fromJSON = function (json, opt_callback) {
  var that = this;
  var done = opt_callback || noop;
  if (!json) {
    done(new Error(
      'Must pass in a JSON object containing the service account auth settings.'));
    return;
  }
  if (!json.client_email) {
    done(new Error(
      'The incoming JSON object does not contain a client_email field'));
    return;
  }
  if (!json.private_key) {
    done(new Error(
      'The incoming JSON object does not contain a private_key field'));
    return;
  }
  // Extract the relevant information from the json key file.
  that.email = json.client_email;
  that.key = json.private_key;
  that.projectId = json.project_id;
  done();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.JWTClient.prototype.fromStream"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>fromStream (stream, opt_callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.fromStream)
- description and source-code
```javascript
fromStream = function (stream, opt_callback) {
  var that = this;
  var done = opt_callback || noop;

  if (!stream) {
    process.nextTick(function() {
      done(
        new Error('Must pass in a stream containing the service account auth settings.'));
    });
    return;
  }
  var s = '';
  stream.setEncoding('utf8');
  stream.on('data', function (chunk) {
    s += chunk;
  });
  stream.on('end', function () {
    try {
      var data = JSON.parse(s);
      that.fromJSON(data, opt_callback);
    } catch (err) {
      done(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.JWTClient.prototype.getRequestMetadata"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>getRequestMetadata (opt_uri, metadataCb)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.getRequestMetadata)
- description and source-code
```javascript
getRequestMetadata = function (opt_uri, metadataCb) {
  if (this.createScopedRequired() && opt_uri) {
    // no scopes have been set, but a uri has been provided.  Use JWTAccess credentials.
    var alt = new JWTAccess(this.email, this.key);
    return alt.getRequestMetadata(opt_uri, metadataCb);
  } else {
    return JWT.super_.prototype.getRequestMetadata.call(
        this, opt_uri, metadataCb);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.google.auth.JWTClient.prototype.refreshToken_"></a>[function <span class="apidocSignatureSpan">youtube-api.google.auth.JWTClient.prototype.</span>refreshToken_ (ignored_, opt_callback)](#apidoc.element.youtube-api.google.auth.JWTClient.prototype.refreshToken_)
- description and source-code
```javascript
refreshToken_ = function (ignored_, opt_callback) {
  var done = opt_callback || noop;

  return this._createGToken(function(err, gToken) {
    if (err) {
      return done(err);
    } else {
      return gToken.getToken(function (err, token) {
        return done(err, {
          access_token: token,
          token_type: 'Bearer',
          expiry_date: gToken.expires_at
        });
      });
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.guideCategories"></a>[module youtube-api.guideCategories](#apidoc.module.youtube-api.guideCategories)

#### <a name="apidoc.element.youtube-api.guideCategories.list"></a>[function <span class="apidocSignatureSpan">youtube-api.guideCategories.</span>list (params, callback)](#apidoc.element.youtube-api.guideCategories.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/guideCategories',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.i18nLanguages"></a>[module youtube-api.i18nLanguages](#apidoc.module.youtube-api.i18nLanguages)

#### <a name="apidoc.element.youtube-api.i18nLanguages.list"></a>[function <span class="apidocSignatureSpan">youtube-api.i18nLanguages.</span>list (params, callback)](#apidoc.element.youtube-api.i18nLanguages.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/i18nLanguages',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.i18nRegions"></a>[module youtube-api.i18nRegions](#apidoc.module.youtube-api.i18nRegions)

#### <a name="apidoc.element.youtube-api.i18nRegions.list"></a>[function <span class="apidocSignatureSpan">youtube-api.i18nRegions.</span>list (params, callback)](#apidoc.element.youtube-api.i18nRegions.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/i18nRegions',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.liveBroadcasts"></a>[module youtube-api.liveBroadcasts](#apidoc.module.youtube-api.liveBroadcasts)

#### <a name="apidoc.element.youtube-api.liveBroadcasts.bind"></a>[function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>bind (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.bind)
- description and source-code
```javascript
bind = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveBroadcasts/bind',
      method: 'POST'
    },
    params: params,
    requiredParams: ['id', 'part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveBroadcasts.control"></a>[function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>control (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.control)
- description and source-code
```javascript
control = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveBroadcasts/control',
      method: 'POST'
    },
    params: params,
    requiredParams: ['id', 'part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveBroadcasts.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>delete (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveBroadcasts',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveBroadcasts.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>insert (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveBroadcasts',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.liveBroadcasts.list"></a>[function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>list (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveBroadcasts',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveBroadcasts.transition"></a>[function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>transition (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.transition)
- description and source-code
```javascript
transition = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveBroadcasts/transition',
      method: 'POST'
    },
    params: params,
    requiredParams: ['broadcastStatus', 'id', 'part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveBroadcasts.update"></a>[function <span class="apidocSignatureSpan">youtube-api.liveBroadcasts.</span>update (params, callback)](#apidoc.element.youtube-api.liveBroadcasts.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveBroadcasts',
      method: 'PUT'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.liveChatBans"></a>[module youtube-api.liveChatBans](#apidoc.module.youtube-api.liveChatBans)

#### <a name="apidoc.element.youtube-api.liveChatBans.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.liveChatBans.</span>delete (params, callback)](#apidoc.element.youtube-api.liveChatBans.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveChat/bans',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveChatBans.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.liveChatBans.</span>insert (params, callback)](#apidoc.element.youtube-api.liveChatBans.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveChat/bans',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```



# <a name="apidoc.module.youtube-api.liveChatMessages"></a>[module youtube-api.liveChatMessages](#apidoc.module.youtube-api.liveChatMessages)

#### <a name="apidoc.element.youtube-api.liveChatMessages.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.liveChatMessages.</span>delete (params, callback)](#apidoc.element.youtube-api.liveChatMessages.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveChat/messages',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveChatMessages.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.liveChatMessages.</span>insert (params, callback)](#apidoc.element.youtube-api.liveChatMessages.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveChat/messages',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.liveChatMessages.list"></a>[function <span class="apidocSignatureSpan">youtube-api.liveChatMessages.</span>list (params, callback)](#apidoc.element.youtube-api.liveChatMessages.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveChat/messages',
      method: 'GET'
    },
    params: params,
    requiredParams: ['liveChatId', 'part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.liveChatModerators"></a>[module youtube-api.liveChatModerators](#apidoc.module.youtube-api.liveChatModerators)

#### <a name="apidoc.element.youtube-api.liveChatModerators.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.liveChatModerators.</span>delete (params, callback)](#apidoc.element.youtube-api.liveChatModerators.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveChat/moderators',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveChatModerators.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.liveChatModerators.</span>insert (params, callback)](#apidoc.element.youtube-api.liveChatModerators.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveChat/moderators',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.liveChatModerators.list"></a>[function <span class="apidocSignatureSpan">youtube-api.liveChatModerators.</span>list (params, callback)](#apidoc.element.youtube-api.liveChatModerators.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveChat/moderators',
      method: 'GET'
    },
    params: params,
    requiredParams: ['liveChatId', 'part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.liveStreams"></a>[module youtube-api.liveStreams](#apidoc.module.youtube-api.liveStreams)

#### <a name="apidoc.element.youtube-api.liveStreams.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.liveStreams.</span>delete (params, callback)](#apidoc.element.youtube-api.liveStreams.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveStreams',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveStreams.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.liveStreams.</span>insert (params, callback)](#apidoc.element.youtube-api.liveStreams.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveStreams',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.liveStreams.list"></a>[function <span class="apidocSignatureSpan">youtube-api.liveStreams.</span>list (params, callback)](#apidoc.element.youtube-api.liveStreams.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveStreams',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.liveStreams.update"></a>[function <span class="apidocSignatureSpan">youtube-api.liveStreams.</span>update (params, callback)](#apidoc.element.youtube-api.liveStreams.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/liveStreams',
      method: 'PUT'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.playlistItems"></a>[module youtube-api.playlistItems](#apidoc.module.youtube-api.playlistItems)

#### <a name="apidoc.element.youtube-api.playlistItems.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.playlistItems.</span>delete (params, callback)](#apidoc.element.youtube-api.playlistItems.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/playlistItems',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.playlistItems.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.playlistItems.</span>insert (params, callback)](#apidoc.element.youtube-api.playlistItems.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/playlistItems',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.playlistItems.list"></a>[function <span class="apidocSignatureSpan">youtube-api.playlistItems.</span>list (params, callback)](#apidoc.element.youtube-api.playlistItems.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/playlistItems',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.playlistItems.update"></a>[function <span class="apidocSignatureSpan">youtube-api.playlistItems.</span>update (params, callback)](#apidoc.element.youtube-api.playlistItems.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/playlistItems',
      method: 'PUT'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.playlists"></a>[module youtube-api.playlists](#apidoc.module.youtube-api.playlists)

#### <a name="apidoc.element.youtube-api.playlists.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.playlists.</span>delete (params, callback)](#apidoc.element.youtube-api.playlists.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/playlists',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.playlists.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.playlists.</span>insert (params, callback)](#apidoc.element.youtube-api.playlists.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/playlists',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.playlists.list"></a>[function <span class="apidocSignatureSpan">youtube-api.playlists.</span>list (params, callback)](#apidoc.element.youtube-api.playlists.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/playlists',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.playlists.update"></a>[function <span class="apidocSignatureSpan">youtube-api.playlists.</span>update (params, callback)](#apidoc.element.youtube-api.playlists.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/playlists',
      method: 'PUT'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.search"></a>[module youtube-api.search](#apidoc.module.youtube-api.search)

#### <a name="apidoc.element.youtube-api.search.list"></a>[function <span class="apidocSignatureSpan">youtube-api.search.</span>list (params, callback)](#apidoc.element.youtube-api.search.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/search',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.sponsors"></a>[module youtube-api.sponsors](#apidoc.module.youtube-api.sponsors)

#### <a name="apidoc.element.youtube-api.sponsors.list"></a>[function <span class="apidocSignatureSpan">youtube-api.sponsors.</span>list (params, callback)](#apidoc.element.youtube-api.sponsors.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/sponsors',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.subscriptions"></a>[module youtube-api.subscriptions](#apidoc.module.youtube-api.subscriptions)

#### <a name="apidoc.element.youtube-api.subscriptions.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.subscriptions.</span>delete (params, callback)](#apidoc.element.youtube-api.subscriptions.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/subscriptions',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.subscriptions.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.subscriptions.</span>insert (params, callback)](#apidoc.element.youtube-api.subscriptions.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/subscriptions',
      method: 'POST'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.subscriptions.list"></a>[function <span class="apidocSignatureSpan">youtube-api.subscriptions.</span>list (params, callback)](#apidoc.element.youtube-api.subscriptions.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/subscriptions',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.thumbnails"></a>[module youtube-api.thumbnails](#apidoc.module.youtube-api.thumbnails)

#### <a name="apidoc.element.youtube-api.thumbnails.set"></a>[function <span class="apidocSignatureSpan">youtube-api.thumbnails.</span>set (params, callback)](#apidoc.element.youtube-api.thumbnails.set)
- description and source-code
```javascript
set = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/thumbnails/set',
      method: 'POST'
    },
    params: params,
    mediaUrl: 'https://www.googleapis.com/upload/youtube/v3/thumbnails/set',
    requiredParams: ['videoId'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.videoAbuseReportReasons"></a>[module youtube-api.videoAbuseReportReasons](#apidoc.module.youtube-api.videoAbuseReportReasons)

#### <a name="apidoc.element.youtube-api.videoAbuseReportReasons.list"></a>[function <span class="apidocSignatureSpan">youtube-api.videoAbuseReportReasons.</span>list (params, callback)](#apidoc.element.youtube-api.videoAbuseReportReasons.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/videoAbuseReportReasons',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.videoCategories"></a>[module youtube-api.videoCategories](#apidoc.module.youtube-api.videoCategories)

#### <a name="apidoc.element.youtube-api.videoCategories.list"></a>[function <span class="apidocSignatureSpan">youtube-api.videoCategories.</span>list (params, callback)](#apidoc.element.youtube-api.videoCategories.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/videoCategories',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.videos"></a>[module youtube-api.videos](#apidoc.module.youtube-api.videos)

#### <a name="apidoc.element.youtube-api.videos.delete"></a>[function <span class="apidocSignatureSpan">youtube-api.videos.</span>delete (params, callback)](#apidoc.element.youtube-api.videos.delete)
- description and source-code
```javascript
delete = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/videos',
      method: 'DELETE'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.videos.getRating"></a>[function <span class="apidocSignatureSpan">youtube-api.videos.</span>getRating (params, callback)](#apidoc.element.youtube-api.videos.getRating)
- description and source-code
```javascript
getRating = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/videos/getRating',
      method: 'GET'
    },
    params: params,
    requiredParams: ['id'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.videos.insert"></a>[function <span class="apidocSignatureSpan">youtube-api.videos.</span>insert (params, callback)](#apidoc.element.youtube-api.videos.insert)
- description and source-code
```javascript
insert = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/videos',
      method: 'POST'
    },
    params: params,
    mediaUrl: 'https://www.googleapis.com/upload/youtube/v3/videos',
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
...

Logger.log("Got the tokens.");

oauth.setCredentials(tokens);

lien.end("The video is being uploaded. Check out the logs in the terminal.");

var req = Youtube.videos.insert({
    resource: {
        // Video title and description
        snippet: {
            title: "Testing YoutTube API NodeJS module"
          , description: "Test video upload via YouTube API"
        }
        // I don't want to spam my subscribers
...
```

#### <a name="apidoc.element.youtube-api.videos.list"></a>[function <span class="apidocSignatureSpan">youtube-api.videos.</span>list (params, callback)](#apidoc.element.youtube-api.videos.list)
- description and source-code
```javascript
list = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/videos',
      method: 'GET'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.videos.rate"></a>[function <span class="apidocSignatureSpan">youtube-api.videos.</span>rate (params, callback)](#apidoc.element.youtube-api.videos.rate)
- description and source-code
```javascript
rate = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/videos/rate',
      method: 'POST'
    },
    params: params,
    requiredParams: ['id', 'rating'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.videos.reportAbuse"></a>[function <span class="apidocSignatureSpan">youtube-api.videos.</span>reportAbuse (params, callback)](#apidoc.element.youtube-api.videos.reportAbuse)
- description and source-code
```javascript
reportAbuse = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/videos/reportAbuse',
      method: 'POST'
    },
    params: params,
    requiredParams: [],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.videos.update"></a>[function <span class="apidocSignatureSpan">youtube-api.videos.</span>update (params, callback)](#apidoc.element.youtube-api.videos.update)
- description and source-code
```javascript
update = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/videos',
      method: 'PUT'
    },
    params: params,
    requiredParams: ['part'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.youtube-api.watermarks"></a>[module youtube-api.watermarks](#apidoc.module.youtube-api.watermarks)

#### <a name="apidoc.element.youtube-api.watermarks.set"></a>[function <span class="apidocSignatureSpan">youtube-api.watermarks.</span>set (params, callback)](#apidoc.element.youtube-api.watermarks.set)
- description and source-code
```javascript
set = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/watermarks/set',
      method: 'POST'
    },
    params: params,
    mediaUrl: 'https://www.googleapis.com/upload/youtube/v3/watermarks/set',
    requiredParams: ['channelId'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.youtube-api.watermarks.unset"></a>[function <span class="apidocSignatureSpan">youtube-api.watermarks.</span>unset (params, callback)](#apidoc.element.youtube-api.watermarks.unset)
- description and source-code
```javascript
unset = function (params, callback) {
  var parameters = {
    options: {
      url: 'https://www.googleapis.com/youtube/v3/watermarks/unset',
      method: 'POST'
    },
    params: params,
    requiredParams: ['channelId'],
    pathParams: [],
    context: self
  };

  return createAPIRequest(parameters, callback);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
