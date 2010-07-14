#Rails Active Calendar
Date renderer for date and time fields in rails using jscalendar javascript library (http://www.dynarch.com/projects/calendar/).

##Installation
    ./script/plugin install git://github.com/sandipransing/rails_activecalendar.git

##Usage
Once you install the plugin, rails will automatically try to render and date or datetime fields using this plugin. However, it won't work properly until you include the necessary javascripts and stylesheets in your layout as follows:

    <%= stylesheet_link_tag "/javascripts/jscalendar-1.0/calendar-win2k-cold-1.css"%>
    <%= javascript_include_tag "jscalendar-1.0/calendar.js" %>
    <%= javascript_include_tag "jscalendar-1.0/lang/calendar-en.js" %>
    <%= javascript_include_tag "jscalendar-1.0/calendar-setup.js" %>
