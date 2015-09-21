# ISDsandbox
CSS for ISD Sandbox

###Folder structure:

css-compiled  // folder of all the css files compiled from the master files in the sass folder

sass   // all the sass file, first level are the master sass files with compiling instructions

sass/sass-partials    // folder of all partials includeing base, colors, fonts, and layout-grid

sass/sass-partials/components  // page block components i.e. accordion, breadcrumbs, social-media, et al

sass/sass-partials/homepage    // homepage specific components

sass/sass-partials/media-queries  // general media queries not determined in any other component files

sass/sass-partials/menus  // partials specific to the main menu, with specific files for admissions and audience (utility) menu

sass/sass-partials/page-specific  // partials that cover page content on individual pages 

###Sass watch command
sass --watch sass/style-all-master.scss:css-compiled/style-all.css sass/customiztion-master.scss:css-compiled/customized.css sass/style-custom-master.scss:css-compiled/style-custom.css sass/header-master.scss:css-compiled/header.css sass/footer-master.scss:css-compiled/footer.css sass/main-menu-master.scss:css-compiled/main-menu.css sass/admissions-master.scss:css-compiled/admissions.css sass/homepage-master.scss:css-compiled/homepage.css sass/shadowbox-master.scss:css-compiled/shadowbox-mobile.css sass/contact-pop-up.scss:css-compiled/contact-pop-up.css
