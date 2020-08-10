# 

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">

<html lang="en">
<head>
    <title>North Kansas City Schools / Homepage</title>
    <!--
    <PageMap>
    <DataObject type="document">
    <Attribute name="siteid">4</Attribute>
    </DataObject>
    </PageMap>
    -->

    
    <meta name="description" content="Homepage for the North Kansas City School District website." />
<meta name="keywords" content="Homepage" />
<meta property="og:type" content="website" />
<meta property="fb:app_id" content="411584262324304" />
<meta property="og:url" content="http%3A%2F%2Fwww.nkcschools.org%2Fsite%2Fdefault.aspx%3FDomainID%3D4" />
<meta property="og:title" content="North Kansas City Schools / Homepage" />
<meta property="og:description" content="Homepage for the North Kansas City School District website." />
<meta name="twitter:card" value="summary" />
<meta name="twitter:title" content="North Kansas City Schools / Homepage" />
<meta name="twitter:description" content="Homepage for the North Kansas City School District website." />
<meta itemprop="name" content="North Kansas City Schools / Homepage" />
<meta itemprop="description" content="Homepage for the North Kansas City School District website." />

    <!-- Begin swuc.GlobalJS -->
<script type="text/javascript">
 staticURL = "https://www.nkcschools.org/Static/";
 SessionTimeout = "60";
 BBHelpURL = "";
</script>
<!-- End swuc.GlobalJS -->

    <script src='https://www.nkcschools.org/Static/GlobalAssets/Scripts/min/sri-failover.min.js' type='text/javascript'></script>

    <!-- Stylesheets -->
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static/GlobalAssets/webfonts/OpenSans-Light.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static/GlobalAssets/webfonts/OpenSans-Italic.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static/GlobalAssets/webfonts/OpenSans-Regular.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static/GlobalAssets/webfonts/OpenSans-SemiBold.css" />
    <link rel="Stylesheet" type="text/css" href="../Static/GlobalAssets/Scripts/ThirdParty/shepherd/shepherd-theme-default.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static/App_Themes/SW/jquery.jgrowl.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static//site/assets/styles/system_2320.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static//site/assets/styles/apps.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static/App_Themes/SW/jQueryUI.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static/GlobalAssets/webfonts/SchoolwiresMobile_2320.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static//site/assets/styles/dashboard.css" />
    <link rel="Stylesheet" type="text/css" href="https://www.nkcschools.org/Static/GlobalAssets/Styles/Grid.css" />

    <!-- Scripts -->
    <script src="https://www.nkcschools.org/Static/GlobalAssets/WCM-2410/WCM.js" type="text/javascript"></script>
    <script src="https://www.nkcschools.org/Static/GlobalAssets/WCM-2410/API.js" type="text/javascript"></script>

    <script src='https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js' type='text/javascript' 
        integrity='sha384-EaUkI/FiMJtEXWAl0dCczvbFvjfzsIF1UNKGJvu9p5JIG71Kih7/kQJvYbBL7HOn' crossorigin='anonymous'
        data-sri-failover='https://www.nkcschools.org/Static/GlobalAssets/Scripts/min/jquery-1.9.1.min.js'></script>
    <script src='https://www.nkcschools.org/Static/GlobalAssets/Scripts/min/jquery-migrate-1.2.1.js' type='text/javascript'></script>
    <script src='https://ajax.googleapis.com/ajax/libs/swfobject/2.2/swfobject.js' type='text/javascript'
        integrity='sha384-JO4qIitDJfdsiD2P0i3fG6TmhkLKkiTfL4oVLkVFhGs5frz71Reviytvya4wIdDW' crossorigin='anonymous'
        data-sri-failover='https://www.nkcschools.org/Static/GlobalAssets/Scripts/min/swfobject.js'></script>
    <script src='../Static/GlobalAssets/Scripts/ThirdParty/tether/tether.min.js' type='text/javascript'></script>
    <script src='../Static/GlobalAssets/Scripts/ThirdParty/shepherd/shepherd.min.js' type='text/javascript'></script>
   
    <script type="text/javascript">
        $(document).ready(function () {
            SetCookie('SWScreenWidth', screen.width);
            SetCookie('SWClientWidth', document.body.clientWidth);
            
            $("div.ui-article:last").addClass("last-article");
            $("div.region .app:last").addClass("last-app");

            // get on screen alerts
            var isAnyActiveOSA = 'False';
            var onscreenAlertCookie = GetCookie('Alerts');

            if (onscreenAlertCookie == '' || onscreenAlertCookie == undefined) {
                onscreenAlertCookie = "";
            }
            if (isAnyActiveOSA == 'True') {
                GetContent(homeURL + "/cms/Tools/OnScreenAlerts/UserControls/OnScreenAlertDialogListWrapper.aspx?OnScreenAlertCookie=" + onscreenAlertCookie + "&SiteID=4", "onscreenalert-holder", 2, "OnScreenAlertCheckListItem();");
            }

            

        });

    // ADA SKIP NAV
    $(document).ready(function () {
        $(document).on('focus', '#skipLink', function () {
            $("div.sw-skipnav-outerbar").animate({
                marginTop: "0px"
            }, 500);
        });

        $(document).on('blur', '#skipLink', function () {
            $("div.sw-skipnav-outerbar").animate({
                marginTop: "-30px"
            }, 500);
        });
    });

    // ADA MYSTART
    $(document).ready(function () {
        var top_level_nav = $('.sw-mystart-nav');

        // Set tabIndex to -1 so that top_level_links can't receive focus until menu is open
        // school dropdown
        $(top_level_nav).find('ul').find('a').attr('tabIndex', -1);

        // my account dropdown
        $(top_level_nav).next('ul').find('a').attr('tabIndex', -1);

        var openNavCallback = function(e, element) {
             // hide open menus
            hideMyStartBarMenu();

            // show school dropdown
            if ($(element).find('ul').length > 0) {
                $(element).find('.sw-dropdown').css('display', 'block').attr('aria-hidden', 'false');
                $(element).find('.sw-dropdown').find('li:first-child a').focus()
            }

            // show my account dropdown
            if ($(element).next('ul').length > 0) {
                $(element).next('.sw-dropdown').css('display', 'block').attr('aria-hidden', 'false');
                $(element).next('.sw-dropdown').find('li:first-child a').focus();
                $('#sw-mystart-account').addClass("clicked-state");
            }
        }

        $(top_level_nav).click(function (e) {
            openNavCallback(e, this);
        });

        $('.sw-dropdown-list li').click(function(e) {
            e.stopImmediatePropagation();
            $(this).focus();
        });
        
        // Bind arrow keys for navigation
        $(top_level_nav).keydown(function (e) {
            if (e.keyCode == 37) { //key left
                e.preventDefault();

                // This is the first item
                if ($(this).prev('.sw-mystart-nav').length == 0) {
                    $(this).parents('div').find('.sw-mystart-nav').last().focus();
                } else {
                    $(this).prev('.sw-mystart-nav').focus();
                }
            } else if (e.keyCode == 38) { //key up
                e.preventDefault();

                // show school dropdown
                if ($(this).find('ul').length > 0) {
                    $(this).find('div.sw-dropdown').css('display', 'block').find('ul').attr('aria-hidden', 'false').find('a').attr('tabIndex', 0).last().focus();
                }

                // show my account dropdown
                if ($(this).find('ul').length > 0) {
                    $(this).find('ul.sw-dropdown').css('display', 'block').attr('aria-hidden', 'false').find('a').attr('tabIndex', 0).last().focus();
                }
            } else if (e.keyCode == 39) { //key right
                e.preventDefault();

                // This is the last item
                if ($(this).next('.sw-mystart-nav').length == 0) {
                    $(this).parents('div').find('.sw-mystart-nav').first().focus();
                } else {
                    $(this).next('.sw-mystart-nav').focus();
                }
            } else if (e.keyCode == 40) { //key down
                e.preventDefault();

                // show school dropdown
                if ($(this).find('ul').length > 0) {
                    $(this).find('div.sw-dropdown').css('display', 'block').find('ul').attr('aria-hidden', 'false').find('a').attr('tabIndex', 0).first().focus();
                }

                // show my account dropdown
                if ($(this).next('ul').length > 0) {
                    $(this).next('ul.sw-dropdown').css('display', 'block').attr('aria-hidden', 'false').find('a').attr('tabIndex', 0).first().focus();
                }
            } else if (e.keyCode == 13 || e.keyCode == 32) { //enter key
                // If submenu is hidden, open it
                e.preventDefault();

                
                openNavCallback(e, this);
                $(this).parent('li').find('ul[aria-hidden=true]').attr('aria-hidden', 'false').find('a').attr('tabIndex', 0).first().focus();
            } else if (e.keyCode == 27) { //escape key
                e.preventDefault();
                hideMyStartBarMenu();
            } else {
                $(this).parent('.sw-mystart-nav').find('ul[aria-hidden=false] a').each(function () {
                    if (typeof keyCodeMap != "undefined" && $(this).text().substring(0, 1).toLowerCase() == keyCodeMap[e.keyCode]) {
                        $(this).focus();
                        return false;
                    }
                });
            }
        });

        // school dropdown
        var startbarlinks = $(top_level_nav).find('ul').find('a');
        bindMyStartBarLinks(startbarlinks);

        // my account dropdown
        var myaccountlinks = $(top_level_nav).next('ul').find('a');
        bindMyStartBarLinks(myaccountlinks);

        function bindMyStartBarLinks(links) {
            $(links).keydown(function (e) {
                e.stopPropagation();

                if (e.keyCode == 38) { //key up
                    e.preventDefault();

                    // This is the first item
                    if ($(this).parent('li').prev('li').length == 0) {
                        if ($(this).parents('ul').parents('.sw-mystart-nav').length > 0) {
                            $(this).parents('ul').parents('.sw-mystart-nav').focus();
                        } else {
                            $(this).parents('ul').prev('.sw-mystart-nav').focus();
                        }
                    } else {
                        $(this).parent('li').prev('li').find('a').first().focus();
                    }
                } else if (e.keyCode == 40) { //key down
                    e.preventDefault();

                    if ($(this).parent('li').next('li').length == 0) {
                        if ($(this).parents('ul').parents('.sw-mystart-nav').length > 0) {
                            $(this).parents('ul').parents('.sw-mystart-nav').focus();
                        } else {
                            $(this).parents('ul').prev('.sw-mystart-nav').focus();
                        }
                    } else {
                        $(this).parent('li').next('li').find('a').first().attr('tabIndex', 0);
                        $(this).parent('li').next('li').find('a').first().focus();
                    }
                } else if (e.keyCode == 27 || e.keyCode == 37) { // escape key or key left
                    e.preventDefault();
                    hideMyStartBarMenu();
                } else if (e.keyCode == 32) { //enter key
                    e.preventDefault();
                    window.location = $(this).attr('href');
                } else {
                    var found = false;

                    $(this).parent('div').nextAll('li').find('a').each(function () {
                        if (typeof keyCodeMap != "undefined" && $(this).text().substring(0, 1).toLowerCase() == keyCodeMap[e.keyCode]) {
                            $(this).focus();
                            found = true;
                            return false;
                        }
                    });

                    if (!found) {
                        $(this).parent('div').prevAll('li').find('a').each(function () {
                            if (typeof keyCodeMap != "undefined" && $(this).text().substring(0, 1).toLowerCase() == keyCodeMap[e.keyCode]) {
                                $(this).focus();
                                return false;
                            }
                        });
                    }
                }
            });
        }
        
        // Hide menu if click or focus occurs outside of navigation
        $('#sw-mystart-inner').find('.sw-mystart-nav').last().keydown(function (e) {
            if (e.keyCode == 9) {
                // If the user tabs out of the navigation hide all menus
                hideMyStartBarMenu();
            }
        });

        /*$(document).click(function() { 
            hideMyStartBarMenu();
        });*/

        // try to capture as many custom MyStart bars as possible
        $('.sw-mystart-button').find('a').focus(function () {
            hideMyStartBarMenu();
        });

        $('#sw-mystart-inner').click(function (e) {
            e.stopPropagation();
        });

        $('ul.sw-dropdown-list').blur(function () {
            hideMyStartBarMenu();
        });

        $('#ui-btn-mypasskey').focus(function () {
            hideMyStartBarMenu();
        });

        $('#ui-btn-sitemanager').focus(function () {
            hideMyStartBarMenu();
        });

        $('#ui-btn-myview').focus(function () {
            hideMyStartBarMenu();
        });

        $('#ui-btn-signin').focus(function () {
            hideMyStartBarMenu();
        });

        $('#ui-btn-register').focus(function () {
            hideMyStartBarMenu();
        });

        // button click events
        $('div.sw-mystart-button.home a').keydown(function (e) {
            e.stopImmediatePropagation();

            if (e.keyCode == 13) {
                $(this).click();
            }
        });

        $('div.sw-mystart-button.pw a').keydown(function (e) {
            e.stopImmediatePropagation();

            if (e.keyCode == 13) {
                $(this).click();
            }
        });

        $('div.sw-mystart-button.manage a').keydown(function (e) {
            e.stopImmediatePropagation();

            if (e.keyCode == 13) {
                $(this).click();
            }
        });

        $('#sw-mystart-account').keydown(function (e) {
            e.stopImmediatePropagation();

            if (e.keyCode == 13) {
                $(this).addClass('clicked-state');
                $('#sw-myaccount-list').show();
            }
        });

        $('#sw-mystart-mypasskey a').keydown(function (e) {
            e.stopImmediatePropagation();

            if (e.keyCode == 13) {
                $(this).click();
            }
        });

        $('div.sw-mystart-button.signin a').keydown(function (e) {
            e.stopImmediatePropagation();

            if (e.keyCode == 13) {
                $(this).click();
            }
        });

        $('div.sw-mystart-button.register a').keydown(function (e) {
            e.stopImmediatePropagation();

            if (e.keyCode == 13) {
                $(this).click();
            }
        });
    });

    function hideMyStartBarMenu() {
        $('.sw-dropdown').attr('aria-hidden', 'true').css('display', 'none');
        $('#sw-mystart-account').removeClass("clicked-state");
    }

    // ADA CHANNEL NAV
    $(document).ready(function() {
        var channelCount;
        var channelIndex = 1;
        var settings = {
            menuHoverClass: 'hover'
        };

        // Add ARIA roles to menubar and menu items
        $('[id="channel-navigation"]').attr('role', 'menubar').find('li a').attr('role', 'menuitem').attr('tabindex', '0');

        var top_level_links = $('[id="channel-navigation"]').find('> li > a');
        channelCount = $(top_level_links).length;


        $(top_level_links).each(function() {
            $(this).attr('aria-posinset', channelIndex).attr('aria-setsize', channelCount);
            $(this).next('ul').attr({ 'aria-hidden': 'true', 'role': 'menu' });

            if ($(this).parent('li.sw-channel-item').children('ul').length > 0) {
                $(this).attr('aria-haspopup', 'true');
            }

            var sectionCount = $(this).next('ul').find('a').length;
            var sectionIndex = 1;
            $(this).next('ul').find('a').each(function() {
                $(this).attr('tabIndex', -1).attr('aria-posinset', sectionIndex).attr('aria-setsize', sectionCount);
                sectionIndex++;
            });
            channelIndex++;

        });

        $(top_level_links).focus(function () {
            //hide open menus
            hideChannelMenu();

            if ($(this).parent('li').find('ul').length > 0) {
                $(this).parent('li').addClass(settings.menuHoverClass).find('ul').attr('aria-hidden', 'false').css('display', 'block');
            }
        });

        // Bind arrow keys for navigation
        $(top_level_links).keydown(function (e) {
            if (e.keyCode == 37) { //key left
                e.preventDefault();

                // This is the first item
                if ($(this).parent('li').prev('li').length == 0) {
                    $(this).parents('ul').find('> li').last().find('a').first().focus();
                } else {
                    $(this).parent('li').prev('li').find('a').first().focus();
                }
            } else if (e.keyCode == 38) { //key up
                e.preventDefault();

                if ($(this).parent('li').find('ul').length > 0) {
                    $(this).parent('li').addClass(settings.menuHoverClass).find('ul').css('display', 'block').attr('aria-hidden', 'false').find('a').attr('tabIndex', 0).last().focus();
                }
            } else if (e.keyCode == 39) { //key right
                e.preventDefault();

                // This is the last item
                if ($(this).parent('li').next('li').length == 0) {
                    $(this).parents('ul').find('> li').first().find('a').first().focus();
                } else {
                    $(this).parent('li').next('li').find('a').first().focus();
                }
            } else if (e.keyCode == 40) { //key down
                e.preventDefault();

                if ($(this).parent('li').find('ul').length > 0) {
                    $(this).parent('li')
                         .addClass(settings.menuHoverClass)
                         .find('ul.sw-channel-dropdown').css('display', 'block')
                         .attr('aria-hidden', 'false')
                         .find('a').attr('tabIndex', 0)
                         .first().focus();
                }
            } else if (e.keyCode == 13 || e.keyCode == 32) { //enter key
                // If submenu is hidden, open it
                e.preventDefault();

                $(this).parent('li').find('ul[aria-hidden=true]').attr('aria-hidden', 'false').addClass(settings.menuHoverClass).find('a').attr('tabIndex', 0).first().focus();
            } else if (e.keyCode == 27) { //escape key
                e.preventDefault();
                hideChannelMenu();
            } else {
                $(this).parent('li').find('ul[aria-hidden=false] a').each(function () {
                    if (typeof keyCodeMap != "undefined" && $(this).text().substring(0, 1).toLowerCase() == keyCodeMap[e.keyCode]) {
                        $(this).focus();
                        return false;
                    }
                });
            }
        });

        var links = $(top_level_links).parent('li').find('ul').find('a');

        $(links).keydown(function (e) {
            if (e.keyCode == 38) {
                e.preventDefault();

                // This is the first item
                if ($(this).parent('li').prev('li').length == 0) {
                    $(this).parents('ul').parents('li').find('a').first().focus();
                } else {
                    $(this).parent('li').prev('li').find('a').first().focus();
                }
            } else if (e.keyCode == 40) {
                e.preventDefault();

                if ($(this).parent('li').next('li').length == 0) {
                    $(this).parents('ul').parents('li').find('a').first().focus();
                } else {
                    $(this).parent('li').next('li').find('a').first().focus();
                }
            } else if (e.keyCode == 27 || e.keyCode == 37) {
                e.preventDefault();
                $(this).parents('ul').first().prev('a').focus().parents('ul').first().find('.' + settings.menuHoverClass).removeClass(settings.menuHoverClass);
            } else if (e.keyCode == 32) {
                e.preventDefault();
                window.location = $(this).attr('href');
            } else {
                var found = false;

                $(this).parent('li').nextAll('li').find('a').each(function () {
                    if (typeof keyCodeMap != "undefined" && $(this).text().substring(0, 1).toLowerCase() == keyCodeMap[e.keyCode]) {
                        $(this).focus();
                        found = true;
                        return false;
                    }
                });

                if (!found) {
                    $(this).parent('li').prevAll('li').find('a').each(function () {
                        if (typeof keyCodeMap != "undefined" && $(this).text().substring(0, 1).toLowerCase() == keyCodeMap[e.keyCode]) {
                            $(this).focus();
                            return false;
                        }
                    });
                }
            }
        });

        function hideChannelMenu() {
            $('li.sw-channel-item.' + settings.menuHoverClass).removeClass(settings.menuHoverClass).find('ul').attr('aria-hidden', 'true').css('display', 'none').find('a').attr('tabIndex', -1);
        }
        
        // Hide menu if click or focus occurs outside of navigation
        $('[id="channel-navigation"]').find('a').last().keydown(function (e) {
            if (e.keyCode == 9) {
                // If the user tabs out of the navigation hide all menus
                hideChannelMenu();
            }
        });

        $('[id="channel-navigation"]').find('a').first().keydown(function (e) {
            if (e.keyCode == 9) {
                // hide open MyStart Bar menus
                hideMyStartBarMenu();
            }
        });

        /*$(document).click(function() {
            hideChannelMenu();
        });*/

        $('[id="channel-navigation"]').click(function (e) {
            e.stopPropagation();
        });
    });

    $(document).ready(function() {
        $('input.required').each(function() {
            if ($('label[for="' + $(this).attr('id') + '"]').length > 0) {
                if ($('label[for="' + $(this).attr('id') + '"]').html().indexOf('recStar') < 0) {
                    $('label[for="' + $(this).attr('id') + '"]').prepend('<span class="recStar" aria-label="required item">*</span> ');
                }
            }
        });

        $(document).ajaxComplete(function() {
            $('input.required').each(function() {
                if ($('label[for="' + $(this).attr('id') + '"]').length > 0) {
                    if ($('label[for="' + $(this).attr('id') + '"]').html().indexOf('recStar') < 0) {
                        $('label[for="' + $(this).attr('id') + '"]').prepend('<span class="recStar" aria-label="required item">*</span> ');
                    }
                }
            });
        });
    });
    </script>

    <!-- Page -->
    
    <style type="text/css">/* MedaiBegin Standard *//* GroupBegin Icon Fonts */
@font-face {
  font-family: 'cs-dev-icons';
  src: url("data:application/x-font-ttf;charset=utf-8;base64,AAEAAAALAIAAAwAwT1MvMg8SBlEAAAC8AAAAYGNtYXAXVtKuAAABHAAAAFRnYXNwAAAAEAAAAXAAAAAIZ2x5Zuo9DToAAAF4AAAfjGhlYWQSZdJAAAAhBAAAADZoaGVhB8MD6wAAITwAAAAkaG10eKQDFbQAACFgAAAAsGxvY2HyEucKAAAiEAAAAFptYXhwAEIC+gAAImwAAAAgbmFtZZNeRWkAACKMAAABwnBvc3QAAwAAAAAkUAAAACAAAwQAAZAABQAAApkCzAAAAI8CmQLMAAAB6wAzAQkAAAAAAAAAAAAAAAAAAAABEAAAAAAAAAAAAAAAAAAAAABAAADpJwPA/8AAQAPAAEAAAAABAAAAAAAAAAAAAAAgAAAAAAADAAAAAwAAABwAAQADAAAAHAADAAEAAAAcAAQAOAAAAAoACAACAAIAAQAg6Sf//f//AAAAAAAg6QD//f//AAH/4xcEAAMAAQAAAAAAAAAAAAAAAQAB//8ADwABAAAAAAAAAAAAAgAANzkBAAAAAAEAAAAAAAAAAAACAAA3OQEAAAAAAQAAAAAAAAAAAAIAADc5AQAAAAADAAL/wAQAA74ABwALABAAABMjCQEjESERJTUjFQEhESERX10B/wH/Xfy8A0SL/l4BFv7qAjMBi/51/Y0Cc3v4i/ylAdD+MAAV//7/0QQAA6gAhAD3AQMBEAEsAU4BagGGAYoCSwJXAmQCcAJ/AowCpQKxAsoC1wLqAvcAABM6ATM2NDU8ATU0Njc+ATc2MhceARceARUcARUcARU6ATMuAScuASMqASMqASMuATc+ATc2FjM6ATMyFhceARceAQcOASMqASMiJjU8ATU0JicuAScOAQcOAQcOARUcARUUBiMqASMiJjc+ATc+ATc+ATM6ATMyFgcUBiMqASMiBgcOAQcDMjM6ATMyMzQ2NTwBNT4BNzYWFxYGFRwBFTIzOgEzMjM8ATU8ATU0Jjc+ATMyFhcWFBUcARUUBiMiIyoBIyIjIiY1PAE1NCYnJgYHBhQVHAEVFAYjKgEjKgEjIiY1PAE1NCY3PgEzMhYXFgYVHAEVHAEVASImNTQ2MzIWFRQGJzI2NTQmIyIGFQYWMwU6ATMyFhUUBiMqASMiJjU8ATU0NjMyFhUcARUzOgEzOgEzMhYVFAYjKgEjKgEjIiY1JjYnNDY3MhYVHAEVIToBMzIWFRQGIyoBIyImNTwBNTQ2Mx4BFRwBFTM6ATMyFhUUBiMqASMuATU8ATU0NjMeARUcARUBFy4BFz4BNx4BFxYUBw4BBzM+ATceARczLgEnLgE3PgE3PgE3HgEVFAYVMzY0NTQ2Mz4BNzYmJyYGBw4BByYiIy4BJy4BJyY0Jy4BBw4BFxYGBw4BBwYmJy4BBw4BFR4BFx4BFxwBFTM8ATU0NjceARceARcWFAcOAQczPgE3PgE3HgEXMy4BJy4BNz4BNzQ2Nx4BFzcOAQcuASc+ATc+ARcWNjMcARU3FzwBNTI2MzoBMzIWFx4BFw4BBxceARUOAQcVMwMqASM+ATceARccARc8ATU+ATceARcqASMlMhYHFAYjIiY3NDYHFhQHDgEHLgEnPgE3HgEHLgEnOgEzHgEXDgEHAx4BFx4BFx4BByoBIyoBIyImJy4BJz4BNycyFhUUBiciJjU0NgU+ATceARcOAQcOAQcOASMqASMiJiMmNjcHOgEzDgEHLgEnPgE3Bz4BNx4BFw4BBy4BJy4BJy4BNycyFhUUBiMiJjc0NjMlTphMAQYHIkQiCxAMIkIiCAZMmE4MFgwCCAM1ajUDBgMGCAEBCAQBBgI4bzcJDQYMGQ0GBQQDDQlPnU8PDQIDIUMiChMKFy0XBgQNEE6cTg8PAQEEAg4cDwMMBTlzOQkKAQsHN2w3BgoFCBQLAS4uLVstLi0BATcqLUwCAgEuLi1bLi0uAQEDBwQDCAMBDhEtLS1aLS4tEA4nHiI7AwEOEBo0GkB/QBMNAQEDBwQDCAMBAQHbJTU2JSY1NiUaJSUZGiUBJBv+XhcuFg0LCw0WLBcRDgcIBwejCxQJDRsNDAoKCxEjEQcOBg0NAQEBBggHCAGnGC0XDAsLDRctFw8OCAcJBaQXLRcNCwsNFy0XEA0IBwcH/u9VEStFDBcMDRcNCAgFCgQVBQoGBQoGFAcNBgICAxYrFQECAQsGASIBBQQeKgQDGxkbOhUCAwIBAQE/f0ACAgEBAgk6IyEqAgEFBjx5PQYIBBM3GRodASEaBgwGIwYMAQMBFSgVAwMHDQYUBAcEAQMDBQoGFAcNBwEBAQ4cDwIBCxgMZhwvEwsYDAwZCgcUERcuFwoIAgQDGjUaAwYCDh0PCxgMAQUFAQMEEK0bNx0UJxMIEQgSCREJEyYUHTccAZ8XIAEgFxcgASA0CggTJxQPGw8hQSABAo0OHA4uWy0BAwIhQiGFAwUCPXk9BgICBw0HJ04nBAcBFSgUBQgEShcfIRYYHyH+0D99PwUIBQUJBQ8eDwIFBS1aLQICAQUGBggtWy8OHA4iQSEBAwETAgICIUEhDxwOAgMCEiYTBAEHRhYgIBcXIAEgFwEFAwcDMF8wCQ0GGjYbCgobNRsGDgovXi8DBwQMFwoCAQEHBgQHAwEBBQYNGQwHDgkIBg4PMWMxBAgCGzUbBxAHEiUSBAoHMGEwEA4ODAQIAw8cDQQECAYJBQQEChML/ugEBwQaMxkrPgYHPC4cOh0DBwMEBgMzZjIDBgIECAgDAgUDNmw2EQ4OEB05HCAvBQYsJBkzGgUMBRAODhI1azYDBgEECAgDAgYDMmQxBQgGAUQ1JiY1NiUmNRwkGholJBoaJf8HCAcHDhEXLhYMCgsLFy4YBwcHBw0NGTEZBwoBCQkYMBkHBwgHDg8YMBgKCQEKCBgvGQcIBwcBDRAXMBgJCgEJChcvGQHXQxgiSQcNBxUrFQwUDAgQCAkSCgkTCQwXCwQGBSVLJQEDAQIMCTBgLzBhMQUEBSseGzQMDQsVAgQCASVKJQEHAwgTCCAkBgU2JQcHAyNFIwMBBRULCwsvHBstCQICAjJlMzBfMAoNAQEFAiNHJAYJBgsWCwcNBgIFBAkTCQwYCwMIAhgxGAECAQcNB1UJIhsHDQcVKRUPDAECAQgPBwgGBw0HAQMCGTQaBw0HKg0cDwwYCwQBLiJCIQMEAx4+Hx4+HwMFAyFDIi0hFxYfIBcXIGkNCA4hRCMZMBkTJRMBAToZMBoGCwYTJhMBGAEDASNHIwQIBgMCI0YjBQkFaCEXFiABHxgXIPkkRyUFCgUIEQgaMxoDBQEHCAQlGTEZFCYTBgoGLgIEAhMmExgxGAMFAiFCIAcMBW0hFxYfIBcXHwAAAgAA/9YD7QPCACQAQQAAJQ4BIyInLgEnJjU0Nz4BNzYzMhceARcWFRQGBwEWFA8BBiInAScyNz4BNzY1NCcuAScmIyIHDgEHBhUUFx4BFxYzAoIyeEJUSkpuICAgIG5KSlRUS0puICAoJAEMExMBFDcU/vXsQTg5VBkYGBlUOThBQDk4VRgYGBhVODlA4SQoICBvSkpUVEpKbiAgICBuSkpUQngy/vUUNxMBFBQBCxQYGVQ5OEFAOThVGBgYGFU4OUBBODlUGRgAAAAADgAa/8ID8QPAAAsAKQBHAHYAlACdAKsAtwDQAO4BBAEiATABOAAAAR4BBw4BJy4BNz4BEy4BIyoBIx4BFx4BHQEeARUeATc+ASc0Jy4BJyYnBTQ2Nz4BNyoBIyIGBwYHDgEHBhUGFhcWNjc0Njc1FxUUBisBIiY9AQ4BBwYWMzoBMxEUFjMyNjUROgEzERQWMzI2NRE6ATMyNicuAScDIgYHDgEVIyIGHQEUFjsBMjY9ATQmKwE0JicuASMHMx4BFSM0NjcXIyImNTQ2OwEyFhUUBgEUBiMiJjU0NjMyFhcuASsBHgEXOAExHgEHERQWMzI2NRM4ATEFMSImJzAUERQWMzI2NREzERQWMzI2NRA0MQ4BKwEDPgE3IyIGFTgBMREUFjMyNjURJjY3Nw4BFSMiBh0BFBY7ATI2PQE0JisBNCYnLgEjDgEHFxQGKwEiJjU0NjsBMhYnIzQ2NzMeAQE8IBoNDUAgIBoNDUCjDi8gAgMCCAwEDxUVJgYeEBAOBgsLHhARCv7iFQ8EDAgCAwIgLw4LEBAeCwsGDhAQHgYmFfYgFooWIAYSDAINCgcPCRwUFB0FCgYcFBQcCRAGCw0CDRIGexEcCAQECAoODgqKCg4OCggEBAgcEQcOCg4+DgooQggMDAhCCAwMAjExIyMxMSMjMXsBOSg1Cw8FERYBGBERFwH+7AsUCB0UFB0VHBQVHAcUDIoSBQ8LNSg5FxERGAMXEiIEBAgKDg4KigoODgoIBAQIHBERHAhqDAhCCAwMCEIIDBY+DgoOCw0DsA1AICAaDQ1AICAa/ucoKQcUCwUcEXo8aAEPDgUGHhABHR5ULS0gBxEcBQsUBykoIC0tVB4dARAeBQYODwFoPHquChYfHxYKIF1BCxD+3BQcHBQBJP7cFBwcFAEkEAtBXSABAhEOBhAIDQq4CQ4NCrgJDggQBg4RHwIRCwsRAssMCAgMDAgIDAFlIzExIyMxMfIoOAgXDQYeE/7ZERcXEQEq7AkHe/6tFB0dFAGF/nsUHR0UAUuDBwkBIA0XCDgo/tYRGBgRASIUIgYDBw8IDgq3Cg4OCrcKDggPBw0SARENuAgMDAgJCwuRCxADAxAAAAMAAP/+BAADggADAAwALQAAJScHMwMTIycjByMTMwEVIRUjBgcOAQcGBxcHJwcnNy4BJzMeARc+ATchNSE1MwNNS0qVH9JaNts3XNJa/nQBSIcNERErGxogdCGR6j/qLkUVWhI1JDZJFv33AUha3sHBATz95IeHAhwBaFlZJCUmSiYlJHVXiuE+5TRkMyNNJzp/O1lZAAAAAQAAAKAEAQLvAC0AAAEuASMiBgciBw4BBwYxAS4BIyIGBw4BHQEUFhcUFx4BFxYXNjc+ATc2Nz4BPQEEAQsnHAsWCQE9PpI9PP6oFy0UBgsGHR4EBR8ffl5ffUA8PHE1NTIeHwKwIB8EBDk6iTk5AT4cHAEBCx4SHgYLBwEfHndZWXU7OThrMjIvGCwUDgAABAAG/+UD/wOXAFQAlwDRARQAAAUuAScuAScmBgcOAScuAScuAQcOAQcOAQcGFBUuAScuAScuATc+ATMyFhceARcWNjc+ARceARcWMjc+ATc2FhceATc+ARceARcUBgcOAQcOAQcOAQcDFAYVKgEjDgEHDgEHDgEXFBYXFgYHDgEVBhYXFBYXHgEXHgEXHgE3PgE3PgE3PgE1PgEnNCYnJjY3NDY3NiYnLgEnJS4BJyYiBw4BJy4BJy4BBw4BJy4BJy4BNz4BNz4BNz4BNz4BNzYWFx4BFx4BFx4BFx4BFw4BBw4BBwEeARceAQcOAQcUFhcyFhUOAQcOAQcOAQcOAScuAScuAScuAScuAScuASc0Njc+ATUuATUmNjc+ATc+ATc+ATc+ATcCugQIBAYZFQkQCClYLwkQCAYNBxQbBwYIBAEqVSErQA4GAgYITC0FCgQWMR0oSSAMGQ0KEwkNGA0NGw4IDgc4gzkMFw0qRAESDx5UPBcvGQYLBtABBAgEEBwJAQcDDAkBAgEBAQgDBgEBAgcDBQUBBhEMGT4bDxMHAQMDBwgBAQEEAgsBAQIBBxcgDx8PAaMYLBYEBgQQIhMMFwwEBwQfQCIFCgUHAQcXIQoHBQIBBQQDEw0teSkOCgIDAwMGJx4DBAIDBgMNHA39lg0hECEeBgIEAgIHBgYBAgMBCQQGCQIJQyMcKw8HCQUDBwMECgIDAQEICAUCAgMBAgIBCQcGCgMJGhAKGA8bESAQFR0HAwQGIAkVBAwGBQMCBRcSECIRAQICGCwkLmg+GTEYLD0FAxEXBAUTGQoEBAMHBAYGBQgEAgUFLQIrCQQDCUY0JUYhP2clDRUHAgMCAasBAQEBCg8DBQEFEwwMGQ0FCQEBCAQKFQsECAICBwUQHAwYAhUNHxIDBwEEDAgIEgkDBwEBDQcDBwMjLwoFBgOfAgwJAgMKDgQDCwUCAQIQDAoCBAMECQYQKRkRIxITJRMRGwsjBygNIhIVLBUmOhcCBgMCBgEDBgMBaAMHBgw3JAsWCwUGAQkGDRkMBQoEBg0JJDUCAhsWChcLBQkEBg0HChYLCAgBAQYFDBoNChQKCAsEAwcFDg8BAQIBAAMAMP/AA9MDwABnAMEAzgAAARwBFRQGBwYmJyY0NTwBNTwBJy4BIw4BFRwBFRwBFRQGBwYmJzwBNTQ1PAE1NDU0JicuATUmNDc0Njc6ATMyFhceARcWMjc+ATc+ARceAQcOAQcOAQcGIicuAScuAQciFBUcARU4ATEBOgEzMhYXHgEVFBUcARUUFRQGIyIjKgEjIiMiJjU8ATU0NjMyMzoBMzIzOgEzMjY1PAE1NDU8ATU0NTwBNTYmIyoBIyIjKgEjIiMiJicuAScuATc0MjM6ATMFIiY1NDYzMhYVFAYjAUwYExIdBAEBAgkGBgkaFBMdAQMFFx4BAS0eMGAvCRAHGDEYAwUDGDAXChQMFw8OAwcDHz8fDx8PFCcTAQMBAQEsR45HFh8GAgIjGUBBQIFBQEEHAwIHPDw8eDw8PAIDAQMCAQMEEiUSNTU2ajU1NQgDAgQRDQEDAQQCSI9I/mQpOjopKTs7KQEeS5ZLExwCAhUSAgYDRIdDAwQDBgcBCQYCAwJEhkQUHAEBGxMCBQIuLy5eLi8uBQUBBygYMWIwHysBBgYUKBQCAhMmEwcGBAYsEwQGAxkxGAwNECEQAQIBAwJMmEwCohYTBAoFRkVGi0ZGRRkiAggQIRAHAgIDAQMBPTw9ejw9PQECAgMDAggTIg8CAgIB0zoqKDs7KSk6AAAAAAUAI//AA94DwAAMABYALQBGAF0AAAEyNjU0JiMiBhUUFjMXLgErASIGBxc3BSIGBzUwBhUcARUcARUUFjMyNjU0JiMFNDY3NQUlFR4BFRQGBxUFFTcXNSU1LgE1NzwBNTQmMRUuASMiBhUUFjMyNjU8ATUB+kxra0xMa2tM9hg7IfEhPBjs7v2YBQkEUzsqKTs7KQJwQjH+l/6YL0BALwFnAQEBaDFC5lMECQQqOzsqKTsCUmtMTGtrTExrQxQXFxVdXpYBATJdLAIDAgICASo7OyoqO2UySQaIjo6JBkkxMUgHRY4BAQEBjkUFSTIFAgMCLF4zAQE7Kik7OykBAwEAAAAADwAAANMEAAKpAAUADgASAB4ANQBMAGQAawCEAJYAvQDCAM8A8AD7AAATMxUjNTMlFSMVIzUjNTMFIyczFxQGIyImNTQ2MzIWBQ4BJy4BJzM1IxUzNR4BFx4BMzI2NycBPgEXHgEXIxUzNSMVLgEnLgEjIgYHFwc0Njc2FhUUBgcjHgEzMjY3Fw4BIy4BNTc0JiMiBgcXNSM1PwEzFTMVIxUUFjMyNjcXDgEjIiY1Ny4BNT4BFx4BBw4BByc+ATUnFzceATMyNjU0JicuATU0NjMyFhcHLgEjIgYVFBYXHgEVFAYjLgEnBSc3FyM/ARU3MwcXIycjFSM1BzU0JiMiBgcVPgEzMhYVDgEVFBYzMjY3HgExMDQ1IiYnJzQ2NxcOASMiJjUbTWgbApI2GzmKAUkRBhwFCgcICgoIBwr+qixrPxosDylgGQ05JxEhDzFWJRH+rixsPhosDylgGgw6JxAhEDBXJBHhJBYgFQEBUAITDwgUBwYJFwwaJFUNDQsRAmwSFAMZIyMICQQIAwQGDAgWElcBAQIKBwoNAgEWDg0LDw4qCgkQCgoMEQoNFxoWDRIHBgcSBwoKEAsNFxkYDRgJAaMCHgEdOhwxIDs8IC8DHFYXGA8VCwkYCQ0KJyMZEQsPCQUeAwQCRw8aAQUKCAgLAYoXpgMYj48YfoShBwoKBwgKClQlGAwFEAcZZj8HGAgDBB8eFAESJRgMBRAHGWY/BxgIAwQfHhSVHyIBASIbBAgCERMCBRQGBwEmHw4ODw4PJDsSBSMjFzsLCwICFwIDGRV3AgMCBwgBARAOEhcKEAUTBw6aFwUFBQcICAQFEBARFwUFFgQFBgYICgQFEBERFwEFBwa1B7y1B3I0PkAwMLWfNRocCAYaBQsPCgQWFBEXCQcMBBEFAQUKCQ0EGAkJBwkAAAAAAQAA/8AEAAPAAAMAABMhESEABAD8AAPA/AAAAAEBmf/AA2ADMgAWAAAFESM1MzU0NjMyFhcVIyIGHQEzByMRIwInjo5sWCtACl8wHKQXjY5AAY+Og2NvBwGVKyFsjv5xAAAAAAEAAv/ABAIDwAAEAAATIREhEQIEAPwAA8D8AAQAAAAAAgCCAEADggNAACAAMQAAJSEiJy4BJyY1ETQ3PgE3NjMhMhceARcWFREUBw4BBwYjASIGFREUFjMhMjY1ETQmIyECsv6gKyYmOBEQEBE4JiYrAWArJiY4ERAQETgmJiv+oDtVVTsBYDxUVDz+oEAQETgmJisBYCsmJjgREBAROCYmK/6gKyYmOBEQAsBUPP6gPFRUPAFgPFQAAAAAAgFCAQACwgKAAAsAFwAAASImNTQ2MzIWFRQGAyIGFRQWMzI2NTQmAgJPcXFPT3FxTzVLSzU1S0sBAHFPT3FxT09xAUBLNTVLSzU1SwAAAAABAqICYAL6ArgACwAAARQGIyImNTQ2MzIWAvoaEhIaGhISGgKMEhoaEhIaGgAAAAABAAH/vwQBA78ABAAAEyERIREBBAD8AAO//AAEAAAAAAEAqgCZA2gC1ABHAAABDgEHPgE3DgEHLgEjIgYVFBYXJicuAScmJw4BFRQWFy4BJzAUMRQWFw4BIyImJx4BFw4BIyImJx4BMzI3PgE3NjU8ASc+ATcDaBMqFRYhCBUuGRM3HzxUAgEsKypLISEbCQojHRIhDkIxCRMKBg4HDkovJVszCREIL3A+Y01MaBsbARYkDgKRCQsDDikZDREFFRhUPAgRCAMLDCcaGyEQJRQlPxQBCQgBNU8KAgMBAis4AR0hAQEfIiYldklJSAQKBBAlFgAAAQAC/8AEAgPAAAQAABMhESERAgQA/AADwPwABAAAAAACAKIAyANiArgAQgBFAAABMCYnLgEnJicuASMmOQEwByIGBwYHDgEHDgExMAYdARQWMTAWFx4BFxYXHgEzFjEwNzI2NzY3PgE3PgExMDY9ATQmBTUXA1sMEBQoCyUrK0oYGRkZSisrJQooFBAMBwcMEBQuCxYoKE8dHhgZSisrJQsoFA8NBwf+VtACTTYQFQcBAwIBAQEBAQECAwEHFRA2Rys2Kkc2EBUHAgICAQIBAQECAQMBCBUQNkcqNitH8tltAAAAAgCu/8IDVwPAAAMABwAAEzMRIwEhESGu//8BqQEA/wADwPwCA/78AgAAAAAB//4ADgQAA28AJQAAJRUUFhceATMyNjcJAS4BIyIGBw4BHQEmJy4BJyYnFRQXHgEXFhcB/woJCRgMDRcKAZP+bQoXDQwYCQkKQkREhD8+Nigoil1ebPKkDBgKCQkJCQGOAY4KCQkKCRgMnwEJCjYxMlJAb2NjmjExDAAAAf/+/8AD/gPAAAIAAAMBEQIEAAPA/AAEAAAAAAIAAP+/BAADvwACAAYAAAUBIQUBESEEAPwABAD8uQL6/QZBBABN/QYC+gAAAwAAAHcEAQMKAA4AHAArAAATITI2NTQmIyEiBhUUFjMFISIGFRQWMyEyNjU0JgMhIgYVFBYzITI2NTQmIykDrxEYGBH8UREYGBEDr/xRERgYEQOvERgYEf1bERkZEQKlERgYEQK3GRERGBgRERnOGBERGBgRERj+4BgRERgYEREYAAAAAQHZ/8ACjAPAAA8AAAEzMhYVERQGKwEiJjURNDYCHC0cJyccLRsoKAPAJxz8hhwnJxwDehwnAAABAAD/wAQAA8AAAwAAEyERIQAEAPwAA8D8AAAAAQAA/8AEAAPAAAMAABMhESEABAD8AAPA/AAAAAEAAP/ABAADwAADAAATIREhAAQA/AADwPwAAAABAAD/wAQAA8AAAwAAEyERIQAEAPwAA8D8AAAAAQAA/8AEAAPAAAMAABMhESEABAD8AAPA/AAAAAECJgEaA3MCZgALAAABFAYjIiY1NDYzMhYDc2FFRWJiRUVhAcBFYWFFRWFhAAAAAAEAjQEaAdoCZgALAAABFAYjIiY1NDYzMhYB2mJFRWFhRUViAcBFYWFFRWFhAAAAAAEAigDGAnoCuwApAAABMw4BIyImNTQ2MzIWFzcuASMiBw4BBwYVFBceARcWMzI3PgE3Nj0BIxUBiocMRjZBXFxBHDUVQSNWLjUuL0UUFBQURS8uNTYsLT8REvABiC8zWkBAWhQSSh4fFBNELi4zNC4tRBQUEhFALS03MGIAAAAAAQK5AVIDqQJCAAsAAAEjNSMVIxUzFTM1MwOpWEBYWEBYAepYWEBYWAAAAAABAb0AzwMfAjQAHQAAJTU0JiMiBgc1IxYVHAEVBjEzNTQ2Nz4BMzIWHQEXAx9MOS4vDHQBAXQBAwYdGSAadM/IUUwoEjINODd9MjLDCA8GDxwsI7oCAAAAAQEDAlsBhQLTAAwAAAEyNjU0JiMiBhUUFjMBRB8iIx4dJCMeAlskGBoiIhoaIgAAAQEKAM8BfgIsAAMAAAEzESMBCnR0Aiz+owAAAAEAzQAgAzIDQABZAAAlLgE3Njc+ATc2MTAmNTQ2MzIWFRQGBwYWMzI2NTQmIyIHDgEHBhUUFhceAQcOAQcOAScuATU0Nz4BNzYzMhceARcWFRQHDgEHBiMiJicwBgcOAQcOATEwJicBUQMDBwQJCRMIBw4zJB8eHgoILCNAV3BYNCgoOA8OFQ8DAQEDCQIBCActNBUUUDs8TT82NlAXFhITQi0uNiU+DBkECSkKChAEA1IXVB8OJydSICAoIDJCJx0eVyskMnthVm0REjomJigfPBIEBgQLJgUHAwMVcTU5NDVRGBgVFUozMzw+NjZRGBchFmERH1APDxgcFgAAAAABAOEA0QMdArQALwAAEzA2FxYXHgEXFhceATc2Nz4BNzY3NicmBgcGBzYWBw4BIyImJy4BBwYHDgEHBjEX+TQNBg4NHQ4OBw1EKBUoJ1MjIwwMISFcKywJMCwaGSsMDBUNDhg7HR4eMxARGAIUIA4HKChhLS0QHDEaDSIhYj49REQcHAkjIzsdPC8wOT02OJgMBhUVLxISHQAAAAABAAAAAQAAlSUfG18PPPUACwQAAAAAANejRuEAAAAA16NG4f/+/78EAgPCAAAACAACAAAAAAAAAAEAAAPA/8AAAAQA//7//gQCAAEAAAAAAAAAAAAAAAAAAAAsBAAAAAAAAAAAAAAAAAAAAAQAAAIEAP/+BAAAAAQAABoEAAAABAAAAAQAAAYEAAAwBAAAIwQAAAAEAAAABAABmQQAAAIEAACCBAABQgQAAqIEAAABBAAAqgQAAAIEAACiBAAArgQA//4EAP/+BAAAAAQAAAAEAAHZBAAAAAQAAAAEAAAABAAAAAQAAAAEAAImBAAAjQQAAIoEAAK5BAABvQQAAQMEAAEKBAAAzQQAAOEAAAAAAAoAFAAeAEIELgSUBjQGgAbICGgJagnsC0gLVgt6C4oL2AwADBgMKAySDKINBA0aDVgNZg18Db4N2g3oDfYOBA4SDiAOOA5QDpAOpg7SDuoO+A94D8YAAAABAAAALAL4ABUAAAAAAAIAAAAAAAAAAAAAAAAAAAAAAAAADgCuAAEAAAAAAAEADAAAAAEAAAAAAAIABwCNAAEAAAAAAAMADABFAAEAAAAAAAQADACiAAEAAAAAAAUACwAkAAEAAAAAAAYADABpAAEAAAAAAAoAGgDGAAMAAQQJAAEAGAAMAAMAAQQJAAIADgCUAAMAAQQJAAMAGABRAAMAAQQJAAQAGACuAAMAAQQJAAUAFgAvAAMAAQQJAAYAGAB1AAMAAQQJAAoANADgY3MtZGV2LWljb25zAGMAcwAtAGQAZQB2AC0AaQBjAG8AbgBzVmVyc2lvbiAxLjAAVgBlAHIAcwBpAG8AbgAgADEALgAwY3MtZGV2LWljb25zAGMAcwAtAGQAZQB2AC0AaQBjAG8AbgBzY3MtZGV2LWljb25zAGMAcwAtAGQAZQB2AC0AaQBjAG8AbgBzUmVndWxhcgBSAGUAZwB1AGwAYQByY3MtZGV2LWljb25zAGMAcwAtAGQAZQB2AC0AaQBjAG8AbgBzRm9udCBnZW5lcmF0ZWQgYnkgSWNvTW9vbi4ARgBvAG4AdAAgAGcAZQBuAGUAcgBhAHQAZQBkACAAYgB5ACAASQBjAG8ATQBvAG8AbgAuAAAAAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA==") format('truetype');
  font-weight: normal;
  font-style: normal;
}

.cs-dev-icons {
  /* use !important to prevent issues with browser extensions that change fonts */
  font-family: 'cs-dev-icons' !important;
  speak: none;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
  /* Better Font Rendering =========== */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.cs-dev-icon-bullet:before {
  content: "\e919";
}
.cs-dev-icon-menu:before {
  content: "\e918";
}
.cs-dev-icon-more-accent .path1:before {
  content: "\e916";
}
.cs-dev-icon-more-accent .path2:before {
  content: "\e917";
  margin-left: -1em;
}
.cs-dev-icon-curve-arrow:before {
  content: "\e915";
}
.cs-dev-icon-play:before {
  content: "\e914";
}
.cs-dev-icon-facebook .path1:before {
  content: "\e90a";
  color: rgb(60, 87, 158);
}
.cs-dev-icon-facebook .path2:before {
  content: "\e90b";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-instagram .path1:before {
  content: "\e90c";
  color: rgb(0, 0, 0);
}
.cs-dev-icon-instagram .path2:before {
  content: "\e90d";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-instagram .path3:before {
  content: "\e90e";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-instagram .path4:before {
  content: "\e90f";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-twitter .path1:before {
  content: "\e910";
  color: rgb(85, 172, 238);
}
.cs-dev-icon-twitter .path2:before {
  content: "\e911";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-youtube .path1:before {
  content: "\e912";
  color: rgb(204, 25, 30);
}
.cs-dev-icon-youtube .path2:before {
  content: "\e913";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-community:before {
  content: "\e906";
}
.cs-dev-icon-for-staff:before {
  content: "\e907";
}
.cs-dev-icon-for-students:before {
  content: "\e908";
}
.cs-dev-icon-lets-talk:before {
  content: "\e909";
}
.cs-dev-icon-chevron:before {
  content: "\e905";
}
.cs-dev-icon-home:before {
  content: "\e900";
}
.cs-dev-icon-school:before {
  content: "\e901";
}
.cs-dev-icon-search:before {
  content: "\e902";
}
.cs-dev-icon-students:before {
  content: "\e903";
}
.cs-dev-icon-translate:before {
  content: "\e904";
}
.cs-dev-icon-flickr .path1:before {
  content: "\e91a";
  color: rgb(230, 230, 230);
}
.cs-dev-icon-flickr .path2:before {
  content: "\e91f";
  margin-left: -1em;
  color: rgb(255, 64, 129);
}
.cs-dev-icon-flickr .path3:before {
  content: "\e920";
  margin-left: -1em;
  color: rgb(30, 64, 138);
}
.cs-dev-icon-google-plus .path1:before {
  content: "\e91b";
  color: rgb(217, 80, 50);
}
.cs-dev-icon-google-plus .path2:before {
  content: "\e921";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-google-plus .path3:before {
  content: "\e922";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-linkedin .path1:before {
  content: "\e91c";
  color: rgb(0, 122, 185);
}
.cs-dev-icon-linkedin .path2:before {
  content: "\e923";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-linkedin .path3:before {
  content: "\e924";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-linkedin .path4:before {
  content: "\e925";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-pinterest .path1:before {
  content: "\e91e";
  color: rgb(189, 32, 38);
}
.cs-dev-icon-pinterest .path2:before {
  content: "\e926";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}
.cs-dev-icon-vimeo .path1:before {
  content: "\e91d";
  color: rgb(99, 180, 228);
}
.cs-dev-icon-vimeo .path2:before {
  content: "\e927";
  margin-left: -1em;
  color: rgb(255, 255, 255);
}


/* GroupEnd */

/* GroupBegin Global */
@-ms-viewport {
	width: device-width;
} 
body {
	-webkit-text-size-adjust: none;
	-webkit-tap-highlight-color:  rgba(255, 255, 255, 0);
    background: #FFF;
}
body:before {
	content: "desktop";
	display: none;
}
.show960 {
	display: block;
}
.hide960 {
	display: none;
}
.hidden {
	display: none;
}
.acc-hidden {
    width: 0 !important;
    height: 0 !important;
    display: block !important;
    padding: 0 !important;
    margin: 0 !important;
    border: 0 !important;
    overflow: hidden !important;
}
.cs-html-btn-reset {
	background: none;
    border: 0;
    padding: 0;
    margin: 0;
    cursor: pointer;
    font-family: 'Open Sans', sans-serif;
    border-radius: 0;    
}
.cs-html-input-reset {
	background: none;
    border: 0;
    padding: 0;
    margin: 0;
    font-family: 'Open Sans', sans-serif;
}
.cs-html-list-reset {
	list-style: none;
    margin: 0;
    padding: 0;
}
.ui-clear:after {
	content: "";
}
.border-box {
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}
.inline-children > *:not(script):not(style) {
	display: inline-block;
	vertical-align: middle;
}
.inline-children:after {
	content: ".";
	visibility: hidden;
	clear: both;
	display: block;
	height: 0;
}
.flex {
	display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
}
.flex-wrap {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
}
.flex-inline {
    display: -ms-inline-flexbox;
    display: -webkit-inline-flex;
    display: inline-flex;
}
.flex-column {
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
}
.flex-column-reverse {
    -webkit-flex-direction: column-reverse;
    -ms-flex-direction: column-reverse;
    flex-direction: column-reverse;
}
.flex-justify-space {
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
}
.flex-justify-center {
	-webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
}
.flex-justify-end {
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
}
.flex-content-center {
    -webkit-align-content: center;
    -ms-flex-line-pack: center;
    align-content: center;
}
.flex-items-center {
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
}
.flex-items-end {
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
}
.flex-iten-baseline {
    -webkit-align-items: baseline;
    -ms-flex-align: baseline;
    align-items: baseline;
}
.fixed-element {
	width: 100%;
	position: fixed !important;
    top: 0;
    left: 0;
    z-index: 8000;
}
.transition-all {
	-webkit-transition: all 0.25s;
	-moz-transition: all 0.25s;
	-ms-transition: all 0.25s;
	-o-transition: all 0.25s;
	transition: all 0.25s;
}
.max-width{
	position: relative;
	max-width: 1240px;
	margin: 0 auto;
	padding: 0 25px;
	box-sizing: border-box;
}
div.sw-special-mode-bar {
	position: fixed !important;
	bottom: 0px;
	left: 0px;
	width: 100%;
}
.gb-section-parent {
	position: relative;
}
.gb-section {
	width: 100%;
	max-width: 1240px;
	margin: 0 auto;
	position: relative;
}
.gb-section-pad {
	padding: 0 20px;
}
#gb-page {
	width: 100%;
	position: relative;
	overflow: hidden;
}
/* GroupEnd */

/* GroupBegin Mystart */
#sw-mystart-outer {
    display: none;
}
.sw-mystart-button {
	margin: 0 1px 0 0;
    padding: 0;
    color: #1D1F22;
	display: inline-block;
	font: 600 12px "Source Sans Pro", Arial, sans-serif;
    height: 43px;
	background: none;  
}
.sw-mystart-button:hover {
    background: none;
    -moz-border-radius: 0px;
    -webkit-border-radius: 0;
    border-radius: 0;
}
.cs-mystart-dropdown, .cs-mystart-item {
    color: #1D1F22;
    height: 43px;
	font: 600 12px "Source Sans Pro", Arial, sans-serif;
    text-transform: uppercase;
    cursor: pointer;
    position: relative;
    margin: 0 1px 0 0;
}
#gb-mystart {
	position: relative;
}
.fixed-element #gb-mystart {
	display: none;
}
.cs-mystart-item a, .sw-mystart-button a, .sw-mystart-button a:hover, .sw-mystart-button a:active, .sw-mystart-button a:visited {
    color: #1D1F22;
    text-decoration: none;
    position: relative;
    height: 43px;
}
.cs-mystart-item a span {
	position: relative;
}
.cs-selector {
	padding-top: 11px;
    height: 100%;
}
.cs-mystart-dropdown.open .cs-selector,
.cs-selector:hover,
.cs-selector:focus {
	background: #00275D !important;
    color: #fff;
}
.cs-selector span {
	position: relative;
    top: -2px;
}
.cs-selector:after {
  	content: "\e905";
	font-size: 10px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
.cs-dropdown {
	width: 195px;
	position: absolute;
    left: 0;
    top: 100%;
    z-index: 8000;
    display: block;
	background: #00275D;
}
.cs-dropdown ul {
    max-height: 330px;
    overflow: auto;
}
.cs-dropdown a {
	display: block;
    font-weight: 600;
	padding: 8px 23px 10px 23px;
	color: #fff;
    text-transform: uppercase;
    background: rgba(0,0,0,0);
    text-decoration: none;
	-webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;    
}
.cs-dropdown a:hover,
.cs-dropdown a:focus {
    background: #a4ceee; /* rgba(0,0,0,0.35); */
}
.cs-dropdown a:hover:before {
	-webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;   
}
.cs-dropdown a:hover:before,
.cs-dropdown a:focus:before {
	color: rgba(255,255,255,0.3) !important;
}

.district-home a {
	min-width: 134px;
	background: #D6CCC3;
}
.district-home a:before {
  	content: "\e901";
	font-size: 34px;
	color: rgba(255,255,255,0.7);
    position: absolute;
    top: 4px;
    left: 5px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
	-webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;       
}
.district-home a:hover,
.district-home a:focus {
	background: #B7AFA7;
}
.district-home a:hover:before,
.district-home a:focus:before {
	color: rgba(255,255,255,0.3);
}
.cs-mystart-dropdown.schools {
	min-width: 116px;
}
.cs-mystart-dropdown.schools:before {
  	content: "\e903";
	font-size: 34px;
	color: rgba(255,255,255,0.7);
    position: absolute;
    top: 4px;
    left: 8px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;    
}
.cs-mystart-dropdown.schools .cs-selector {
	background: #F37720;
}
.cs-mystart-dropdown.translate {
	min-width: 116px;
}
.cs-mystart-dropdown.translate:before {
  	content: "\e904";
	font-size: 34px;
	color: rgba(255,255,255,0.7);
    position: absolute;
    top: 4px;
    left: 8px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;    
}
.cs-mystart-dropdown.translate .cs-selector {
	background: #FFCD34;
}
.cs-mystart-item.search {
	width: 43px;
	background: #00275D;
    margin: 0;
}
.cs-mystart-item.search .cs-dev-icons {
	font-size: 17px;
    color: #fff;
}

#google_translate_element {
	text-align: center;
    padding-top: 10px;
}
.goog-te-gadget,
.goog-logo-link, .goog-logo-link:link, .goog-logo-link:visited, .goog-logo-link:hover, .goog-logo-link:active {
	color: #fff !important;
}

div#ui-mypasskey-overlay {
	top: 76px !important;
}
a#ui-btn-mypasskey {
	padding: 0 10px;
	text-transform: uppercase;
	font: 600 12px "Source Sans Pro", Arial, sans-serif;
	height: 100%;
 	display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-align-content: stretch;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;
	background: #D6CCC3;      
}
a#ui-btn-mypasskey:hover {
	background: #B7AFA7;
}
#ui-mypasskey-overlay {
	padding: 10px;
}
#gb-footer-mystart {
	padding-top: 34px;
	-webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;    
}
#gb-footer-mystart .cs-mystart-item,
#gb-footer-mystart .cs-mystart-dropdown {
	color: #fff;
	height: auto;
    margin-right: 18px;
}
#gb-footer-mystart .cs-mystart-item:last-child {
	margin: 0;
}
#gb-footer-mystart .cs-mystart-item a {
	top: 0;
	border-bottom: 1px solid rgba(255,255,255,0.5);
}
#gb-footer-mystart .cs-mystart-item a:hover,
#gb-footer-mystart .cs-mystart-item a:focus,
#gb-footer-mystart .cs-selector:hover,
#gb-footer-mystart .cs-selector:focus {
	border-bottom: 1px solid #E77819;
}
#gb-footer-mystart .cs-mystart-item:after,
#gb-footer-mystart .cs-mystart-dropdown:after {
	content: "";
	width: 25px;
    height: 1px;
    background: #E77819;
    position: absolute;
    bottom: -2px;
    left: 0;
}
#gb-footer-mystart .cs-mystart-dropdown:after {
	bottom: -1px;
}
#gb-footer-mystart .cs-selector {
	padding: 0;
    font-size: 14px;
    font-weight: 400;
    border-bottom: 1px solid rgba(255,255,255,0.5);
}
#gb-footer-mystart .cs-selector:hover,
#gb-footer-mystart .cs-selector:focus {
    background: none !important;
}
#gb-footer-mystart .cs-selector span {
	position: static;
}
#gb-footer-mystart .cs-selector:after {
	margin-left: 5px;
    display: inline-block;    
}
#gb-footer-mystart .cs-dropdown {
	background: #E77819;
}
#gb-footer-mystart .cs-dropdown a {
	color: #000;
    padding: 5px 3px;
}
/* GroupEnd */ 

/* GroupBegin Search */
#gb-search-form {
	width: 100%;
    max-width: 325px;
    background: #00275D;
    position: absolute;
    top: 0;
    right: 43px;
    display: none;
}
#gb-search-input {
    padding: 0 10px;
    height: 43px;
    font-size: 13px;
    color: #fff;
    margin: 0;
    border: none;
    box-shadow: none;
    -webkit-border-radius: 0;
    border-radius: 0;    
}
/* GroupEnd */ 

/* GroupBegin Header */
header {
	background: #fff;
	border-top: 3px solid #AFD4E5;
}
.sp header {
    -webkit-box-shadow: 0 4px 0 0 rgba(0,0,0,0.3);
    box-shadow: 0 4px 0 0 rgba(0,0,0,0.3); 
}
header:before {
    content: "";
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
	left: calc(-50% - 752px);
    opacity: 0.3;
    background: #D7D7D7;
    overflow: hidden;
}
header.fixed-element {
	max-height: 96px;
}
header.fixed-element:before {
    left: calc(-50% - 735px);
}
header.fixed-element:after {
	content: "";
    width: 100%;
    height: 4px;
    background: rgba(0,0,0,0.3);
    position: absolute;
    bottom: -4px;
    left: 0;
}
#gb-header-svg {
	min-height: 163px;
	position: absolute;
	bottom: 0;
    left: -133px;
}
.fixed-element #gb-header-svg {
	min-height: 155px;
    left: -116px;
}
#gb-header-left {
	position: relative;
    -webkit-flex: 0 1 40%;
    -ms-flex: 0 1 40%;
    flex: 0 1 40%;
    min-height: 115px;    
}
#gb-header-right {
	position: relative;
    -webkit-flex: 0 1 60%;
    -ms-flex: 0 1 60%;
    flex: 0 1 60%;
    min-height: 115px;    
}
.fixed-element #gb-header-left {
	min-height: 96px;
}
.fixed-element #gb-header-right {
	min-height: 96px;
  	display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
	-webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;    
  	-webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
}
#gb-logo {
	padding-top: 2px;
	margin: 0 21px 0 0;
}
[data-show-logo="false"] #gb-logo,
[data-show-logo-only="true"] #gb-sitename {
	display: none;
}
#gb-logo a {
	display: block;
}
#gb-logo img {
	max-width: 100%;
	max-height: 100%;
}
.fixed-element #gb-logo img {
    max-width: 84%;
}
#gb-sitename {
	margin-top: -3px;
}
#gb-sitename span {
	display: block;
}
#gb-sitename .gb-sitename-one {
	font: 600 30px/1 'Crimson Text', Times New Roman, serif;
    text-transform: uppercase;
	color: #00275d;
    margin-bottom: 3px;
}
.fixed-element #gb-sitename .gb-sitename-one {
	font-size: 28px;
}
#gb-sitename .gb-sitename-two {
	font: 700 15px/1 'Merriweather', Times New Roman, serif;
    text-transform: uppercase;    
	color: #00275d;
}
.fixed-element #gb-sitename .gb-sitename-two {
	font-size: 13px;
}
.sp #gb-tab-links-outer {
	height: 44px;
}
#gb-tab-links {
	position: absolute;
    top: 0;
    left: 0;
    right: 0;
    z-index: 10;
}
.sp #gb-tab-links,
.sp #gb-tab-links ul {
	position: static;
}
#gb-tab-links ul {
	position: absolute;
    top: 0;
    right: 0;
    z-index: 10;
}
.gb-tab-link {
	font: 600 12px "Source Sans Pro", Arial, sans-serif;
	color: #fff;
	text-transform: uppercase;
	text-decoration: none;
    height: 41px;
    border-bottom: 2px solid rgba(0,0,0,0.3);
}
.gb-tab-link:hover,
.gb-tab-link:focus {
	height: 44px;
}
.gb-tab-link-0 {
	width: 130px;
	background: #00662B;
}
.gb-tab-link-0:after {
    content: "\e908";
    font-size: 27px;
    opacity: 0.25;
    margin: 1px 0 0 4px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
.gb-tab-link-1 {
	width: 104px;
	color: #000;
	background: #92C1E9;
}
.gb-tab-link-1:after {
    content: "\e907";
    font-size: 27px;
    opacity: 0.25;
    margin: 1px 0 0 4px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
.gb-tab-link-2 {
	width: 138px;
	background: #512D6D;
}
.gb-tab-link-2:after {
    content: "\e906";
    font-size: 27px;
    opacity: 0.25;
    margin: 1px 0 0 5px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
.gb-tab-link-3 {
	width: 200px;
    padding: 0 5px;
	background: #9D2235;
}
.gb-tab-link-3:after {
    content: "";
    width: 27px;
    height: 27px;
    display: inline-block;
    opacity: 0.25;
    margin: 1px 0 0 5px;    
    background: url("/cms/lib/MO49000025/Centricity/Template/18/speech.png") no-repeat;
}
/* GroupEnd */ 

/* GroupBegin Navigation Styles */
div.ui-widget.app.navigation li {
	padding: 0 0 6px 0;
}
div.ui-widget.app.navigation li div.bullet,
div.ui-widget.app.navigation li div.bullet.expandable,
div.ui-widget.app.navigation li div.bullet.collapsible {
	width: 14px;
    height: 17px;
	background: none;
}
div.ui-widget.app.navigation li div.bullet.expandable,
div.ui-widget.app.navigation li div.bullet.collapsible {
	cursor: pointer;
}
div.ui-widget.app.navigation li div.bullet:before {
	content: "\e915";
    color: #E77819;
    font-size: 10px;
    position: relative;
    top: 5px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;    
}
div.ui-widget.app.navigation li a {
	width: calc(100% - 14px);
	font-size: 15px;
    font-weight: 600;
    color: #00275d;
    position: relative;
    display: inline-block;
}
div.ui-widget.app.navigation li a:after {
	content: "";
	height: 3px;
	width: 43px;
	position: absolute;
    bottom: -4px;
    left: 0;
	background-color: #E77819;
    opacity: 0;
    -webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;    
}
div.ui-widget.app.navigation li a:hover:after,
div.ui-widget.app.navigation li a:focus:after {
    opacity: 1;
}
div.ui-widget.app.navigation li ul {
	padding: 4px 0 0 23px;
}
div.ui-widget.app.navigation li ul li div.bullet {
	display: none;
}
div.ui-widget.app.navigation li ul li:last-child {
	padding: 0;
}
/* GroupEnd */
 
/* GroupBegin Channel Bar Styles */
nav {
	margin: 0 9px 11px 0;
}
.fixed-element nav {
	margin: 0 9px 0 0;
}
#sw-channel-list-container {
	width: auto;
}
ul.sw-channel-list li.sw-channel-item {
	height: 40px;
	margin: 0;
}
li.sw-channel-item > a {
	font: 600 18px "Source Sans Pro", Arial, snas-serif;
	color: #00275d;
	padding: 0 10px 0 0;
}
li.sw-channel-item > a span {
	display: block;
	padding: 7px 0 23px 11px;
}
li.sw-channel-item.hover > a,
li.sw-channel-item.active > a {
	color: #00275d;
}
#navc-HP {
    height: 37px;
}
#navc-HP > a {
    display: -ms-inline-flexbox;
    display: -webkit-inline-flex;
    display: inline-flex;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-align-content: center;
    -ms-flex-line-pack: center;
    align-content: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center; 
}
#navc-HP > a:before {
    content: "\e900";
    font-size: 15px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;   
}
.fixed-element #navc-HP > a:before {
	position: relative;
    top: -3px;
}
#navc-HP > a span {
    width: 0 !important;
    height: 0 !important;
    display: block !important;
    padding: 0 !important;
    margin: 0 !important;
    border: 0 !important;
    overflow: hidden !important;
}
/* GroupEnd */

/* GroupBegin Channel Bar Dropdown Styles */
ul.sw-channel-dropdown {
    background: rgba(255,255,255,0.9);
	border: none;
	font-size: 12px;
	font-weight: normal;
    width: auto;
    width: 561px;
    -webkit-column-break-inside: avoid;
    page-break-inside: avoid;
    break-inside: avoid;
    top: calc(100% + 10px);
    padding-bottom: 44px;
    -webkit-box-shadow: 0 4px 0 0 rgba(0,0,0,0.3);
    box-shadow: 0 4px 0 0 rgba(0,0,0,0.3);    
}
.cs-sub-list {
    display: -ms-flexbox !important;
    display: -webkit-flex !important;
    display: flex !important;
}
li.no-dropdown ul.sw-channel-dropdown {
	display: none !important;   
}
ul.sw-channel-list li.sw-channel-item ul.sw-channel-dropdown.edge {
	left: auto;
    right: 0;
}
ul.sw-channel-dropdown > ul {
	width: 100%;
    /*-webkit-column-count: 3;
    -moz-column-count: 3;
    column-count: 3; */   
}
ul.sw-channel-dropdown li {
	width: 187px;
}
.sw-channel-more-li {
	background: none;
}
ul.sw-channel-dropdown li a,
ul.sw-channel-dropdown li.sw-channel-more-li a {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
	font-weight: 600;
	background: none repeat scroll 0 0 transparent;
	color: #00275D;
    width: 100%;
	display: inline-block;
	padding: 11px 22px 6px 22px;
	text-decoration: none;
    -webkit-transition: all 0.25s linear;
    -moz-transition: all 0.25s linear;
    -ms-transition: all 0.25s linear;
    -o-transition: all 0.25s linear;
    transition: all 0.25s linear;    
}
ul.sw-channel-dropdown li a:hover,
ul.sw-channel-dropdown li.sw-channel-more-li a:hover {
	background: rgba(0,0,0,0.15);
	color: #00275D;
}
ul.sw-channel-dropdown li.sw-channel-more-li a span.sw-channel-more-span {
	color: #00275D;
}   
ul.sw-channel-dropdown li.sw-channel-more-li a:hover span.sw-channel-more-span {
	color: #00275D;
}        
/* GroupEnd */ 

/* GroupBegin Global Icons */
#gb-global-icons-outer {
	background: #1D1F22;
    padding: 0 41px 0 32px;
    overflow: hidden;
}
.sp #gb-global-icons-outer {
	background: #0C121E;
}
#gb-global-icons-outer:before {
    content: "";
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    right: calc(-50% - 741px);
    opacity: 0.3;
    background: #000;
}
.sp #gb-global-icons-outer:before {
    content: "";
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    opacity: 0.6;
    background: url(/cms/lib/MO49000025/Centricity/Template/18/gb-pattern.png);
}
#gb-global-icons {
	position: relative;
}
.sp #gb-global-icons {
	padding: 20px 0 56px 0;
}
#gb-global-icons-svg {
    min-height: 180px;
    position: absolute;
    bottom: 0;
    right: calc(50% - 746px);
}
.cs-global-icons {
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;    
	padding: 45px 0 53px 0;
    position: relative;
}
.cs-global-icons li {
	width: 14.285714285714286%;
}
.cs-global-icon {
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    width: 100%;
    height: 100%;
	min-height: 82px;
    position: relative;
    text-decoration: none;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;    
}
.cs-global-icon:before {
	content: "";
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
	opacity: 0.33;
	background: #AFD4E5;
	-webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;    
}
.cs-global-icon:hover:before,
.cs-global-icon:focus:before {
	opacity: 0.5;
}
.cs-global-icon .icon {
 	color: #000;
    font-size: 30px;
    position: relative;
	-webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;    
}
.cs-global-icon:hover .icon,
.cs-global-icon:focus .icon {
	color: #fff;
}
.cs-global-icon .text {
	color: #E6E2DF;
    font: 400 16px/1 "Source Sans Pro", Arial, sans-serif;
    padding-left: 13px;
    position: relative;    
}
.cs-global-icons li:nth-child(1),
.cs-global-icons li:nth-child(5) {
	border-left: 2px solid #009940;
}
.cs-global-icons li:nth-child(2),
.cs-global-icons li:nth-child(6) {
	border-left: 2px solid #92C1E9;
}
.cs-global-icons li:nth-child(3),
.cs-global-icons li:nth-child(7) {
	border-left: 2px solid #512D6D;
}
.cs-global-icons li:nth-child(4) {
	border-left: 2px solid #9D2235;
}
.cs-global-icons li:last-child {
	border-right: 2px solid #9D2235;
}
/* GroupEnd */

/* GroupBegin Social Media Icons */
#gb-social-media-icons {
	width: 58px;
	position: fixed;
    top: 320px;
    right: 0;
    z-index: 10;
}
#gb-social-media-icons li a {
    font-size: 50px;
	text-decoration: none;
    display: block;
    margin: 0;
    float: right;
    background-color: #00275D;
}
#gb-social-media-icons li a:hover,
#gb-social-media-icons li a:focus {
	padding-right: 6px;
}
.cs-dev-icon-district {
	width: 50px;
    height: 50px;
    background: url('/cms/lib/MO49000025/Centricity/Template/18/gb-district-home.png') no-repeat;
}
.cs-dev-icon-instagram {
    /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#ffb900+0,9100eb+100 */
    background: #ffb900; /* Old browsers */
    background: -moz-linear-gradient(45deg, #ffb900 0%, #9100eb 100%); /* FF3.6-15 */
    background: -webkit-linear-gradient(45deg, #ffb900 0%,#9100eb 100%); /* Chrome10-25,Safari5.1-6 */
    background: linear-gradient(45deg, #ffb900 0%,#9100eb 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ffb900', endColorstr='#9100eb',GradientType=1 ); /* IE6-9 fallback on horizontal gradient */
}
.cs-dev-icon-instagram .path1:before {
	color: transparent;
}
#gb-social-media-icons li a.cs-dev-icon-facebook {
	background-color: #3b5998;
}
#gb-social-media-icons li a.cs-dev-icon-twitter {
	background-color: #55acee;
}
#gb-social-media-icons li a.cs-dev-icon-instagram {
	background-color: #e95950;
}
#gb-social-media-icons li a.cs-dev-icon-youtube {
	background-color: #CA1D26;
}

#gb-social-media-icons li a.cs-dev-icon-google-plus {
	background-color: rgb(217, 80, 50);
}
#gb-social-media-icons li a.cs-dev-icon-cs-dev-icon-pinterest {
	background-color: rgb(189, 32, 38);
}
#gb-social-media-icons li a.cs-dev-icon-cs-dev-icon-vimeo {
	background-color: rgb(99, 180, 228);
}
#gb-social-media-icons li a.cs-dev-icon-cs-dev-icon-flickr {
	background-color: rgb(230, 230, 230);
}
#gb-social-media-icons li a.cs-dev-icon-cs-dev-icon-linkedin {
	background-color: rgb(0, 122, 185);
}
/* GroupEnd */

/* GroupBegin App Styles */
div.ui-widget.app div.ui-widget-header h1, div.ui-widget.app.navigation div.ui-widget-header h1, div.ui-widget.app.detail .ui-widget-header h1,
div.ui-widget.app div.ui-widget-header h4, div.ui-widget.app.navigation div.ui-widget-header h4, div.ui-widget.app.detail .ui-widget-header h4 {
	font: 400 24px/1 "Source Sans Pro", Arial, sans-serif;
	margin: 0;
}
.headlines .ui-article-thumb .img {
	margin: 0 27px 0 0;
}
h1.ui-article-title,
h4.ui-article-title,
.ui-article-title {
	font: 600 20px/1 "Source Sans Pro", Arial, sans-serif;
}
.ui-read-more {
    margin: 27px 0 5px 7px;
}
.ui-read-more .cs-dev-icons {
    font-size: 12px;
    color: #E77819;
    display: inline-block;
    position: relative;
    top: 2px;
    margin-left: 7px;
}
.ui-read-more .cs-dev-icons span {
    -webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;
}
.ui-read-more .cs-dev-icons .path2,
.ui-read-more:hover .cs-dev-icons .path1,
.ui-read-more:focus .cs-dev-icons .path1 {
	opacity: 1;
}
.ui-read-more .cs-dev-icons .path1,
.ui-read-more:hover .cs-dev-icons .path2,
.ui-read-more:focus .cs-dev-icons .path2 {
	opacity: 0;
}
a.more-link, .ui-return {
	display: inline-block;
	font: 700 14px/1 "Source Sans Pro", Arial, sans-serif;
	text-transform: uppercase;
	color: #00275d;
    padding: 0;
}
.more-link-under {
	display: none;
}
.ui-article-title a {
	font-size: 15px;
    color: #00275d;
}
.headlines .ui-article-description,
.announcements .ui-article-description {
	padding-top: 4px;
    font: 400 14px/1.5 'Merriweather', Times New Roman, serif;
}
.flexpage .ui-article-description {
    font: 400 14px/1.5 'Merriweather', Times New Roman, serif;
}

#calendar-pnl-buttons div.app-level-social-rss a.ui-btn-toolbar.rss, div.app-level-social-rss a.ui-btn-toolbar.rss {
	margin: 0;
}
.headlines div.app-level-social-rss a.ui-btn-toolbar.rss {
	margin-left: 7px;
}
.ui-btn-general-primary, .ui-btn-general, .ui-btn-toolbar, .ui-btn-toggle {
	line-height: 1;
}
#calendar-pnl-smcalendar {
	display: block;
}
#cal-event-detail-col1, #cal-event-detail-col2 {
	width: 100% !important;
	padding: 10px 0px 0px;
}
.cal-ed-header-title {
	width: auto;
}
#sw-content-layout-wrapper .region {
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}
.ui-column-one.region {
	width: auto;
	clear: both;
}
.ui-column-one-quarter.region {
	width: 25%;
	float: left;
}
.ui-column-one-half.region {
	width: 50%;
	float: left;
}
.ui-column-one-third.region {
	width: 33%;
	float: left;
}
.ui-column-two-thirds.region {
	width: 66%;
	float: left;
}
.region.right {
	float: right;
}
.region.clearleft {
	clear: left;
}

/* Homepage Apps **/
.hp-row.one div.ui-widget.app {
	padding: 66px 21px 0 12px;
}
.hp-row.one .region > div:last-child div.ui-widget.app {
	padding-bottom: 91px;
}
.hp-row.one div.ui-widget.app .ui-widget-header {
	color: #fff;
    text-align: center;
    padding-bottom: 20px;
}
.hp-row.one div.ui-widget.app ul.ui-articles {
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
}
.hp-row.one div.ui-widget.app ul.ui-articles li {
    -webkit-flex: 0 1 calc(25% - 1px);
    -ms-flex: 0 1 calc(25% - 1px);
    flex: 0 1 calc(25% - 1px);	
}
.hp-row.one div.ui-widget.app ul.ui-articles li:nth-child(4n+2) .ui-article {
	border-left: 2px solid #009940;
}
.hp-row.one div.ui-widget.app ul.ui-articles li:nth-child(4n+3) .ui-article {
	border-left: 2px solid #92C1E9;
}
.hp-row.one div.ui-widget.app ul.ui-articles li:nth-child(4n+4) .ui-article {
	border-left: 2px solid #512D6D;
}
.hp-row.one .headlines .ui-article-thumb .img {
	margin: 0;
}
.hp-row.one div.ui-widget.app .ui-article {
	position: relative;
    padding: 0;
}
.cs-article-info {
	width: 100%;
    height: 100%;
    padding: 0 11px 52px 11px;
    max-height: 275px;
	position: absolute;
    top: 0;
    left: 0;
	background: rgba(0,19,46,0.50 - Default);
    z-index: 1;
}
[data-headlines-opacity="50 - Default;100;90;80;70;60;50;40;30;20;10;0"] .cs-article-info,
[data-headlines-opacity="50 - Default"] .cs-article-info {
	background: rgba(0,19,46,0.5);
}
[data-headlines-opacity="100"] .cs-article-info {
	background: rgba(0,19,46,1);
}
.cs-article-info h1.ui-article-title a,
.cs-article-info h4.ui-article-title a,
.cs-article-info .ui-article-title a {
	font-size: 20px;
	color: #F3F3F3;
}
.cs-article-info .ui-article-description {
	font: 400 14px "Source Sans Pro", Arial, sans-serif;
    color: #F3F3F3;
    padding-top: 7px;
}
.hp-row.one .ui-article-thumb img {
	-webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s; 
}
.hp-row.one .cs-hover-effect img {
	-moz-transform: scale(1.2);
    -webkit-transform: scale(1.2);
    -o-transform: scale(1.2);
    -ms-transform: scale(1.2);
    transform: scale(1.2);
}
.hp-row.one a.more-link {
	color: #F3F3F3;
}
.hp-row.one .ui-read-more {
	text-align: right;
    margin: 38px 15px 0 0;
}
.hp-row.one .ui-read-more .cs-dev-icons {
    color: #f3f3f3;
}

.hp-row.two .region > div {
	padding: 25px 0 35px 0;
}
.hp-row.two .ui-widget.app {
	background: #fff;
    padding: 26px 30px 26px 30px;
}
.hp-row.two div.ui-widget.app .ui-widget-header {
	color: #00275D;
    position: relative;
    padding-bottom: 5px;
    margin-bottom: 18px;
    border-bottom: 1px solid #E77819; 
}
.hp-row.two div.ui-widget.app.upcomingevents .ui-widget-header {
    margin-bottom: 24px;
}
.hp-row.two div.ui-widget.app .ui-widget-header:after {
	content: "";
	width: 43px;
    height: 3px;
    background: #E77819;
    position: absolute;
    bottom: -3px;
    left: 0;
}
.hp-column.two .region:last-child .ui-widget.app {
	background: #ddd;
    padding: 30px 14px 19px 14px;
}
.hp-column.two .region:last-child div.ui-widget.app .ui-widget-header {
	color: #1D1F22;
    margin-bottom: 12px;
    border-bottom: 1px solid #1D1F22;
}
.hp-column.two .region:last-child div.ui-widget.app .ui-widget-header:after {
	display: none;
}
.hp-column.two .region:last-child div.ui-widget.app div.ui-widget-header h1,
.hp-column.two .region:last-child div.ui-widget.app.navigation div.ui-widget-header h1,
.hp-column.two .region:last-child div.ui-widget.app.detail .ui-widget-header h1,
.hp-column.two .region:last-child div.ui-widget.app div.ui-widget-header h4,
.hp-column.two .region:last-child div.ui-widget.app.navigation div.ui-widget-header h4,
.hp-column.two .region:last-child div.ui-widget.app.detail .ui-widget-header h4 {
    font: 700 16px/1.3 'Merriweather', Times New Roman, serif;
	font-style: italic;
}
.hp-column.two .ui-article {
	margin-bottom: 10px;
}
.hp-column.two .ui-articles li:last-child .ui-article {
	margin: 0;
}

/* Upcoming Events */
div.ui-article.upcoming-column-container {
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    padding-bottom: 37px;
}
.upcomingevents ul.ui-articles div.ui-article.upcoming-column-container:last-child {
    padding-bottom: 31px;
}
.upcoming-column.left .ui-article-title {
	height: 45px;
	width: 43px;
	background: #E77819;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;    
}
.upcoming-column.left h1.ui-article-title,
.upcoming-column.left h4.ui-article-title,
.upcoming-column.left .ui-article-title {
	font: 400 26px/1 "Source Sans Pro", Arial, sans-serif;
    color: #000;
    text-transform: uppercase;
}
.upcoming-column.left .joel-day {
	display: none;
}
.upcoming-column.left .joel-month {
	font-size: 13px;
    margin-bottom: -4px;
}
.upcoming-column.right {
	width: calc(100% - 43px);
    padding-left: 12px;
}
.upcomingevents .ui-article-description {
	margin: 4px 0 21px 0;
}
.upcomingevents p.ui-article-description:last-of-type {
	margin: 4px 0 0 0;
}
.upcomingevents .sw-calendar-block-time {
	font-size: 13px;
	display: block;
}
.upcomingevents .sw-calendar-block-title a {
	color: #1D1F22;
	font-size: 15px;
    font-weight: 600;
	display: block;    
}
.upcomingevents .sw-calendar-block-title a:hover,
.upcomingevents .sw-calendar-block-title a:focus {
	text-decoration: underline;
}
.view-calendar-link {
	color: #00275d;
    font-size:  14px;
	font-weight: 700;
    text-transform: uppercase;
    text-decoration: none;
    display: inline-block;
    margin: 5px 0 0 57px;
}
.view-calendar-link .cs-dev-icons {
    font-size: 12px;
    color: #E77819;
    display: inline-block;
    position: relative;
    top: 2px;
    margin-left: 7px;
}
.view-calendar-link .cs-dev-icons span {
    -webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;
}
.view-calendar-link .cs-dev-icons .path2,
.view-calendar-link:hover .cs-dev-icons .path1,
.view-calendar-link:focus .cs-dev-icons .path1 {
	opacity: 1;
}
.view-calendar-link .cs-dev-icons .path1,
.view-calendar-link:hover .cs-dev-icons .path2,
.view-calendar-link:focus .cs-dev-icons .path2 {
	opacity: 0;
}

/* Subpage Apps */
.sp-column.one div.ui-widget.app.navigation {
	padding: 32px 12px 23px 12px;
    background: #E4E4E4;
    -webkit-box-shadow: 0 4px 0 0 rgba(0,0,0,0.3);
    box-shadow: 0 4px 0 0 rgba(0,0,0,0.3);  
}
.sp-column.one div.ui-widget.app .ui-widget-header {
	color: #1D1F22;
    padding: 0;
    margin: 0;
    border: none;
}
.sp-column.one div.ui-widget.app .ui-widget-header:after {
	display: none;
}
.sp-column.one div.ui-widget.app.navigation div.ui-widget-header h1,
.sp-column.one div.ui-widget.app.navigation div.ui-widget-header h4 {
	display: inline-block;
    padding-right: 70px;
	font: 700 16px "Merriweather", serif, Times New Roman;
	font-style: italic;
    border-bottom: 1px solid #1D1F22;
    padding-bottom: 6px;
    margin-bottom: 13px;
}

.sp div.ui-widget.app .ui-widget-header {
	color: #00275D;
    position: relative;
    padding-bottom: 4px;
    margin-bottom: 18px;
    border-bottom: 1px solid #E77819; 
}
.sp div.ui-widget.app.upcomingevents .ui-widget-header {
    margin-bottom: 24px;
}
.sp div.ui-widget.app .ui-widget-header:after {
	content: "";
	width: 43px;
    height: 3px;
    background: #E77819;
    position: absolute;
    bottom: -3px;
    left: 0;
}
.sp .ui-sp div.ui-widget.app {
	padding: 27px 0 28px 12px;
}
.sp .ui-sp div.ui-widget.app.flexpage {
	padding-bottom: 18px;
}
.sp .ui-article {
	margin-bottom: 9px;
}
.sp .upcomingevents .ui-articles {
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;    
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;   
}
.sp .upcomingevents li {
	-webkit-flex: 0 1 21%;
    -ms-flex: 0 1 21%;
    flex: 0 1 21%;
}
.sp .joel-day {
	display: block;
}
/* GroupEnd */

/* GroupBegin Photo Area */
#sw-content-container10.ui-hp {
    margin-bottom: -38px;
}
#hp-slideshow-outer {
	overflow: hidden;
}
#hp-slideshow-outer:before {
	content: "";
    width: 100%;
    height: 4px;
    background: rgba(0,0,0,0.3);
    position: absolute;
    top: 0;
    left: 0;
    z-index: 10;
}
#hp-slideshow:before {
	content: "";
	height: 675px;
	width: 675px;
	background: url('/cms/lib/MO49000025/Centricity/Template/18/gb-slideshow-watermark.png') no-repeat;    
    position: absolute;
    top: 50px;
    right: 27px;
    z-index: 9;
}
#hp-slideshow[data-show-watermark="false"]:before {
	display: none;
}
#hp-slideshow .mmg-description-outer {
	width: 100%;
	position: absolute;
    bottom: 116px;
    left: 0;
    right: 0;
	max-width: 1240px;
	margin: 0 auto;
    z-index: 10;
}
#hp-slideshow .mmg-description {
	padding: 5px 51px 5px 0;
}
#hp-slideshow .mmg-description-inner {
	width: auto;
    max-width: 363px;
    display: inline-block;
	padding: 20px;
	background: rgba(0,0,0,0.65);
}
#hp-slideshow .mmg-description-title {
    color: #fff;
    font: 400 26px/1 "Source Sans Pro", Arial, sans-serif;
    margin: 0 0 8px 3px;
}
#hp-slideshow .mmg-description-title a {
	color: #fff;
    text-decoration: none;
}
#hp-slideshow .mmg-description-title a:hover,
#hp-slideshow .mmg-description-title a:focus {
	text-decoration: underline;
}
#hp-slideshow .mmg-description-caption {
    font: 400 15px/1.3 'Merriweather', Times New Roman, serif;
	color: #fff;
    margin: 0 0 0 2px;
}
#hp-slideshow .mmg-description-links {
	display: none;
}
#hp-slideshow .mmg-description-link {
	color: #fff;
    font: 700 14px/1 "Source Sans Pro", Arial, sans-serif;
    margin: 0 8px 0 0;
    text-transform: uppercase;
    text-decoration: none;
}
#hp-slideshow .mmg-description-link .cs-dev-icons {
    font-size: 12px;
    color: #f3f3f3;
    display: inline-block;
    position: relative;
    top: 1px;
    margin-left: 8px;
}
#hp-slideshow .mmg-description-link .cs-dev-icons span {
	display: inline-block;
    -webkit-transition: all 0.25s;
    -moz-transition: all 0.25s;
    -ms-transition: all 0.25s;
    -o-transition: all 0.25s;
    transition: all 0.25s;
}
#hp-slideshow .mmg-description-link .cs-dev-icons .path2 {
	opacity: 1;
}
#hp-slideshow .mmg-description-link:hover .cs-dev-icons .path1,
#hp-slideshow .mmg-description-link:focus .cs-dev-icons .path1 {
	font-size: 8px;
    position: relative;
    top: -2px;
	opacity: 1;
    -moz-transform: rotate(45deg);
    -webkit-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    transform: rotate(45deg);    
}
#hp-slideshow .mmg-description-link .cs-dev-icons .path1,
#hp-slideshow .mmg-description-link:hover .cs-dev-icons .path2,
#hp-slideshow .mmg-description-link:focus .cs-dev-icons .path2 {
	opacity: 0;
}
#hp-slideshow .mmg-controls-outer {
	padding: 16px 0 0 0;
}
#hp-slideshow .mmg-controls {
	padding: 22px 8px 0 8px;
}
#hp-slideshow .mmg-control.play-pause {
	position: relative;
    top: -1px;
    left: 0;
	height: 10px;
	width: 8px;
}
#hp-slideshow .mmg-control.play-pause span {
	height: 10px;
	width: 8px;
    display: block;
    color: #FFF;
    background: none;
    border-radius: 0;
}
#hp-slideshow .mmg-control.play-pause span:before {
	content: "\e914";
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
#hp-slideshow .mmg-control.play-pause span:before{
    font-size: 10px;
    top: 0;
    left: 0;
}
#hp-slideshow .mmg-control.play-pause span:after {
	content: "";
    top: -2px;
    left: 0;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 6px 0 6px 6px;
    border-color: transparent transparent transparent #f3f3f3;
}
#hp-slideshow .mmg-bullets-outer {
	padding-left: 11px;
}
#hp-slideshow .mmg-bullet {
    width: 7px;
    height: 7px;
    border: none;
    background: #E77819;
    border-radius: 50%;
    margin: 0 3px;
}
#hp-slideshow .mmg-bullet.active,
#hp-slideshow .mmg-bullet:hover,
#hp-slideshow .mmg-bullet:focus {
    background: #D7D7D7;
}

.ie11 #hp-slideshow .mmg-control.play-pause span {
	position: relative;
    -moz-transform: rotate(180deg);
    -webkit-transform: rotate(180deg);
    -o-transform: rotate(180deg);
    -ms-transform: rotate(180deg);
    transform: rotate(180deg);    
}
.ie11 #hp-slideshow .mmg-control.play-pause span:after {
    backface-visibility: visible;
}
.ie11 #hp-slideshow .mmg-control.play-pause.paused span:before, .ie11 #hp-slideshow .mmg-control.play-pause.playing span:after {
	opacity: 0;
}
.ie11 #hp-slideshow .mmg-control.play-pause.playing span:befor, .ie11 #hp-slideshow .mmg-control.play-pause.paused span:after {
	opacity: 1;
}

#gb-sitetagline-outer {
	background: #AFD4E5;
}
#gb-sitetagline p {
    font: 700 16px/1 'Merriweather', Times New Roman, serif;
	font-style: italic;
    text-align: center;
	margin: 0;
    padding: 10px 0 9px 0;
    color: #1d1f22;
}
#gb-sitetagline[data-text-color="White"] p {
	color: #fff;
}
#gb-sitetagline[data-text-color="Grey"] p {
	color: #333;
}
/* GroupEnd */

/* GroupBegin Streaming Video */
.cs-using-fullscreen-video #sw-content-container10.ui-hp {
    margin-bottom: -16px;
}
#cs-fullscreen-video-outer {
	z-index: -1;
}
.cs-fullscreen-video-buttons {
	position: relative;
    margin: 22px 8px 0 8px;
    height: 10px;
}
.cs-fullscreen-video-button {
    height: 10px;
    width: 8px;
    position: absolute;
    top: 0;
    left: 0;
}
.cs-fullscreen-video-button.pause-button:before {
    content: "\e914";
    font-size: 10px;
    color: #fff;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    position: absolute;
    top; 0;
    left: 0;
}
.cs-fullscreen-video-button.play-button:before {
	content: "";
    position: absolute;
    top; -2px
    left: 0;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 6px 0 6px 6px;
    border-color: transparent transparent transparent #f3f3f3;
}
.cs-fullscreen-video-buttons.video-playing .cs-fullscreen-video-button.play-button,
.cs-fullscreen-video-buttons.video-paused .cs-fullscreen-video-button.pause-button,
.cs-fullscreen-video-buttons .cs-fullscreen-video-button.mute-button,
.cs-fullscreen-video-buttons .cs-fullscreen-video-button.unmute-button,
.cs-fullscreen-video-control-text {
    display: none;
}
/* GroupEnd */

/* GroupBegin Homepage */
.hp-row.one {
    background: #00275D;
}
.hp-row.one:before {
	content: "";
    width: 100%;
    height: 100%;
    position: absolute;
    opacity: 0.8;
    background: url('/cms/lib/MO49000025/Centricity/Template/18/gb-pattern.png');    
}
.hp-row.two {
	z-index: 1;
	background: #000611 url('/cms/lib/MO49000025/Centricity/Template/18/gb-pattern.png');
}
.hp-row.two:before {
	background: #000611 url(/cms/lib/MO49000025/Centricity/Template/18/gb-pattern.png);
    content: '';
    display: block;
    height: 50%;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    z-index: -1;
    -webkit-backface-visibility: hidden;
    transform: skewY(2.4658deg);
    transform-origin: 100% 0;
}
.hp-column.one {
    -webkit-flex: 0 1 36%;
    -ms-flex: 0 1 36%;
    flex: 0 1 36%;
	padding-bottom: 68px;
}
.hp-column.one .region {
	padding: 0 30px 0 20px;
}
.hp-column.two {
    -webkit-flex: 0 1 64%;
    -ms-flex: 0 1 64%;
    flex: 0 1 64%;
	padding-bottom: 68px;    
}
.hp-column.two > div {
	padding-right: 20px;
}
.hp-column.two .region:first-child {
    -webkit-flex: 0 1 calc(76% - 20px);
    -ms-flex: 0 1 calc(76% - 20px);
    flex: 0 1 calc(76% - 20px);
    padding-right: 20px;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;  
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;    
}
.hp-column.two .region:last-child {
    -webkit-flex: 0 1 24%;
    -ms-flex: 0 1 24%;
    flex: 0 1 24%;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;    
}
.hp-column.two .region > div,
.hp-column.two .region > div > div,
.hp-column.two .region > div > div > div,
.hp-column.two .region > div > div .ui-widget.app {
    position: relative;
	/*flex: 1;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;*/
}
.hp-column.two .region:last-child div > div .ui-widget.app:before {
	content: "";
	position: absolute;
    bottom: 0;
    right: 0;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 0 0 109px 171px;
    border-color: transparent transparent rgba(136,136,136,0.15) transparent;
}
.hp-column.two .region:last-child div > div .ui-widget.app > div {
	position: relative;
}
/* GroupEnd */

/* GroupBegin Subpage */
#sp-content {
	padding-top: 20px;
    padding-bottom: 56px;
    min-height: 600px;
}
.sp-column.one {
    -webkit-flex: 0 1 325px;
    -ms-flex: 0 1 325px;
    flex: 0 1 325px; 
}
.sp-column.two {
    -webkit-flex: 0 1 calc(100% - 325px);
    -ms-flex: 0 1 calc(100% - 325px);
    flex: 0 1 calc(100% - 325px);
}
.ui-sp > div {
	position: relative;
}
.ui-sp > div:before {
	content: "";
    position: absolute;
    width: 197px;
    height: 197px;
    top: 0;
    left: 0;
	background: url('/cms/lib/MO49000025/Centricity/Template/18/sp-watermark.png');
}
#sw-content-layout-wrapper .region {
	position: relative;
}
.sp-column.two .ui-sp {
	padding: 0 0 0 37px;
    position: relative;
}
#sw-edit-page-button {
	float: none;
    margin: 0 auto 10px auto;
}
/* GroupEnd */

/* GroupBegin Subpage No Nav */
#spn-content {
	padding-top: 20px;
    padding-bottom: 56px;
	min-height: 600px;    
}
#swlogin {
    padding: 0;
    margin: 0;
}
.cse .gsc-control-cse, .gsc-control-cse {
    background: none;
    border: none;
    padding: 0px;
}
/* GroupEnd */

/* GroupBegin Subpage Breadcrumbs */
ul.ui-breadcrumbs {
	margin: 0; 
    padding: 0;
}
ul.ui-breadcrumbs > li {
	margin: 0;
}
ul.ui-breadcrumbs > li:after {
	content: "";
	height: 7px;
	width: 7px;
	background-color: #000;
    -webkit-border-radius: 7px;
    border-radius: 7px;
    display: inline-block;
    margin: 0 10px;
}
ul.ui-breadcrumbs > li:last-child:after {
	display: none;
}
ul.ui-breadcrumbs > li {
	color: #000;
	font-family: "Open Sans";
	font-size: 11px;
	font-weight: bold;
    text-transform: uppercase;
}
ul.ui-breadcrumbs > li > a {
	color: #000;
    text-decoration: none;
    background: none;
    padding: 0;
}
/* GroupEnd */ 

/* GroupBegin Footer */
footer {
	background: #26292E;
  	position: relative; 
    z-index: 1;
}
footer:before {
    background: inherit;
    content: '';
    display: block;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    z-index: -1;
    -webkit-backface-visibility: hidden;
    transform: skewY(2.465deg);
    transform-origin: 100% 0;
}
#gb-footer-outer {
	padding: 0 99px;
}
#gb-footer {
	top: -11px;
}
#gb-footer:before {
	content: "";
	height: 252px;
	width: 252px;
    position: absolute;
    top: -3px;
    left: 0;
    background: url('/cms/lib/MO49000025/Centricity/Template/18/gb-footer-watermark.png') no-repeat;
}
.gb-footer {
	position: relative;
}
.gb-footer h2 {
	font: 600 30px/1 'Crimson Text', Times New Roman, serif;
    color: #fff;
}
.gb-footer h3 {
	font: 400 18px "Source Sans Pro", Arial, sans-serif;
    text-transform: uppercase;
    color: #fff;
}
.gb-footer p {
	font: 400 14px "Source Sans Pro", Arial, sans-serif;
	color: #fff;
	margin: 0;
	padding: 0;
}
.gb-footer p .acc-hidden {
	display: none !important;
}
.gb-footer a {
	font: 400 14px "Source Sans Pro", Arial, sans-serif;
	color: #F3F3F3;
    text-decoration: none;
}
.gb-phone[data-phone=""], .gb-fax[data-fax=""] {
	display: none;
}
.cs-spacer {
	padding: 0 10px;
}
.gb-footer-row.two {
	position: relative;
	padding: 26px 0;
}
.gb-footer-info {
	padding: 1px 44px 0 22px;
}
.gb-footer.one {
	padding-top: 100px;
	-webkit-flex: 0 0 252px;
    -ms-flex: 0 0 252px;
    flex: 0 0 252px;
}
.gb-footer.two {
    padding: 80px 0 0 78px;
	-webkit-flex: 0 1 50%;
    -ms-flex: 0 1 50%;
    flex: 0 1 50%;
}
.gb-footer.three {
    padding-top: 80px;
	-webkit-flex: 0 1 50%;
    -ms-flex: 0 1 50%;
    flex: 0 1 50%;
}
.gb-footer.three ul {
    -webkit-column-count: 2;
    -moz-column-count: 2;
    column-count: 2;
}
.gb-footer.three li {
    display: inline-block;
	padding: 0 25px 7px 0;
}
.gb-footer.three a {
	text-transform: uppercase;
}
.gb-footer.three a:hover,
.gb-footer.three a:focus {
	text-decoration: underline;
}
.gb-footer.four {
	padding: 80px 0 0 10px;
	-webkit-flex: 0 0 200px;
    -ms-flex: 0 0 200px;
    flex: 0 0 200px;
}
.gb-footer-watermark:first-child {
	margin-right: 44px;
}
.gb-footer-watermark a {
	display: block;
	text-decoration: none;
    position: relative;
}
.gb-footer-watermark-0 a {
    height: 52px;
    width: 100px;
}
.gb-footer-watermark-0 a .gb-footer-watermark-image-1,
.gb-footer-watermark-0 a .gb-footer-watermark-image-2 {
    height: 52px;
    width: 100px;
    position: absolute;
    top: 0;
    left: 0;
}
.gb-footer-watermark-0 a .gb-footer-watermark-image-1 {
	opacity: 1;
    background: url('/cms/lib/MO49000025/Centricity/Template/18/gb-watermark-01.png') no-repeat;
}
.gb-footer-watermark-0 a .gb-footer-watermark-image-2 {
	opacity: 0;
	background: url('/cms/lib/MO49000025/Centricity/Template/18/gb-watermark-01-hover.png') no-repeat;
}
.gb-footer-watermark-0 a:hover .gb-footer-watermark-image-1,
.gb-footer-watermark-0 a:focus .gb-footer-watermark-image-1 {
	opacity: 0;
}
.gb-footer-watermark-0 a:hover .gb-footer-watermark-image-2,
.gb-footer-watermark-0 a:focus .gb-footer-watermark-image-2 {
	opacity: 1;
}
.gb-footer-watermark-1 a {
	height: 70px;
	width: 57px;
    position: relative;
    top: -2px;
}
.gb-footer-watermark-1 a .gb-footer-watermark-image-1,
.gb-footer-watermark-1 a .gb-footer-watermark-image-2 {
	height: 70px;
	width: 57px;
    position: absolute;
    top: 0;
    left: 0;
}
.gb-footer-watermark-1 a .gb-footer-watermark-image-1 {
	opacity: 1;
    background: url('/cms/lib/MO49000025/Centricity/Template/18/gb-watermark-02.png') no-repeat;
}
.gb-footer-watermark-1 a .gb-footer-watermark-image-2 {
	opacity: 0;
	background: url('/cms/lib/MO49000025/Centricity/Template/18/gb-watermark-02-hover.png') no-repeat;
}
.gb-footer-watermark-1 a:hover .gb-footer-watermark-image-1,
.gb-footer-watermark-1 a:focus .gb-footer-watermark-image-1 {
	opacity: 0;
}
.gb-footer-watermark-1 a:hover .gb-footer-watermark-image-2,
.gb-footer-watermark-1 a:focus .gb-footer-watermark-image-2 {
	opacity: 1;
}
#cs-back-to-top {
	cursor: pointer;
	height: 69px;
	width: 79px;
	background: #AFD4E5;
    position: absolute;
    bottom: 0;
    right: 0;
}
#cs-back-to-top .cs-dev-icons {
	font-size: 25px;
    display: block;
    -moz-transform: rotate(180deg);
    -webkit-transform: rotate(180deg);
    -o-transform: rotate(180deg);
    -ms-transform: rotate(180deg);
    transform: rotate(180deg);    
}
/* GroupEnd */ 

/* GroupBegin Legal Footer */
#gb-legal-footer-outer {
	background: #000;
}
#gb-legal-footer-links-copyright {
	margin: 3px 0px;
}
.gb-legal-logo {
	margin: 0 11px 0 0;
}
.gb-legal-footer.links ul {
	list-style: none;
    margin: 0px;
    padding: 0px;
}
.gb-legal-footer.links ul li {
	display: inline-block;
    line-height: 1;
    color: #FFF;
}
.gb-legal-footer.links ul li:before {
	content: "•";
    display: inline-block;
    color: #FFF;
    line-height: 6px;
    font-size: 10px;
    position: relative;
    top: -1px;
    margin: 0 5px;
}
.gb-legal-footer.links ul li:first-child:before {
	display: none;
}
.gb-legal-footer.links a {
	font-family: Arial, sans-serif;
	font-size: 10px;
    color: #FFF;
    line-height: 1;
    letter-spacing: -.2px;
    text-decoration: none;
}
.gb-legal-footer.links a:hover {
    text-decoration: underline;
}
.gb-legal-footer.copyright {
	font-family: Arial, sans-serif;
	font-size: 10px;
    color: #FFF;
    line-height: 1;
    text-decoration: none;
    font-style: italic;
    margin: 2px 0 0 0;    
}
#sw-footer-outer {
	display: none;
}
/* GroupEnd */ 

/* GroupBegin Standard Styles */
body, .ui-article-detail {
	font: 400 16px "Source Sans Pro", Arial, sans-serif;
	color: #1D1F22;
}
.ui-article-detail {
	line-height: 1.5;
}
.ui-article p {
	margin: 0 0 10px 0;
}
.ui-article p:last-of-type {
	margin: 0;
}
h1, li h1 {
	font-family: 'Merriweather', Times New Roman, serif;
	font-size: 20px;
	font-weight: bold;
	margin: 0;
	padding: 0;
    line-height: 1.2;
}
h2 {
	font-family: "Source Sans Pro", Arial, sans-serif;
	font-size: 16px;
	font-weight: bold;
	margin: 0;
	padding: 0;
    line-height: 1.2;
}
h3 {
	font-family: 'Merriweather', Times New Roman, serif;
	font-size: 16px;
	font-weight: normal;
	margin: 0;
	padding: 0;
    line-height: 1.2;
}
h4 {
	font-family: "Source Sans Pro", Arial, sans-serif;
	font-size: 14px;
	font-weight: bold;
    margin: 0;
	padding: 0;
    line-height: 1.2;
}
h5 {
	font-family: "Source Sans Pro", Arial, sans-serif;
	font-size: 12px;
	font-weight: bold;
	margin: 0;
	padding: 0;
    line-height: 1.2;
}
h6 {
	font-family: "Source Sans Pro", Arial, sans-serif;
	font-size: 12px;
	font-weight: boldl;
	font-style: italic;
	margin: 0;
	padding: 0;
    line-height: 1.2;
}    
/* GroupEnd */

/* GroupBegin EditorStyles */
.H1_Template {
	font-family: 'Merriweather', Times New Roman, serif;
	font-size: 20px;
	font-weight: bold;
	margin: 0;
	padding: 0;
    line-height: 1.2;
}
.H2_Template {
	font-family: "Source Sans Pro", Arial, sans-serif;
	font-size: 16px;
	font-weight: bold;
	margin: 0;
	padding: 0;
    line-height: 1.2;
}
.H3_Template {
	font-family: 'Merriweather', Times New Roman, serif;
	font-size: 16px;
	font-weight: bold;
	margin: 0;
	padding: 0;
    line-height: 1.2;
}
.H4_Template {
	font-family: "Source Sans Pro", Arial, sans-serif;
	font-size: 14px;
	font-weight: bold;
	margin: 0;
	padding: 0;
    line-height: 1.2;
}   
/* GroupEnd */

/* GroupBegin Windows Adjustments */
.Win32 #gb-sitename .gb-sitename-one {
	margin-bottom: -3px;
}
.Win32 .cs-mystart-dropdown,
.Win32 .cs-mystart-item,
.Win32 a#ui-btn-mypasskey {
	font-weight: 700;
}
.ie11 .hp-column.two .region > div,
.ie11 .hp-column.two .region > div > div,
.ie11 .hp-column.two .region > div > div > div,
.ie11 .hp-column.two .region > div > div .ui-widget.app {
	flex: 1 1 0;
    width: 100%;
    height: 100%;
    display: block;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}
.ie11 .sp-column.one {
	min-width: 325px;
}
/* GroupEnd */

/* GroupBegin 1024 Breakpoint */
@media (max-width: 1319px) {
    .cs-global-icon {
        min-height: 105px;
        -webkit-flex-direction: column;
        -ms-flex-direction: column;
        flex-direction: column;
    }
    .cs-global-icon .text {
        font-size: 14px;
        padding: 15px 0 0 0;
    }
    #gb-footer-outer {
        padding: 0 25px 0 20px;
    }
    .gb-footer.two {
        padding: 80px 25px 0 10px;
    }
    .gb-footer-row.two {
    	display: block;
    }
    #gb-legal-footer {
    	margin-top: 10px;
    	padding-left: 22px;
    }
}
/* GroupEnd *//* MediaEnd *//* MediaBegin 768+ */ @media (max-width: 1023px) {/* GroupBegin Mystart */
#ui-mypasskey-overlay {
	top: 73px !important;
}
/* GroupEnd */ 
 
/* GroupBegin Global */
body:before {
	content: "768";
}
.show768 {
	display: block;
}
.hide768 {
	display: none;
}
#ui-mypasskey-overlay {
    top: 166px !important;
}
/* GroupEnd */

/* GroupBegin Header */
#gb-header-outer {
	padding: 0;
}
#gb-header {
	-webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
}
#gb-header-left {
	min-height: 0;
  	-webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
	background: #D7D7D7;
    padding: 9px 20px;
    flex: 0 1 100%;
}
#gb-header-right {
	min-height: 0;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;    
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;    
    flex: 0 1 100%;
}
/* GroupEnd */

/* GroupBegin Responsive Menu */
#rs-menu-btn {
	float: none;
    margin-left: 28px;
    padding-top: 9px;
}
#rs-menu-btn:before {
    content: "\e918";
    background: none;
	font-size: 18px;
    position: relative;
    top: 2px;
    padding: 0;
	color: #00275D;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;    
}
#rs-menu-btn span {
	color: #00275D;
	font-size: 18px;
	font-weight: 600;
}
/* GroupEnd */

/* GroupBegin Global Icons */
.sp #gb-tab-links-outer {
	margin-right: -20px;
}
#gb-global-icons-outer {
	padding: 0 20px;
}
#gb-global-icons-outer:before {
	display: none;
}
.sp #gb-global-icons {
	padding: 0;
}
/* GroupEnd */

/* GroupBegin App Styles */
#calendar-pnl-calendarcontainer {
	min-width: 0px;
}
#calendar-pnl-smcalendar {
	display: none;
}
#sw-content-layout3 #sw-content-container1,
#sw-content-layout8 #sw-content-container2,
#sw-content-layout9 #sw-content-container2,
#sw-content-layout10 #sw-content-container3 {
	padding-right: 0px; /* TOTAL GUTTER WIDTH / 2 */
}
#sw-content-layout3 #sw-content-container3,
#sw-content-layout8 #sw-content-container4,
#sw-content-layout9 #sw-content-container4,
#sw-content-layout10 #sw-content-container2 {
	padding-left: 0px; /* SHOULD BE 0px */
    padding-right: 0px; /* TOTAL GUTTER WIDTH / 2 */
}
#sw-content-layout3 #sw-content-container2,
#sw-content-layout8 #sw-content-container3,
#sw-content-layout9 #sw-content-container3,
#sw-content-layout10 #sw-content-container4 {
	padding-left: 0px; /* TOTAL GUTTER WIDTH / 2 */
    padding-right: 0px; /* SHOULD BE 0px */
}
#sw-content-layout10 #sw-content-container1 {
	padding-right: 0px; /* SHOULD BE 0px */
}
.ui-column-one-quarter.region {
	width: 50%;
	float: left;
	clear: left;
}
.ui-column-one-third.region {
	width: 50%;
	float: left;
}
.ui-column-two-thirds.region {
	width: 50%;
	float: left;
}
.region.right {
	float: left;
}
.region.clearleft {
	clear: none;
}

.hp-row.one .ui-read-more {
	text-align: center;
}

/* Homepage Apps */
.hp-row .ui-widget-header,
.sp-column.one .ui-widget-header {
	position: relative;
}
.hp-row .ui-widget-header:before,
.sp-column.one .ui-widget-header:before {
  	content: "\e919";
    color: #fff;
    font-size: 23px;
    display: block;
    position: absolute;
    top: calc(50% - 12.5px);
    right: 40.5px;
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
	-webkit-transition: all 0.25s;
	-moz-transition: all 0.25s;
	-ms-transition: all 0.25s;
	-o-transition: all 0.25s;
	transition: all 0.25s;    
}
.hp-row .ui-widget-header:after,
.hp-row.two div.ui-widget.app .ui-widget-header:after,
.hp-column.two .region:last-child div.ui-widget.app .ui-widget-header:after,
.sp-column.one div.ui-widget.app .ui-widget-header:after {
  	content: "\e919";
    color: #fff;
    font-size: 23px;
    display: block;
    position: absolute;
    top: calc(50% - 12.5px);
    right: 39px;
    background: none;
    left: auto;
    bottom: auto;
    width: auto;
    height: auto;
    -moz-transform: rotate(90deg);
    -webkit-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    transform: rotate(90deg);    
    font-family: 'cs-dev-icons' !important;
    speak: none;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;    
}
.hp-row .open .ui-widget-header:before,
.sp-column.one .open .ui-widget-header:before {
    -moz-transform: rotate(90deg);
    -webkit-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    transform: rotate(90deg);
}
.hp-row .ui-widget-header > *,
.sp-column.one .ui-widget-header > * {
	position: relative; 
}
.sp-column.one {
	margin-bottom: 20px;
}
.sp-column.one .ui-widget-header:before {
	right: 1px;
    color: #1D1F22;
}
.sp-column.one div.ui-widget.app .ui-widget-header:after {
	right: 0;
    color: #1D1F22;
}
.sp-column.one div.ui-widget.app.navigation {
	box-shadow: none;
}

.hp-row.one div.ui-widget.app,
.hp-row.one .region > div:last-child div.ui-widget.app {
	padding: 0;
}
.hp-row.one div.ui-widget.app .ui-widget-header {
	background: #071131 url('/cms/lib/MO49000025/Centricity/Template/18/gb-pattern.png');
    padding: 18px 84px 19px 82px;
}
.hp-row.one div.ui-widget.app .ui-widget-detail {
	padding: 24px 84px 0 82px;
}
.hp-row.one div.ui-widget.app ul.ui-articles li {
	-webkit-flex: 0 1 50%;
    -ms-flex: 0 1 50%;
    flex: 0 1 50%;
    margin-bottom: 31px;
}
.hp-row.one div.ui-widget.app ul.ui-articles li:nth-child(4n+2) .ui-article,
.hp-row.one div.ui-widget.app ul.ui-articles li:nth-child(4n+3) .ui-article,
.hp-row.one div.ui-widget.app ul.ui-articles li:nth-child(4n+4) .ui-article {
	border: none;
}
.hp-row.one div.ui-widget.app .ui-widget-footer {
	padding: 0 84px 0 82px;
}

.hp-column.one .region,
.hp-row.two .region > div {
	padding: 0;
}
.hp-row.two .ui-widget.app {
    background: none;
    padding: 0;
}
.hp-row.two div.ui-widget.app .ui-widget-header {
	border: none;
    text-align: center;
    color: #fff;
	background: #071131 url('/cms/lib/MO49000025/Centricity/Template/18/gb-pattern.png');
    margin: 0;
    padding: 18px 84px 19px 82px;  
}
.hp-row.two div.ui-widget.app.upcomingevents .ui-widget-header {
	margin: 0;
    padding: 18px 84px 19px 82px;
}
.hp-column.two .region:last-child div > div .ui-widget.app:before {
	display: none;
}
.hp-row.two div.ui-widget.app .ui-widget-detail {
	padding: 51px 20px 20px 20px;
    background: #fff;
}
.hp-row.two div.ui-widget.app .ui-widget-footer {
	padding: 5px 20px;
    background: #fff;
    -webkit-box-shadow: 0 4px 0 0 rgba(0,0,0,0.3);
    box-shadow: 0 4px 0 0 rgba(0,0,0,0.3);        
}

.hp-column.two > div {
	padding: 0;
    display: block;
}
.hp-column.two .region:last-child .ui-widget.app {
	background: none;
    padding: 0 0 19px 0;
}
.hp-column.two .region:last-child div.ui-widget.app .ui-widget-header {
    color: #fff;
    margin: 0;
    padding: 18px 84px 19px 82px;    
    border: none;
	background: #071131 url('/cms/lib/MO49000025/Centricity/Template/18/gb-pattern.png');    
}
.hp-column.two .region:last-child div.ui-widget.app div.ui-widget-header h1,
.hp-column.two .region:last-child div.ui-widget.app.navigation div.ui-widget-header h1,
.hp-column.two .region:last-child div.ui-widget.app.detail .ui-widget-header h1,
.hp-column.two .region:last-child div.ui-widget.app div.ui-widget-header h4,
.hp-column.two .region:last-child div.ui-widget.app.navigation div.ui-widget-header h4,
.hp-column.two .region:last-child div.ui-widget.app.detail .ui-widget-header h4 {
    font: 400 24px/1 "Source Sans Pro", Arial, sans-serif;
}

.hp-row.two .hp-column.two div.ui-widget.app .ui-widget-detail,
.hp-row.two .hp-column.two div.ui-widget.app .ui-widget-footer {
    margin: 0 20px;
}

.hp-row .ui-widget.app {
	margin-bottom: 60px;
}
.hp-row .ui-widget.app.last-app {
	margin: 0;
}

.hp-row .upcomingevents .ui-articles {
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
}
.hp-row .upcomingevents li {
    -webkit-flex: 0 1 33%;
    -ms-flex: 0 1 33%;
    flex: 0 1 33%;
}
.hp-row .view-calendar-link {
	margin: 5px 0 35px 0;
}

.hp-row .navigation .site-shortcuts {
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
}   
.hp-row .navigation .site-shortcuts > li {
    -webkit-flex: 0 1 50%;
    -ms-flex: 0 1 50%;
    flex: 0 1 50%;
}
/* GroupEnd */

/* GroupBegin Photo Area */
#sw-content-container10.ui-hp {
	margin: 0;
}
#hp-slideshow:before {
	display: none;
}
#hp-slideshow .mmg-description-outer {
	bottom: 0;
}
#hp-slideshow .mmg-description-inner {
	padding: 20px 20px 5px 20px;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
    max-width: none;
}
#hp-slideshow .mmg-description {
	width: 80%;
    padding: 5px 0;
}
#hp-slideshow .mmg-controls-outer {
	width: 20%;
    padding: 0 0 0 10px;    
}
#hp-slideshow .mmg-mobile-links {
	text-align: right;
}
#hp-slideshow .mmg-controls {
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;  
}
/* GroupEnd */

/* GroupBegin Homepage */
#hp-content {
	position: relative;
    background: #00275D;
}
#hp-content:before {
    content: '';
    background: url(/cms/lib/MO49000025/Centricity/Template/18/gb-pattern.png);
    display: block;
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    opacity: 0.8;
}
.hp-row.two {
    background: transparent;
}
.hp-row.two:before {
	display: none;
}
.hp-row.two .gb-section {
	display: block;
}
.hp-column.one,
.hp-column.two {
	padding: 0;
}
.hp-column.two .region:first-child,
.hp-column.two .region:last-child {
	padding: 0;
    flex: auto;
    display: block;
}
/* GroupEnd */

/* GroupBegin Subpage */
#sp-content {
	display: block
}
.sp-column.two .ui-sp {
	padding-left: 0;
}
/* GroupEnd */

/* GroupBegin Channel Bar Dropdown Styles */
ul.sw-channel-list li.sw-channel-item:last-child ul.sw-channel-dropdown {
	left: auto;
	right: 0px;
}
/* GroupEnd */

/* GroupBegin Footer */
footer:before {
    transform: none;
}
#gb-footer-outer {
	padding: 0;
}
#gb-footer {
	top: 0;
}
#gb-footer:before {
	top: 107px;
    left: 82px;
}
.gb-footer h3 {
    padding: 31px 0 0 0;
}
.gb-footer.two {
	padding: 0;
}
.gb-footer-row.one {
	padding: 107px 80px 0 80px;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
}
.gb-footer-row.one .gb-footer-info {
	padding: 0 12px 66px 0;
    -webkit-flex: 0 1 100%;
    -ms-flex: 0 1 100%;
    flex: 0 1 100%;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;    
}
.gb-footer.two,
.gb-footer.three {
	padding: 0;
    -webkit-flex: 0 1 50%;
    -ms-flex: 0 1 50%;
    flex: 0 1 50%;	
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;  
}
.gb-footer.one {
	padding: 12px 11px 0;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
	height: 200px;
}
.gb-footer.two {
    -webkit-flex: 0 1 calc(50% - 22px);
    -ms-flex: 0 1 calc(50% - 22px);
	flex: 0 1 calc(50% - 22px);
}
.gb-footer.four {
	padding: 0;
    -webkit-flex: 0 1 47%;
    -ms-flex: 0 1 47%;
    flex: 0 1 47%	  
}
.gb-footer-row.two {
	padding: 34px 0 13px 0;
}
#cs-back-to-top {
	right: 12px;
}
/* GroupEnd */

/* GroupBegin Legal Footer */
#gb-legal-footer {
    height: auto;
    margin-top: 0;
    padding: 18px 0 13px 25px;
}
/* GroupEnd */} /* MediaEnd *//* MediaBegin 640+ */ @media (max-width: 767px) {/* GroupBegin Mystart */
#rs-menu-btn {
	margin-left: 11px;
}
#gb-search-form {
	width: auto;
    max-width: 350px;
}
/* GroupEnd */ 
 
/* GroupBegin Global */
body:before {
	content: "640";
}
.show640 {
	display: block;
}
.hide640 {
	display: none;
}
div#ui-mypasskey-overlay {
    top: 167px !important;
}
#gb-schoolwires-footer-outer {
	padding-left: 0px;
    padding-right: 0px;
}
/* GroupEnd */

/* GroupBegin App Styles */
#sw-content-layout2 #sw-content-container1,
#sw-content-layout2 #sw-content-container2,
#sw-content-layout3 #sw-content-container1,
#sw-content-layout3 #sw-content-container2,
#sw-content-layout3 #sw-content-container3,
#sw-content-layout4 #sw-content-container1,
#sw-content-layout4 #sw-content-container2,
#sw-content-layout6 #sw-content-container2,
#sw-content-layout6 #sw-content-container3,
#sw-content-layout7 #sw-content-container2,
#sw-content-layout7 #sw-content-container3,
#sw-content-layout8 #sw-content-container2,
#sw-content-layout8 #sw-content-container3,
#sw-content-layout8 #sw-content-container4,
#sw-content-layout9 #sw-content-container2,
#sw-content-layout9 #sw-content-container3,
#sw-content-layout9 #sw-content-container4,
#sw-content-layout10 #sw-content-container1
#sw-content-layout10 #sw-content-container2,
#sw-content-layout10 #sw-content-container3,
#sw-content-layout10 #sw-content-container4 {
	padding-left: 0px;
    padding-right: 0px;
}
.ui-spn .ui-column-one-third {
    width: auto !important;
    float: none !important;
}
.ui-column-one.region {
	width: auto;
	clear: none;
}
.ui-column-one-quarter.region {
	width: auto;
	float: none;
}
.ui-column-one-half.region {
	width: auto;
	float: none;
}
.ui-column-one-third.region {
	width: auto;
	float: none;
}
.ui-column-two-thirds.region {
	width: auto;
	float: none;
}
.region.right {
	float: none;
}
input.ui-txt-general.medium, textarea.ui-txt-general.medium, input.ui-txt-heading.medium {
	width: 80%;
}

.hp-row.one div.ui-widget.app ul.ui-articles {
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
}

.hp-row .upcomingevents li {
    -webkit-flex: 0 1 45%;
    -ms-flex: 0 1 45%;
    flex: 0 1 45%;
}

.hp-row.two div.ui-widget.app .ui-widget-detail {
	padding: 51px 20px 20px 20px;
    background: #fff;
}

.hp-row .view-calendar-link {
	margin-bottom: 13px;
}

.sp .upcomingevents li {
    -webkit-flex: 0 1 47%;
    -ms-flex: 0 1 47%;
    flex: 0 1 47%;
}
/* GroupEnd */

/* GroupBegin Photo Area */
#hp-slideshow .mmg-description-inner {
	padding-top: 10px;
    padding-bottom: 10px;
}
#hp-slideshow .mmg-description-link {
	margin: 0 0 0 8px;
}
#hp-slideshow .mmg-controls {
	padding-right: 0;
    padding-bottom: 10px;
}
/* GroupEnd */

/* GroupBegin Homepage */
#hp-content {
	padding-top: 57px;
}
/* GroupEnd */
 
/* GroupBegin Footer */
#gb-footer:before {
    left: 36px;
}
.gb-footer-row.one {
	padding: 107px 36px 0 36px;
}
.gb-footer-row.one .gb-footer-info {
	padding-right: 0;
}
.gb-footer h3 {
    padding: 35px 0 0 0;
}
.cs-spacer {
    padding: 0 7px;
}
.gb-footer.one {
	padding: 18px 0px 0;
}
.gb-footer.two {
	padding-left: 15px;
}
.gb-footer.three {
	padding-left: 24px;
    -webkit-flex: 0 1 60%;
    -ms-flex: 0 1 60%;
    flex: 0 1 60%;
}
.gb-footer.three li {
    padding-right: 55px;
}
.gb-footer.three li:nth-child(n+3) {
	padding-right: 0;
}
.gb-footer.four {
    -webkit-flex: 0 1 40%;
    -ms-flex: 0 1 40%;
    flex: 0 1 40%;
}
.gb-footer.four {
	padding-right: 24px;
}
/* GroupEnd */ 

/* GroupBegin Legal Footer */
#gb-legal-footer {
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
}
.gb-legal-footer.links ul li:last-child {
	display: block;
}
.gb-legal-footer.links ul li:last-child:before {
	display: none;
}
/* GroupEnd */} /* MediaEnd *//* MediaBegin 480+ */ @media (max-width: 639px) {/* GroupBegin Mystart */
#rs-menu-btn {
	margin-left: 11px;
    padding: 15px 0;
}
/* GroupEnd */ 
 
/* GroupBegin Global */
body:before {
	content: "480";
}
.show480 {
	display: block;
}
.hide480 {
	display: none;
}
.sw-mystart-button,
.sw-mystart-button a {
	height: 53px;
    margin: 0;
}
.gb-schoolwires-footer.links ul li:last-child:before {
	display: none;
}
.gb-schoolwires-footer.links ul li:last-child {
	display: block;
    margin-top: 4px;
}
/* GroupEnd */

/* GroupBegin Header */
#gb-header-left {
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
}
#gb-logo img {
    max-width: 84%;
}
/* GroupEnd */

/* GroupBegin App Styles */
#calendar-pnl-buttons-top {
    width: auto;
    text-align: left;
}
#calendar-pnl-dateselect {
	float: left;
	clear: both;
}
#calendar-pnl-title {
	width: auto;	
}
#cal-event-detail-header h1 {
	margin: 0px;
}

.hp-row.one div.ui-widget.app .ui-widget-header,
.hp-row.one div.ui-widget.app .ui-widget-detail,
.hp-row.one div.ui-widget.app .ui-widget-footer,
.hp-row.two div.ui-widget.app.upcomingevents .ui-widget-header,
.hp-column.two .region:last-child div.ui-widget.app .ui-widget-header {
	padding-left: 20px;
    padding-right: 20px;
}

.hp-row.one div.ui-widget.app ul.ui-articles {
	display: block;
    text-align: center;
}
.hp-row.one div.ui-widget.app ul.ui-articles li {
	display: inline-block;
}
.cs-article-info {
    width: calc(100% - 10px);
}

.hp-row .upcomingevents .ui-articles {
	display: block;
}

.sp .upcomingevents li {
    -webkit-flex: 0 1 41%;
    -ms-flex: 0 1 41%;
    flex: 0 1 41%;
}
/* GroupEnd */

/* GroupBegin Photo Area */
#hp-slideshow .mmg-description-title {
	font-size: 20px;
    margin-left: 0;
}
#hp-slideshow .mmg-description-caption {
	font-size: 12px;
}
/* GroupEnd */
 
/* GroupBegin Footer */
#gb-footer:before {
	top: 43px;
    left: 20px;
    height: 220px;
    width: 220px;
    background-size: cover;
}
#gb-footer-mystart {
	padding-top: 12px;
 	-webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
}
#gb-footer-mystart .cs-mystart-item,
#gb-footer-mystart .cs-mystart-dropdown {
	margin-bottom: 5px;
}
.gb-footer-row.one {
    padding: 43px 0 0 0;
}
.gb-footer.one {
    height: 169px;
}
.gb-footer h2 {
    padding: 15px 0 0 18px;
	font-size: 26px;
}
.gb-footer h3 {
	font-size: 15px;
}
.gb-footer-row.one .gb-footer-info {
	padding: 0 45px 0 45px;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;    
}
.gb-footer p,
.gb-footer a {
	font-size: 13px;
}
.gb-phone .cs-spacer {
	display: none;
}
.gb-footer.two {
	padding: 0;
}
.gb-footer.three ul {
    -webkit-column-count: 1;
    -moz-column-count: 1;
    column-count: 1;
}
.gb-footer.three {
    -webkit-flex: 0 1 40%;
    -ms-flex: 0 1 40%;
    flex: 0 1 40%;
	padding: 68px 0 0 57px;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
}
.gb-footer.four {
	padding: 92px 57px 0 0;
    -webkit-flex: 0 1 60%;
    -ms-flex: 0 1 60%;
    flex: 0 1 60%;
}
.gb-footer-watermark:first-child {
    margin-right: 45px;
}
/* GroupEnd */ 

/* GroupBegin Footer */
#cs-back-to-top {
	width: 100%;
    height: 52px;
	position: static;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
}
#cs-back-to-top span:first-child {
	color: #1D1F22;
	font-size: 9px;
	font-weight: 700;
}
/* GroupEnd */} /* MediaEnd *//* MediaBegin 320+ */ @media (max-width: 479px) {/* GroupBegin Mystart */
#ui-mypasskey-overlay {
	left: 0px !important;
	width: 320px !important;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}
#sw-passkey-container {
	height: 263px;
	max-height: 263px;
	width: 300px !important;
}

#gb-logo {
	margin: 0;
}
/* GroupEnd */ 
 
/* GroupBegin Global */
body:before {
	content: "320";
}
.show320 {
	display: block;
}
.hide320 {
	display: none;
}
#gb-schoolwires-footer {
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
}
.gb-schoolwires-footer.logo {
    margin: 0px 11px 2px 5px;
}
#gb-schoolwires-footer-links-copyright {
	text-align: center;
}
/* GroupEnd */

/* GroupBegin App Styles */
.hp-row .ui-widget-header:before {
	right: 20px;
}
.hp-row .ui-widget-header:after,
.hp-row.two div.ui-widget.app .ui-widget-header:after,
.hp-column.two .region:last-child div.ui-widget.app .ui-widget-header:after {
	right: 19px;
}
html:not(.ios) .cs-article-info {
	width: 100%;
}
.hp-row .navigation .site-shortcuts {
	display: block;
}
.hp-row.two .hp-column.two div.ui-widget.app .ui-widget-detail {
	padding-top: 20px;
}

.sp .upcomingevents .ui-articles {
	display: block;
}
/* GroupEnd */

/* GroupBegin Photo Area */
#hp-slideshow .mmg-description-outer {
	background: #1D1F22;
	position: static;  
}
#hp-slideshow .mmg-description {
	width: 100%;
}
#hp-slideshow .mmg-description-inner {
	display: block;
   	padding-top: 22px;
    padding-bottom: 32px;
    background: rgba(0,0,0,0.2);
}
#hp-slideshow .mmg-controls-outer {
	width: 100%;
	padding: 15px 0 0 0;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap; 
}
#hp-slideshow .mmg-mobile-links {
    text-align: left; 
}
#hp-slideshow .mmg-controls {
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
    padding: 2px 0 0 26px;
}
#hp-slideshow .mmg-description-link {
	margin: 0;
}
/* GroupEnd */

/* GroupBegin Footer */
#gb-footer:before {
	left: calc(50% - 110px);
}
.cs-spacer {
    padding: 0 5px;
}
.gb-footer.one {
    height: 145px;
    -webkit-flex: 0 1 100%;
    -ms-flex: 0 1 100%;
    flex: 0 1 100%;
}
.gb-footer.two {
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-flex: 0 1 100%;
    -ms-flex: 0 1 100%;
    flex: 0 1 100%;
}
.gb-footer h3 {
	padding: 0;
}
.gb-footer-row.one .gb-footer-info {
	padding: 0 20px;
    display: block;    
}
.gb-footer-row.one .gb-footer-info p {
    text-align: center;
    margin-top: 20px;
}
.gb-footer p, .gb-footer a {
    font-size: 11px;
}
.gb-footer.three {
    -webkit-flex: 0 1 50%;
    -ms-flex: 0 1 50%;
    flex: 0 1 50%;
    padding: 38px 0 0 43px;
}
.gb-footer.three a {
	font-size: 11px;
}
.gb-footer.three li,
.gb-footer.three li:nth-child(n+3) {
	padding: 0;
}
.gb-footer.three li:nth-child(3) {
	margin-bottom: 20px;
}
.gb-footer.four {
    -webkit-flex: 0 1 50%;
    -ms-flex: 0 1 50%;
    flex: 0 1 50%;
    padding: 38px 43px 0 0;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;    
}
.gb-footer-watermark:first-child {
	margin: 0 0 25px 0;
}
/* GroupEnd */

/* GroupBegin Legal Footer */
#gb-legal-footer {
	padding: 15px 0;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;    
}
#gb-legal-footer-left {
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
    -webkit-align-content: flex-start;
    -ms-flex-line-pack: start;
    align-content: flex-start;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
}
.gb-legal-logo {
	margin: 0 0 5px 0;
}
.gb-legal-footer.links {
	width: 100%;
    margin; 0;
}
.gb-legal-footer.links ul li:last-child {
    width: 72%;
    margin: 0 auto;
}
.gb-legal-footer.links ul {
	text-align: center;
}
/* GroupEnd */} /* MediaEnd */</style>
    <style>
.NKCSchools .gb-footer h2 { display: none; } /* Jim 03979003 */
</style>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-125523535-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-125523535-1');
</script>
<link rel='shortcut icon' href='https://www.nkcschools.org/cms/lib/MO49000025/Centricity/Domain/4/favicon.ico'><!-- Meta Tags -->
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="format-detection" content="telephone=no" />

<!-- Link Tags -->
<link href="https://fonts.googleapis.com/css?family=Crimson+Text:400,600,700|Merriweather:300,400,700,700i,900|Source+Sans+Pro:200,300,400,600,700,900" rel="stylesheet">
<link rel="stylesheet" type="text/css" href="//extend.schoolwires.com/creative/scripts/creative/tools/creative-icons-v4/css/creativeIcons.v4.min.css" />
<link type="text/css" rel="stylesheet" href="//extend.schoolwires.com/creative/scripts/creative/global/css/cs.global.min.css" />

<!-- Script Tags -->
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/accessibility/creative.accessible.navigation.app.min.js"></script>
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/global/js/cs.global.min.js"></script>
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/responsive/creative-app-accordion/creative.app.accordion.min.js"></script>
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/responsive/creative-responsive-menu-v3/creative.responsive.menu.v3.min.js"></script>
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/rotate/multimedia-gallery/default/cs.multimedia.gallery.default.min.js"></script>
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/tools/creative-icons-v4/creativeIcons.v4.min.js"></script>
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/tools/streaming-video/cs.fullscreen.video.min.js"></script>
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/tools/head.min.js"></script>
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/tools/creative-translate/creative.translate.min.js"></script>
<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/joel/mod-events/joel.mod-events.min.js"></script>
<script type="text/javascript" src="/cms/lib/MO49000025/Centricity/Template/18//scripts/jquery.ba-resize.min.js"></script>

<!-- Main Script -->
<script type="text/javascript">
    $(function() {
    	CreativeTemplate.Init();
    });
    
    var CreativeTemplate = {
    	// PROPERTIES
        "KeyCodes": { "tab": 9, "enter": 13, "esc": 27, "space": 32, "end": 35, "home": 36, "left": 37, "up": 38, "right": 39, "down": 40 },
        "IsMyViewPage": false, // UPDATES IN SetTemplateProps METHOD
        "HeaderIsSticky": false,
        
        // METHODS
        "Init": function() {
            // FOR SCOPE
            var _this = this;
			
            this.SetTemplateProps();
            this.JsMediaQueries();
            this.Header();
            this.MyStart();
            this.ChannelBar();
            this.Body();
            this.UpcomingEvents();
            this.Footer();
            this.Slideshow();
            this.StreamingVideo();
            this.RsMenu();
            this.AppAccordion();
            this.Search();
            
            csGlobalJs.OpenInNewWindowWarning();
 
            $(window).load(function(){ _this.WindowLoad(); });
            $(window).resize(function(){ _this.WindowResize(); });
            $(window).scroll(function() { _this.WindowScroll(); });
        },
        
        "SetTemplateProps": function() {
        	// MYVIEW PAGE CHECK
            if($("#pw-body").length) this.IsMyViewPage = true;
        },

        "WindowLoad": function() {
            // MAKE NAVIGATION APPS ACCESSIBLE
            $(".ui-widget.app.navigation").csAccessibleNavigationApp();
            
            this.StickyHeader();
            this.AnimateScrollButton();
            
             $(".hp-column.two .region:last-child .app:eq(0)").height($(".hp-column.two .region:first-child .app:eq(0)").height()+3);
        },

        "WindowResize": function() {
            this.JsMediaQueries();
            this.StickyHeader();
            this.AnimateScrollButton();
        },
        
        "WindowScroll": function() {
            this.StickyHeader();
            this.AnimateScrollButton();
        },
        
        "JsMediaQueries": function() {
            switch(this.GetBreakPoint()) {
                case "desktop": 
                   
                break;
                case "768":
                case "640":
                case "480":
                case "320":
                    
                break;
            }
        },

		"StickyHeader": function() {
			if(!this.IsMyViewPage) {
                switch(this.GetBreakPoint()) {
                    case "desktop":
                        var navOffSet = $("header").outerHeight();
                        if ($(window).scrollTop() <= navOffSet) {
                            if(this.HeaderIsSticky) {
                                $("header").removeClass("fixed-element").removeAttr("style");
                                $("#gb-page").css("padding-top", 0);

                                this.HeaderIsSticky = false;
                            }
                            
                            if($(".sp").length && $(".ui-widget.app.calendar").length) {
                                $(".wcm-controls").css("margin-top", "0px");
                            }
                        } else {
                            $("header").css("height", $("#gb-header-outer").outerHeight(true));
                            $("#gb-page").css("padding-top", $("#gb-header-outer").outerHeight(true));

                            if(!this.HeaderIsSticky) {
                                $("header").addClass("fixed-element");

                                this.HeaderIsSticky = true;
                            }
                            
                            if($(".sp").length && $(".ui-widget.app.calendar").length) {
                            	if($(".wcm-controls").hasClass("wcm-stuck")) {
                                	$(".wcm-controls").css("margin-top", $("#gb-header-outer").outerHeight(true));
                                }
                            }
                        }
                        
                        $("#sw-maincontent").css({
                            "display": "block",
                            "position": "relative",
                            "top": "-" + $("nav").outerHeight(true) + "px"
                        });
                        
                        $(".hp-column.two .region:last-child .app:eq(0)").height($(".hp-column.two .region:first-child .app:eq(0)").height()+3);
                        
                        $(".hp-column.two .region:last-child .app:eq(0)").children().resize(function(){
                            $(".hp-column.two .region:last-child .app:eq(0)").height("auto");
                            $(".hp-column.two .region:last-child .app:eq(0)").height(function(){
                              	$(this).height($(".hp-column.two .region:first-child .app:eq(0)").height()+3);
                            });
                        });
                    break;
                    case "768": case "640": case "480": case "320":
                        if(this.HeaderIsSticky) {
                            $("header").removeClass("fixed-element").removeAttr("style");
                            $("#gb-page").css("padding-top", 0);

                            this.HeaderIsSticky = false;
                        }
                                                
                        if($(".sp").length && $(".ui-widget.app.calendar").length) {
                            $(".wcm-controls").css("margin-top", "0px");
                        }
                        $("#sw-maincontent").removeAttr("style");
                        
                        $(".hp-column.two .region:last-child .app:eq(0)").height("auto");
                    break;
                }
            }
        },
        
        "AnimateScrollButton": function() {
			if(!this.IsMyViewPage) {
                switch(this.GetBreakPoint()) {
                    case "desktop":
                    	var scrollHeight = $(document).height();
                        var scrollPosition = $(window).height() + $(window).scrollTop();
                        
                        if((scrollHeight - scrollPosition) <= 90) {
                            $("#cs-back-to-top").fadeIn(500);
                        } else {
                        	$("#cs-back-to-top").fadeOut(500);
                        }
                    break;
                    case "768": case "640": case "480": case "320":
                        $("#cs-back-to-top").show();
                    break;
                }
            }
        },

        "MyStart": function() {
       	 	// ADD USER OPTIONS
            var userOptionsItems = "";
            
            
            	if($("#ui-btn-signin").length) {                    
                	userOptionsItems += '<div class="cs-mystart-item find-us">' + $("#ui-btn-signin").html() + '</div>';
                }
                
                if($("#ui-btn-register").length) {
                	userOptionsItems += '<div class="cs-mystart-item find-us">' + $("#ui-btn-register").html() + "</div>";
                }
                
                $("#gb-footer-mystart .cs-mystart-item:eq(0)").after(userOptionsItems);
            
            
            $("#sw-mystart-mypasskey").insertBefore($(".search"));
            
            // REMOVE TAB INDEXES FROM SYSTEM <a> TAGS
            $("#cs-user-options-list a").removeAttr("tabindex");
        
        	// ADD SCHOOLS
            $("#cs-schools-list .cs-dropdown-list").html($(".sw-mystart-dropdown.schoollist .sw-dropdown-list").html());
            
        	// ADD TRANSLATE
          	$(".cs-mystart-dropdown.translate .cs-dropdown").creativeTranslate({
                "type": 2,
            	"advancedOptions": {
                    "addMethod": "append"
                },
                "translateLoaded": function() {
                    $(".cs-mystart-dropdown.translate .cs-dropdown #google_translate_element").wrap('<ul class="cs-dropdown-list cs-html-list-reset"></ul>');
                }
            });

            this.MyStartDropdownActions({
            	"dropdownParent": ".cs-mystart-dropdown",
                "dropdownSelector": ".cs-selector",
                "dropdown": ".cs-dropdown",
                "dropdownList": ".cs-dropdown-list",
                "openDrowpdownList" : ".cs-mystart-dropdown.open"
            });
        },
        
        "MyStartDropdownActions": function(params) {
        	// FOR SCOPE
            var template = this;

            var dropdownParent = params.dropdownParent;
            var dropdownSelector = params.dropdownSelector;
            var dropdown = params.dropdown;
            var dropdownList = params.dropdownList;
            
            $(dropdownParent + " " + dropdownList + " a").attr("tabindex", "-1");
            
            // MYSTART DROPDOWN SELECTOR CLICK EVENT
            $(document).on("click", dropdownSelector, function(e) {
                e.preventDefault();
                
                if($(this).parent().hasClass("open")){
                	$("+ " + dropdownList + " a").attr("tabindex", "-1");
                    $(this).attr("aria-expanded", "false").parent().removeClass("open").find(dropdown).attr("aria-hidden", "true").slideUp(300, "swing"); 
                } else {
                	$(this).attr("aria-expanded", "true").parent().addClass("open").find(dropdown).attr("aria-hidden","false").slideDown(300, "swing");
                }
        	});
            
            // MYSTART DROPDOWN SELECTOR KEYDOWN EVENTS
            $(document).on("keydown", dropdownSelector, function(e) {
                // CAPTURE KEY CODE
                switch(e.keyCode) {
                    // CONSUME LEFT AND UP ARROWS
                    case template.KeyCodes.enter:
                    case template.KeyCodes.space:
                        e.preventDefault();

                        // IF THE DROPDOWN IS OPEN, CLOSE IT
                        if($(dropdownParent).hasClass("open")){
                        	$("+ " + dropdown + " " + dropdownList + " a").attr("tabindex", "-1");
                            $(this).attr("aria-expanded", "false").parent().removeClass("open").find(dropdown).attr("aria-hidden", "true").slideUp(300, "swing"); 
                        } else {
                        	$(this).attr("aria-expanded", "true").parent().addClass("open").find(dropdown).attr("aria-hidden", "false").slideDown(300, "swing", function(){
                            	if($(dropdownList + " .goog-te-combo", this).length) {
                                	$(dropdownList + " .goog-te-combo", this).focus();
                                } else {
                                	$(dropdownList + " li:first-child a", this).attr("tabindex", "0").focus();
                                }
                            });
                        }
                    break;

                    // CONSUME TAB KEY
                    case template.KeyCodes.tab:
                        $("+ " + dropdown + " " + dropdownList + " a").attr("tabindex", "-1");
                        $(this).attr("aria-expanded", "false").parent().removeClass("open").find(dropdown).attr("aria-hidden", "true").slideUp(300, "swing");
                    break;

                    // CONSUME LEFT AND UP ARROWS
                    case template.KeyCodes.down:
                    case template.KeyCodes.right:
                        e.preventDefault();
						
                        $("+ " + dropdown + " " + dropdownList + " a").attr("tabindex", "-1");
                        $("+ " + dropdown + " " + dropdownList + " li:first-child > a", this).attr("tabindex", "0").focus();
                    break;
                }
            });
			
            // MYSTART DROPDOWN LINK KEYDOWN EVENTS
            $(document).on("keydown", dropdownList + " li a", function(e) {
                // CAPTURE KEY CODE
                switch(e.keyCode) {
                    // CONSUME LEFT AND UP ARROWS
                    case template.KeyCodes.left:
                    case template.KeyCodes.up:
                        e.preventDefault();

                        // IS FIRST ITEM
                        if($(this).parent().is(":first-child")) {
                            // FOCUS DROPDOWN BUTTON
                            $(this).closest(dropdownList).find("a").attr("tabindex", "-1");
                            $(this).closest(dropdownParent).find(dropdownSelector).focus();
                        } else {
                            // FOCUS PREVIOUS ITEM
                            $(this).closest(dropdownList).find("a").attr("tabindex", "-1");
                            $(this).parent().prev("li").find("> a").attr("tabindex", "0").focus();
                        }
                    break;

                    // CONSUME RIGHT AND DOWN ARROWS
                    case template.KeyCodes.right:
                    case template.KeyCodes.down:
                        e.preventDefault();

                        // IS LAST ITEM
                        if($(this).parent().is(":last-child")) {
                            // FOCUS FIRST ITEM
                            $(this).closest(dropdownList).find("a").attr("tabindex", "-1");
                            $(this).closest(dropdownList).find("li:first-child > a").attr("tabindex", "0").focus();
                        } else {
                            // FOCUS NEXT ITEM
                            $(this).closest(dropdownList).find("a").attr("tabindex", "-1");
                            $(this).parent().next("li").find("> a").attr("tabindex", "0").focus();
                        }
                    break;
                    
                    // CONSUME TAB KEY
                    case template.KeyCodes.tab:
                    	if(e.shiftKey) {
                        	e.preventDefault();
                            
                        	// FOCUS DROPDOWN BUTTON
                            $(this).closest(dropdownList).find("a").attr("tabindex", "-1");
                            $(this).closest(dropdownParent).find(dropdownSelector).focus();
                        }
                    break;

                    // CONSUME HOME KEY
                    case template.KeyCodes.home:
                        e.preventDefault();

                        // FOCUS FIRST ITEM
                        $(this).closest(dropdownList).find("a").attr("tabindex", "-1");
                        $(this).closest(dropdownList).find("li:first-child > a").attr("tabindex", "0").focus();
                    break;

                    // CONSUME END KEY
                    case template.KeyCodes.end:
                        e.preventDefault();

                        // FOCUS LAST ITEM
                        $(this).closest(dropdownList).find("a").attr("tabindex", "-1");
                        $(this).closest(dropdownList).find("li:last-child > a").attr("tabindex", "0").focus();
                    break;
                    
                    // CONSUME ESC KEY
                    case template.KeyCodes.esc:
                    	e.preventDefault();
                    
                    	// CLOSE MENU
                    	$(this).closest(dropdownList).find("a").attr("tabindex", "-1");
                        $(this).parents(dropdownParent).find(dropdownSelector).focus().attr("aria-expanded", "false").parent().removeClass("open").find(dropdown).attr("aria-hidden", "true").slideUp(300, "swing"); 
					break;
                }
            });
            
            $(dropdownParent).mouseleave(function() {
				$(dropdownList + " a", this).attr("tabindex", "-1");
				$(dropdownSelector, this).attr("aria-expanded", "false").parent().removeClass("open").find(dropdown).attr("aria-hidden", "true").slideUp(300, "swing"); 
            }).focusout(function() {
                var thisDropdown = this;
                
                setTimeout(function () {
                    if(!$(thisDropdown).find(":focus").length) {
                        $(dropdownSelector, thisDropdown).attr("aria-expanded", "false").parent().removeClass("open").find(dropdown).attr("aria-hidden", "true").slideUp(300, "swing");
                    }
                }, 500);
            });
        },


        "Header": function() {
            // ADD LOGO
            var showLogo = true;
            var logoSrc = $.trim("/cms/lib/MO49000025/Centricity/Template/GlobalAssets/images///Logo/DistrictHeader2.png");

            if(showLogo) {
            	var srcCheck = logoSrc.indexOf("Faces/default-man.jpg") > -1;
                
                if((logoSrc != "") && (!srcCheck)) {
                    $("#gb-logo").append('<a href="/NKCSchools"><img src="' + logoSrc + '" alt="North Kansas City Schools logo" /></a>');
                } else {
                    $("#gb-logo").append('<a href="/NKCSchools"><img src="/cms/lib/MO49000025/Centricity/Template/18/gb-logo.png" alt="North Kansas City Schools logo" /></a>');
                }
            }

            // ADD SITENAME
            var siteNameOne = $.trim("NKC Schools");
            var siteNameTwo = $.trim("Champions For All Students");
            if((siteNameOne == "") && (siteNameTwo == "")) {
                var splitLen = 2;
                var siteName = "North Kansas City Schools";
                siteName = siteName.split(" ");
                var siteNameLength = siteName.length;
                if(siteNameLength > 2){
                    siteNameEnd = $.trim(siteName.splice(-splitLen, siteName.length).toString().replace(/,/g, " "));
                } else {
                    siteNameEnd = $.trim(siteName.splice(-1, siteName.length).toString().replace(/,/g, " "));
                }
                siteNameBegin = $.trim(siteName.toString().replace(/,/g, " "));
                $("#gb-sitename").prepend("<h1><span class='gb-sitename-one'>" + siteNameBegin + "</span><span class='gb-sitename-two'>" + siteNameEnd + "</span></h1>");
            } else if((siteNameOne != "") && (siteNameTwo == "")) {
                $("#gb-sitename").prepend("<h1><span class='gb-sitename-one'>" + siteNameOne + "</span></h1>");
            } else if((siteNameOne == "") && (siteNameTwo != "")) {
                $("#gb-sitename").prepend("<h1><span class='gb-sitename-two'>" + siteNameTwo + "</span></h1>");
            } else if((siteNameOne != "") && (siteNameTwo != "")) {
                $("#gb-sitename").prepend("<h1><span class='gb-sitename-one'>" + siteNameOne + "</span><span class='gb-sitename-two'>" + siteNameTwo + "</span></h1>");
            }
            
            var linkBank = [
                {
                    "show": true,
                    "text": "For Students",
                    "url": "/Page/4095"
                },
                {
                    "show": true,
                    "text": "For Staff",
                    "url": "/domain/2974"
                },
                {
                    "show": true,
                    "text": "For Community",
                    "url": "/page/197"
                },
                {
                    "show": true,
                    "text": "Questions-Comments-Kudos",
                    "url": "https://www.k12insight.com/Lets-Talk/embed.aspx?k=WF7R4NLT"
                }
            ];

            var links = '';
            $.each(linkBank, function(index, link) {
                if(link.show) {
                    links += '<li><a class="gb-tab-link gb-tab-link-' + index + ' flex flex-items-center flex-justify-center transition-all" href="' + link.url + '"><span>' + link.text + '</span></a></li>';
                }
            });

            if(links.length) {
                $("#gb-tab-links").html('<ul class="cs-html-list-reset flex">' + links + '</ul>');
            }
        },

        "ChannelBar": function() {
        	$(".hidden-sections").remove();
        
            $(".sw-channel-item").unbind('hover');
            $(".sw-channel-item").hover(function(){
                $(".sw-channel-item ul").stop(true, true);
                var subList = $(this).children('ul');
                if ($.trim(subList.html()) !== "") {
                    subList.slideDown(300, "swing");
                }
                $(this).addClass("hover");
            }, function(){
                $(".sw-channel-dropdown").slideUp(300, "swing");
                $(this).removeClass("hover");
            });
            
            $(".sw-channel-item").each(function(){
            	$(".sw-channel-dropdown", this).wrapInner('<ul class="cs-sub-list cs-html-list-reset" />');
            
            	if($(".sw-channel-dropdown li", this).length == 0) {
                	$(this).addClass("no-dropdown");
                }
            });
            
            $(".sw-channel-item").on('mouseenter mouseleave', function (e) {
                if ($('.sw-channel-dropdown', this).length) {
                    var elm = $('.sw-channel-dropdown', this);
                    var off = elm.offset();
                    var l = off.left;
                    var w = elm.width();
                    var docH = $("header").height();
                    var docW = $("header").width();

                    var isEntirelyVisible = (l + w <= docW);

                    if (!isEntirelyVisible) {
                        $('.sw-channel-dropdown', this).addClass('edge');
                    } else {
                        $('.sw-channel-dropdown', this).removeClass('edge');
                    }
                }
            });
            
            var num_cols = 3,
            container = $(".cs-sub-list"),
            listItem = 'li',
            listClass = 'cs-html-list-reset';
            container.each(function() {
                var items_per_col = new Array(),
                items = $(this).find(listItem),
                min_items_per_col = Math.floor(items.length / num_cols),
                difference = items.length - (min_items_per_col * num_cols);
                for (var i = 0; i < num_cols; i++) {
                    if (i < difference) {
                        items_per_col[i] = min_items_per_col + 1;
                    } else {
                        items_per_col[i] = min_items_per_col;
                    }
                }
                for (var i = 0; i < num_cols; i++) {
                    $(this).append($('<ul ></ul>').addClass(listClass));
                    for (var j = 0; j < items_per_col[i]; j++) {
                        var pointer = 0;
                        for (var k = 0; k < i; k++) {
                            pointer += items_per_col[k];
                        }
                        $(this).find('.' + listClass).last().append(items[j + pointer]);
                    }
                }
            });
            
            $(".sw-channel-item > a").on('focus', function (e) {
                if ($(this).siblings('.sw-channel-dropdown').length) {
                    var elm = $(this).siblings('.sw-channel-dropdown');
                    var off = elm.offset();
                    var l = off.left;
                    var w = elm.width();
                    var docH = $("header").height();
                    var docW = $("header").width();

                    var isEntirelyVisible = (l + w <= docW);

                    if (!isEntirelyVisible) {
                        $(this).parent().find(".sw-channel-dropdown").addClass('edge');
                    } else {
                        $(this).parent().find(".sw-channel-dropdown").removeClass('edge');
                    }
                }
            });
        },

        "Body": function() {
        	$("body").addClass(navigator.platform);
        
            // FOR SCOPE
            var _this = this;         
        
            // GLOBAL ICONS
            $("#gb-global-icons").creativeIcons({
                "iconNum"       : "7",
                "defaultIconSrc": "",
                "icons"         : [
                    {
                        "image": "Student Program/19.png",
                        "showText": true,
                        "text": "Transportation",
                        "url": "Domain/153",
                        "target": "_self"
                        
                    },
                    {
                        "image": "Education Portal/6.png",
                        "showText": true,
                        "text": "PowerSchool",
                        "url": "https://powerschool.nkcschools.org/public/",
                        "target": "_blank"
                    },
                    {
                        "image": "Education Portal/8.png",
                        "showText": true,
                        "text": "Canvas",
                        "url": "http://canvas.nkcschools.org",
                        "target": "_blank"
                    },
                    {
                        "image": "Communication/66.png",
                        "showText": true,
                        "text": "Board Docs",
                        "url": "https://www.boarddocs.com/mo/nkcsd/Board.nsf/Public",
                        "target": "_blank"
                    },
                    {
                        "image": "Student Program/40.png",
                        "showText": true,
                        "text": "Menus",
                        "url": "http://www.schoolnutritionandfitness.com/index.php?sid=0306152235285801&page=menus",
                        "target": "_blank"
                    },
                    {
                        "image": "Student Program/66.png",
                        "showText": true,
                        "text": "Webstore",
                        "url": "domain/6098",
                        "target": "_self"
                    },
                    {
                        "image": "Communication/64.png",
                        "showText": true,
                        "text": "Contact Us",
                        "url": "domain/76",
                        "target": "_self"
                    }
                ],
                "siteID"        : "4",
                "siteAlias"     : "NKCSchools",
                "calendarLink"  : "/Page/2",
                "contactEmail"  : "communications@nkcschools.org ",
                "allLoaded"     : function(){ }
            });
            
            var socialIcons = [
                {
                    "show": true,
                    "label": "District",
                    "class": "district",
                    "url": "/page/1"
                },
                {
                    "show": true,
                    "label": "Facebook",
                    "class": "facebook",
                    "url": "https://www.facebook.com/NKCSchools/"
                },
                {
                    "show": true,
                    "label": "Twitter",
                    "class": "twitter",
                    "url": "https://twitter.com/NKCSchools"
                },
                {
                    "show": true,
                    "label": "Instagram",
                    "class": "instagram",
                    "url": "https://www.instagram.com/nkcschools/"
                },
                {
                    "show": true,
                    "label": "YouTube",
                    "class": "youtube",
                    "url": "https://www.youtube.com/user/NKCSchools"
                },
                {
                    "show": false,
                    "label": "Google+",
                    "class": "google-plus",
                    "url": "#"
                },
                {
                    "show": false,
                    "label": "Pinterest",
                    "class": "pinterest",
                    "url": "#"
                },
                {
                    "show": false,
                    "label": "Vimeo",
                    "class": "vimeo",
                    "url": "#"
                },
                {
                    "show": false,
                    "label": "Flickr",
                    "class": "flickr",
                    "url": "#"
                },
                {
                    "show": false,
                    "label": "LinkedIn",
                    "class": "linkedin",
                    "url": "#"
                }
            ];

            var icons = '';
            $.each(socialIcons, function(index, icon) {
                if(icon.show) {
                    icons += '<li class="ui-clear"><a class="gb-social-media-icon cs-dev-icons cs-dev-icon-' + icon.class + ' transition-all" href="' + icon.url + '" aria-label="' + icon.label + '"><span class="path1"></span><span class="path2"></span><span class="path3"></span><span class="path4"></span></a></li>';
                }
            });

            if(icons.length) {
                $("#gb-social-media-icons").html('<ul class="cs-html-list-reset">' + icons + '</ul>');
            }
            
            // ADD TAGLINE
            var siteTagline = $.trim('Ensuring all are life-ready and ethically grounded in an ever-changing world through innovative educational experiences.');
            
            if(siteTagline != "") {
                $("#gb-sitetagline").prepend("<p>" + siteTagline + "</p>");
            }
        
            // AUTO FOCUS SIGN IN FIELD
            $("#swsignin-txt-username").focus();

            // CENTER SIGNED OUT MESSAGE AND SIGNIN BUTTON
            if($("div.ui-spn > div > p > span").text() == "You have been signed out."){
                $("div.ui-spn > div").css({"text-align" : "center", "padding" : "50px 0px 50px 0px"});
                //DOC add signed out breadcrumb
                $(".ui-breadcrumbs").append("<li class='ui-breadcrumb-last'>Signed Out</li>");
            }

            // ADJUST SIGN IN PAGE
            if($("#swlogin").length){
                $("#sw-content-layout-wrapper .ui-widget.app").addClass("signin");
                $(".ui-breadcrumbs").append("<li class='ui-breadcrumb-last'>Sign In</li>");
            }

            // ADJUST REGISTER PAGE
            if($("#swageprompt-txt-birthmonth").length && $("#swageprompt-txt-birthday").length && $("#swageprompt-txt-birthyear").length) {
                $("#sw-content-layout-wrapper .ui-widget.app").addClass("register");
                $(".ui-breadcrumbs").append("<li class='ui-breadcrumb-last'>Register</li>");
            }

            // ADJUST SEARCH RESULTS PAGE
            if($("#sw-content-layout-wrapper.ui-spn #swsearch-pnl-main").length) {
                $("#sw-content-layout-wrapper").children().wrapAll('<div class="ui-widget app search-results"><div class="ui-widget-detail"></div></div>');
                $(".ui-breadcrumbs").append("<li class='ui-breadcrumb-last'>Search Results</li>");
            }

            // ADJUST MORE/VIEW ALL
            $(".more-link").each(function(){
                $(this).parent("li").addClass("cs-more-link-parent");
            });

            // APPLY RESPONSIVE DIMENSIONS TO CONTENT IMAGES
            $("div.ui-widget.app .ui-widget-detail img")
                .not($("div.ui-widget.app.cs-rs-multimedia-rotator .ui-widget-detail img"))
                .not($("div.ui-widget.app.gallery.json .ui-widget-detail img"))
                .not($("div.ui-widget.app.headlines .ui-widget-detail img"))
                .each(function() {
                    if ($(this).attr('width') !== undefined && $(this).attr('height') !== undefined) { // IMAGE HAS INLINE DIMENSIONS
                        $(this).css({"display": "inline-block", "width": "100%", "max-width": $(this).attr("width") + "px", "height": "auto", "max-height": $(this).attr("height") + "px"});
                    }
            });

            // ADJUST FIRST BREADCRUMB
            $("li.ui-breadcrumb-first > a > span").text("Home");

            // USE CHANNEL NAME FOR PAGELIST NAV HEADER IF ONE IS NOT PRESENT
            if(!$("div.sp.column.one .ui-widget-header h1").length) {
                $("div.sp.column.one .ui-widget-header").append("<h1></h1>");
            }
            
            $(".sp.column.two .ui-widget.app, #spn-content .ui-widget.app").first().addClass("first-app");
            
            $(".view-calendar-link, .ui-read-more a").append('<span class="cs-dev-icons cs-dev-icon-more-accent"><span class="path1"></span><span class="path2"></span></span>');
            
            $(".headlines a").attr("tabindex", 0);
            
            $(".hp-row.one .headlines .ui-article").each(function() {
            	if($(".ui-article-thumb", this).length) {
                	$(this).addClass("has-thumb");
				}
            	$(this).prepend('<div class="cs-article-info border-box flex flex-column flex-justify-end" />');
            	$(".ui-article-title", this).appendTo($(".cs-article-info", this));
                $(".ui-article-description", this).appendTo($(".cs-article-info", this));
            });
            
            $(".hp-row.one .headlines .ui-article.has-thumb").hover(function() {
            	//$(".cs-article-info", this).fadeOut(250);
                $(".ui-article-thumb", this).addClass("cs-hover-effect");
            }, function() {
            	//$(".cs-article-info", this).fadeIn(250);
                $(".ui-article-thumb", this).removeClass("cs-hover-effect");
            });
        },
        
        "UpcomingEvents": function() {
            // FOR SCOPE
            var _this = this;   

            if (!$(".upcomingevents .joel-month").length) {
                $(".upcomingevents").modEvents({
                    columns     : "yes",
                    monthLong   : "no",
                    dayWeek     : "yes"
                });
                eventsByDay(".upcomingevents .ui-articles");
            }

            function eventsByDay(container) {
                var countLi = 0;
                $(".ui-article", container).each(function(){
                    if (!$(this).find("h1.ui-article-title.sw-calendar-block-date").size()){
                        var moveArticle = $(this).html();
                        $(this).parent().prev().children().children().next().append(moveArticle);
                        $(this).parent().remove();
                    };

					$(".joel-day", this).text($(".joel-day", this).text()+" ");
                    $(".joel-day", this).prependTo($(".upcoming-column.right .sw-calendar-block-time:eq(0)", this));
                });
            }
        },

        "Footer": function() {
        	var _this = this;
        
            $(".gb-footer-info > p").each(function() {
            	$(this).html($(this).html().replace("MI", "Missouri"));
            });
    
            if('NKC Schools' != "") {
                $(".gb-footer.two").prepend('<h3>NKC Schools</h3>');
            }
            
            /*REMOVE*/
            if('NKC Schools' == "NKC Schools") {
            	$(".gb-footer.two h3").text("NORTH KANSAS CITY SCHOOLS");
            }
    
            var linkBank = [
                {
                    "show": true,
                    "text": "NKC Schools Education Foundation",
                    "url": "http://nkcschoolsfoundation.org/"
                },
                {
                    "show": false,
                    "text": "Legislative Agenda",
                    "url": "#"
                },
                {
                    "show": true,
                    "text": "Diversity Statement",
                    "url": "/Page/4219"
                },
                {
                    "show": true,
                    "text": "Nondiscrimination Notice",
                    "url": "/Page/4220"
                },
                {
                    "show": true,
                    "text": "Discover NKC Schools",
                    "url": "/cms/lib/MO49000025/Centricity/Domain/4/NKCS_2018_District_Profile.pdf"
                },
                {
                    "show": false,
                    "text": "Diversity Statement",
                    "url": "#"
                }
            ];

            var links = '';
            $.each(linkBank, function(index, link) {
                if(link.show) {
                    links += '<li><a class="gb-footer-link gb-footer-link-' + index + '" href="' + link.url + '">' + link.text + '</a></li>';
                }
            });

            if(links.length) {
                $(".gb-footer.three").html('<ul class="cs-html-list-reset">' + links + '</ul>');
            }
            
            var linkBank = [
                {
                    "show": true,
                    "text": "Link 7",
                    "url": "https://www.advanc-ed.org"
                },
                {
                    "show": true,
                    "text": "Link 8",
                    "url": "https://dese.mo.gov"
                }
            ];

            var links = '';
            $.each(linkBank, function(index, link) {
                if(link.show) {
                	links += '<div class="gb-footer-watermark gb-footer-watermark-' + index + '"><a href="' + link.url + '" aria-label="' + link.text + '"><span class="gb-footer-watermark-image-1 transition-all"></span><span class="gb-footer-watermark-image-2 transition-all"></span></a></div>';
                }
            });

            if(links.length) {
                $(".gb-footer.four").html(links);
            }
            
            $(document).on("click keydown", "#cs-back-to-top", function(e) { 
                if(_this.AllyClick(e)) {
                    $("html, body").animate({
                        scrollTop: $("#gb-page").offset().top
                    }, 500, function(){
                        $("html, body").stop(true, false);
                        $("header").find(":focusable").first().focus();
                    });
                } 
            });
                    
            // MOVE Bb FOOTER STUFF
            $(".gb-legal-logo").html($("#sw-footer-logo").html());
            var legalLinks = '';
            legalLinks += '<li>' + $.trim($("#sw-footer-links li:eq(0)").html().replace("|", "")) + '</li>';
            legalLinks += '<li>' + $.trim($("#sw-footer-links li:eq(2)").html().replace("|", "")) + '</li>';
            legalLinks += '<li>' + $.trim($("#sw-footer-links li:eq(1)").html().replace("|", "")) + '</li>';
            $(".gb-legal-footer.links").append('<ul>' + legalLinks + '</ul>');
            $(".gb-legal-footer.copyright").append($("#sw-footer-copyright").html());
        },

        "Slideshow": function() {
        	var _this = this;
            
            if($("#sw-content-container10 .ui-widget.app.multimedia-gallery").length) {
                var mmg = eval("multimediaGallery" + $("#sw-content-container10 .ui-widget.app.multimedia-gallery:first").attr("data-pmi"));
                mmg.props.defaultGallery = false;

                $("#sw-content-container10 .ui-widget.app.multimedia-gallery:first").csMultimediaGallery({
                    "efficientLoad" : true,
                    "imageWidth" : 1500,
                    "imageHeight" : 910,
                    "mobileDescriptionContainer": [960, 768, 640, 480, 320], // [960, 768, 640, 480, 320]
                    "galleryOverlay" : false,
                    "linkedElement" : ["title"], // ["image", "title", "overlay"]
                    "playPauseControl" : true,
                    "backNextControls" : false,
                    "bullets" : true,
                    "thumbnails" : false,
                    "thumbnailViewerNum": [4, 4, 3, 3, 2], // NUMERICAL - [960 view, 768 view, 640 view, 480 view, 320 view]
                    "autoRotate" : true,
                    "hoverPause" : true,
                    "transitionType" : "fade", // fade, slide, custom
                    "transitionSpeed" : 3,
                    "transitionDelay" : 8,
                    "fullScreenRotator" : true,
                    "fullScreenBreakpoints" : [960], // NUMERICAL - [960, 768, 640, 480, 320]
                    "onTransitionStart" : function(props) {                        
                        $(".mmg-description-outer .mmg-description-link", props.element).append('<span class="cs-dev-icons cs-dev-icon-more-accent"><span class="path1"></span><span class="path2"></span></span>');
                                            
                    	if(!$(".mmg-container > .mmg-description-outer .mmg-description-inner", props.element).length) {
                            //MOD DESCRIPTION
                            $(".mmg-container > .mmg-description-outer .mmg-description", props.element).each(function() {
                            	$(this).wrap('<div class="mmg-description-inner" />');
                            });
                        }
     
                        $("#hp-slideshow .mmg-mobile-links").html("");
                        $("#hp-slideshow .mmg-mobile-links").html($(".mmg-container > .mmg-description-outer .mmg-description-inner .mmg-description-links", props.element).html());
                    },
                    "allLoaded" : function(props) {
                        //MOD DESCRIPTION
                    	$(".mmg-description", props.element).each(function() {
                        	$(this).wrap('<div class="mmg-description-inner" />');
                        });
                        
                        $(".mmg-description-link", props.element).append('<span class="cs-dev-icons cs-dev-icon-more-accent"><span class="path1"></span><span class="path2"></span></span>');
                        
                        //MOD CONTROLS
                    	$(".mmg-control", props.element).wrapAll('<div class="mmg-controls-outer"><div class="mmg-controls flex"><div class="mmg-controls-inner" /></div></div>');
                        $(".mmg-controls-outer", props.element).appendTo($(".mmg-container > .mmg-description-outer .mmg-description-inner", props.element));
                        $(".mmg-bullets-outer", props.element).appendTo($(".mmg-controls", props.element));
                        
                        $(".mmg-controls-outer", props.element).prepend('<div class="mmg-mobile-links"></div>');

						$("#hp-slideshow .mmg-mobile-links").html($(".mmg-container > .mmg-description-outer .mmg-description-inner .mmg-description-links", props.element).html());
                    } // props.element, props.mmgRecords
                });
            }
        },

        "StreamingVideo": function() {
        	var _this = this;
        
        	if(true) {
            	//Variables
                var mobilePhoto = "/cms/lib/MO49000025/Centricity/Template/GlobalAssets/images///Mobile/nashua_BR.jpg";
                $("html").addClass("cs-streaming-video");
                
                if($.trim(mobilePhoto) == "" || mobilePhoto.indexOf("default-man.jpg") > -1) {
                	mobilePhoto = "/cms/lib/MO49000025/Centricity/Template/18/gb-mobile-streaming-default.jpg";
                }
                
                $("#sw-content-container10.region.ui-hp").fullScreenRotator({
                    "videoSource" : "youtube", // OPTIONS ARE: youtube, vimeo
                    "videoID": '8HZs1i5u9co', // YouTube and Vimeo ids are set as default in the script
                    "fullScreenBreakpoints" : [960], // OPTIONS ARE [960, 768, 640, 480, 320]
                    "showControls" : true,
                    "mobileBackgroundPhoto" : mobilePhoto,
                    "mobileBackgroundPhotoBreakpoint" : 768, // OPTIONS ARE 768, 640, 480, 320
                    "onReady" : function(props) {
                    	// ADD POSITIONING STYLES
                        var dynStyleSheet = document.createElement('style');
                        if(dynStyleSheet) {
                            dynStyleSheet.setAttribute('type', 'text/css');
                            var head = document.getElementsByTagName('head')[0];

                            if(head) {
                                head.insertBefore(dynStyleSheet, head.childNodes[0]);
                            }

                            var dynStyles = 'iframe#cs-fullscreen-video {' +
                                                'top: calc(((100vw * .4) - (100vw * ' + (props.height / props.width) + ')) / 2);' +	
                                            '}';

                            var rules = document.createTextNode(dynStyles);

                            if(dynStyleSheet.styleSheet){ // IE
                                dynStyleSheet.styleSheet.cssText = dynStyles;
                            } else {
                                dynStyleSheet.appendChild(rules);
                            }
                        }
                        
                        $("html").addClass("cs-using-fullscreen-video");
                        
                        var sbvStructure = "";
                        
                        sbvStructure += '<div class="mmg-description-outer"><div class="mmg-description-inner"><div class="mmg-description">';

                        
                        if('Welcome to NKC Schools!' != "") {
            				sbvStructure += '<h2 class="mmg-description-title">Welcome to NKC Schools!</h2>';
						}
                        
                        if('Just north of Kansas City&#39s vibrant downtown, we are a district of over 21,000 learners who benefit daily from an academically challenging curriculum for grades pre-K to 12.' != "") {         
            				sbvStructure += '<p class="mmg-description-caption">Just north of Kansas City&#39s vibrant downtown, we are a district of over 21,000 learners who benefit daily from an academically challenging curriculum for grades pre-K to 12.</p>';
						}
                        
                        sbvStructure += '</div></div></div>';
                        
                        $(".cs-using-fullscreen-video #sw-content-container10.ui-hp").append(sbvStructure);
                        
                        $("#cs-fullscreen-video-outer .cs-fullscreen-video-buttons").addClass("hide768").appendTo($(".cs-using-fullscreen-video #sw-content-container10.ui-hp .mmg-description-inner"));
                       
                        // ADD ARIA LABELS TO BUTTONS
                        $("#hp-slideshow .cs-fullscreen-video-button.mute-button").attr("aria-label", "Mute Background Video");
                        $("#hp-slideshow .cs-fullscreen-video-button.unmute-button").attr("aria-label", "Unmute Background Video");
                        $("#hp-slideshow .cs-fullscreen-video-button.play-button").attr("aria-label", "Play Background Video");
                        $("#hp-slideshow .cs-fullscreen-video-button.pause-button").attr("aria-label", "Pause Background Video");
                        
                        // BUTTON ACTIONS
                        $("#hp-slideshow").on("click keydown", ".cs-fullscreen-video-button.play-button", function(e) {
                        	if(_this.AllyClick(e)) {
                            	setTimeout(function() {
                                	$("#hp-slideshow .cs-fullscreen-video-button.pause-button").focus();
                                }, 100);
                            }
                        });
                        $("#hp-slideshow").on("click keydown", ".cs-fullscreen-video-button.pause-button", function(e) {
                        	if(_this.AllyClick(e)) {
                            	setTimeout(function() {
                                	$("#hp-slideshow .cs-fullscreen-video-button.play-button").focus();
                                }, 100);
                            }
                        });
                        $("#hp-slideshow").on("click keydown", ".cs-fullscreen-video-button.mute-button", function(e) {
                        	if(_this.AllyClick(e)) {
                            	setTimeout(function() {
                                	$("#hp-slideshow .cs-fullscreen-video-button.unmute-button").focus();
                                }, 100);
                            }
                        });
                        $("#hp-slideshow").on("click keydown", ".cs-fullscreen-video-button.unmute-button", function(e) {
                        	if(_this.AllyClick(e)) {
                            	setTimeout(function() {
                                	$("#hp-slideshow .cs-fullscreen-video-button.mute-button").focus();
                                }, 100);
                            }
                        });
                    },
                    "onStateChange" : function(props) { }
                });
                
                // MOVE BUTTONS
                $("#hp-slideshow #cs-fullscreen-video-outer").append($("#hp-slideshow .cs-fullscreen-video-buttons"));
            }
        },

		"RsMenu": function() {
			// FOR SCOPE
			var _this = this;
            
                        
            // ADDITIONAL ITEMS OBJECT
            var additionalItems = {};
                        
            // GLOBAL ICONS
            var globalIconsData = [
                {
                    "text": "Transportation",
                    "url": "Domain/153"
                },
                {
                    "text": "PowerSchool",
                    "url": "https://powerschool.nkcschools.org/public/"
                },
                {
                    "text": "Canvas",
                    "url": "http://canvas.nkcschools.org"
                },
                {
                    "text": "Board Docs",
                    "url": "https://www.boarddocs.com/mo/nkcsd/Board.nsf/Public"
                },
                {
                    "text": "Menus",
                    "url": "http://www.schoolnutritionandfitness.com/index.php?sid=0306152235285801&page=menus"
                },
                {
                    "text": "Webstore",
                    "url": "domain/6098"
                },
                {
                    "text": "Contact Us",
                    "url": "domain/76"
                }
            ];

            var haveGlobalIcons = false;
            var globalIcons = [];
            var globalIconNum = parseInt('7');
            if(globalIconNum == NaN) {
                var splitDefaultVal = globalIconNum.split(";");
                globalIconNum = parseInt(splitDefaultVal[0]);
			}
            
            for(var g = 0; g < globalIconNum; g++) {
                globalIcons.push({ "text": globalIconsData[g].text, "url": globalIconsData[g].url });

                haveGlobalIcons = true;
            }
            
            if(haveGlobalIcons) {
            	additionalItems["Global Icons"] = globalIcons;
            }            
                        
            var socialIcons = [
                {
                    "show": true,
                    "label": "District",
                    "class": "district",
                    "url": "/page/1"
                },
                {
                    "show": true,
                    "label": "Facebook",
                    "class": "facebook",
                    "url": "https://www.facebook.com/NKCSchools/"
                },
                {
                    "show": true,
                    "label": "Twitter",
                    "class": "twitter",
                    "url": "https://twitter.com/NKCSchools"
                },
                {
                    "show": true,
                    "label": "Instagram",
                    "class": "instagram",
                    "url": "https://www.instagram.com/nkcschools/"
                },
                {
                    "show": true,
                    "label": "YouTube",
                    "class": "youtube",
                    "url": "https://www.youtube.com/user/NKCSchools"
                },
                {
                    "show": false,
                    "label": "Google+",
                    "class": "google-plus",
                    "url": "#"
                },
                {
                    "show": false,
                    "label": "Pinterest",
                    "class": "pinterest",
                    "url": "#"
                },
                {
                    "show": false,
                    "label": "Vimeo",
                    "class": "vimeo",
                    "url": "#"
                },
                {
                    "show": false,
                    "label": "Flickr",
                    "class": "flickr",
                    "url": "#"
                },
                {
                    "show": false,
                    "label": "LinkedIn",
                    "class": "linkedin",
                    "url": "#"
                }
            ];

            var icons = [];
            $.each(socialIcons, function(index, icon) {
                if(icon.show) {
                    icons.push({ "text": icon.label, "url": icon.url });
                }
            });

            if(icons.length) {
            	additionalItems["Social Icons"] = icons;
            }
            
            var linkBank = [
                {
                    "show": true,
                    "text": "For Students",
                    "url": "/Page/4095"
                },
                {
                    "show": true,
                    "text": "For Staff",
                    "url": "/domain/2974"
                },
                {
                    "show": true,
                    "text": "For Community",
                    "url": "/page/197"
                },
                {
                    "show": true,
                    "text": "lets Talk!",
                    "url": "https://www.k12insight.com/Lets-Talk/embed.aspx?k=WF7R4NLT"
                }
            ];
            
            var links = [];
            $.each(linkBank, function(index, link) {
                if(link.text != "") {
                    links.push({ "text": link.text, "url": link.url });
                }
            });

            if(links.length) {
            	additionalItems["Extra Links"] = links;
            }
            
            $.csRsMenu({
                "breakPoint" : 768, // SYSTEM BREAK POINTS - 768, 640, 480, 320
                "slideDirection" : "left-to-right", // OPTIONS - left-to-right, right-to-left
                "menuButtonParent" : "#gb-header-right",
                "menuBtnText" : "Menu Options",
                "colors": {
                    "pageOverlay": "#000000", // DEFAULT #000000
                    "menuBackground": "#FFFFFF", // DEFAULT #FFFFFF
                    "menuText": "#333333", // DEFAULT #333333
                    "menuTextAccent": "#333333", // DEFAULT #333333
                    "dividerLines": "#E6E6E6", // DEFAULT #E6E6E6
                    "buttonBackground": "#E6E6E6", // DEFAULT #E6E6E6
                    "buttonText": "#333333" // DEFAULT #333333
                },
                "showSchools" : true,
                "schoolMenuText": "Our Schools",
                "showTranslate" : true,
                "translateMenuText": "Languages",
                "translateVersion": 2, // 1 = FRAMESET, 2 = BRANDED
                "translateId" : "",
                "showAccount": true,
                "accountMenuText": "User Options",
                "usePageListNavigation": true,
                "extraMenuOptions": additionalItems, 
                "siteID": "4",
                "allLoaded": function() {}
            });
        },

        "AppAccordion": function() {
            $("#hp-content").csAppAccordion({
                "accordionBreakpoints" : [768, 640, 480, 320]
            });

            $(".sp-column.one").csAppAccordion({
                "accordionBreakpoints" : [768, 640, 480, 320]
            });
            
            $("#hp-content .ui-widget.app .ui-widget-header").eq(0).click();
        },

        "Search": function() {
        	var _this = this;
            
            // FORM SUMBIT
            $("#gb-search-form").submit(function(e) {
            	e.preventDefault();
            	if($("#gb-search-input").val() != "") {
                	window.location.href = "/site/Default.aspx?PageType=6&SiteID=4&SearchString=" + $("#gb-search-input").val();
                }
            });
            
            //Show/hide search
            $(document).on("click keydown", ".cs-mystart-item.search", function(e) {            
                if(_this.AllyClick(e)) {
                	e.preventDefault();
                    if($(this).attr("aria-expanded") == "false") {
                    	$(this).attr("aria-expanded", "true");
                        $("#gb-search-form").attr("aria-hidden", "false").show("slide", { direction: "right" }, 250);
                        
                        setTimeout(function() {
                            $("#gb-search-input").focus();
                        }, 260);
                    } else {
                    	$(this).attr("aria-expanded", "false");
                        $("#gb-search-form").attr("aria-hidden", "true").hide("slide", { direction: "right" }, 250);
                    }
                }
            });
            
            $(document).on("keydown", "#gb-search-input", function(e) {
                // CAPTURE KEY CODE
                switch(e.keyCode) {
                    // CONSUME TAB KEY
                    case _this.KeyCodes.tab:
                        e.preventDefault();
                        $(".cs-mystart-item.search").click().focus();
                    break;
                }
            });
        },

        "AllyClick": function(event) {
            if(event.type == "click") {
                return true;
            } else if(event.type == "keypress" || event.type == "keydown" && (event.keyCode == this.KeyCodes.space || event.keyCode == this.KeyCodes.enter)) {
                return true;
            } else {
                return false;
            }
        },

        "GetBreakPoint": function() {
            return window.getComputedStyle(document.querySelector("body"), ":before").getPropertyValue("content").replace(/"|'/g, "");/*"*/
        }
    };
</script>

    <!-- App Preview -->
    


    <style type="text/css">
        /* HOMEPAGE EDIT THUMBNAIL STYLES */

        div.region {
            ;
        }

            div.region span.homepage-thumb-region-number {
                font: bold 100px verdana;
                color: #fff;
            }

        div.homepage-thumb-region {
            background: #264867; /*dark blue*/
            border: 5px solid #fff;
            text-align: center;
            padding: 40px 0 40px 0;
            display: block;
        }

            div.homepage-thumb-region.region-1 {
                background: #264867; /*dark blue*/
            }

            div.homepage-thumb-region.region-2 {
                background: #5C1700; /*dark red*/
            }

            div.homepage-thumb-region.region-3 {
                background: #335905; /*dark green*/
            }

            div.homepage-thumb-region.region-4 {
                background: #B45014; /*dark orange*/
            }

            div.homepage-thumb-region.region-5 {
                background: #51445F; /*dark purple*/
            }

            div.homepage-thumb-region.region-6 {
                background: #3B70A0; /*lighter blue*/
            }

            div.homepage-thumb-region.region-7 {
                background: #862200; /*lighter red*/
            }

            div.homepage-thumb-region.region-8 {
                background: #417206; /*lighter green*/
            }

            div.homepage-thumb-region.region-9 {
                background: #D36929; /*lighter orange*/
            }

            div.homepage-thumb-region.region-10 {
                background: #6E5C80; /*lighter purple*/
            }

        /* END HOMEPAGE EDIT THUMBNAIL STYLES */
    </style>

    <style type="text/css" media="print">
        .noprint {
            display: none !important;
        }
    </style>

    <style type ="text/css">
        .ui-txt-validate {
            display: none;
        }
    </style>

    

<!-- Begin Schoolwires Traffic Code --> 

<script type="text/javascript">

    (function (i, s, o, g, r, a, m) {
        i['GoogleAnalyticsObject'] = r; i[r] = i[r] || function () {
            (i[r].q = i[r].q || []).push(arguments)
        }, i[r].l = 1 * new Date(); a = s.createElement(o),
        m = s.getElementsByTagName(o)[0]; a.async = 1; a.src = g; m.parentNode.insertBefore(a, m)
    })(window, document, 'script', '//www.google-analytics.com/analytics.js', 'ga');

    ga('create', 'UA-5173826-6', 'auto', 'BBTracker' );
    ga('BBTracker.set', 'dimension1', 'AWS');
    ga('BBTracker.set', 'dimension2', 'False');
    ga('BBTracker.set', 'dimension3', 'MO49000025');
    ga('BBTracker.set', 'dimension4', '4');
    ga('BBTracker.set', 'dimension5', '1');
    ga('BBTracker.set', 'dimension6', '1');

    ga('BBTracker.send', 'pageview');

</script>

<!-- End Schoolwires Traffic Code --> 

    <!-- Ally Alternative Formats Loader    START   -->
    
<script data-ally-loader src="https://prod.ally.ac/integration/api/ally.ui.js"></script>

    <!-- Ally Alternative Formats Loader    END     -->

</head>
<body>

    <input type="hidden" id="hidFullPath" value="https://www.nkcschools.org/" />
    <input type="hidden" id="hidActiveChannelNavType" value="-1" />
    <input type="hidden" id="hidActiveChannel" value ="0" />
    <input type="hidden" id="hidActiveSection" value="0" />

    <!-- OnScreen Alert Dialog Start -->
    <div id="onscreenalert-holder"></div>
    <!-- OnScreen Alert Dialog End -->

    <!-- ADA Skip Nav -->
    <div class="sw-skipnav-outerbar">
        <a href="#sw-maincontent" id="skipLink" class="sw-skipnav" tabindex="0">Skip to Main Content</a>
    </div>

    <!-- DashBoard SideBar Start -->
    
    <!-- DashBoard SideBar End -->

    <!-- off-canvas menu enabled-->
    

    

<style type="text/css">
	/* SPECIAL MODE BAR */
	div.sw-special-mode-bar {
		background: #FBC243 url('https://www.nkcschools.org/Static//GlobalAssets/Images/special-mode-bar-background.png') no-repeat;
		height: 30px;
		text-align: left;
		font-size: 12px;
		position: relative;
		z-index: 10000;
	}
	div.sw-special-mode-bar > div {
		padding: 8px 0 0 55px;
		font-weight: bold;
	}
	div.sw-special-mode-bar > div > a {
		margin-left: 20px;
		background: #A0803D;
		-moz-border-radius: 5px;
		-webkit-border-radius: 5px;
		color: #fff;
		padding: 4px 6px 4px 6px;
		font-size: 11px;
	}

	/* END SPECIAL MODE BAR */
</style>

<script type="text/javascript">
	
	function SWEndPreviewMode() { 
		var data = "{}";
		var success = "window.location='';";
		var failure = "CallControllerFailure(result[0].errormessage);";
		CallController("https://www.nkcschools.org/site/SiteController.aspx/EndPreviewMode", data, success, failure);
	}
	
    function SWEndEmulationMode() {
        var data = "{}";
        var success = "DeleteCookie('SourceEmulationUserID');DeleteCookie('SidebarIsClosed');window.location='https://www.nkcschools.org/ums/Users/Users.aspx';";
        var failure = "CallControllerFailure(result[0].errormessage);";
        CallController("https://www.nkcschools.org/site/SiteController.aspx/EndEmulationMode", data, success, failure);
	}

	function SWEndPreviewConfigMode() {
	    var data = "{}";
	    var success = "window.location='';";
	    var failure = "CallControllerFailure(result[0].errormessage);";
	    CallController("https://www.nkcschools.org/site/SiteController.aspx/EndPreviewConfigMode", data, success, failure);
	}
</script>
            

    <!-- BEGIN - MYSTART BAR -->
<div id='sw-mystart-outer' class='noprint'>
<div id='sw-mystart-inner'>
<div id='sw-mystart-left'>
<div class='sw-mystart-nav sw-mystart-button home'><a tabindex="0" href="https://www.nkcschools.org/Domain/4" alt="District Home" title="Return to the homepage on the district site."><span>District Home<div id='sw-home-icon'></div>
</span></a></div>
<div class='sw-mystart-nav sw-mystart-dropdown schoollist' tabindex='0' aria-label='Select a School' role='navigation'>
<div class='selector' aria-hidden='true'>Select a School...</div>
<div class='sw-dropdown' aria-hidden='false'>
<div class='sw-dropdown-selected' aria-hidden='true'>Select a School</div>
<ul class='sw-dropdown-list' aria-hidden='false' aria-label='Schools'>
<li><a href="/Domain/8">Bell Prairie</a></li>
<li><a href="/Domain/9">Briarcliff</a></li>
<li><a href="/Domain/10">Chapel Hill</a></li>
<li><a href="/Domain/11">Chouteau</a></li>
<li><a href="/Domain/12">Clardy</a></li>
<li><a href="/Domain/13">Crestview</a></li>
<li><a href="/Domain/14">Davidson</a></li>
<li><a href="/Domain/15">Fox Hill</a></li>
<li><a href="/Domain/16">Gashland</a></li>
<li><a href="/Domain/18">Gracemor</a></li>
<li><a href="/Domain/19">Lakewood</a></li>
<li><a href="/Domain/20">Linden West</a></li>
<li><a href="/Domain/21">Maplewood</a></li>
<li><a href="/Domain/22">Meadowbrook</a></li>
<li><a href="/Domain/23">Nashua</a></li>
<li><a href="/Domain/24">Northview</a></li>
<li><a href="/Domain/25">Oakwood Manor</a></li>
<li><a href="/Domain/26">Ravenwood</a></li>
<li><a href="/Domain/17">Rising Hill</a></li>
<li><a href="/Domain/27">Topping</a></li>
<li><a href="/Domain/28">West Englewood</a></li>
<li><a href="/Domain/29">Winnwood</a></li>
<li><a href="/Domain/31">Eastgate</a></li>
<li><a href="/Domain/39">Gateway</a></li>
<li><a href="/Domain/30">Antioch</a></li>
<li><a href="/Domain/32">Maple Park</a></li>
<li><a href="/Domain/33">New Mark</a></li>
<li><a href="/Domain/34">Northgate</a></li>
<li><a href="/Domain/35">North Kansas City</a></li>
<li><a href="/Domain/36">Oak Park</a></li>
<li><a href="/Domain/37">Staley</a></li>
<li><a href="/Domain/38">Winnetonka</a></li>
<li><a href="/Domain/40">Early Childhood</a></li>
<li><a href="/Domain/43">SAGE</a></li>
</ul>
</div>
<div class='sw-dropdown-arrow' aria-hidden='true'></div>
</div>
</div>
<div id='sw-mystart-right'>
<div id='ui-btn-signin' class='sw-mystart-button signin'><a href="https://www.nkcschools.org/site/Default.aspx?PageType=7&SiteID=4&IgnoreRedirect=true"><span>Sign In</span></a></div>
<div id='sw-mystart-search' class='sw-mystart-nav'>
<script type="text/javascript">
$(document).ready(function() {
    $('#sw-search-input').keyup(function(e) {        if (e.keyCode == 13) {
            SWGoToSearchResultsPageswsearchinput();
        }
    });
    $('#sw-search-input').val($('#swsearch-hid-word').val())});
function SWGoToSearchResultsPageswsearchinput() {
window.location.href="https://www.nkcschools.org/site/Default.aspx?PageType=6&SiteID=4&SearchString=" + $('#sw-search-input').val();
}
</script>
<label for="sw-search-input" class="hidden-label">Search Our Site</label>
<input id="sw-search-input" type="text" title="Search Term" aria-label="Search Our Site" placeholder="Search this Site..." />
<a tabindex="0" id="sw-search-button" title="Search" href="javascript:;" role="button" aria-label="Submit Site Search" onclick="SWGoToSearchResultsPageswsearchinput();"><span><img src="https://www.nkcschools.org/Static//globalassets/images/sw-mystart-search.png" alt="Search" /></span></a><script type="text/javascript">
$(document).ready(function() {
    $('#sw-search-button').keyup(function(e) {        if (e.keyCode == 13) {
            SWGoToSearchResultsPageswsearchinput();        }
    });
});
</script>

</div>
<div class='clear'></div>
</div>
</div>
</div>
<!-- END - MYSTART BAR -->
<div id="gb-page" class="hp NKCSchools">
	<header class="gb-section-parent">
		<section id="gb-header-outer" class="gb-section-parent gb-section-pad">
			<div id="gb-header" class="gb-section flex">
                <svg id="gb-header-svg" class="hide768" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="400px" height="100%">
                	<path fill-rule="evenodd"  opacity="0.302" fill="rgb(215, 215, 215)" d="M-0.001,-0.000 L398.000,163.000 L1.000,163.000 L1.000,-0.000 L-0.001,-0.000 Z"/>
                </svg>
            	<div id="gb-header-left" class="flex flex-items-center" data-show-logo="true" data-show-logo-only="true">
                    <div id="gb-logo"></div>
                    <div id="gb-sitename"></div>
                </div>
            	<div id="gb-header-right" class="flex flex-column flex-items-end flex-justify-space">
                    <div id="gb-mystart" class="flex">
                        <div class="cs-mystart-item district-home hide640"><a href="/page/1" class="flex flex-items-center flex-justify-center transition-all"><span>District Home</span></a></div>
                        <div class="cs-mystart-dropdown schools hide640">
                        	<div class="cs-selector border-box transition-all flex flex-column flex-items-center flex-justify-center" aria-haspopup="true" aria-controls="cs-schools-list" tabindex="0" aria-label="Our Schools" role="button" aria-expanded="false"><span>Our Schools</span></div>
                        	<div class="cs-dropdown" aria-hidden="true" style="display: none;" id="cs-schools-list">
                        		<ul class="cs-dropdown-list cs-html-list-reset"></ul>
                        	</div>
                        </div>
                        <div class="cs-mystart-dropdown translate hide640">
                        	<div class="cs-selector border-box transition-all flex flex-column flex-items-center flex-justify-center" aria-haspopup="true" aria-controls="cs-translate-list" tabindex="0" aria-label="Choose Language" role="button" aria-expanded="false"><span>Languages</span></div>
                        	<div class="cs-dropdown" aria-hidden="true" style="display: none;" id="cs-translate-list"></div>
                        </div>
                        <div class="cs-mystart-item search flex flex-items-center flex-justify-center hide480" aria-haspopup="true" aria-controls="gb-search-form" aria-label="Search Form" tabindex="0" role="button" aria-expanded="false">
                        	<span class="cs-dev-icons cs-dev-icon-search"></span>
                        </div>
                        <form id="gb-search-form" aria-hidden="true" class="hide480">
                        	<label for="gb-search-input" class="acc-hidden">Search this site</label>
                       		<input type="text" id="gb-search-input" class="cs-html-input-reset border-box" value="" />
                        </form>
                    </div>
                    <nav class="hide768">
                    	<div id="sw-channel-list-container" role="navigation">
<ul id="channel-navigation" class="sw-channel-list" role="menubar">
<li id="navc-HP" class="sw-channel-item" ><a href="/Page/1" aria-label="Home"><span>Home</span></a></li>
<li id="navc-59" class="sw-channel-item">
<a href="/domain/65"">
<span>Our District</span></a>
<div class="hidden-sections"><ul>"

</ul></div>
<ul class="sw-channel-dropdown">
<li id="navs-65"><a href="/domain/65"><span>North Kansas City Schools</span></a></li>
<li id="navs-66"><a href="/domain/66"><span>Administration</span></a></li>
<li id="navs-69"><a href="/domain/69"><span>Awards & Distinctions</span></a></li>
<li id="navs-67"><a href="/domain/67"><span>Board of Education</span></a></li>
<li id="navs-76"><a href="/domain/76"><span>Contacts & Map</span></a></li>
<li id="navs-6253"><a href="/site/Default.aspx?PageID=5058"><span>2020 Bond Program</span></a></li>
<li id="navs-71"><a href="/site/Default.aspx?PageID=132"><span>History</span></a></li>
<li id="navs-73"><a href="https://www.nkcschools.org/cms/lib/MO49000025/Centricity/Domain/4/NKCS_2020_Legislative.pdf" target="_blank"><span>Legislative Agenda</span></a></li>
<li id="navs-68"><a href="/domain/68"><span>Mission & Strategic Plan</span></a></li>
<li id="navs-75"><a href="/domain/75"><span>Staff Directory</span></a></li>
<li id="navs-72"><a href="/domain/72"><span>State Report Card</span></a></li>
</ul>
</li><li id="navc-58" class="sw-channel-item">
<a href="/site/Default.aspx?PageType=1&SiteID=4&ChannelID=58&DirectoryType=6
"">
<span>Academics</span></a>
<div class="hidden-sections"><ul>"
<li id="navs-77" class="hidden-section"><a href="/domain/77"><span>A+ Schools Program</span></a></li>
<li id="navs-6335" class="hidden-section"><a href="https://www.nkcschools.org/Page/703"><span>Adult Education & Literacy</span></a></li>
<li id="navs-6068" class="hidden-section"><a href="/domain/6068"><span>Alternative Education</span></a></li>
<li id="navs-91" class="hidden-section"><a href="/site/Default.aspx?PageID=217"><span>AVID</span></a></li>
<li id="navs-6317" class="hidden-section"><a href="/domain/6317"><span>Career Planning & Education Guide</span></a></li>
<li id="navs-79" class="hidden-section"><a href="/site/Default.aspx?PageID=194"><span>College & Career Readiness</span></a></li>
<li id="navs-80" class="hidden-section"><a href="/site/Default.aspx?PageID=199"><span>Curriculum</span></a></li>
<li id="navs-82" class="hidden-section"><a href="/domain/82"><span>Distinguished Achievement</span></a></li>
<li id="navs-6182" class="hidden-section"><a href="/domain/6182"><span>eCampus Fueled by Launch</span></a></li>
<li id="navs-83" class="hidden-section"><a href="https://www.nkcschools.org/Page/219"><span>Elementary Education (K-5)</span></a></li>
<li id="navs-84" class="hidden-section"><a href="/site/Default.aspx?PageID=635"><span>English Language Learners (ELL)</span></a></li>
<li id="navs-6252" class="hidden-section"><a href="/domain/6252"><span>Fine Arts</span></a></li>
<li id="navs-6286" class="hidden-section"><a href="/Page/79"><span>Gifted Education (SAGE)</span></a></li>
<li id="navs-6344" class="hidden-section"><a href="/domain/6344"><span>Indian Education</span></a></li>
<li id="navs-85" class="hidden-section"><a href="/domain/85"><span>Library Media Centers</span></a></li>
<li id="navs-86" class="hidden-section"><a href="/domain/86"><span>No Child Left Behind</span></a></li>
<li id="navs-6364" class="hidden-section"><a href="https://www.nkcschools.org/Page/4476"><span>Off Campus Programs</span></a></li>
<li id="navs-87" class="hidden-section"><a href="/Page/665"><span>PE-Health</span></a></li>
<li id="navs-88" class="hidden-section"><a href="https://www.nkcschools.org/Page/220"><span>Secondary Education (6-12)</span></a></li>
<li id="navs-89" class="hidden-section"><a href="/Page/212"><span>Special Education</span></a></li>
<li id="navs-90" class="hidden-section"><a href="/domain/90"><span>Summer Learning</span></a></li>
<li id="navs-6249" class="hidden-section"><a href="/domain/6249"><span>Overview</span></a></li>

</ul></div>
<ul class="dropdown-hidden">
</ul>
</li><li id="navc-60" class="sw-channel-item">
<a href="/site/Default.aspx?PageType=1&SiteID=4&ChannelID=60&DirectoryType=6
"">
<span>Departments</span></a>
<div class="hidden-sections"><ul>"
<li id="navs-131" class="hidden-section"><a href="/domain/131"><span>Academic Services </span></a></li>
<li id="navs-6334" class="hidden-section"><a href="https://www.nkcschools.org/Page/703"><span>Adult Education & Literacy</span></a></li>
<li id="navs-6316" class="hidden-section"><a href="/Page/670"><span>Adventure Club</span></a></li>
<li id="navs-6308" class="hidden-section"><a href="/domain/6308"><span>Athletics & Activities</span></a></li>
<li id="navs-133" class="hidden-section"><a href="/domain/133"><span>College & Career Readiness</span></a></li>
<li id="navs-134" class="hidden-section"><a href="/site/Default.aspx?PageID=161"><span>Communications & Media</span></a></li>
<li id="navs-6250" class="hidden-section"><a href="/domain/6250"><span>Community Education</span></a></li>
<li id="navs-136" class="hidden-section"><a href="/domain/136"><span>Community Relations</span></a></li>
<li id="navs-137" class="hidden-section"><a href="/domain/137"><span>Counseling </span></a></li>
<li id="navs-138" class="hidden-section"><a href="/domain/138"><span>Curriculum & Instruction</span></a></li>
<li id="navs-140" class="hidden-section"><a href="/domain/140"><span>Data & Accountability</span></a></li>
<li id="navs-141" class="hidden-section"><a href="/domain/141"><span>Education Foundation</span></a></li>
<li id="navs-142" class="hidden-section"><a href="/domain/142"><span>Educational Technology</span></a></li>
<li id="navs-143" class="hidden-section"><a href="/domain/143"><span>Facilities</span></a></li>
<li id="navs-144" class="hidden-section"><a href="/domain/144"><span>Finance Office</span></a></li>
<li id="navs-145" class="hidden-section"><a href="http://www.schoolnutritionandfitness.com/index.php?sid=0306152235285801&page=staff" target="_blank"><span>Food & Nutrition Services</span></a></li>
<li id="navs-146" class="hidden-section"><a href="/domain/146"><span>Health Services</span></a></li>
<li id="navs-147" class="hidden-section"><a href="/site/Default.aspx?PageID=208"><span>Human Resources</span></a></li>
<li id="navs-6251" class="hidden-section"><a href="/domain/6251"><span>Operations</span></a></li>
<li id="navs-149" class="hidden-section"><a href="/domain/149"><span>Organizational Development</span></a></li>
<li id="navs-6282" class="hidden-section"><a href="/domain/6282"><span>Purchasing</span></a></li>
<li id="navs-150" class="hidden-section"><a href="/domain/150"><span>Safety & Security</span></a></li>
<li id="navs-6281" class="hidden-section"><a href="https://www.nkcschools.org/Domain/43"><span>SAGE</span></a></li>
<li id="navs-151" class="hidden-section"><a href="/domain/151"><span>Special Education</span></a></li>
<li id="navs-152" class="hidden-section"><a href="/domain/152"><span>Student Services</span></a></li>
<li id="navs-153" class="hidden-section"><a href="/domain/153"><span>Transportation</span></a></li>
<li id="navs-6309" class="hidden-section"><a href="/domain/6309"><span>Wellness</span></a></li>
<li id="navs-6343" class="hidden-section"><a href="/domain/6343"><span>Temp</span></a></li>
<li id="navs-6383" class="hidden-section"><a href="/domain/6383"><span>Coronavirus (COVID-19) Updates</span></a></li>

</ul></div>
<ul class="dropdown-hidden">
</ul>
</li><li id="navc-63" class="sw-channel-item">
<a href="/domain/6184"">
<span>Families</span></a>
<div class="hidden-sections"><ul>"
<li id="navs-6367" class="hidden-section"><a href="/domain/6367"><span>Coronavirus (COVID-19) Updates</span></a></li>
<li id="navs-6379" class="hidden-section"><a href="/domain/6379"><span>Graduation 2020</span></a></li>

</ul></div>
<ul class="sw-channel-dropdown">
<li id="navs-6184"><a href="/domain/6184"><span>Family Resources</span></a></li>
<li id="navs-93"><a href="/site/Default.aspx?PageID=670"><span>Adventure Club</span></a></li>
<li id="navs-4004"><a href="/site/Default.aspx?PageID=198"><span>Counseling</span></a></li>
<li id="navs-92"><a href="/site/Default.aspx?PageID=730"><span>Enrollment & Registration</span></a></li>
<li id="navs-94"><a href="/domain/94"><span>Parents As Teachers</span></a></li>
<li id="navs-2923"><a href="/domain/2923"><span>Peachjar</span></a></li>
<li id="navs-6280"><a href="https://powerschool.nkcschools.org/public/" target="_blank"><span>PowerSchool</span></a></li>
<li id="navs-95"><a href="/domain/95"><span>Early Childhood</span></a></li>
<li id="navs-2975"><a href="/site/Default.aspx?PageID=694"><span>Residency</span></a></li>
<li id="navs-4008"><a href="/domain/4008"><span>Resource Specialists</span></a></li>
<li id="navs-96"><a href="/domain/96"><span>School Closures</span></a></li>
<li id="navs-6098"><a href="/domain/6098"><span>Webstore</span></a></li>
</ul>
</li><li id="navc-64" class="hidden-channel">
<a href="/site/Default.aspx?PageID=4095" target="_blank"">
<span>Student Life</span></a>
<div class="hidden-sections"><ul>"

</ul></div>
<ul class="dropdown-hidden">
<li id="navs-6115"><a href="/site/Default.aspx?PageID=4095" target="_blank"><span>For Students</span></a></li>
</ul>
</li><li id="navc-62" class="hidden-channel">
<a href="/site/Default.aspx?PageID=197"">
<span>Community</span></a>
<div class="hidden-sections"><ul>"
<li id="navs-6333" class="hidden-section"><a href="/domain/6333"><span>Retirees</span></a></li>

</ul></div>
<ul class="sw-channel-dropdown">
<li id="navs-3987"><a href="/site/Default.aspx?PageID=197"><span>Overview</span></a></li>
<li id="navs-102"><a href="/site/Default.aspx?PageID=703"><span>Adult Education & Literacy</span></a></li>
<li id="navs-103"><a href="/site/Default.aspx?PageID=708"><span>Business Partnerships</span></a></li>
<li id="navs-101"><a href="/site/Default.aspx?PageID=197"><span>Community Education</span></a></li>
<li id="navs-2984"><a href="/site/Default.aspx?PageID=202"><span>Education Foundation</span></a></li>
<li id="navs-107"><a href="/site/Default.aspx?PageID=701"><span>Facility Usage</span></a></li>
<li id="navs-100"><a href="/domain/100"><span>Follow Us</span></a></li>
<li id="navs-104"><a href="/site/Default.aspx?PageID=707"><span>Golden Pass</span></a></li>
<li id="navs-105"><a href="/site/Default.aspx?PageID=711"><span>Senior Tax Exchange Program</span></a></li>
<li id="navs-106"><a href="/site/Default.aspx?PageID=667"><span>YouthFriends</span></a></li>
</ul>
</li><li id="navc-61" class="hidden-channel">
<a href="/domain/2974"">
<span>Staff</span></a>
<div class="hidden-sections"><ul>"

</ul></div>
<ul class="sw-channel-dropdown">
<li id="navs-2974"><a href="/domain/2974"><span>Employee Information</span></a></li>
<li id="navs-3985"><a href="/domain/3985"><span>Professional Development</span></a></li>
<li id="navs-2982"><a href="/site/Default.aspx?PageID=136"><span>Staff Directory</span></a></li>
<li id="navs-2981"><a href="https://outlook.com/nkcschools.org"><span>Webmail</span></a></li>
<li id="navs-6296"><a href="/domain/6296"><span>Employee Information</span></a></li>
</ul>
</li><li id="navc-2976" class="sw-channel-item">
<a href="/Page/208"">
<span>Careers</span></a>
<div class="hidden-sections"><ul>"

</ul></div>
<ul class="sw-channel-dropdown">
<li id="navs-2977"><a href="/Page/208"><span>Work for NKC Schools</span></a></li>
<li id="navs-6351"><a href="https://www.nkcschools.org/Page/4572"><span>Benefits, Salary Schedules & Calendars</span></a></li>
<li id="navs-6352"><a href="https://www.nkcschools.org/Page/4589"><span>Administrative Positions</span></a></li>
<li id="navs-6353"><a href="https://www.nkcschools.org/Page/4969"><span>Certified Positions</span></a></li>
<li id="navs-6354"><a href="https://www.nkcschools.org/Page/4575"><span>Classified Positions</span></a></li>
<li id="navs-6355"><a href="https://www.nkcschools.org/Page/4575"><span>Coaching & Activities</span></a></li>
<li id="navs-6360"><a href="https://www.nkcschools.org/Page/4573"><span>Student Teaching & Internships</span></a></li>
<li id="navs-6361"><a href="https://www.nkcschools.org/Page/4574"><span>Substitutes</span></a></li>
<li id="navs-6359"><a href="https://www.nkcschools.org/Page/4967"><span>Contact Information</span></a></li>
</ul>
</li><li id="navc-CA" class="sw-channel-item "><a href="/Page/2"><span>Calendar</span></a></li>
</ul><div class='clear'></div>
</div>



<script type="text/javascript">
    $(document).ready(function() {
        channelHoverIE();
        channelTouch();
        closeMenuByPressingKey();
    });

    function channelTouch() {
        // this will change the dropdown behavior when it is touched vs clicked.
        // channels will be clickable on second click. first click simply opens the menu.
        $('#channel-navigation > .sw-channel-item > a').on({
            'touchstart': function (e) {
                
                // see if has menu
                if ($(this).siblings('ul.sw-channel-dropdown').children('li').length > 0)  {
                    var button = $(this);

                    // add href as property if not already set
                    // then remove href attribute
                    if (!button.prop('linkHref')) {
                        button.prop('linkHref', button.attr('href'));
                        button.removeAttr('href');
                    }

                    // check to see if menu is already open
                    if ($(this).siblings('ul.sw-channel-dropdown').is(':visible')) {
                        // if open go to link
                        window.location.href = button.prop('linkHref');
                    } 

                } 
            }
        });
    }


    
    function channelHoverIE(){
		// set z-index for IE7
		var parentZindex = $('#channel-navigation').parents('div:first').css('z-index');
		var zindex = (parentZindex > 0 ? parentZindex : 8000);
		$(".sw-channel-item").each(function(ind) {
			$(this).css('z-index', zindex - ind);
			zindex --;
		});
	    $(".sw-channel-item").hover(function(){
	        var subList = $(this).children('ul');
	        if ($.trim(subList.html()) !== "") {
	            subList.show();
	            subList.attr("aria-hidden", "false").attr("aria-expanded", "true");
		    }
		    $(this).addClass("hover");
	    }, function() {
	        $(".sw-channel-dropdown").hide();
	        $(this).removeClass("hover");
	        var subList = $(this).children('ul');
	        if ($.trim(subList.html()) !== "") {
	            subList.attr("aria-hidden", "true").attr("aria-expanded", "false");
	        }
	    });
    }

    function closeMenuByPressingKey() {
        $(".sw-channel-item").each(function(ind) {
            $(this).keyup(function (event) {
                if (event.keyCode == 27) { // ESC
                    $(".sw-channel-dropdown").hide();
                    $(this).removeClass("hover");
                    var subList = $(this).children('ul');
                    if ($.trim(subList.html()) !== "") {
                        subList.attr("aria-hidden", "true").attr("aria-expanded", "false");
                    }
                }
                if (event.keyCode == 13 || event.keyCode == 32) { //enter or space
                    $(this).find('a').get(0).click();
                }
            }); 
        });

        $(".sw-channel-item a").each(function (ind) {
            $(this).parents('.sw-channel-item').keydown(function (e) {
                if (e.keyCode == 9) { // TAB
                    $(".sw-channel-dropdown").hide();
                    $(this).removeClass("hover");
                    var subList = $(this).children('ul');
                    if ($.trim(subList.html()) !== "") {
                        subList.attr("aria-hidden", "true").attr("aria-expanded", "false");
                    }
                }
            });
        });

        $(".sw-channel-dropdown li").each(function(ind) {
            $(this).keydown(function (event) {
                if (event.keyCode == 9) { // TAB
                    $(".sw-channel-dropdown").hide();
                    var parentMenuItem = $(this).parent().closest('li');
                    parentMenuItem.removeClass("hover");
                    var subList = parentMenuItem.children('ul');
                    if ($.trim(subList.html()) !== "") {
                        subList.attr("aria-hidden", "true").attr("aria-expanded", "false");
                    }
                    parentMenuItem.next().find('a:first').focus();
                    event.preventDefault();
                    event.stopPropagation();
                }

                if (event.keyCode == 37 || // left arrow
                    event.keyCode == 39) { // right arrow
                    $(".sw-channel-dropdown").hide();
                    var parentMenuItem = $(this).parent().closest('li');
                    parentMenuItem.removeClass("hover");
                    var subList = parentMenuItem.children('ul');
                    if ($.trim(subList.html()) !== "") {
                        subList.attr("aria-hidden", "true").attr("aria-expanded", "false");
                    }
                    if (event.keyCode == 37) {
                        parentMenuItem.prev().find('a:first').focus();
                    } else {
                        parentMenuItem.next().find('a:first').focus();
                    }
                    event.preventDefault();
                    event.stopPropagation();
                }
            });
        });
    }

</script>


                    </nav>
                </div>                
			</div>
		</section>
	</header>
	<main>
		<section id="hp-slideshow-outer" class="gb-section-parent">
			<div id="hp-slideshow" data-show-watermark="true">
                <div id="gb-tab-links" class="gb-section flex flex-justify-end hide480"></div>
                <div id="gb-social-media-icons" class="hide768 flex flex-justify-end"></div>
				<div id="sw-content-container10" class="region ui-hp"><div id='pmi-4424'>



<div id='sw-module-43480'>
    <script type="text/javascript">
        $(document).ready(function() {
            var DomainID = '4';
            var PageID = '1';
            var RenderLoc = '0';
            var MIID = '4348';

            //added to check to make sure moderated content doesn't bleed through the dialog
            if ($('#dialog-overlay-WindowLargeModal-body.moderateContent').length > 0) {
                $("#module-content-" + MIID).find(".ui-widget-detail").find(".ui-article").append("<p>&nbsp;</p>");
            }
        });
    </script>

    <script type="text/javascript">$(document).ready(function() {CheckScript('ModuleView');CheckScript('Mustache');
 });</script>
    
    <div id="module-content-4348" >
<div class="ui-widget app multimedia-gallery" data-pmi="4424" data-mi="4348">
	<div class="ui-widget-header ui-helper-hidden">
		
	</div>
    <div class="ui-widget-detail">
    	<div id="mmg-container-4424" class="mmg-container" data-gallery-type="default" data-transition="fade" data-record-num="0" data-is-animating="false" data-play-state="playing" data-is-hovering="false" data-has-focus="false" data-is-touching="false" data-active-record-index="0" data-active-gallery-index="0">
            <div class="mmg-viewer">
                <div class="mmg-slides-outer">
                    <ul class="mmg-slides"></ul>
                </div>
                <div class="mmg-live-feedback mmg-ally-hidden" aria-live="polite"></div>
            </div>
        </div>
        
        <script type="text/javascript">
            var multimediaGallery4424 = {
            	"props": {
                	"defaultGallery": true,
                    "imageWidth" : 960,
                	"imageHeight" : 500,
                	"pageModuleInstanceId": "4424",
                    "moduleInstanceId": "4348",
                    "virtualFolderPath": "/cms/lib/MO49000025/Centricity/ModuleInstance/4348/"
                },
				"records": [
{}]
			};
		</script>
	</div>
	<div class="ui-widget-footer ui-clear"></div>
</div>

<script type="text/javascript" src="//extend.schoolwires.com/creative/scripts/creative/rotate/multimedia-gallery/cs.multimedia.gallery.min.js"></script>
<script type="text/javascript">
	$(function() {
    	if(multimediaGallery4424.props.defaultGallery) {
        	$("#pmi-4424 .ui-widget.app.multimedia-gallery").csMultimediaGallery({
                "pageModuleInstanceId": 4424,
                "moduleInstanceId": 4348,
                "imageWidth" : multimediaGallery4424.props.imageWidth,
                "imageHeight" : multimediaGallery4424.props.imageHeight,
                "playPauseControl" : true,
                "bullets" : true
            });
        }
    });
</script>
<script type="text/javascript">
$(document).ready(function (){
$(".tag-list li a").keypress(function(e) { if(e.which == 13) { $(this).click();   }});
});
function LoadGroupedData(container, MIID, PMI, groupYear, groupMonth, groupBy, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&EnableQuirksMode=0&ViewID=' + viewToUse + '&Tag=' + tag, container, 2, 'chkSidebar();');
}
function LoadData(container, MIID, PMI, flexDataID, groupYear, groupMonth, groupBy, targetView, tag) {
  if(targetView !== undefined || targetView.Length() == 0){
  //targetView looks at the hidden Detail View defined in the Builder View.
      targetView = $('#hid-'+MIID+'-DetailView').val();
   }
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&FlexDataID=' + flexDataID + '&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&RenderLoc=0&FromRenderLoc=0&EnableQuirksMode=0&Tag=' + tag + '&ViewID=' + targetView, container, 2, 'chkSidebar();');
}
function LoadTaggedData(container, MIID, PMI, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&Tag=' + tag + '&EnableQuirksMode=0&ViewID='+viewToUse, container, 2, 'chkSidebar();');
  setTimeout(function(){ $("#module-content-"+ MIID +"").find('[tabindex]:first').focus(); }, 200);
}
</script>
</div>

</div></div>
</div>
			</div>
		</section>
        <section id="gb-sitetagline-outer" class="gb-section-parent hide480">
            <div id="gb-sitetagline" class="gb-section" data-text-color="Black"></div>
        </section>
        <section id="gb-global-icons-outer" class="gb-section-parent hide640">
        	<div id="gb-global-icons" class="gb-section">
                <svg id="gb-global-icons-svg" class="hide768" xmlns="http://www.w3.org/2000/svg"xmlns:xlink="http://www.w3.org/1999/xlink"width="772px" height="100%">
                    <path fill-rule="evenodd"  opacity="0.302" fill="rgb(0, 0, 0)" d="M439.999,-0.000 L0.000,180.000 L772.000,180.000 L772.000,-0.000 L439.999,-0.000 Z"/>
                </svg>
            </div>
    	</section>
        <a id="sw-maincontent" name="sw-maincontent" tabindex="-1"></a>
		<section id="hp-content-outer" class="gb-section-parent">
			<div id="hp-content">
				<div class="hp-row one gb-section-parent" data-headlines-opacity="50 - Default">
                	<div class="gb-section">
						<div id="sw-content-container1" class="region ui-hp"><div id='pmi-9651'>



<div id='sw-module-43500'>
    <script type="text/javascript">
        $(document).ready(function() {
            var DomainID = '4';
            var PageID = '1';
            var RenderLoc = '0';
            var MIID = '4350';

            //added to check to make sure moderated content doesn't bleed through the dialog
            if ($('#dialog-overlay-WindowLargeModal-body.moderateContent').length > 0) {
                $("#module-content-" + MIID).find(".ui-widget-detail").find(".ui-article").append("<p>&nbsp;</p>");
            }
        });
    </script>

    <script type="text/javascript">$(document).ready(function() {CheckScript('ModuleView');CheckScript('Mustache');
 });</script>
    
    <div id="module-content-4350" >
<div class="ui-widget app headlines">
	
	<div class="ui-widget-header">
		<h1>Headlines &amp; Features</h1>
	</div>
	
	<div class="ui-widget-detail" id="sw-app-headlines-4350">
		<ul class="ui-articles">
<li>  
    <div  class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt=" Coronavirus Update Graphic Image" height="313" width="300" src="../..//cms/lib/MO49000025/Centricity/Domain/4/Coronavirus Updates-2.png" />
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="https://www.nkcschools.org/coronavirus" target="_blank" ><span>Information and Resources</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Timely details from NKC Schools on coronavirus and its impact on our schools.</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Information and Resources" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=4350&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28049&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div  class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt=" Bond 2020 Graphic Image" height="313" width="300" src="../..//cms/lib/MO49000025/Centricity/Domain/4/bond for h-f.jpg" />
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="https://www.nkcschools.org/site/Default.aspx?PageID=5058" target="_blank" ><span>Bond 2020 Information</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Learn about plans to manage growth and maintain facilities.</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Bond 2020 Information" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=4350&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=27926&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div  class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt="Inspire Video Series logo image " height="313" width="300" src="../..//cms/lib/MO49000025/Centricity/Domain/4/SquareiNspire.png" />
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=4350&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=8530&PageID=1"><span>Inspire Video Series</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Helping tell the extraordinary story of NKC Schools!</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Inspire Video Series" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=4350&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=8530&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div  class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt="Clip art image of app launch announcement " height="313" width="300" src="../..//cms/lib/MO49000025/Centricity/Domain/4/App Launch Materials_basic_host email header 2.png" />
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=4350&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=26747&PageID=1"><span>NKC Schools Launches New App</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Visit the App Store or Google Play to download it today!</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for NKC Schools Launches New App" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=4350&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=26747&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
</ul>
	</div>

	<div class="ui-widget-footer">
		
		
		<div class="clear"></div>
	</div>
</div>
<script type="text/javascript">
	$(document).ready(function() {
        /*$(document).on('click', 'a.ui-article-thumb', function() {
        	window.location = $(this).attr('href');
    	});*/
    		
		$('#sw-app-headlines-4350').find('img').each(function() {
			if ($.trim(this.src) == '' ) {
				$(this).parent().parent().remove();
			}
		});
        
        // Jason Smith - 12/9/2014 - Removed due to bandwidth implications
		
	});

</script>
<script type="text/javascript">
$(document).ready(function (){
$(".tag-list li a").keypress(function(e) { if(e.which == 13) { $(this).click();   }});
});
function LoadGroupedData(container, MIID, PMI, groupYear, groupMonth, groupBy, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&EnableQuirksMode=0&ViewID=' + viewToUse + '&Tag=' + tag, container, 2, 'chkSidebar();');
}
function LoadData(container, MIID, PMI, flexDataID, groupYear, groupMonth, groupBy, targetView, tag) {
  if(targetView !== undefined || targetView.Length() == 0){
  //targetView looks at the hidden Detail View defined in the Builder View.
      targetView = $('#hid-'+MIID+'-DetailView').val();
   }
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&FlexDataID=' + flexDataID + '&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&RenderLoc=0&FromRenderLoc=0&EnableQuirksMode=0&Tag=' + tag + '&ViewID=' + targetView, container, 2, 'chkSidebar();');
}
function LoadTaggedData(container, MIID, PMI, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&Tag=' + tag + '&EnableQuirksMode=0&ViewID='+viewToUse, container, 2, 'chkSidebar();');
  setTimeout(function(){ $("#module-content-"+ MIID +"").find('[tabindex]:first').focus(); }, 200);
}
</script>
</div>

</div></div>
</div>
                    </div>
				</div>               
                <div class="hp-row two gb-section-parent">
                    <div class="gb-section flex">
                        <div class="hp-column one">
                            <div id="sw-content-container2" class="region ui-hp"><div id='pmi-96'>
<div id="module-content-96" ><div class="ui-widget app upcomingevents">
 <div class="ui-widget-header">
     <h1>Upcoming Events</h1>
 </div>
 <div class="ui-widget-detail">
		<ul class="ui-articles">
<li>
<div class="ui-article">
     <h1 class="ui-article-title sw-calendar-block-date">Today</h1>
     <p class="ui-article-description">
         <span class="sw-calendar-block-title"><a href="
https://www.nkcschools.org/site/Default.aspx?PageID=2&DomainID=4#calendar1/20200810/event/11858">Leadership Team Workshops</a></span>
     </p>
</div>
</li>
<li>
<div class="ui-article">
     <h1 class="ui-article-title sw-calendar-block-date">Tomorrow</h1>
     <p class="ui-article-description">
         <span class="sw-calendar-block-title"><a href="
https://www.nkcschools.org/site/Default.aspx?PageID=2&DomainID=4#calendar1/20200811/event/11860">New &amp; Beginning Teacher Orientation</a></span>
     </p>
</div>
</li>
<li>
<div class="ui-article">
     <h1 class="ui-article-title sw-calendar-block-date">Wednesday</h1>
     <p class="ui-article-description">
         <span class="sw-calendar-block-title"><a href="
https://www.nkcschools.org/site/Default.aspx?PageID=2&DomainID=4#calendar1/20200812/event/11861">New &amp; Beginning Teacher Orientation</a></span>
     </p>
</div>
</li>
<li>
<div class="ui-article">
     <h1 class="ui-article-title sw-calendar-block-date">Thursday</h1>
     <p class="ui-article-description">
         <span class="sw-calendar-block-title"><a href="
https://www.nkcschools.org/site/Default.aspx?PageID=2&DomainID=4#calendar1/20200813/event/11862">New &amp; Beginning Teacher Orientation</a></span>
     </p>
</div>
</li>
<li>
<div class="ui-article">
     <h1 class="ui-article-title sw-calendar-block-date">Friday</h1>
     <p class="ui-article-description">
         <span class="sw-calendar-block-title"><a href="
https://www.nkcschools.org/site/Default.aspx?PageID=2&DomainID=4#calendar1/20200814/event/11863">New &amp; Beginning Teacher Orientation</a></span>
     </p>
</div>
</li>
<li>
<div class="ui-article">
     <h1 class="ui-article-title sw-calendar-block-date">August 17, 2020</h1>
     <p class="ui-article-description">
         <span class="sw-calendar-block-title"><a href="
https://www.nkcschools.org/site/Default.aspx?PageID=2&DomainID=4#calendar1/20200817/event/11864">Teacher Workday</a></span>
     </p>
</div>
</li>
<li>
<div class="ui-article">
     <h1 class="ui-article-title sw-calendar-block-date">August 18, 2020</h1>
     <p class="ui-article-description">
         <span class="sw-calendar-block-title"><a href="
https://www.nkcschools.org/site/Default.aspx?PageID=2&DomainID=4#calendar1/20200818/event/11865">Building Based Workshop - Elementary</a></span>
     </p>
</div>
</li>
	</ul>
<a class='view-calendar-link' href="/Page/2"><span>View Calendar</span></a>
 </div>
 <div class="ui-widget-footer">
 </div>
</div>
</div>
</div>
<div id='pmi-7246'>



<div id='sw-module-70290'>
    <script type="text/javascript">
        $(document).ready(function() {
            var DomainID = '4';
            var PageID = '1';
            var RenderLoc = '0';
            var MIID = '7029';

            //added to check to make sure moderated content doesn't bleed through the dialog
            if ($('#dialog-overlay-WindowLargeModal-body.moderateContent').length > 0) {
                $("#module-content-" + MIID).find(".ui-widget-detail").find(".ui-article").append("<p>&nbsp;</p>");
            }
        });
    </script>

    <script type="text/javascript">$(document).ready(function() {CheckScript('ModuleView');CheckScript('Mustache');
 });</script>
    
    <div id="module-content-7029" >
<div class="ui-widget app flexpage">
	<div class="ui-widget-header">
		<h1>NKC Schools on Twitter</h1>
	</div>
	
	<div class="ui-widget-detail">
<div class="ui-article"><span ><a class="twitter-timeline" data-width="300" data-height="500" data-link-color="#000033" href="https://twitter.com/NKCSchools?ref_src=twsrc%5Etfw">Tweets by NKCSchools</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script></span></div> 
<div class="clear"></div>
</div>
	<div class="ui-widget-footer">
		
			
		
		<div class="clear"></div>
	</div>
</div>
<script type="text/javascript">
$(document).ready(function (){
$(".tag-list li a").keypress(function(e) { if(e.which == 13) { $(this).click();   }});
});
function LoadGroupedData(container, MIID, PMI, groupYear, groupMonth, groupBy, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&EnableQuirksMode=0&ViewID=' + viewToUse + '&Tag=' + tag, container, 2, 'chkSidebar();');
}
function LoadData(container, MIID, PMI, flexDataID, groupYear, groupMonth, groupBy, targetView, tag) {
  if(targetView !== undefined || targetView.Length() == 0){
  //targetView looks at the hidden Detail View defined in the Builder View.
      targetView = $('#hid-'+MIID+'-DetailView').val();
   }
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&FlexDataID=' + flexDataID + '&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&RenderLoc=0&FromRenderLoc=0&EnableQuirksMode=0&Tag=' + tag + '&ViewID=' + targetView, container, 2, 'chkSidebar();');
}
function LoadTaggedData(container, MIID, PMI, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&Tag=' + tag + '&EnableQuirksMode=0&ViewID='+viewToUse, container, 2, 'chkSidebar();');
  setTimeout(function(){ $("#module-content-"+ MIID +"").find('[tabindex]:first').focus(); }, 200);
}
</script>
</div>

</div></div>
</div>
                        </div>
                        <div class="hp-column two">
                        	<div class="flex">
                            	<div id="sw-content-container3" class="region ui-hp"><div id='pmi-97'>



<div id='sw-module-970'>
    <script type="text/javascript">
        $(document).ready(function() {
            var DomainID = '4';
            var PageID = '1';
            var RenderLoc = '0';
            var MIID = '97';

            //added to check to make sure moderated content doesn't bleed through the dialog
            if ($('#dialog-overlay-WindowLargeModal-body.moderateContent').length > 0) {
                $("#module-content-" + MIID).find(".ui-widget-detail").find(".ui-article").append("<p>&nbsp;</p>");
            }
        });
    </script>

    <script type="text/javascript">$(document).ready(function() {CheckScript('ModuleView');CheckScript('Mustache');
 });</script>
    
    <div id="module-content-97">
<div class="ui-widget app headlines">
	
	<div class="ui-widget-header">
		<h1>Latest News</h1>
	</div>
	
	<div class="ui-widget-detail" id="sw-app-headlines-97">
		<ul class="ui-articles">
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt="September 8 " height="80" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/sep 8.jpeg">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="https://www.nkcschools.org/Page/2" target="_blank"><span>Updated Academic Calendars for 2020-21</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">The Board of Education approved new academic calendars for the upcoming school year. The first day of school will be September 8. View calendars to see additional changes.</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Updated Academic Calendars for 2020-21" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28859&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt="computer clipart" height="80" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/online registration.jpg">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="https://www.nkcschools.org/Page/5171" target="_blank"><span>Select a Virtual Option by Friday, August 14</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">We will provide a continuum of learning options this school year. If selecting a virtual option for your student, please let us know here by Friday, August 14.</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Select a Virtual Option by Friday, August 14" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28856&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt=" NKC Schools Parents as Teachers Logo Image" height="80" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/PAT.jpg">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="https://www.nkcschools.org/cms/lib/MO49000025/Centricity/Domain/4/2020-21_PAT_Enrollment_Info.pdf" target="_blank" data-ally-content-id="e9c9c81b-3cfc-4bcd-bc0e-b3ce554568ec" data-ally-file-eid="62886"><span>Parents as Teachers Enrollment for 2020-21</span></a><a href="#" data-ally-content-ref="e9c9c81b-3cfc-4bcd-bc0e-b3ce554568ec" data-ally-show="alternativeformats" data-ally-invoke="alternativeformats" data-ally-show-display="inline" style="display:none;padding-left:5px;" class="bb-icon-ally-download-transparent" role="button" title="Alternative Formats" aria-label="Alternative Formats" onclick="AddAnalyticsEvent('Ally', 'Download Alternative Formats', 'Headlines & Features');" translate="no"></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Parents as Teachers will provide high-quality connections and support virtually for 2020-21!</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Parents as Teachers Enrollment for 2020-21" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28693&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt=" NKC Schools Logo" height="80" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/district logo square.png">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="https://www.nkcschools.org/coronavirus" target="_blank"><span>Return to School Planning</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Learn more about the NKC Schools Return to School Plan, which was created in collaboration with other local school districts and with input from our stakeholder groups.</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Return to School Planning" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28647&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt=" School supply drive clip art" height="53" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/School_Supply_Drive.jpg">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="https://www.nkcschools.org/cms/lib/MO49000025/Centricity/Domain/4/School_Supply_Drive_Flyer_2020.pdf" target="_blank" data-ally-content-id="02e6fa18-d7bd-4427-b7ca-ee1ee025b970" data-ally-file-eid="62608"><span>School Supply Online Donation Drive</span></a><a href="#" data-ally-content-ref="02e6fa18-d7bd-4427-b7ca-ee1ee025b970" data-ally-show="alternativeformats" data-ally-invoke="alternativeformats" data-ally-show-display="inline" style="display:none;padding-left:5px;" class="bb-icon-ally-download-transparent" role="button" title="Alternative Formats" aria-label="Alternative Formats" onclick="AddAnalyticsEvent('Ally', 'Download Alternative Formats', 'Headlines & Features');" translate="no"></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Our Partners in Education and the Education Foundation are teaming up to help students get ready for a new year!</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for School Supply Online Donation Drive" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28564&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt=" Clip art of an immunization record" height="74" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/iStock_000078387753_Medium.jpg">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28524&PageID=1"><span>Immunizations Required Prior to the Start of School</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">The Missouri Bureau of Immunizations has confirmed that they will not be issuing waivers or accepting delays regarding the required immunizations due to COVID-19.</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Immunizations Required Prior to the Start of School" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28524&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt=" Clay County Children&#39;s Fund Logo Image" height="44" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/ClayCoChildrensFund_Logo.jpg.jpg">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28512&PageID=1"><span>District Awarded Grant from Clay County Children&#39;s Fund</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Earmarked funds will allow for the continuation and expansion of mental health services. </p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for District Awarded Grant from Clay County Children&#39;s Fund" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28512&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt="" height="80" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/district logo square.png">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28425&PageID=1"><span>NKC Schools Statement on Equity</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">We stand with our community, especially our students, families and staff of color, against any and all forms of injustice, including racial injustice, and acts of violence. </p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for NKC Schools Statement on Equity" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28425&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt=" Kindergarten Enrollment Graphic Image" height="80" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/Kindergarten Enrollment.png">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28259&PageID=1"><span>Kindergarten Enrollment for 2020-21 Now Open</span></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Spring has arrived and with it time for kindergarten students to enroll for the 2020-21 school year! Families of incoming kindergartners can enroll online.</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Kindergarten Enrollment for 2020-21 Now Open" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=28259&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
<li>  
    <div class="ui-article">   
        <span class="ui-article-thumb" aria-hidden="true">
            <span class="img">
                <img alt=" Handprint graphic image" height="77" width="80" src="../..//cms/lib/MO49000025/Centricity/Domain/4/handprints.jpg">
            </span>
        </span>   
        
        <h1 class="ui-article-title">
        	<a href="/cms/lib/MO49000025/Centricity/Domain/95/Preschool_screening_letter.pdf" target="_blank" data-ally-content-id="398f0ff0-8283-4b6b-8098-050276dffda2" data-ally-file-eid="61615"><span>Online Title I Pre-K Screenings for 2020-21</span></a><a href="#" data-ally-content-ref="398f0ff0-8283-4b6b-8098-050276dffda2" data-ally-show="alternativeformats" data-ally-invoke="alternativeformats" data-ally-show-display="inline" style="display:none;padding-left:5px;" class="bb-icon-ally-download-transparent" role="button" title="Alternative Formats" aria-label="Alternative Formats" onclick="AddAnalyticsEvent('Ally', 'Download Alternative Formats', 'Headlines & Features');" translate="no"></a>
            </h1>     <!--"-->
        <p class="ui-article-description">Screenings assess development in the areas of language, gross and fine motor and social skills. Appointments can currently be scheduled online..</p>   
        <div class="ui-article-controls">                                    
            <a class="sub-link" title="Go to comments for Online Title I Pre-K Screenings for 2020-21" href="../../site/default.aspx?PageType=3&DomainID=4&ModuleInstanceID=97&ViewID=6446EE88-D30C-497E-9316-3F8874B3E108&RenderLoc=0&FlexDataID=27697&PageID=1&Comments=true"><span>Comments (-1)</span></a>
               
        </div>   
        <div class="clear"></div>  
    </div>
</li>
</ul>
	</div>

	<div class="ui-widget-footer">
		
		
		<div class="clear"></div>
	</div>
</div>
<script type="text/javascript">
	$(document).ready(function() {
        /*$(document).on('click', 'a.ui-article-thumb', function() {
        	window.location = $(this).attr('href');
    	});*/
    		
		$('#sw-app-headlines-97').find('img').each(function() {
			if ($.trim(this.src) == '' ) {
				$(this).parent().parent().remove();
			}
		});
        
        // Jason Smith - 12/9/2014 - Removed due to bandwidth implications
		
	});

</script>
<script type="text/javascript">
$(document).ready(function (){
$(".tag-list li a").keypress(function(e) { if(e.which == 13) { $(this).click();   }});
});
function LoadGroupedData(container, MIID, PMI, groupYear, groupMonth, groupBy, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&EnableQuirksMode=0&ViewID=' + viewToUse + '&Tag=' + tag, container, 2, 'chkSidebar();');
}
function LoadData(container, MIID, PMI, flexDataID, groupYear, groupMonth, groupBy, targetView, tag) {
  if(targetView !== undefined || targetView.Length() == 0){
  //targetView looks at the hidden Detail View defined in the Builder View.
      targetView = $('#hid-'+MIID+'-DetailView').val();
   }
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&FlexDataID=' + flexDataID + '&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&RenderLoc=0&FromRenderLoc=0&EnableQuirksMode=0&Tag=' + tag + '&ViewID=' + targetView, container, 2, 'chkSidebar();');
}
function LoadTaggedData(container, MIID, PMI, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&Tag=' + tag + '&EnableQuirksMode=0&ViewID='+viewToUse, container, 2, 'chkSidebar();');
  setTimeout(function(){ $("#module-content-"+ MIID +"").find('[tabindex]:first').focus(); }, 200);
}
</script>
</div>

</div></div>
<div id='pmi-7247'>



<div id='sw-module-70300'>
    <script type="text/javascript">
        $(document).ready(function() {
            var DomainID = '4';
            var PageID = '1';
            var RenderLoc = '0';
            var MIID = '7030';

            //added to check to make sure moderated content doesn't bleed through the dialog
            if ($('#dialog-overlay-WindowLargeModal-body.moderateContent').length > 0) {
                $("#module-content-" + MIID).find(".ui-widget-detail").find(".ui-article").append("<p>&nbsp;</p>");
            }
        });
    </script>

    <script type="text/javascript">$(document).ready(function() {CheckScript('ModuleView');CheckScript('Mustache');
 });</script>
    
    <div id="module-content-7030" >
<div class="ui-widget app flexpage">
	<div class="ui-widget-header">
		<h1>NKC Schools on Facebook</h1>
	</div>
	
	<div class="ui-widget-detail">
<div class="ui-article"><span ><div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = 'https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v3.1';
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>

<div class="fb-page" data-href="https://www.facebook.com/NKCSchools/" data-tabs="timeline" data-small-header="true"  data-width="500" data-hide-cover="true" data-show-facepile="false"><blockquote cite="https://www.facebook.com/NKCSchools/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/NKCSchools/">North Kansas City Schools</a></blockquote></div></span></div> 
<div class="clear"></div>
</div>
	<div class="ui-widget-footer">
		
			
		
		<div class="clear"></div>
	</div>
</div>
<script type="text/javascript">
$(document).ready(function (){
$(".tag-list li a").keypress(function(e) { if(e.which == 13) { $(this).click();   }});
});
function LoadGroupedData(container, MIID, PMI, groupYear, groupMonth, groupBy, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&EnableQuirksMode=0&ViewID=' + viewToUse + '&Tag=' + tag, container, 2, 'chkSidebar();');
}
function LoadData(container, MIID, PMI, flexDataID, groupYear, groupMonth, groupBy, targetView, tag) {
  if(targetView !== undefined || targetView.Length() == 0){
  //targetView looks at the hidden Detail View defined in the Builder View.
      targetView = $('#hid-'+MIID+'-DetailView').val();
   }
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&FlexDataID=' + flexDataID + '&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&RenderLoc=0&FromRenderLoc=0&EnableQuirksMode=0&Tag=' + tag + '&ViewID=' + targetView, container, 2, 'chkSidebar();');
}
function LoadTaggedData(container, MIID, PMI, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&Tag=' + tag + '&EnableQuirksMode=0&ViewID='+viewToUse, container, 2, 'chkSidebar();');
  setTimeout(function(){ $("#module-content-"+ MIID +"").find('[tabindex]:first').focus(); }, 200);
}
</script>
</div>

</div></div>
</div>
                            	<div id="sw-content-container4" class="region ui-hp"><div id='pmi-98'>
<div id="module-content-98" >
<div class="ui-widget app navigation  siteshortcuts">
	<div class="ui-widget-header"><h1>Quick Links</h1></div>
	<div class="ui-widget-detail">
		<ul class="site-shortcuts">
<li id="siteshortcut-1239" class=""><a href="/Page/708" target="_parent" >Business Partnerships</a>
</li>
<li id="siteshortcut-1237" class=""><a href="/Page/705" target="_parent" >Community Education</a>
</li>
<li id="siteshortcut-1293" class=""><a href="/Page/4499" target="_parent" >Missouri Course Access and Virtual School Program</a>
</li>
<li id="siteshortcut-1236" class=""><a href="/Page/4189" target="_parent" >eCampus Fueled by Launch</a>
</li>
<li id="siteshortcut-1180" class=""><a href="/Page/730" target="_parent" >Enrollment &amp; Registration</a>
</li>
<li id="siteshortcut-1285" class=""><a href="https://www2.mypaymentsplus.com/welcome" target="_blank" >MyPaymentsPlus</a>
</li>
<li id="siteshortcut-1240" class=""><a href="https://login.microsoftonline.com/common/oauth2/authorize?client_id=00000002-0000-0ff1-ce00-000000000000&amp;redirect_uri=https%3a%2f%2foutlook.office365.com%2fowa%2f&amp;resource=00000002-0000-0ff1-ce00-000000000000&amp;response_mode=form_post&amp;response_type=code+id_token&amp;scope=openid&amp;msafed=0&amp;client-request-id=e6594b7f-0f3a-484d-80db-ecb3374de38c&amp;protectedtoken=true&amp;domain_hint=nkcschools.org&amp;nonce=636736701102784392.c0505251-b65a-4c75-92a5-50a479825acc&amp;state=DYtBDoAgDMBAn-A7kDEYg-fMHTTRSKIHv--Strd659xsTqYHi-OaKxuQEiC3kjuuCgSElMJWSUJRptBRKBBI4d6QRNXbu8TxSbxPffUY43rX8ew_" target="_blank" >Student/Staff Email</a>
</li>
<li id="siteshortcut-2" class=""><a href="http://open.nkcschools.org/links/staff" target="_blank" >Student/Staff Links</a>
</li>
<li id="siteshortcut-1238" class=""><a href="/Page/667" target="_parent" >YouthFriends</a>
</li></ul>
<div class="app-level-social-follow"></div>
	</div>
	<div class="ui-widget-footer">
	</div>
</div></div>
</div>
<div id='pmi-9728'>



<div id='sw-module-67040'>
    <script type="text/javascript">
        $(document).ready(function() {
            var DomainID = '4';
            var PageID = '1';
            var RenderLoc = '0';
            var MIID = '6704';

            //added to check to make sure moderated content doesn't bleed through the dialog
            if ($('#dialog-overlay-WindowLargeModal-body.moderateContent').length > 0) {
                $("#module-content-" + MIID).find(".ui-widget-detail").find(".ui-article").append("<p>&nbsp;</p>");
            }
        });
    </script>

    <script type="text/javascript">$(document).ready(function() {CheckScript('ModuleView');CheckScript('Mustache');
 });</script>
    
    <div id="module-content-6704">
<div class="ui-widget app flexpage">
	<div class="ui-widget-header">
		<h1>Community Education Classes</h1>
	</div>
	
	<div class="ui-widget-detail">
		<ul class="ui-articles">
<li>
	<div class="ui-article">
		<div class="ui-article-description">
        	<span><span><p><a href="https://www.nkcschools.org/cms/lib/MO49000025/Centricity/Domain/6250/ces-summer-2020-brochure.pdf" target="_blank" rel="noopener noreferrer" data-ally-content-id="0f09bbaf-4ffb-4284-9f3c-b9ac336f85aa" data-ally-file-eid="61885"><img title="Summer 2020 Community Ed Catalog Cover Image" src="/cms/lib/MO49000025/Centricity/Domain/4/ces-summer-2020-brochure-cover.jpg" alt="Summer 2020 Community Ed Catalog Cover Image " width="300" height="384"></a><a href="#" data-ally-content-ref="0f09bbaf-4ffb-4284-9f3c-b9ac336f85aa" data-ally-show="alternativeformats" data-ally-invoke="alternativeformats" data-ally-show-display="inline" style="display:none;padding-left:5px;" class="bb-icon-ally-download-transparent" role="button" title="Alternative Formats" aria-label="Alternative Formats" onclick="AddAnalyticsEvent('Ally', 'Download Alternative Formats', 'Content');" translate="no"></a></p></span></span>
        </div>
		<div class="clear"></div>
	</div>
</li>
</ul>
</div>
	<div class="ui-widget-footer">
		
			
		
		<div class="clear"></div>
	</div>
</div>
<script type="text/javascript">
$(document).ready(function (){
$(".tag-list li a").keypress(function(e) { if(e.which == 13) { $(this).click();   }});
});
function LoadGroupedData(container, MIID, PMI, groupYear, groupMonth, groupBy, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&EnableQuirksMode=0&ViewID=' + viewToUse + '&Tag=' + tag, container, 2, 'chkSidebar();');
}
function LoadData(container, MIID, PMI, flexDataID, groupYear, groupMonth, groupBy, targetView, tag) {
  if(targetView !== undefined || targetView.Length() == 0){
  //targetView looks at the hidden Detail View defined in the Builder View.
      targetView = $('#hid-'+MIID+'-DetailView').val();
   }
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&FlexDataID=' + flexDataID + '&GroupYear=' + groupYear + '&GroupMonth=' + groupMonth + '&GroupByField=' + groupBy + '&RenderLoc=0&FromRenderLoc=0&EnableQuirksMode=0&Tag=' + tag + '&ViewID=' + targetView, container, 2, 'chkSidebar();');
}
function LoadTaggedData(container, MIID, PMI, tag) {
  //ViewToUse looks at the hidden Sidebar List View defined in the Builder View.
  var viewToUse = "";
    if($('#hid-'+MIID+'-SidebarListView').length > 0){
      viewToUse = $("#hid-" + MIID + "-SidebarListView").val();
    };
  GetContent('https://www.nkcschools.org//cms/UserControls/ModuleView/ModuleViewRendererWrapper.aspx?DomainID=4&PageID=1&ModuleInstanceID=' + MIID + '&PageModuleInstanceID=' + PMI + '&RenderLoc=0&FromRenderLoc=0&Tag=' + tag + '&EnableQuirksMode=0&ViewID='+viewToUse, container, 2, 'chkSidebar();');
  setTimeout(function(){ $("#module-content-"+ MIID +"").find('[tabindex]:first').focus(); }, 200);
}
</script>
</div>

</div></div>
</div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>
		</section>
	</main>
	<footer class="gb-section-parent">
		<section id="gb-footer-outer" class="gb-section-parent">
			<div id="gb-footer" class="gb-section">
            	<div class="gb-footer-row one flex flex-justify-space">
                    <div class="gb-footer one flex flex-justify-center">
                    	<h2>NKC SCHOOLS</h2>
                    </div>
                    <div class="gb-footer two border-box flex flex-column">
                        <div id="gb-footer-mystart" class="flex">
                        	<div class="cs-mystart-item find-us"><a href="/Page/137">Find Us</a></div>
                            <div class="cs-mystart-item cs-sitemap">
                                <a href="/site/Default.aspx?PageType=15&SiteID=4&SectionMax=15&DirectoryType=6">Site Map</a>
                            </div>
                        </div>
                    </div>
                    <div class="gb-footer-info gb-footer hide960 show768">
                        <p>2000 NE 46th St.<span class="cs-spacer"></span>Kansas City, MO 64116 <a class="gb-phone" data-phone="816.321.5000 " href="tel:816.321.5000 "><span class="cs-spacer"></span><br class="hide960 show480"/><span class="acc-hidden">Phone</span><span aria-hidden="true">P</span>:  816.321.5000 </a><span class="gb-fax" data-fax=""><span class="cs-spacer"></span><span class="acc-hidden">Fax</span><span aria-hidden="true">F</span>:  </span></p>
                    </div>
                    <div class="gb-footer three border-box flex"></div>
                    <div class="gb-footer four border-box flex flex-items-center flex-justify-end"></div>
            	</div>
				<div class="gb-footer-row two flex flex-items-center flex-justify-space">
                    <div class="gb-footer-info gb-footer hide768">
                        <p>2000 NE 46th St.<span class="cs-spacer"></span>Kansas City, MO 64116 <a class="gb-phone" data-phone="816.321.5000 " href="tel:816.321.5000 "><span class="cs-spacer"></span><span class="acc-hidden">Phone</span><span aria-hidden="true">P</span>:  816.321.5000 </a><span class="gb-fax" data-fax=""><span class="cs-spacer"></span><span class="acc-hidden">Fax</span><span aria-hidden="true">F</span>:  </span></p>
                    </div>
                    <div id="gb-legal-footer" class="flex flex-items-center">
                        <div class="gb-legal-logo"></div>
                        <div id="gb-legal-footer-links-copyright">
                            <div class="gb-legal-footer links"></div>
                            <div class="gb-legal-footer copyright"></div>
                        </div>
                    </div>
				</div>
			</div>
            <div id="cs-back-to-top" class="transition-all flex flex-items-center flex-justify-center" role="button" tabindex="0" aria-label="Scroll to the top of the page">
                <span class="hide960 show480">BACK TO TOP</span>
                <span class="cs-dev-icons cs-dev-icon-chevron"></span>
            </div>
		</section>
	</footer>
</div><!-- BEGIN - STANDARD FOOTER -->
<div id='sw-footer-outer'>
<div id='sw-footer-inner'>
<div id='sw-footer-left'></div>
<div id='sw-footer-right'>
<div id='sw-footer-links'>
<ul>
<li><a title='Click to email the primary contact' href='mailto:communications@nkcschools.org'>Questions or Feedback?</a> | </li>
<li><a href='https://www.blackboard.com/blackboard-web-community-manager-privacy-statement' target="_blank">Blackboard Web Community Manager Privacy Policy (Updated)</a> | </li>
<li><a href='https://help.blackboard.com/Terms_of_Use' target="_blank">Terms of Use</a></li>
</ul>
</div>
<div id='sw-footer-copyright'>Copyright &copy; 2002-2020 Blackboard, Inc. All rights reserved.</div>
<div id='sw-footer-logo'><a href='http://www.blackboard.com' title="Blackboard, Inc. All rights reserved.">
<img src='https://www.nkcschools.org/Static//GlobalAssets/Images/Navbar/blackboard_logo.png'
 alt="Blackboard, Inc. All rights reserved."/>
</a></div>
</div>
</div>
</div>
<!-- END - STANDARD FOOTER -->
<script type="text/javascript">
   $(document).ready(function(){
      var beaconURL='https://analytics.schoolwires.com/analytics.asmx/Insert?AccountNumber=XNJ6GbzuzcdD5dO1qpF0TQ%3d%3d&SessionID=c7031911-30db-41cd-a7d5-b9e53e782c28&SiteID=4&ChannelID=0&SectionID=4&PageID=1&HitDate=8%2f10%2f2020+4%3a54%3a15+PM&Browser=Unknown+0.0&OS=Unknown&IPAddress=10.61.2.92';
      try {
         $.getJSON(beaconURL + '&jsonp=?', function(myData) {});
      } catch(err) { 
         // prevent site error for analytics
      }
   });
</script>

    <input type="hidden" id="hid-pageid" value="1" />

    

    <div id='dialog-overlay-WindowMedium-base' class='ui-dialog-overlay-base' ><div id='WindowMedium' role='dialog' tabindex='-1'  class='ui-dialog-overlay medium' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-WindowMedium-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-WindowMedium-body' ></div><button class='ui-dialog-overlay-close' title='Close' aria-label='Close' onclick='CloseDialogOverlay("WindowMedium");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-WindowMedium-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-WindowMedium-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>
    <div id='dialog-overlay-WindowSmall-base' class='ui-dialog-overlay-base' ><div id='WindowSmall' role='dialog' tabindex='-1'  class='ui-dialog-overlay small' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-WindowSmall-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-WindowSmall-body' ></div><button class='ui-dialog-overlay-close' title='Close' aria-label='Close' onclick='CloseDialogOverlay("WindowSmall");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-WindowSmall-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-WindowSmall-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>
    <div id='dialog-overlay-WindowLarge-base' class='ui-dialog-overlay-base' ><div id='WindowLarge' role='dialog' tabindex='-1'  class='ui-dialog-overlay large' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-WindowLarge-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-WindowLarge-body' ></div><button class='ui-dialog-overlay-close' title='Close' aria-label='Close' onclick='CloseDialogOverlay("WindowLarge");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-WindowLarge-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-WindowLarge-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>

    <div id='dialog-overlay-WindowMediumModal-base' class='ui-dialog-overlay-base-modal' ><div id='WindowMediumModal' role='dialog' tabindex='-1'  class='ui-dialog-overlay medium' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-WindowMediumModal-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-WindowMediumModal-body' ></div><button class='ui-dialog-overlay-close modal' title='Close' aria-label='Close' onclick='CloseDialogOverlay("WindowMediumModal");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-WindowMediumModal-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-WindowMediumModal-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>
    <div id='dialog-overlay-WindowSmallModal-base' class='ui-dialog-overlay-base-modal' ><div id='WindowSmallModal' role='dialog' tabindex='-1'  class='ui-dialog-overlay small' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-WindowSmallModal-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-WindowSmallModal-body' ></div><button class='ui-dialog-overlay-close modal' title='Close' aria-label='Close' onclick='CloseDialogOverlay("WindowSmallModal");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-WindowSmallModal-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-WindowSmallModal-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>
    <div id='dialog-overlay-WindowLargeModal-base' class='ui-dialog-overlay-base-modal' ><div id='WindowLargeModal' role='dialog' tabindex='-1'  class='ui-dialog-overlay large' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-WindowLargeModal-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-WindowLargeModal-body' ></div><button class='ui-dialog-overlay-close modal' title='Close' aria-label='Close' onclick='CloseDialogOverlay("WindowLargeModal");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-WindowLargeModal-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-WindowLargeModal-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>
    <div id='dialog-overlay-WindowXLargeModal-base' class='ui-dialog-overlay-base-modal' ><div id='WindowXLargeModal' role='dialog' tabindex='-1'  class='ui-dialog-overlay xlarge' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-WindowXLargeModal-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-WindowXLargeModal-body' ></div><button class='ui-dialog-overlay-close modal' title='Close' aria-label='Close' onclick='CloseDialogOverlay("WindowXLargeModal");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-WindowXLargeModal-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-WindowXLargeModal-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>

    <div id='dialog-overlay-MyAccountSubscriptionOverlay-base' class='ui-dialog-overlay-base-modal' ><div id='MyAccountSubscriptionOverlay' role='dialog' tabindex='-1'  class='ui-dialog-overlay medium' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-MyAccountSubscriptionOverlay-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-MyAccountSubscriptionOverlay-body' ></div><button class='ui-dialog-overlay-close modal' title='Close' aria-label='Close' onclick='CloseDialogOverlay("MyAccountSubscriptionOverlay");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-MyAccountSubscriptionOverlay-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-MyAccountSubscriptionOverlay-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>

    <div id='dialog-overlay-InsertOverlay-base' class='ui-dialog-overlay-base-modal' ><div id='InsertOverlay' role='dialog' tabindex='-1'  class='ui-dialog-overlay large' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-InsertOverlay-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-InsertOverlay-body' ></div><button class='ui-dialog-overlay-close modal' title='Close' aria-label='Close' onclick='CloseDialogOverlay("InsertOverlay");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-InsertOverlay-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-InsertOverlay-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>
    <div id='dialog-overlay-InsertOverlay2-base' class='ui-dialog-overlay-base-modal' ><div id='InsertOverlay2' role='dialog' tabindex='-1'  class='ui-dialog-overlay large' ><div class='ui-dialog-overlay-title-bar' id='dialog-overlay-InsertOverlay2-title-bar' ></div><div class='ui-dialog-overlay-body' id='dialog-overlay-InsertOverlay2-body' ></div><button class='ui-dialog-overlay-close modal' title='Close' aria-label='Close' onclick='CloseDialogOverlay("InsertOverlay2");' ></button><div class='ui-dialog-overlay-footer' id='dialog-overlay-InsertOverlay2-footer' ></div></div></div>

<script type="text/javascript">
    $(document).ready(function() {
        $('#dialog-overlay-InsertOverlay2-base').appendTo('body');
        
        $('body').on('keydown', '.ui-dialog-overlay-base-modal, .ui-dialog-overlay, .ui-sw-alert', function (e) {
            var swAlertOpen = $(".ui-sw-alert").length;
            if (swAlertOpen > 1) {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    //get id of open alert
                    var alertboxid = $('.ui-sw-alert').attr('id');
                    //click ok or no
                    if ($('#' + alertboxid + 'ok').length > 0) {
                        $('#' + alertboxid + 'ok').click();
                    } else {
                        $('#' + alertboxid + 'no').click();
                    }
                }
            } else {
                if (e.keyCode == 27) {//escape key
                    e.stopImmediatePropagation();
                    e.preventDefault();
                    // Check if ESC was pressed on DatePicker
                    var raisedByDatepicker = e.target.classList.contains("datepicker");
                    if (!raisedByDatepicker) {
                        e.stopImmediatePropagation();
                        e.preventDefault();
                        // Close Dialog
                        $('.ui-dialog-overlay-close.modal:visible').last().click();
                    } else {
                        // Remove focus
                        e.target.blur();
                        e.target.classList.remove("focus");
                    }
                }
            }
        });
 		
        

    });
</script>
    
    <div id="videowrapper" class="ui-helper-hidden">
        <div id="videodialog" role="application">
            <a id="videodialog-close" role="button" href="javascript:;" aria-label="Close Overlay" class="close-btn" onclick="closeVideoDialog();">CLOSE</a>
            <div id="videodialog-video" ></div>
            <div id="videodialog-foot" tabindex="0"></div>
        </div>
    </div>
    <div id="attachmentwrapper" class="ui-helper-hidden">
        <div id="attachmentdialog" role="application">
            <a id="attachmentdialog-close" role="button" href="javascript:;" aria-label="Close Overlay" class="close-btn" onclick="closeAttachmentDialog();">CLOSE</a>
            <div id="attachmentdialog-container"></div>
        </div>
    </div>
    <script type="text/javascript">

        $(document).ready(function () {

            removeBrokenImages();
            checkSidebar();
            RemoveCookie();

            $('div.bullet').attr('tabindex', '');

            $('.navigation li.collapsible').each(function () {
                if ($(this).find('ul').length == 0) {
                    $(this).removeClass('collapsible');
                }
            });

            // find page nav state cookie and add open chevron
            var arrValues = GetCookie('SWPageNavState').split('~');

            $.each(arrValues, function () {
                if (this != '') {
                    $('#' + this).addClass('collapsible').prepend("<div class='bullet collapsible' aria-label='Close Page Submenu'/>");
                }
            });

            // find remaining sub menus and add closed chevron and close menu
            $('.navigation li > ul').each(function () {
                var list = $(this);

                if (list.parent().hasClass('active') && !list.parent().hasClass('collapsible')) {
                    // open sub for currently selected page                    
                    list.parent().addClass('collapsible').prepend("<div class='bullet collapsible'aria-label='Close Page Submenu' />");
                } else {
                    if (list.parent().hasClass('collapsible') && !list.siblings('div').hasClass('collapsible')) {
                        // open sub for page with auto expand
                        list.siblings('div.expandable').remove();
                        list.parent().prepend("<div class='bullet collapsible' aria-label='Close Page Submenu' />");
                    }
                }

                if (!list.siblings('div').hasClass('collapsible')) {
                    // keep all closed that aren't already set to open
                    list.parent().addClass('expandable').prepend("<div class='bullet expandable' aria-label='Open Page Submenu' />");
                    ClosePageSubMenu(list.parent());
                } else {
                    OpenPageSubMenu(list.parent());
                }
            });

            // remove bullet from hierarchy if no-bullet set
            $('.navigation li.collapsible').each(function () {
                if ($(this).hasClass('no-bullet')) {
                    if (!$(this).hasClass('navigationgroup')) { $(this).removeClass('collapsible'); }
                    $(this).children('div.collapsible').remove();
                }
            });

            $('.navigation li.expandable').each(function () {
                if ($(this).hasClass('no-bullet')) {
                    if (!$(this).hasClass('navigationgroup')) { $(this).removeClass('expandable'); }
                    $(this).children('div.expandable').remove();
                }
            });

            $('.navigation li:not(.collapsible,.expandable,.no-bullet)').each(function () {
                $(this).prepend("<div class='bullet'/>");
            });

            $('.navigation li.active').parents('ul').each(function () {
                if (!$(this).hasClass('page-navigation')) {
                    OpenPageSubMenu($(this).parent());
                }
            });

            // Set aria ttributes
            $('li.collapsible').each(function () {
                $(this).attr("aria-expanded", "true");
                $(this).find('div:first').attr('aria-pressed', 'true');
            });

            $('li.expandable').each(function () {
                $(this).attr("aria-expanded", "false");
                $(this).find('div:first').attr('aria-pressed', 'false');
            });

            $('div.bullet').each(function () {
                $(this).attr("aria-hidden", "true");
            });

            // set click event for chevron
            $(document).on('click', '.navigation div.collapsible', function () {
                ClosePageSubMenu($(this).parent());
            });

            $(document).on('click', '.navigation div.expandable', function () {
                OpenPageSubMenu($(this).parent());
            });

            // set navigation grouping links
            $(document).on('click', '.navigationgroup.collapsible > a', function () {
                ClosePageSubMenu($(this).parent());
            });

            $(document).on('click', '.navigationgroup.expandable > a', function () {
                OpenPageSubMenu($(this).parent());
            });

            //SW MYSTART DROPDOWNS
            $(document).on('click', '.sw-mystart-dropdown', function () {
                $(this).children(".sw-dropdown").css("display", "block");
            });

            $(".sw-mystart-dropdown").hover(function () { }, function () {
                $(this).children(".sw-dropdown").hide();
                $(this).blur();
            });

            //SW ACCOUNT DROPDOWN
            $(document).on('click', '#sw-mystart-account', function () {
                $(this).children("#sw-myaccount-list").show();
                $(this).addClass("clicked-state");
            });

            $("#sw-mystart-account, #sw-myaccount-list").hover(function () { }, function () {
                $(this).children("#sw-myaccount-list").hide();
                $(this).removeClass("clicked-state");
                $("#sw-myaccount").blur();
            });

            // set hover class for page and section navigation
            $('.ui-widget.app.pagenavigation, .ui-widget.app.sectionnavigation').find('li > a').hover(function () {
                $(this).addClass('hover');
            }, function () {
                $(this).removeClass('hover');
            });

            //set aria-label for home
            $('#navc-HP > a').attr('aria-label', 'Home');

            // set active class on channel and section
            var activeChannelNavType = $('input#hidActiveChannelNavType').val();
            if (activeChannelNavType == -1) {
                // homepage is active
                $('#navc-HP').addClass('active');
            } else if (activeChannelNavType == 1) {
                // calendar page is active
                $('#navc-CA').addClass('active');
            } else {
                // channel is active - set the active class on the channel
                var activeSelectorID = $('input#hidActiveChannel').val();
                $('#navc-' + activeSelectorID).addClass('active');

                // set the breadcrumb channel href to the channel nav href
                $('li[data-bccID=' + activeSelectorID + '] a').attr('href', $('#navc-' + activeSelectorID + ' a').attr('href'));
                $('li[data-bccID=' + activeSelectorID + '] a span').text($('#navc-' + activeSelectorID + ' a span').first().text());

                // set the active class on the section
                activeSelectorID = $('input#hidActiveSection').val();
                $('#navs-' + activeSelectorID).addClass('active');

                // set the breadcrumb section href to the channel nav href
                $('li[data-bcsID=' + activeSelectorID + '] a').attr('href', $('#navs-' + activeSelectorID + ' a').attr('href'));
                if ($('#navs-' + activeSelectorID + ' a').attr('target') !== undefined) {
                    $('li[data-bcsID=' + activeSelectorID + '] a').attr('target', $('#navs-' + activeSelectorID + ' a').attr('target'));
                }
                $('li[data-bcsID=' + activeSelectorID + '] span').text($('#navs-' + activeSelectorID + ' a span').text());

                if ($('.sw-directory-columns').length > 0) {
                    $('ul.ui-breadcrumbs li:last-child').remove();
                    $('ul.ui-breadcrumbs li:last-child a').replaceWith(function() { return $('span', this); });
                    $('ul.ui-breadcrumbs li:last-child span').append(' Directory');
                }
            }
        }); // end document ready

        function OpenPageSubMenu(li) {
            if (li.prop('tagName').toLowerCase() == "li") {
                if (li.hasClass('expandable')) {
                    li.removeClass('expandable').addClass('collapsible');
                }
                if (li.find('div:first').hasClass('expandable')) {
                    li.find('div:first').removeClass('expandable').addClass('collapsible').attr('aria-pressed', 'true').attr('aria-label','Close Page Submenu');
                }
                li.find('ul:first').attr('aria-hidden', 'false').show();

                li.attr("aria-expanded", "true");

                PageNavigationStateCookie();
            }
        }

        function ClosePageSubMenu(li) {
            if (li.prop('tagName').toLowerCase() == "li") {
                li.removeClass('collapsible').addClass('expandable');
                li.find('div:first').removeClass('collapsible').addClass('expandable').attr('aria-pressed', 'false').attr('aria-label','Open Page Submenu');
                li.find('ul:first').attr('aria-hidden', 'true').hide();

                li.attr("aria-expanded", "false");

                PageNavigationStateCookie();
            }
        }

        function PageNavigationStateCookie() {
            var strCookie = "";

            $('.pagenavigation li > ul').each(function () {
                var item = $(this).parent('li');
                if (item.hasClass('collapsible') && !item.hasClass('no-bullet')) {
                    strCookie += $(this).parent().attr('id') + '~';
                }
            });

            SetCookie('SWPageNavState', strCookie);
        }

        function checkSidebar() {
            $(".ui-widget-sidebar").each(function () {
                if ($.trim($(this).html()) != "") {
                    $(this).show();
                    $(this).siblings(".ui-widget-detail").addClass("with-sidebar");
                }
            });
        }

        function removeBrokenImages() {
            //REMOVES ANY BROKEN IMAGES
            $("span.img img").each(function () {
                if ($(this).attr("src") !== undefined && $(this).attr("src") != '../../') {
                    $(this).parent().parent().show();
                    $(this).parent().parent().siblings().addClass("has-thumb");
                }
            });
        }

        function LoadEventDetailUE(moduleInstanceID, eventDateID, userRegID, isEdit) {
            (userRegID === undefined ? userRegID = 0 : '');
            (isEdit === undefined ? isEdit = false : '');
            OpenDialogOverlay("WindowMediumModal", { LoadType: "U", LoadURL: "https://www.nkcschools.org//site/UserControls/Calendar/EventDetailWrapper.aspx?ModuleInstanceID=" + moduleInstanceID + "&EventDateID=" + eventDateID + "&UserRegID=" + userRegID + "&IsEdit=" + isEdit });
        }

        function RemoveCookie() {
            // There are no sub page            
            if ($('.pagenavigation li li').length == 0) {
                //return false;
                PageNavigationStateCookie();
            }
        }
    </script>

    <script type="text/javascript">

        function AddOffCanvasMenuHeightForSiteNav() {
            var sitenavulHeight = 0;

            if ($('#sw-pg-sitenav-ul').length > 0) {
                sitenavulHeight = parseInt($("#sw-pg-sitenav-ul").height());
            }

            var swinnerwrapHeight = 0;

            if ($('#sw-inner-wrap').length > 0) {
                swinnerwrapHeight = parseInt($("#sw-inner-wrap").height());
            }

            // 360px is abount 5 li height
            if (sitenavulHeight + 360 >= swinnerwrapHeight) {
                $("#sw-inner-wrap").height(sitenavulHeight + 360);
            }
        }

        function AddOffCanvasMenuHeightForSelectSchool() {
            var selectschoolulHeight = 0;

            if ($('#sw-pg-selectschool-ul').length > 0) {
                selectschoolulHeight = parseInt($("#sw-pg-selectschool-ul").height());
            }

            var swinnerwrapHeight = 0;

            if ($('#sw-inner-wrap').length > 0) {
                swinnerwrapHeight = parseInt($("#sw-inner-wrap").height());
            }

            // 360px is abount 5 li height
            if (selectschoolulHeight + 360 >= swinnerwrapHeight) {
                $("#sw-inner-wrap").height(selectschoolulHeight + 360);
            }
        }

        $(document).ready(function () {
            if ($("#sw-pg-sitenav-a").length > 0) {
                $(document).on('click', '#sw-pg-sitenav-a', function () {
                    if ($("#sw-pg-sitenav-ul").hasClass('sw-pgmenu-closed')) {
                        AddOffCanvasMenuHeightForSiteNav();

                        $("ul.sw-pgmenu-toplevel").removeClass('sw-pgmenu-open').addClass('sw-pgmenu-closed');
                        $("#sw-pg-sitenav-ul").removeClass('sw-pgmenu-closed');
                        $("#sw-pg-sitenav-ul").addClass('sw-pgmenu-open');
                    } else {
                        $("#sw-pg-sitenav-ul").removeClass('sw-pgmenu-open');
                        $("#sw-pg-sitenav-ul").addClass('sw-pgmenu-closed');
                    }
                });

                $(document).on('click', '#sw-pg-selectschool-a', function () {
                    if ($("#sw-pg-selectschool-ul").hasClass('sw-pgmenu-closed')) {
                        AddOffCanvasMenuHeightForSelectSchool();

                        $("ul.sw-pgmenu-toplevel").removeClass('sw-pgmenu-open').addClass('sw-pgmenu-closed');
                        $("#sw-pg-selectschool-ul").removeClass('sw-pgmenu-closed');
                        $("#sw-pg-selectschool-ul").addClass('sw-pgmenu-open');
                    } else {
                        $("#sw-pg-selectschool-ul").removeClass('sw-pgmenu-open');
                        $("#sw-pg-selectschool-ul").addClass('sw-pgmenu-closed');
                    }
                });

                $(document).on('click', '#sw-pg-myaccount-a', function () {
                    if ($("#sw-pg-myaccount-ul").hasClass('sw-pgmenu-closed')) {
                        $("ul.sw-pgmenu-toplevel").removeClass('sw-pgmenu-open').addClass('sw-pgmenu-closed');
                        $("#sw-pg-myaccount-ul").removeClass('sw-pgmenu-closed');
                        $("#sw-pg-myaccount-ul").addClass('sw-pgmenu-open');
                    } else {
                        $("#sw-pg-myaccount-ul").removeClass('sw-pgmenu-open');
                        $("#sw-pg-myaccount-ul").addClass('sw-pgmenu-closed');
                    }
                });

                $(document).on('click', '.pg-list-bullet', function () {
                    $(this).prev().toggle();

                    if ($(this).hasClass('closed')) {
                        AddOffCanvasMenuHeightForSiteNav();

                        $(this).removeClass('closed');
                        $(this).addClass('open');
                    } else {
                        $(this).removeClass('open');
                        $(this).addClass('closed');
                    }
                });

                $(document).on('mouseover', '#sw-pg-selectschool', function () {
                    $("#sw-pg-selectschool-firstli").removeClass('sw-pg-selectschool-firstli-mouseout').addClass('sw-pg-selectschool-firstli-mouseover');
                    $("#sw-pg-selectschool-firstli a").addClass('sw-pg-selectschool-firstli-a-mouseover').removeClass('sw-pg-selectschool-firstli-a-mouseout');
                });

                $(document).on('mouseout', '#sw-pg-selectschool', function () {
                    $("#sw-pg-selectschool-firstli").removeClass('sw-pg-selectschool-firstli-mouseover').addClass('sw-pg-selectschool-firstli-mouseout');
                    $("#sw-pg-selectschool-firstli a").addClass('sw-pg-selectschool-firstli-a-mouseout').removeClass('sw-pg-selectschool-firstli-a-mouseover');
                });

                $(document).on('mouseover', '#sw-pg-myaccount', function () {
                    $("#sw-pg-myaccount-firstli").removeClass('sw-pg-myaccount-firstli-mouseout').addClass('sw-pg-myaccount-firstli-mouseover');
                    $("#sw-pg-myaccount-firstli a").addClass('sw-pg-myaccount-firstli-a-mouseover').removeClass('sw-pg-myaccount-firstli-a-mouseout');
                });

                $(document).on('mouseout', '#sw-pg-myaccount', function () {
                    $("#sw-pg-myaccount-firstli").removeClass('sw-pg-myaccount-firstli-mouseover').addClass('sw-pg-myaccount-firstli-mouseout');
                    $("#sw-pg-myaccount-firstli a").addClass('sw-pg-myaccount-firstli-a-mouseout').removeClass('sw-pg-myaccount-firstli-a-mouseover');
                });

                $(document).on('mouseover', '#sw-pg-sitenav', function () {
                    $("#sw-pg-sitenav-firstli").removeClass('sw-pg-sitenav-firstli-mouseout').addClass('sw-pg-sitenav-firstli-mouseover');
                    $("#sw-pg-sitenav-firstli a").addClass('sw-pg-sitenav-firstli-a-mouseover').removeClass('sw-pg-sitenav-firstli-a-mouseout');
                });

                $(document).on('mouseout', '#sw-pg-sitenav', function () {
                    $("#sw-pg-sitenav-firstli").removeClass('sw-pg-sitenav-firstli-mouseover').addClass('sw-pg-sitenav-firstli-mouseout');
                    $("#sw-pg-sitenav-firstli a").addClass('sw-pg-sitenav-firstli-a-mouseout').removeClass('sw-pg-sitenav-firstli-a-mouseover');
                });

                $(document).on('mouseover', '#sw-pg-district', function () {
                    $("#sw-pg-district-firstli").removeClass('sw-pg-district-firstli-mouseout').addClass('sw-pg-district-firstli-mouseover');
                    $("#sw-pg-district-firstli a").addClass('sw-pg-district-firstli-a-mouseover').removeClass('sw-pg-district-firstli-a-mouseout');
                });

                $(document).on('mouseout', '#sw-pg-district', function () {
                    $("#sw-pg-district-firstli").removeClass('sw-pg-district-firstli-mouseover').addClass('sw-pg-district-firstli-mouseout');
                    $("#sw-pg-district-firstli a").addClass('sw-pg-district-firstli-a-mouseout').removeClass('sw-pg-district-firstli-a-mouseover');
                });
            }
        });


    </script>
    <script src='https://ajax.googleapis.com/ajax/libs/jqueryui/1.10.1/jquery-ui.min.js' type='text/javascript'
        integrity='sha384-zmfsMNrucM3rN4b5thw5WfWYo/krlewoA1acogud/GtvNIYJBsFo1A57Ao19uYjE' crossorigin='anonymous'
        data-sri-failover='https://www.nkcschools.org/Static/GlobalAssets/Scripts/min/jquery-ui-1.10.1.min.js'></script>
    <script src="https://www.nkcschools.org/Static/GlobalAssets/Scripts/min/SW-UI.min.js" type='text/javascript'></script>
    <script src="https://www.nkcschools.org/Static/GlobalAssets/Scripts/jquery.sectionlayer.js" type='text/javascript'></script>
    <script src="https://www.nkcschools.org/Static/GlobalAssets/Scripts/Initialize_2430.js" type='text/javascript'></script>
    <script src="https://www.nkcschools.org/Static/GlobalAssets/Scripts/min/swfobject.min.js" type="text/javascript"></script>
    <script src="https://www.nkcschools.org/Static/GlobalAssets/Scripts/min/jquery.ajaxupload_2440.min.js" type="text/javascript"></script>

    <!-- Begin swuc.CheckScript -->
  <script type="text/javascript" src="https://www.nkcschools.org/Static/GlobalAssets/Scripts/ThirdParty/json2.js"></script>
  <script type="text/javascript" src="https://www.nkcschools.org/Static/GlobalAssets/Scripts/CheckScript_2430.js"></script>
<!-- End swuc.CheckScript -->


    <!-- Server Load Time (03): 0.0624977 Seconds -->

    

    <!-- off-canvas menu enabled-->
    

    <!-- Ally Alternative Formats Configure START   -->
    
<script>
    AFExtensions = ".pdf,.doc,.docx,.ppt,.pptx,.odt,.odp";
    AllyClientID = "1029";
	    // Wait for the API to load     
	    ally.ready(function() {
		    // Configure an API instance
            const ui = ally.ui({
			    'client': {
				    'baseUrl': 'https://prod.ally.ac',
				    'clientId': 1029
			    },
			    'courseId': 's4',
			    'locale': $('html').attr('lang'),
			    'platformName': 'Wcm',  
			    'role': 'anonymous'
		    });
	        // Apply the API to the page body   
            ui.autoUpdate({'domWatch': 250});
    });

</script>
    <!-- Ally Alternative Formats Configure END     -->

</body>
</html>
