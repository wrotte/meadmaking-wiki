---
revision_id: 551bb118-37a5-11ec-8b88-beb04831c063
revision_date: 1635394377
---

/* hope this works */
/*announcement sticky leo1cw */
div.content {
    /*This lowers the links to create space*/
    margin-top: 30px
    }
.titlebox form {
    /*Hack to enable repositioning of child elements*/
    position: static
    }
.side h4:nth-of-type(1) {
    /*this code positions the sticky*/
    position: absolute;
    display: block;
    top: 80px;
    left: 100px;
    /*this code styles the sticky*/
    background-color: #F5DA81;
    color: #555555;
    text-align: left;
    margin: 15px;
    border-radius: 8px;
    width: 33%;
    padding: 7px 0px 7px 40px;
    } 

/* Allow absolute positioning to page */
.titlebox form {
    position: static
    }

/* Flair Sprites */
#container li {
   background: no-repeat top left;
}

.flairselector .customizer {
    display: none !important;
}

/* Added 12/08/16 by /u/balathustrius */
div.flairselector .flairoptionpane ul{
    width:250px;
}

/* Flair Updated 7/7/16 by /u/balathustrius */
/* Updated 12/08/16 by /u/balathustrius to add flair names to flair selector. */
.flair {
    border: none !important;
    top:20px;
    padding:0px;
    background: url(%%spritesheet3%%);
    display:inline-block;
}

.flair-moderator {
    width: 20px;
    height: 20px;
    background-position: 0 0;
    text-align: center !important; text-indent: -9999em;
}

li.flairsample-right .flair-moderator {
    width: 20px;
    height: 20px;
    background-position: 0 0;
    text-align: center !important; text-indent: 2.2em;
}

.flair-beginner {
    width: 20px;
    height: 20px;
    background-position: 0 -20px;
    text-align: center !important; text-indent: -9999em;
}

li.flairsample-right .flair-beginner {
    width: 20px;
    height: 20px;
    background-position: 0 -20px;
    text-align: center !important; text-indent: 2.2em;
}

.flair-expert {
    width: 20px;
    height: 20px;
    background-position: 0 -40px;
    text-align: center !important; text-indent: -9999em;
}

li.flairsample-right .flair-expert{
    width: 20px;
    height: 20px;
    background-position: 0 -40px;
    text-align: center !important; text-indent: 2.2em;
}

.flair-intermediate {
    width: 20px;
    height: 20px;
    background-position: 0 -60px;
    text-align: center !important; text-indent: -9999em;
}

li.flairsample-right .flair-intermediate{
    width: 20px;
    height: 20px;
    background-position: 0 -60px;
    text-align: center !important; text-indent: 2.2em;
}

.flair-master {
    width: 20px;
    height: 20px;
    background-position: 0 -80px;
    text-align: center !important; text-indent: -9999em;
}

li.flairsample-right .flair-master{
    width: 20px;
    height: 20px;
    background-position: 0 -80px;
    text-align: center !important; text-indent: 2.2em;
}

.flair-wiki-editor {
    width: 25px;
    height: 25px;
    background-position: 0 -99px;
    text-align: center !important; text-indent: -9999em;
}

li.flairsample-right .flair-wiki-editor{
    width: 20px;
    height: 20px;
    background-position: 0 -99px;
    text-align: center !important; text-indent: 2.2em;
}

.flair-welcoming-committee {
    width: 25px;
    height: 25px;
    background-position: 0 -123px;
    text-align: center !important; text-indent: -9999em;
}

li.flairsample-right .flair-welcoming-committee{
    width: 20px;
    height: 20px;
    background-position: 0 -123px;
    text-align: center !important; text-indent: 2.2em;
}

/* Upvote and Downvote icons */
.arrow.upmod, .arrow.up, .arrow.down, .arrow.downmod {
    background-position: 0 0;
    height: 16px;
    width: 16px
    }
.arrow.up {
    background-image: url(%%upvote%%)
    }
.arrow.upmod {
    background-image: url(%%upvoteclick%%)
    }
.arrow.down {
    background-image: url(%%downvote%%)
    }
.arrow.downmod {
    background-image: url(%%downvoteclick%%)
    }

/*=========================================== HEADER =====================================*/
/* Reddit logo */
#header-img {
    visibility: hidden;
    padding: 2px;
    margin-top: 25px !important
    }
/*Header where mail button is */
#header-bottom-right {
    top: 19px !important;
    margin: 7px 4px 0 0 !important;
    bottom: auto !important
    }
#header-bottom-right {
    position: absolute !important;
    right: 0px !important;
    padding-left: 20px !important;
    padding-right: 7px !important;
    padding-top: 4px !important;
    padding-bottom: 4px !important;
    line-height: 12px !important;
    -moz-border-radius: 7px !important;
    -webkit-border-radius: 7px !important;
    border-radius: 7px !important;
    border: 2px solid #aa6622 !important
    }
#userbarToggle {
    position: absolute;
    top: 0px;
    left: 0px;
    width: 16px;
    /*padding-right: 3px;*/
    height: 21px;
    font-size: 15px;
    -moz-border-radius-topleft: 7px;
    -webkit-border-top-left-radius: 7px;
    -moz-border-radius-topright: 0px;
    -webkit-border-top-right-radius: 0px;
    border-top-left-radius: 7px;
    border-top-right-radius: 0px;
    -moz-border-radius-bottomleft: 7px;
    -webkit-border-bottom-left-radius: 7px;
    -moz-border-radius-bottomright: 0px;
    -webkit-border-bottom-right-radius: 0px;
    border-bottom-left-radius: 7px;
    border-bottom-right-radius: 0px;
    display: inline-block;
    border-right: 1px solid #aa6622;
    cursor: pointer;
    text-align: right;
    line-height: 20px
    }
/*my subreddits very top header bar*/
#sr-header-area {
    padding: 3px 0px 3px 5px;
    white-space: nowrap;
    overflow: hidden;
    text-transform: uppercase;
    border: 2px solid #aa6622;
    font-size: 90%;
    -moz-border-radius-topleft: 10px;
    -webkit-border-top-left-radius: 10px;
    -moz-border-radius-topright: 10px;
    -webkit-border-top-right-radius: 10px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    -moz-border-radius-bottomleft: 10px;
    -webkit-border-bottom-left-radius: 10px;
    -moz-border-radius-bottomright: 10px;
    -webkit-border-bottom-right-radius: 10px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px
    }
#header {
    border-bottom: none
    }
/*name of subreddit in header, replaced with logo*/
.pagename a {
    position: absolute !important;
    z-index: 100;
    top: 30px !important;
    left: 20px !important;
    width: 275px !important;
    /*color: #aa6622 !important;*/
    font-size: 0px !important;
    padding: 50px 6px 0 50px !important;
    /*background-color: #ffdd77;*/
    background-image: url(%%meadlogo%%);
    background-repeat: no-repeat;
    -moz-border-radius-topleft: 10px;
    -webkit-border-top-left-radius: 10px;
    -moz-border-radius-topright: 10px;
    -webkit-border-top-right-radius: 10px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    -moz-border-radius-bottomleft: 10px;
    -webkit-border-bottom-left-radius: 10px;
    -moz-border-radius-bottomright: 10px;
    -webkit-border-bottom-right-radius: 10px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    border: 0px solid #aa6622;
    border-bottom: 0px solid #aa6622 !important
    }
/*tabs at top*/
/*selected tab*/
.tabmenu li.selected a {
    font-size: 12px !important;
    -moz-border-radius-topleft: 10px;
    -webkit-border-top-left-radius: 10px;
    -moz-border-radius-topright: 10px;
    -webkit-border-top-right-radius: 10px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    border: 2px solid #aa6622;
    -moz-border-radius-bottomleft: 10px;
    -webkit-border-bottom-left-radius: 10px;
    -moz-border-radius-bottomright: 10px;
    -webkit-border-bottom-right-radius: 10px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    border: 2px solid #aa6622 !important;
    border-bottom: 2px solid #aa6622 !important;
    z-index: 100
    }
/*other tabs*/
.tabmenu li a {
    font-size: 12px !important;
    padding: 2px 6px 0 6px;
    -moz-border-radius-topleft: 10px;
    -webkit-border-top-left-radius: 10px;
    -moz-border-radius-topright: 10px;
    -webkit-border-top-right-radius: 10px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    border: 2px solid #aa6622 !important;
    -moz-border-radius-bottomleft: 10px;
    -webkit-border-bottom-left-radius: 10px;
    -moz-border-radius-bottomright: 10px;
    -webkit-border-bottom-right-radius: 10px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    border: 2px solid #aa6622 !important;
    border-bottom: 2px solid #aa6622 !important;
    z-index: 100
    }
/*Title bar background*/
#header-bottom-left {
    padding-top: 0px;
    padding-bottom: 0px;
    background: url(%%meadbackgroundpattern%%);
    /* opacity: 0.4;*/
    border-bottom: 2px solid #aa6622
    }

/* ==================================BODY============================================ */

/* Mazer Count */
div.titlebox span.word {
    display: none
    }
div.titlebox span.number:after {
    content: " Mazers"
    }

/* Change color of subreddit title in sidebar*/
.side .redditname {
    text-transform: capitalize;
    /*display:block;*/
    /*text-indent:-9999px;*/
    /*height:150px;*/
    /*width:275px;*/

    /*Update these two lines to change sidebar image.*/
    /*background:url(%%SidebarShowcase5%%) no-repeat center;*/
    /*background-size: 275px 150px;*/
}

/* Customize Search Bar */
#search input[type="text"] {
    font-size: 14px;
    width: 290px !important;
    padding: 2px 2px 2px 2px !important;
    border: 2px solid #aa6622 !important;
    -moz-border-radius-topleft: 10px;
    -webkit-border-top-left-radius: 10px;
    -moz-border-radius-topright: 10px;
    -webkit-border-top-right-radius: 10px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    -moz-border-radius-bottomleft: 10px;
    -webkit-border-bottom-left-radius: 10px;
    -moz-border-radius-bottomright: 10px;
    -webkit-border-bottom-right-radius: 10px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px
    }

/* Sidebox */
.sidecontentbox {
    /*  background: url(%%sidebottlesthing%%) repeat #ddd !important; */
    padding: 10px;
    border: 2px solid #aa6622 !important;
    border-radius: 10px;
    -moz-border-radius: 10px;
    -webkit-border-radius: 10px;
    color: white !important
    }
.sidecontentbox h1 {
    font-size: small;
    text-transform: none
    }
.sidecontentbox ul.content {
    /*background: url(http://c.thumbs.redditmedia.com/xAIb0gZY8ioBTavh.png) repeat #ddd !important; */
    border: 0
    }
.sidecontentbox ul.content li {
    /*background: url(http://c.thumbs.redditmedia.com/xAIb0gZY8ioBTavh.png) repeat #ddd !important; */
    font-size: small;
    margin-bottom: 2px
    }
.icon-menu a {
    background-color: transparent
    }
.titlebox {
    padding: 10px;
    border: 2px solid #aa6622;
    border-radius: 10px;
    -moz-border-radius: 10px;
    -webkit-border-radius: 10px
    }