# Hierarchical Checkbox Plugin
Adds a 'select all from category' checkbox to all categories in hierarchical tracklist

When you check/uncheck the box, it applies to all tracks in that category and any subcategories

##Install

For JBrowse 1.11.6+ in the _JBrowse/plugins_ folder, type:  
``git clone https://github.com/bhofmei/jbplugin-hierarchicalcheckbox.git HierarchicalCheckboxPlugin``

##Activate
Add this to jbrowse.conf:

    [ plugins.HierarchicalCheckboxPlugin ]
    location = plugins/HierarchicalCheckboxPlugin

If that doesn't work, add this to jbrowse_conf.json:

    "plugins" : {
        "HierarchicalCheckboxPlugin" : { "location" : "plugins/HierarchicalCheckboxPlugin" }
    }
