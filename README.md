
<!DOCTYPE html>
<html lang="tr">
<head>

    <title>Final Eğitim Kurumları | Online Bilgi Sistemi</title>
    <link rel="shortcut icon" href="images/favicon.ico">

    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <meta name="HandheldFriendly" content="true" />
    <meta name="author" content="Seçkin KUZOLUK">
    <meta name="version" content="v1.14.0">
    <meta name="copyright" content="AKBİM KOÇ YAZILIM">
    <meta name="description" content="final eğitim kurumları online bilgi sistemi">
    <meta name="keywords" content="final, final öbs, final obs, akbim obs, final, öbs, obs">
    <meta property="og:title" content="FİNAL EĞİTİM KURUMLARI">
    <meta property="og:image" content="images/og.png">
    <meta property="og:description" content="Bu yazılım dersaneler ve özel okullar için geliştirilmiş olan çok yönlü bir online bilgi sistemidir.">
    <meta name="apple-itunes-app" content="app-id=1350015884, app-argument=lync://join?url=/">
    <meta name="google-play-app" content="app-id=com.obsmobile">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">

    <link type="text/css" rel="stylesheet" class="theme" href="assets/css/theme-3/bootstrap.css" />
    <link type="text/css" rel="stylesheet" class="theme" href="assets/css/theme-3/materialadmin.css" />
    <link type="text/css" rel="stylesheet" class="theme" href="assets/css/theme-3/font-awesome.min.css" />
    <link type="text/css" rel="stylesheet" class="theme" href="assets/css/theme-3/material-design-iconic-font.min.css" />
    <link type="text/css" rel="stylesheet" class="theme" href="assets/css/theme-3/libs/ytload/ytLoad.jquery.css" />
    <link type="text/css" rel="stylesheet" class="theme" href="assets/css/theme-3/libs/fullcalendar/fullcalendar.css" />
    <link type="text/css" rel="stylesheet" href="assets/js/libs/toastr/toastr.min.css"/>
    <link type="text/css" rel="stylesheet" href="assets/css/other/xloader.css" />
    <link type="text/css" rel="stylesheet" href="assets/css/other/notification.css" />
    <link type="text/css" rel="stylesheet" href="assets/css/other/style.css?v1" />
    <link type="text/css" rel="stylesheet" href="assets/js/libs/jquery-ui/jquery-ui-theme.css" />
    <link type="text/css" rel="stylesheet" href="assets/js/libs/nestable/jquery.nestable.min.css" />

    <link href="/assets/js/other/FileAttachment/style.css" rel="stylesheet" type="text/css">
    <!--[if lt IE 9]>
    <script type="text/javascript" src="assets/js/libs/utils/html5shiv.js"></script>
    <script type="text/javascript" src="assets/js/libs/utils/respond.min.js"></script>
    <![endif]-->
    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css" rel="stylesheet">
</head>
<body class="menubar-hoverable header-fixed menubar-pin menubar-first" theme-name="theme-3">
    <header id="header" class=" display-none">
        <div class="headerbar" apptitle="">
            <div class="headerbar-left">
                <ul class="header-nav header-nav-options">
                    <li>
                        <a class="btn btn-icon-toggle menubar-toggle" data-toggle="menubar" href="javascript:void(0);">
                            <i class="fa fa-bars"></i>
                        </a>
                    </li>
                </ul>
            </div>
            <div id="head"></div>
        </div>
    </header>
    <div class="offcanvas"></div>
    <div id="base" style="padding-left: 0 !important;">
        <div id="content" style="padding-top: 0 !important;">
            <section style="padding: 0 !important;">
                <div class="section-body" style="margin-top: 0 !important;">
                    <div id="main">
                        <div id="pageLoader"><div id="xLoader"><div class="google-spin-wrapper"><div class="google-spin"></div></div></div></div>
                        <div id="page" style="display: none;"></div>
                    </div>
                </div>
            </section>
        </div>
        <div id="menubar" class="menubar-inverse display-none">
            <div class="menubar-fixed-panel">
                <div>
                    <a class="btn btn-icon-toggle btn-default menubar-toggle" data-toggle="menubar" href="javascript:void(0);">
                        <i class="fa fa-bars"></i>
                    </a>
                </div>
            </div>
            <div class="menubar-scroll-opacity"></div>
            <div class="menubar-scroll-panel">
                <ul class="gui-controls" style="margin: 0px;">
                    <li id="searchContainer">
                        <a>
                            <div class="gui-icon" style="top: 4px;"><i class="fa fa-search" aria-hidden="true"
                                                                       id="menu-search-icon"></i></div>
                            <span class="title" style="margin-left: 50px;"><input type="text" id="searchMenu"
                                                                                  placeholder="Menüde ara"></span>
                        </a>
                    </li>
                    <div id="search-menu-list">
                    </div>
                </ul>
                <ul id="main-menu" class="gui-controls" style="margin-bottom: 10px;"></ul>
                <div class="menubar-foot-panel" style="position:relative; padding: 10px 16px;" id="menubar-foot">
                    <small class="no-linebreak hidden-folded" style="text-align: center;">
                        <span class="opacity-75">Copyright &copy; 2015 - 2025</span><br />
                        <a target="_blank" href="http://www.akbimkoc.com/"><img src="images/owner.png" title="AKBİM KOÇ YAZILIM"><strong>&nbsp;AKBİM KOÇ YAZILIM</strong></a><br />
                        <span>Tel: (232) 463 2135</span><br />
                        <a href="https://tr-tr.facebook.com/Akbim-Ko%C3%A7-Bilgisayar-104400036400/" target="_blank" style="color: transparent;">
                            <img src="images/facebook-16.png" width="16" height="16" alt="Facebook" style="margin: 4px;" />
                        </a>
                        <a href="https://twitter.com/akbimkoc" target="_blank" style="color: transparent;">
                            <img src="images/twitter-16.png" width="16" height="16" alt="Twitter" style="margin: 4px;" />
                        </a>
                        <a href="#" target="_blank" style="color: transparent; display: none;">
                            <img src="images/instagram-16.png" width="16" height="16" alt="Instagram" style="margin: 4px;" />
                        </a>
                        <a href="https://www.youtube.com/channel/UCYNZB8hFQQvljl6EL3UImaQ" target="_blank" style="color: transparent;">
                            <img src="images/youtube-16.png" width="16" height="16" alt="Youtube" style="margin: 4px;" />
                        </a>
                    </small>
                </div>
            </div>
        </div>
    </div>
    <div class="mobile-app-notification display-none">
        <div class="close-button">
            <i class="md md-close"></i>
        </div>
        <a href="https://play.google.com/store/apps/details?id=com.obsmobile" target="_blank">
            <img src="images/get-it-on-play-store.png">
        </a>
        <a href="https://itunes.apple.com/RO/app/id1350015884?mt=8" target="_blank">
            <img src="images/download-on-the-app-store.png">
        </a>
    </div>

    <script src="assets/js/libs/jquery/jquery-1.11.2.min.js"></script>
    <script type="text/javascript">
$(document).ready(function(){function n(){var n=$("body").attr("theme-name"),t=["assets/css/{theme-name}/libs/DataTables/jquery.dataTables.css","assets/css/{theme-name}/libs/DataTables/extensions/dataTables.tableTools.css","assets/css/{theme-name}/libs/DataTables/extensions/dataTables.colVis.css","assets/css/{theme-name}/libs/multi-select/multi-select.css","assets/css/{theme-name}/libs/summernote/summernote.css","assets/css/{theme-name}/libs/bootstrap-tagsinput/bootstrap-tagsinput.css","assets/css/{theme-name}/libs/typeahead/jquery.typeahead.min.css","assets/css/{theme-name}/libs/select2/select2.css","assets/css/{theme-name}/libs/bootstrap-datepicker/datepicker3.css","assets/js/libs/DataTables/extensions/FixedColumns/css/dataTables.fixedColumns.min.css","assets/js/libs/DataTables/extensions/RowReorder/css/rowReorder.dataTables.min.css","assets/js/libs/DataTables/extensions/FixedHeader/css/dataTables.fixedHeader.min.css","assets/js/libs/DataTables/extensions/Responsive/css/responsive.dataTables.min.css","assets/js/libs/fancytree/ui.fancytree.css","assets/css/other/secoscheduler.css"];setTimeout(function(){$.each(t,function(t,i){$("<link/>",{rel:"stylesheet",type:"text/css",href:i.replace("{theme-name}",n)}).appendTo("head")})},500)}$("#customerLogo").load(function(){$(this).css("display",this.width<=250?"inline-block":"none");$("span#customerText").css("display","inline-block")}).attr("src","images/customer.png");navigator.userAgent.match(/Android/i)&&$(".mobile-app-notification").removeClass("display-none");$(".mobile-app-notification .close-button").click(function(){$(".mobile-app-notification").addClass("display-none")});n();CreateRouter({title:$(".headerbar").attr("apptitle"),container:"#page",fadeOutDuration:200,fadeInDuration:300,errorPages:{"404":"pages/common/error/404.html","500":"pages/common/error/500.html",all:"pages/common/error/500.html"},onInit:function(){loadMenus();$.ytLoad({registerAjaxHandlers:!1});Router.onBeforePageLoad.push(function(n){$(".tooltip, .popover, table.fixedHeader-floating, #device-breakpoints, [class^=select2], .tooltip").remove();$("#main-menu li, #main-menu a").removeClass("active");!$('#main-menu a[goto*="'+n.page+'"]').parents(".gui-folder.expanded").length>0&&$("#main-menu li, #main-menu a").removeClass("expanded")});Router.onAfterPageLoad.push(function(n){$("#main-menu li, #main-menu a").removeClass("expanded");$('#main-menu a[goto*="'+n.page+'"]').addClass("active");$("#pageLoader").css("display","none");$("[data-toggle='dropdown'], [data-toggle='menubar']").off();refreshMaterialEvents();typeof globRepDt!="undefined"&&delete globRepDt;window.innerWidth<=768&&n.page.substr(-9)!=="index.php"?materialadmin.AppNavigation._handleMenuToggleClick():window.innerWidth>768;materialadmin.App.initialize();materialadmin.AppCard.initialize();materialadmin.AppForm.initialize();materialadmin.AppVendor.initialize()});Router.onNavigationError.push(function(n){$('#main-menu a[goto="'+n.page+'"]').addClass("active");$("#pageLoader").css("display","none");$("[data-toggle='dropdown'], [data-toggle='menubar']").off();refreshMaterialEvents();typeof globRepDt!="undefined"&&delete globRepDt});Router.onAjaxProgress.push(function(n){$.ytLoad&&$.ytLoad("progress",n,100)});Router.onTitleChange=function(n,t){return Router.title.length>0?Router.title+" | "+t:document.title};$("body").on("click","[goto]",handleLinkClick).on("click",".logout-trigger",logoutApp)}});$("#menubar").on("input","#searchMenu",function(){if($("#search-menu-list").css("display")==="none"&&$("#search-menu-list").css("display","block"),$("#searchMenu").val().length>1){for(menuList=menuArr.filter(function(n,t){return t.search.toLocaleLowerCase("TR-tr").includes($("#searchMenu").val().toLocaleLowerCase("TR-tr"))}),menuListHtml="",i=0;i<menuList.length;i++)menuListHtml+='<a goto="'+menuList[i].link+'" goto-title="'+menuList[i].title+'">'+menuList[i].title+"<\/a>";menuList.length>0?($("#search-menu-list").html(menuListHtml),index=1,$("#search-menu-list a:nth-child(1)").addClass("active")):$("#search-menu-list").html("<a>Aradığınız menü bulunamadı<\/a>");$("#main-menu").css("display","none");$("#menubar-foot").css("display","none");$("#menu-search-icon").removeClass("fa-search");$("#menu-search-icon").addClass("fa-times")}else $("#searchMenu").val().length<=1&&($("#search-menu-list").html(""),$("#main-menu").css("display","block"),$("#menubar-foot").css("display","block"),$("#menu-search-icon").addClass("fa-search"),$("#menu-search-icon").removeClass("fa-times"))}).on("click","#search-menu-list",function(){menuList.length>0?($("#search-menu-list").css("display","none"),$("#searchMenu").val(""),$("#main-menu").css("display","block"),$("#menubar-foot").css("display","block"),$("#menu-search-icon").addClass("fa-search"),$("#menu-search-icon").removeClass("fa-times")):$("#search-menu-list").html("<a>Aradığınız menü bulunamadı<\/a>")}).on("click","#menu-search-icon",function(){$("#search-menu-list").css("display","none");$("#searchMenu").val("");$("#main-menu").css("display","block");$("#menubar-foot").css("display","block");$("#menu-search-icon").addClass("fa-search");$("#menu-search-icon").removeClass("fa-times")}).on("keydown","#searchMenu",function(n){switch(n.which){case 38:$("#search-menu-list a:nth-child("+index+")").removeClass("active");index>1&&(index-=1);$("#search-menu-list a:nth-child("+index+")").addClass("active");break;case 40:$("#search-menu-list a:nth-child("+index+")").removeClass("active");index<menuList.length&&(index+=1);$("#search-menu-list a:nth-child("+index+")").addClass("active");break;case 13:var t=$("#search-menu-list a:nth-child("+index+")").attr("goto"),i=$("#search-menu-list a:nth-child("+index+")").attr("goto-title");typeof t!="undefined"&&typeof i!="undefined"&&Router.gotoLink(t,i);break;case 27:$("#search-menu-list").css("display","none");$("#searchMenu").val("");$("#main-menu").css("display","block");$("#menubar-foot").css("display","block");$("#menu-search-icon").addClass("fa-search");$("#menu-search-icon").removeClass("fa-times");break;default:return}n.preventDefault()});Router.onEveryPageLeave.push(function(){$("#search-menu-list").css("display","none");$("#searchMenu").val("");$("#main-menu").css("display","block");$("#menubar-foot").css("display","block");$("#menu-search-icon").addClass("fa-search");$("#menu-search-icon").removeClass("fa-times")})})
</script>
    <script src="assets/js/libs/jquery/jquery-migrate-1.2.1.min.js"></script>
    <script src="assets/js/libs/jquery/jquery-ui.min.js"></script>
    <script src="assets/js/libs/ytload/jquery.transit.js"></script>
    <script src="assets/js/libs/ytload/ytLoad.jquery.js"></script>
    <script src="assets/js/libs/bootstrap/bootstrap.min.js"></script>
    <script src="assets/js/libs/historyjs/jquery.history.js"></script>
    <script src="assets/js/other/fn.js?v4"></script>
    <script src="assets/js/other/router.js"></script>
    <script src="assets/js/libs/spin.js/spin.min.js"></script>
    <script src="assets/js/libs/ECharts/echarts.min.js"></script>
    <script src="https://www.google.com/jsapi"></script>
    <script src="assets/js/libs/moment/moment-with-langs.min.js"></script>
    <script src="assets/js/libs/fullcalendar/fullcalendar.min.js"></script>
    <script src="assets/js/libs/fullcalendar/lang/tr.js"></script>
    <script src="assets/js/libs/inputmask/jquery.inputmask.bundle.min.js"></script>
    <script src="assets/js/other/settings.js"></script>
    <script src="assets/js/libs/toastr/toastr.min.js"></script>
    <script src="assets/js/libs/select2/select2.min.js"></script>
    <script src="assets/js/libs/nanoscroller/jquery.nanoscroller.min.js"></script>
    <script src="assets/js/libs/fancytree/jquery.fancytree.js"></script>
    <script src="assets/js/libs/fancytree/jquery.fancytree.filter.js"></script>
    <script src="assets/js/libs/fancytree/jquery.fancytree.table.js"></script>
    <script src="assets/js/libs/fancytree/jquery.fancytree.gridnav.js"></script>
    <script src="assets/js/libs/jquery-validation/dist/jquery.validate.min.js"></script>
    <script src="assets/js/libs/jquery-validation/dist/additional-methods.min.js"></script>
    <script src="assets/js/libs/jquery-validation/dist/localization/messages_tr.min.js"></script>
    <script src="assets/js/libs/maskedinput/jquery.maskedinput.min.js"></script>
    <script src="assets/js/other/modalstrap.js?v2"></script>
    <script src="assets/js/libs/autosize/jquery.autosize.min.js"></script>
    <script src="assets/js/other/secopoller.js"></script>
    <script src="assets/js/libs/DataTables/jquery.dataTables.min.js"></script>
    <script src="assets/js/libs/DataTables/extensions/Responsive/js/dataTables.responsive.min.js"></script>
    <script src="assets/js/libs/DataTables/extensions/ColVis/js/dataTables.colVis.min.js"></script>
    <script src="assets/js/libs/DataTables/extensions/FixedColumns/js/dataTables.fixedColumns.min.js"></script>
    <script src="assets/js/libs/DataTables/extensions/FixedHeader/js/dataTables.fixedHeader.min.js"></script>
    <script src="assets/js/libs/DataTables/extensions/TableTools/js/dataTables.tableTools.min.js"></script>
    <script src="assets/js/libs/DataTables/plugins/fnDisplayRow.js"></script>
    <script src="assets/js/libs/DataTables/plugins/select.js"></script>
    <script src="assets/js/libs/nestable/jquery.nestable.min.js"></script>
    <script src="assets/js/other/jquery.eSchedule.js"></script>
    <script src="/assets/js/other/FileAttachment/index.js"></script>
    <script src="assets/js/other/vue.min.js"></script>
    <script src="dist/timeline.umd.min.js"></script>
    <script>
$(document).ready(function(){$.ajaxSetup({cache:!0});dataTableSetup();$(window).scroll(function(){var n=$(window).scrollTop();n>30?$("#header").addClass("scrolled"):$("#header").removeClass("scrolled")})})
</script>
</body>
</html>
