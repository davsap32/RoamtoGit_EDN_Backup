- [[CSS theme]]
- ```css
@import url('https://abhayprasanna.github.io/kanban%20agenda/kanban-agenda.css');
h1,
h2,
h3,
h4,
h5,
h6 {
    font-family: "Lato", sans-serif;
    font-size: 3em;
}
/* this is the CSS block that affects the appearance of the caption  */
/* remove and see what happens
div,
textarea {
    font-weight: 400;
    color: #3F4758;
    font-size: 1.002em;
}
*/
/* this block affects the color of links */
a:link, a:visited {
  color: #E91E63;
  background-color: transparent;
  text-decoration: underline;
}

.roam-block-container {
    max-width: 1200px;
}

.rm-block-text {
    max-width: 1200px;
}

.rm-pomodoro {
    background: #fff !important;
    color: #ff4747 !important;
    padding: 4px 14px;
    line-height: 2em;
    font-weight: 600;
    border-radius: 2em;
    border: 1px solid #ff474770;
}

.rm-pomodoro {
    background: #ff6956 !important;
    color: #fff !important;
    padding: 4px 14px;
    line-height: 2em;
    font-weight: 600;
    border-radius: 2em;
    border: 1px solid #ed5845;
}

.rm-pomodoro::first-letter {
  margin-right: 8px;
}

.rm-query {
    border: 0.5px solid #e4e9ec;
    border-radius: 5px;
    
}

.rm-query .rm-query-title {
    background-color: #f7f8f8;
    padding: 0.8em;
    color: #d1dbe2;
    font-size: 80%;
}

.rm-reference-main.rm-query-content {
    padding: 0.8em;
}

.rm-reference-main .rm-reference-item .rm-block-text {
    font-size: 90%;
}

.rm-ref-page-view-title span {
    
}

.rm-reference-main .rm-reference-item .controls {
    margin-left: -1em;
}

.rm-ref-page-view {
    padding: 0.4em 0.2em;
}

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page {
    padding: 6px;
}

div.flex-v-box.starred-pages-wrapper > div.flex-h-box > span {
    font-size: 14px !important;
    opacity: 80%;
    letter-spacing: 0.04em;
}

div.roam-sidebar-container.noselect > div > div {
    font-size: 14px !important;
    letter-spacing: 0.03em;
    
}

#block-input {
    background: white;
}

.roam-body #block-input > span > div {
    padding: 6px 24px;
    background: white;
}

span.bp3-icon-small.bp3-icon-star {
    display: none;
    visibility: hidden;
}

.roam-block {
    max-width: 850px;
}

#right-sidebar > div {
    background-color: #f7f8fa;
    border-left: 1px solid #e9ebef;
}
/* control bullet point appearence */
.controls .simple-bullet-outer .simple-bullet-inner {
    background-color: #C8C8C9;
}
.block-border-left {
    border-left: 1px solid #f3f6f7;
}
.kanban-board {
    background-color: #fff;
}
.kanban-card {
    background-color: white;
    margin: 8px;
    box-shadow: 0px 1px 2px #9eb3c0a8;
    padding: 10px;
    border-radius: 2px;
    line-height: 1.3em;
}
.kanban-title {
    text-align: center;
    font-weight: 600;
    font-size: 1.1em;
    opacity: 80%;
    color: #485f6f;
    padding-top: 8px;
    border-bottom: 1px solid #c5d1d8;
}
.kanban-column {
    background-color: #e7eff3;
    margin: 0px 4px 0px 4px;
    padding: 4px;
    min-width: 200px;
    border-radius: 3px;
}


.rm-block-ref::before {
    content: '';
    display: inline-block;
    width: 2px;
    border-radius: 40px;
    height: 12px;
    background: #ff913c;
    margin-right: 8px;
}

.rm-block-ref {
    border-bottom: none;
    font-size: 1em;
    color: #515e70;
}
 .rm-block-ref:hover {
    background: none; 
    cursor: pointer;
} 

.checkmark {
    background: #fff;
}
.check-container input:checked ~ .checkmark {
    background: #33bdea;
}
.check-container input:checked ~ .checkmark:after {
    border-color: #fff;
}
.rm-reference-item {
    margin-top: 8px;
    border-radius: 6px;
    border: 1px solid #e4e9ee;
    margin-right: 8px;
    flex: 1 1 100%;
    word-break: break-word;
    background-color: #f7f9fb;
    padding: 8px;
}

.rm-level2 {
    font-size: 1.5em;
}
.rm-level3 {
    color: #939aae;
    font-weight: 400;
    font-size: 1.3em;
}
.rm-page-ref {
    color: #9aabd0;
}

/* Change the link color for references */ 

.rm-page-ref-link-color {
    color: #2980b9;
    font-weight: 600;
}

/* Change the link color in queries */

a {
    color: #8e44ad;
}
.intercom-app,
.intercom-launcher-frame,
#intercom-container {
    display: none !important;
}
.roam-body .roam-app .roam-sidebar-container {
    background-color: white;
    border-right: 1px #eee solid;
}
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page,
.roam-body .roam-app .roam-sidebar-container > * {
    opacity: 80%;
    box-shadow: none;
}
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page:hover,
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button:hover {
    background: white;
    color: black;
    opacity: 100%;
}
#buffer.tall {
    height: calc(100vh - 50px) !important;
}
.check-container {
    padding-right: 4px;
}
span.rm-page-ref {
    border-radius: 2px;
    padding-left: 1px;
    padding-right: 1px;
}
.content span.rm-page-ref {
    padding: 4px 1px 1px;
    /* required for fixing azo */
}
.center-proj {
    text-align: center;
}

/* Custom data tags */
span.rm-page-ref[data-tag="Tweets"] {
    background: #2980b9 !important;
    color: white !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Projects"] {
    background: #2980b9 !important;
    color: white !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}
span.rm-page-ref[data-tag="Capstone Project"] {
    background: #F4A460 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Business Future"] {
    background: #DAA520 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Storage and Backup"] {
    background: #B8860B !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Booklists"] {
    background: #CD853F !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Lightroom Cleanup"] {
    background: #D2691E !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Touch Typing"] {
    background: #8B4513 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
/* Tags for specific projects which begin with P: will be highlighted */
span.rm-page-ref[data-tag^="P:"] {
    background: #2980b9 !important;
    color: white !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}
span.rm-page-ref[data-tag="Areas"] {
    background: #795548 !important;
    color: white !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}
/* Tags for specific areas which begin with A: will be highlighted */
span.rm-page-ref[data-tag^="A:"] {
    background: #795548 !important;
    color: white !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Books"] {
    background: #8e44ad !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Digital Garden"] {
    background: #483D8B !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Sort and Tidy"] {
    background: #6A5ACD !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Work"] {
    background: #7B68EE !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Home Tech"] {
    background: #4B0082 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Home Improvement"] {
    background: #DA70D6 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Personal Finance"] {
    background: #800080 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Health"] {
    background: #8B008B !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Philosophy"] {
    background: #9932CC !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Creativity"] {
    background: #9400D3 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Photography"] {
    background: #8A2BE2 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Psychology"] {
    background: #9370DB !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Personal"] {
    background: #BA55D3 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="Productivity"] {
    background: #FF00FF !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="History"] {
    background: #EE82EE !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}
span.rm-page-ref[data-tag="People"] {
    background: #8e44ad !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}

span.rm-page-ref[data-tag="Ideas"] {
    background: #e67e22 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}

span.rm-page-ref[data-tag="Recipes"] {
    background: #e67e22 !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}

span.rm-page-ref[data-tag="Videos"] {
    background: #f1c40f !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}

span.rm-page-ref[data-tag="Articles"] {
    background: #27ae60;
    color: #fff;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Goals"] {
    background: #27ae60;
    color: #fff;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Podcasts"] {
    background: #7f8c8d;
    color: #fff;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Waiting"] {
    background: #f39c12;
    color: #fff;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Inbox"] {
    background: #e74c3c;
    color: #fff;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}
span.rm-page-ref[data-tag="Evergreens"] {
    background: #436F45;
    color: #fff;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}
/* Evergreens notes */
span.rm-page-ref[data-tag^="E:"] {
    background: #DD604A !important;
    color: #fff !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}#fff !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}!important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}#fff !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}```
