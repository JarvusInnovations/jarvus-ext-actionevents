# jarvus-ext-actionevents
An override of Ext.grid.column.ActionView which adds custom click events based on the actioncolumn's action configuration attribute

eg. The following actioncolumn item will fire a 'editpersonclick' event:
```
    {
        xtype:'actioncolumn',
        width:50,
        items: [{
            icon: 'extjs-build/examples/shared/icons/fam/cog_edit.png',  // Use a URL in the icon config
            tooltip: 'Edit',
            action: 'editperson'
        }]
    }
```

