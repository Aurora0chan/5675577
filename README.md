@font-face {
    font-family: 'yekan';
    src: url('//cdn.bayan.ir/blog/templates/shared/fonts/BYekan.woff?download') format('woff');
    font-weight: normal;
    font-style: normal;
}
/*---body---*/
body {
	background: #eceff1;
	font-family: tahoma;
	font-size: 12px;
}
body a{
	text-decoration: none;
}
ul {
	list-style: none;
	margin: 0;
	padding: 0;
}
.clear {
	clear: both;
}
#wrp {
	width: 680px;
	margin: auto;
}
/*---header---*/
#header {
	background: #fff0b9;
	padding: 10px;
	text-align: center;
}
#header a{
	color: #8f6e51;
}
#header h1{
	font-weight: normal;
	font-family: yekan,tahoma;
	font-size: 16px;
	margin: 0;
}
#header h2{
	font-weight: normal;
	font-family: yekan,tahoma;
	font-size: 12px;
	margin: 0;
}
.header-image {
	margin: 10px 0px;
	text-align: center;
}
.header-img-back {
	display: inline-block;
	padding: 2px;
	border: 1px solid #e5e5e5;
}
.header-img-back img{
	width: 120px;
	height: 120px;
}
/*---block-post---*/
#block-post {
	width: 400px;
	float: right;
	background: #fff;
	box-shadow: 0px 0px 4px 2px #ededed;
	margin-top: 40px;
	padding: 10px;
}
/*---block-message---*/
.align {
	margin-bottom: 10px;
}
.messages {
	background: #fff;
	box-shadow: 0px 0px 4px 2px #ededed;
	padding: 1px 10px;
	text-align: center;
}
.messages h2{
	font-family: yekan,tahoma;
	font-weight: normal;
	font-size: 16px;
}
/*---post---*/
.post {
	margin-bottom: 20px;
}
.post img{
	max-width: 100%;
	height: inherit;
}
.post audio{
	max-width: 100%;
	height: inherit;
}
.post video{
	max-width: 100%;
	height: inherit;
}
.post-title {
	padding: 2px 10px;
	background: #fff0b9;
}
.post-title a{
	color: #8f6e51 !important;
}
.post-title a:hover{
	color: #755a43;
}
.post a{
	color: #f29340;
}
.post a:hover{
	color: #e17314;
}
.post-title h2{
	font-size: 12px;
	font-family: yekan,tahoma;
	font-weight: normal;
	margin: 0;
	padding: 0;
}
.post-content {
	line-height: 1.7;
	padding: 5px 10px 5px 10px;
	margin: 4px 0px;
    	border: 1px solid #e5e5e5;
}
.read-more {
	text-align: center;
	margin-bottom: 10px;
}
/*---post-detail---*/
.post-detail {
	border: 1px solid #e5e5e5;
	padding: 6px 6px;
}
.post-detail li{
	display: inline-block;
	padding: 0px;
}
.post-detail li:after {
	content: "|";
	color: #e5e5e5;
}
.post-detail li:last-child:after {
	content: "";
}
.post-detail-right {
	float: right;
}
.post-detail-right span{
	padding: 0px 2px;
	color: #999999;
}
.post-detail-left span {
	color: #999999;
}
.post-detail-left {
	float: left;
}
.post-detail-left a{
	color: #f29340;
}
.rate-box:hover .fa-heart-o:before {
	content:"\f004";
	transition-duration: .5s;
}
.rate-box.rated .fa-heart-o:before {
	content:"\f004";
	transition-duration: .5s;
}
.post-tags {
}
.post-tags a{
	color: #000;
}
.post-tags a:hover{
	color: #f29340;
}
.post-tags-title {
	background: #fff0b9;
	padding: 6px 10px;
	margin-bottom: 4px;
	border-radius: 2px;
	color: #7d7d7d;
}
/*----comment-----*/
.comment-count-box {
	text-align: center;
	margin-top: 10px;
	padding: 8px 0px;
	background: #fff;
	border: 1px solid #e5e5e5;
	font-family: yekan;
}
.comment-count-box a{
	color: #000;
	font-size: 20px;
}
.cm-body {
	background: #fff;
	border: 1px solid #e5e5e5;
	margin-right: 56px;
	padding-bottom: 1px;
}
.cm-main {
	margin-top: 10px;
}
.cm-avatar {
	float: right;
}
.cm-av {
	width: 50px;
	border-radius: 50%;
}
.comment-details {
	padding: 6px;
	background: #fff0b9;
	overflow: hidden;
	border-top-right-radius: 2px;
	border-top-left-radius: 2px;
}
.cm-name {
	margin-right: 5px;
	float: right;
	color: #636363;
}
.cm-name a{
	color: #a3a3a3;
}
.cm-name a:hover{
	color: #858585;
}
.comment-matn {
	padding: 10px;
	line-height: 1.7;
	overflow: hidden;
	color: #000;
}
.comment-link {
	width: 15px;
	height: 15px;
}
.cm-reply-main {
	overflow: hidden;
	padding: 0px 10px 10px 10px;
}
.comment-reply {
	margin-right: 40px;
	margin-left: auto;
	padding: 8px;
	border: 1px solid #e5e5e5;
	background: #fafafa;
	line-height: 1.7em;
	color: #000;
}
.comment-reply-page {
	padding: 8px;
	border: 1px solid #e5e5e5;
	background: #fafafa;
	line-height: 1.7em;
	color: #000;
	border-radius: 6px;
}
.reply-av {
	width: 35px;
	float: right;
	border-radius: 50%;
}
.comment-add-form {
	margin-top: 15px;
	margin-bottom: 15px;
	padding: 10px;
	background: #fff;
	color: #000;
	border: 1px solid #e5e5e5;
}
.bComForm .sendbutton.hasCheckbox:hover {
	background: #e0e0e0;
	transition-duration: .3s;
}
input[type=button], input[type=text], input[type=password], input[type=submit], button, textarea, select, .inputBox, input.text, a.btn, a.btn:hover, a.btn:visited {
	background-color: #f7f7f7;
	border: 1px solid #e5e5e5;
	color: #454545;
	border-radius: 0px;
}
.htmlbox {
	border: 1px solid #dedede !important;
	background: #fff;
}
.bComForm .sendbutton.hasCheckbox {
	background: #fafafa;
	border: 1px solid #e5e5e5;
	cursor: pointer;
	margin-top: 0;
	width: 100px;
	border-radius: 2px;
	color: #000;
}
.bComForm .sendbutton.hasCheckbox:hover {
	background: #f7f7f7;
	transition-duration: .3s;
}
/*--cm-detail-top--*/
.post-detail-top {
	padding: 2px 0px;
	background: #fafafa;
	border-bottom: 1px solid #ebebeb;
	color: #707070;
	cursor: default;
	font-size: 12px;
}
.post-detail-top a {
	color: #787878;
	cursor: default;
}
.post-detail-top ul{
	list-style: none;
	padding: 0;
	margin: 0;
}
.post-detail-top li{
	border-left: 1px solid #e0e0e0;
	display: inline-block;
	padding: 0px 5px;
}
.post-detail-top li:last-child {
	border-left: 0px;
}
/*---pagingation---*/
.pagingation {
	background: #fff;
	border: 1px solid #e5e5e5;
	text-align: center;
	padding: 4px 6px;
}
.pagesList {
	display: inline-block;
}
.pagingation li{
	display: inline-block;
}
.pagingation li:after{
	content: "|";
	color: #e5e5e5;
}
.pagingation li:last-child:after{
	content: "";
}
.pagingation a{
	padding: 0px 4px;
	color: #f29340;
}
.pagingation a:hover{

}
/*---block-left---*/
#block-left {
	width: 190px;
	float:left;
	line-height: 1.6em;
	color: #666;
	background: #fff;
	box-shadow: 0px 0px 4px 2px #ededed;
	padding: 10px;
	margin-top: 40px;
}
#block-left .left-box {
	background: #fff;
	margin-bottom: 10px;
	cursor: default;
}
#block-left .left-detail {
	margin: 4px 0px;
	border: 1px solid #e5e5e5;
}
#block-left .left-title {
	background: #fff0b9;
	padding: 4px 6px;
	font-family: yekan,tahoma;
	color: #8f6e51;
}
#block-left a{
	color: #000;
}
#block-left a:hover {
	color: #f29340;
}
#block-left .left-detail li{
	border-bottom: 1px solid #e5e5e5;
	padding: 4px 6px;
}
#block-left .left-detail li:last-child{
	border-bottom: 0px;
}
.left-detail li:hover {
	background: #fafafa;
}
.left-detail a{
	display: block;
}
/*---about-me---*/
.about-me {
	padding: 0px 10px 10px 10px;
	border: 1px solid #e5e5e5;
}
.blog-image {
	text-align: center;
}
.about-me img{
	width: 170px;
	margin-top: 10px;
}
.blog-description {
	padding-top: 10px;
}
/*---follow-box---*/
.followBx {
	margin-top: 10px;
	background: #fff;
	border-radius: 0px;
	border-top: 1px solid #e5e5e5;
}
.followThis.followed {
	background: #f29340;
}
.followThis {
	background: #f29340;
	border-radius: 0px;
	font-family: yekan,tahoma;
	font-size: 14px;
}
#followInBx #followersLs .followImg {
	border-radius: 50%;
}
/*---stat---*/
.left-stat {
	border: 1px solid #e5e5e5;
	margin: 4px 0px;
}
.left-stat li{
	padding: 4px 6px;
	border-bottom: 1px solid #e5e5e5;
}
.left-stat li:last-child{
	border-bottom: 0px;
}
.stat-value {
	float: left;
}
/*---category---*/
.left-category {
	border: 1px solid #e5e5e5;
	margin: 4px 0px;
}
.left-category li{
	padding: 4px 6px;
}
.count {
	color: #bdbdbd;
}
.left-category li a{
	padding-right: 12px;
	background-image: url(//bayanbox.ir/view/8661660237688751606/category-right.png);
	background-repeat: no-repeat;
	background-position: right center;
	display: inline-block;
}
.left-category .category-child a{
	padding-right: 12px;
	background-image: url(//bayanbox.ir/view/4955324527815090542/category-child-right.png);
	background-repeat: no-repeat;
	background-position: right center;
	display: inline-block;
}
/*---recent-comments---*/
.recent-cm-main {
	overflow: hidden;
}
.recent-cm-main img{
	width: 30px;
	float: right;
	border-radius: 50%;
	margin-top: 3px;
}
.recent-cm-detail {
	margin-right: 35px;
}
.recent-cm-name {
	color: #f29340;
}
.recent-cm-matn {
	color: #000;
}
/*---recent-post---*/
.left-detail a:hover{
	color: #666;
}
/*---tags---*/
.left-tag {
	padding: 4px 0px;
}
.tags a{
	border: 1px solid #e5e5e5;
	padding: 4px 6px;
	margin: 2px 0px;
	display: inline-block;
}
/*---footer---*/
.footer {
	padding: 6px 6px;
	margin: 10px 0px;
	background: #fff;
	box-shadow: 0px 0px 4px 2px #ededed;
}
.footer a{
	color: #f29340;
}
footer a:hover {
	color: #e87e21;
}
.erfan {
	float: left;
}
.bayan {
	float: right;
}8
