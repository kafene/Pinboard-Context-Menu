/* This is it. Simple, eh? */
chrome.contextMenus.create({
    "title": "&+ Pinboard",
    "contexts": ["all"],
    "onclick": function(info, tab) {
        void(open(
            'https://pinboard.in/add?showtags=yes'
                + '&url=' + encodeURIComponent(info.pageUrl)
                + '&title=' + encodeURIComponent(tab.title)
                + '&description=' + encodeURIComponent(info.selectionText || ''),
            'PinboardContextMenu',
            'top=100,left=100,width=700,height=550,scrollbars=yes,toolbar=no'
        ));
    }
});
