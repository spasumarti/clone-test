# Accessibility Guidelines

## Aria-label:  

The aria-label attribute is used to define a string that labels the current element. Use it in cases where a text label is not visible on the screen

## Aria-labelledby: 

The aria-labelledby attribute contains the element IDs of labels in objects such as input elements, widgets, and groups. The attribute establishes relationships between objects and their labels. Assistive technology, such as screen readers, use this attribute to catalog the objects in a document so that users can navigate between them. Without an element ID, the assistive technology cannot catalog the object.

## Aria-describedby: 

aria- describedby is very similar to aria-labelledby A label provides essential information about an object, while a description provides extended information that the user might need.

## Roles: 

## ARIA: alert role

The alert role can be used to tell the user an element has been dynamically updated. Screen readers will instantly start reading out the updated content when the role is added. If the user is expected to close the alert, then the alertdialog role should be used instead.

## ARIA: application role

The application role indicates to assistive technologies that an element and all of its children should be treated similar to a desktop application, and no traditional HTML interpretation techniques should be used. This role should only be used to define very dynamic and desktop-like web applications.


# ARIA: article role

The article role indicates a section of a page that could easily stand on its own on a page, in a document, or on a web site. It is usually set on related content items such as comments, forum posts, newspaper articles or other items grouped together on one page.

## ARIA: banner role

A banner role represents general and informative content frequently placed at the beginning of the page. This usually includes a logo, company name, search icon, photo related to the page, or slogan.

## ARIA: button role

The button role should be used for clickable elements that trigger a response when activated by the user. Adding role="button" will make an element appear as a button control to a screen reader. This role can be used in combination with the aria-pressed attribute to create toggle buttons.

## ARIA: cell role

The cell value of the ARIA role attribute identifies an element as being a cell in a tabular container that does not contain column or row header information. To be supported, the cell must nested in an element with the role of row.

## ARIA: checkbox role

The checkbox role is used for checkable interactive controls. Elements containing role="checkbox" must also include the aria-checked attribute to expose the checkbox's state to assistive technology.

## ARIA: Complementary role

The complementary landmark role is used to designate a supporting section that relates to the main content, yet can stand alone when separated. These sections are frequently presented as sidebars or call-out boxes. If possible, use the HTML `<aside>` element instead.


## ARIA: contentinfo role

The contentinfo landmark role is used to identify information repeated at the end of every page of a website, including copyright information, navigation links, and privacy statements. This section is commonly called a footer.

## ARIA: dialog role

The dialog role is used to mark up an HTML based application dialog or window that separates content or UI from the rest of the web application or page. Dialogs are generally placed on top of the rest of the page content using an overlay. Dialogs can be either non-modal (it's still possible to interact with content outside of the dialog) or modal (only the content in the dialog can be interacted with).

## ARIA: document role

Generally used in complex composite widgets or applications, the document role can inform assistive technologies to switch context to a reading mode: the document role tells assistive technologies with reading or browse modes to use the document mode to read the content contained within this element.

## ARIA: feed role

A feed is a dynamic scrollable list of articles in which articles are added to or removed from either end of the list as the user scrolls. A feed enables screen readers to use the browse mode reading cursor to both read and scroll through a stream of rich content that may continue scrolling infinitely by loading more content as the user reads.

## ARIA: figure role

The ARIA figure role can be used to identify a figure inside page content where appropriate semantics do not already exist. A figure is generally considered to be one or more images, code snippets, or other content that puts across information in a different way to a regular flow of text.

## ARIA: form role

The form landmark role can be used to identify a group of elements on a page that provide equivalent functionality to an HTML form.

## ARIA: grid role

The grid role is for a widget that contains one or more rows of cells. The position of each cell is significant and can be focused using keyboard input.

## ARIA: heading role

The heading role defines this element as a heading to a page or section. To give the page more structure, a level should also be provided to indicate relationships between sections.

## ARIA: img role

The ARIA img role can be used to identify multiple elements inside page content that should be considered as a single image. These elements could be images, code snippets, text, emojis, or other content that can be combined to deliver information in a visual manner.

## ARIA: List role

The ARIA list role can be used to identify a list of items. It is normally used in conjunction with the listitem role, which is used to identify a list item contained inside the list.

## ARIA: listbox role

The listbox role is used for lists from which a user may select one or more items which are static and, unlike HTML `<select>` elements, may contain images.

## ARIA: Listitem role

The ARIA listitem role can be used to identify an item inside a list of items. It is normally used in conjunction with the list role, which is used to identify a list container.

## ARIA: Main role

The main landmark role is used to indicate the primary content of a document. The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application.

## ARIA: Navigation Role

The navigation landmark role is used to identify major groups of links used for navigating through a website or page conrent.

## ARIA: Region role

The region landmark role is used to identify an area in the document that the author has identified as significant. It is used to provide a generic landmark for people to be able to navigate to easily when none of the other landmark roles are appropriate.

## ARIA: row role

An element with role="row" is a row of cells within a tabular structure. A row contains one or more cells,  grid cells, or column headers, and possibly a row header, within a grid, table or treegrid, and optionally within a rowgroup.

## ARIA: rowgroup role

An element with role="rowgroup" is a group of rows within a tabular structure. A rowgroup contains one or more rows of cells,  grid cells, column headers, or row headerswithin a grid, table or treegrid.

## ARIA: Search role

The search landmark role is used to identify a section of the page used to search the page, site, or collection of sites.

## ARIA: switch role

The ARIA switch role is functionally identical to the role, except that instead of representing "checked" and "unchecked" states, which are fairly generic in meaning, the switch role represents the states "on" and "off."

## ARIA: Tab Role

The ARIA tab role indicates an interactive element that, when activated, displays its associated tab panel.

## ARIA: table role

The table value of the ARIA role attribute identifies the element containing the role as having a non-interactive table structure containing data arranged in rows and columns, similar to the native ` <table>` HTML element.

## ARIA: textbox role

The textbox role is used to identify an element that allows the input of free-form text.

## aria-live: 

The aria-live=POLITENESS_SETTING is used to set the priority with which screen reader should treat updates to live regions - the possible settings are: off, polite or assertive. The default setting is off. This attribute is by far the most important.

Normally, only aria-live="polite" is used. Any region which receives updates that are important for the user to receive, but not so rapid as to be annoying, should receive this attribute. The screen reader will speak changes whenever the user is idle.

For regions which are not important, or would be annoying because of rapid updates or other reasons, silence them with aria-live="off".


## aria-controls:

The aria-controls=[IDLIST] is used to associate a control with the regions that it controls. Regions are identified just like an id in a div, and multiple regions can be associated with a control using a space, e.g. aria-controls="myRegionID1 myRegionsID2".








