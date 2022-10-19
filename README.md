# DARKSIGHT
>v1.1.7

Darksight is a dark-themed, user interface composed of a series of re-usable, responsive, material design components. Darksight was created in Vue, developed in Vite, styled with CSS, and lovingly crafted by Front-End Developer [John Durtche][email].

## How is it Different?

Darksight has been a passion project since it's conception in early 2022. It's creator, John Durtche, describes it best:

> A beautiful monstrosity and I love it. I combined all the parts of various other existing frameworks to create Darksight. I spent months pouring through the repositories and source code of front-end frameworks like Bootstrap, Vuetify, Bulma, Tailwind, Core Elements, and Vuesax. These are arguably the best frameworks out there, yet only one came close to exactly what I desired. I wanted something compact, powerful, and simple. I knew I had to create what I wanted and Darksight is the child of that idea.

## The Principles

These three principles of compact, powerful, and simple make Darksight unique.

- COMPACT - You can use all of the framework by importing one cascading style sheet (CSS) file&mdash;no JavaScript required. The annoying class name prefixes found in other frameworks have been omitted (-vs-, -tw-, -v-, etc.), since they are understandable but unneccesary. A limited color palette but with variations for both opacity and application of colors to text, borders, backgrounds and more. Also, a minified version of the main stylesheet exists and future versions will use SASS. The framework only exists as a dark theme&mdash;half the code required!
- POWERFUL - Using the best of the latest HTML and CSS element tags, classes, pseudo-elements, transitions, filters, and transforms, the framework has dozens of pre-built components that are ready to include in your web projects and has many generic styles that can be applied to various elements, giving you more flexibility in designing your own components.
- SIMPLE - Built from the ground with a minimalist, semantic-above-all-else approach to keep the framework from devolving into a cluster of confusing class names and overriding, conflicting styles like other frameworks, it contains class names that are divided into 7 major categories: Colors, Typography, Elevation, Icons, Labels, Layout, and Components.

## The Framework

Darksight's styles are divided into 7 main categories: Colors, Typography, Elevation, Icons, Labels, Layout, and Components. The following tables are a list of elements, class names, children, and states:

| Element | Class Names | Children | States | Comments |
| ------ | ------ | ------ | ------ | ------ |
| :root | various colors and default settings |
| * | css reset settings |
| ::-webkit-scrollbar, ::-webkit-scrollbar-thumb | | | | scrollbar styles |
| body |
| aside | .navbar | .hide | | use js to change display onclick |
| nav>menu | | li>div, li>span | :hover, :active, :focus | |
| main |
| section | .section | div.container, :last-child | | last-child sets margin |
| h1, h2, h3, h4, h5, h6, a | | | :link, :hover, :active, :focus |
| * | .hl | | | formatting style for highlight |
| article | .hero | header |
| * | .container |
| * | .flex-item |
| * | .box | i, .d-2>i |
| * | .shaped | | | border-radius style |
| i | .dbl | | | .dbl is for right-aligned icons or elements with two icons |
| div | .primary, .success, .danger, .warn, .dark, .light | | | styles for lighted palette cube usage |
| div | .cube | .side, .top, .front, .left | :hover | styles to create 3d cube |
| * | .hero | h1 | | .hero is usually article or section level class |
| table | | tr, td |
| * | .centered | | | center-align hack |
| * | .lead, strong | | | bold white text formatting |
| * | .text-sm | | | small text formatting |
| * | .capitalize | | | styled capitalized formatting for headers |
| * | .text-(primary, success, danger, warn, light, white, gradient) | | | text color formatting using palette |
| code, .text-code | .code--box | | | code text formatting and larger box child |
| * | .border-(primary, success, danger, warn, dark, light, gradient) | | | border color formatting |
| * | .bg-(color), .bg-(color)-80, .bg-(color)-60, .bg-(color)-40, .bg-(color)-20 | | | colors: primary, success, danger, warn, dark, light. Changes background color opacity. |
| * | .bg-(color) | | | tailwind colors: slate, gray, zinc, neutral, stone, red, orange, amber, yellow, lime, green, emerald, teal, cyan, sky, blue, indigo, violet, purple, fuchsia, pink, rose |
| * | .color-80, .color-60, .color-40, .color-20 | | | Changes opacity |
| * | .bg-lighten-1, .bg-lighten-2, .bg-lighten-3, .bg-lighten-4, .bg-lighten-5 | | | Desaturates element |
| blockquote |
| * | .e-1, .e-2, .e-3, .e-4, .e-5, .e-6, .flat, .d-1, .d-2, .d-3 | | | Material design elevation styles which control box shadows |
| * | .label | | | Design formatting |
| p | .sm, .lg | | | Font size hacking for paragraph elements |
| ul, ol | ::before | li>i | | List styles which allow icons
| div, * | .grid-container | .col-3, .col-4, .col-5, .col-6, .col-12, .full, .grid-item |
| div. * | .grid-item | .lg, .x-lg, .full, :first-child | | .grid-items are children of .grid-containers |
| button | *, i, i.dbl | .sm, .lg, .btn--primary, .outlined, .pill, .is-icon, .ripple | :hover, :active, :focus, :not(.is-icon) | Many buttons with icons, sizes, types, and ripple onclick |
| details[open]>summary | .accordion | *, p.content | | Tabs effect component, some js makes it better |
| * | .alert | i, .is-icon, .alert--info, .alert--success, .alert--danger, .alert--warn, .alert--gradient, footer>button | | Alert component works best with js |
| * | .avatar | .btn--large, .has-image, i, div.status-dot | | Custom built avatar with status dot; js makes is useful |
| * | .chip | .dbl, .badge | | chip component |
| * | .tooltip | span, .top-caret, .bottom-caret, .right, .lft, .tip (button.popover) | | tooltip component |
| * | .notifiable, .notice | | | notifications component-related classes |
| input[type=checkbox], input[type=radio], input[type=range] | | | | input styles |
| * | .toggle, .toggle-switch, .toggle-checkbox, .toggle-label | | :before, :after, :hover, :checked | toggle component-related styles |
| * | .card | .card-header, .card-content, .card-footer, img, .full-product-image, .quote, h4, .has-icon, i, .number, .has-image, .rounded-imaged, .shifted-image, .has-full-image, .is-numbered, .card--avatar, .has-author, .large | :hover | various card component styles |
| * | .glass, .glass--invert | | | Material design material transparent glass-like styles |
| * | .align-left, .align-bottom | | | Alignment hacks |
| .tag, cite, .no-pad | | | | Various formatting styles |
| input, textarea, label | [type=text], [type=search] | | | Various form component styles |
| div, * | .modal-container, .modal, .modal-closable, .modal-content.with-icon>i, .modal-footer | | | Modal component-related styles. js makes it useful. |
| header | .topbar | *, .tb-container, .tb-left, .tb-mid, .tb-right, .tb, button, h4 | :hover, :active, :focus | Responsive 88px top navbar divided into three parts inside a flexible container |
| footer | .main-footer | .copy |
| table | thead, tr, td, tbody | | :hover | Table styles |
| @media | (max-width: 1440px), (max-width: 1024px), (max-width: 768px), (max-width: 425px) | Responsive, mobile-friendly breakpoints |
| @keyframes | dropIn | | | One animation of drop-in with a fade-like effect for tabs component |

## Installation

Using the framework is now as easy as downloading one CSS file, and adding the following line of code into the top of your &lt;head&gt; element:

```sh
<link rel="stylesheet" type="text/css" src="darksight.css" />
```
## Development

You can clone this version (1.1.7) of Darksight or build your own. You'll need to install NodeJS and use the following dependencies:

```sh
npm install vue@latest boxicons
npm install @vitejs/plugin-vue vite --D
npm run install
npm run dev
npm run build
```

Want to contribute? Great!

John Durtche uses Vue + Vite + SASS for the fastest development.

If you have comments, suggestions, bugs, or anything to report, you can contact John directly by [email].

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [email]: <mailto:johndurtche@gmail.com>