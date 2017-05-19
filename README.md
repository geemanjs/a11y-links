# a11y-links
A collection of useful accessibility links

**Table of Contents**
* [How this list was formed](#how-this-list-was-formed)
   * [Learn more sections](#learn-more-sections)
   * [Libraries sections](#libraries-sections)
* [Content](#content)
   * [Headings](#headings)
   * [Typography](#typography)
   * [Tables](#tables)
   * [Colour](#colour)
* [Forms](#forms)
   * [Inputs](#inputs)
   * [Select](#select)
   * [Checkboxes](#checkboxes)
   * [Radios](#radios)
   * [Buttons](#buttons)
   * [Validation](#validation)
* [Navigation](#navigation)
* [General Components](#general-components)
   * [Dialogs](#dialogs)
   * [WYSIWYG editors](#wysiwyg-editors)
* [Testing](#testing)
   * [Tools](#tools)
      * [In Browser](#in-browser)
      * [CLI](#cli)
      * [IDE (Could be considered CLI)](#ide-could-be-considered-cli)
   * [Tool Testing](#tool-testing)

## How this list was formed
The articles/libraries were tested in Google Chrome with:
   * JAWS
   * Dragon
   * Zoomtext
   * OSX Voiceover
   
### Learn more sections
* Could someone with a basic grasp of JS,CSS,HTML understand it?
* Is it well written?
* Is it well presented?
* Are coding samples supplied?
* Do the coding samples follow 'best' practice?
* Do the coding samples follow WCAG Guidelines/advice?
* Does the output from the coding samples work well with the tools?
* Does the guidance come from a 'well known' resource?

### Libraries sections
* Does the recommended output work well with the tools?
* Is it easy to produce errors?
* Library size?
* Library usability?
* Library extension points?

### Content
#### Headings
##### Learn more
|Links|
|-|
| [W3](https://www.w3.org/WAI/tutorials/page-structure/headings/) |
| [BBC](http://www.bbc.co.uk/guidelines/futuremedia/accessibility/mobile/structure/headings#HTML)|
| [Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)  |
##### Libraries
You should be using HTML, CSS only for these

#### Typography
##### Learn more
| Links | Description |
|-|-|
| [WebAIM](http://webaim.org/techniques/fonts/) | Font considerations |
| [Hemming Way] (http://www.hemingwayapp.com/)| Improve content readability |
| [Penn State university](http://accessibility.psu.edu/boldfacehtml/)| `<b>` vs `<strong>` & `<i>` vs `<em>` |
| [UK Government](https://accessibility.blog.gov.uk/2017/02/08/advice-for-creating-content-that-works-well-with-screen-readers/)| |
##### Libraries
You should be using the semantics of HTML for text

#### Tables
##### Learn more
| Links | Description |
|-|-|
| [WebAIM](https://www.w3.org/WAI/tutorials/tables/) | Comprehensive Guide | 
| [Hong Kiat](http://www.hongkiat.com/blog/html-table-accessibility/) | Good write up with good content | 
| [Usability.com](http://usability.com.au/2005/06/accessible-data-tables-2005/) | Old, but covers complex tables | 
##### Libraries
| Links | Description |
|-|-|
| [Pivotal Table](http://styleguide.cfapps.io/react_base_tables.html) | Great Library from an accessibility perspective, limited extension | 
| [React Bootstrap Table](http://allenfang.github.io/react-bootstrap-table/) | Apart from Headers been in a seperate table, the rest of the markup is pretty good!  |

#### Bad Tables
| Links | Description |
|-|-|
| [React Tables](https://github.com/tannerlinsley/react-table) | See [Issue 130](https://github.com/tannerlinsley/react-table/issues/130) |
| [Facebook Fixed Data Table](https://github.com/facebook/fixed-data-table)| See [Issue 129](https://github.com/facebook/fixed-data-table/issues/129) for more details | 

#### Colour
##### Learn more
|Links|Description|
|-|-|
| [WCAG2.0 colour](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-without-color.html) | WCAG advice |
| [Contrast Checker](https://colour-contrast.github.io/)| - |
| [WEBAIM Contrast Checker](http://webaim.org/resources/contrastchecker/)| - |
| ['We Are Color Blind'](http://wearecolorblind.com/)| A movement to try and raise awareness of colour blindness |
| [Designing for colour blindness](http://blog.usabilla.com/how-to-design-for-color-blindness/)| Good blog post on designing for colour 
blindness |
| [How users change colours](https://accessibility.blog.gov.uk/2017/03/27/how-users-change-colours-on-websites/)| gov.uk research 
article on how users change colours in the browser |
##### Libraries

### Forms
#### Inputs
##### Learn more
|Links|Description|
|-|-|
| [W3 WAI advice](https://www.w3.org/WAI/tutorials/forms/) | More general than just input fields but solid tutorials |
| [WebAIM form advice](http://webaim.org/techniques/forms/controls#input) | |
| [Building accessible forms](http://usability.com.au/2013/04/accessible-forms-1-labels-and-identification/) | In depth write up 
including the why |
##### Libraries

#### Select
##### Learn more 
##### Resources

#### Checkboxes
##### Learn more
##### Libraries

#### Radios
##### Learn more
##### Libraries

#### Buttons
##### Learn more
| Links | Description |
|-|-|
|[Mozilla 'Button role'](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_button_role)| |
##### Libraries

#### Validation
##### Learn more
##### Libraries

### Navigation
#### Learn more
| Links | Description | 
|-|-|
| [W3 Guidance](https://www.w3.org/WAI/tutorials/menus/) | Fantastic resource from W3 with a collection of recommendations & best practices |
| [Heydon works guidance](http://heydonworks.com/practical_aria_examples/#submenus) | Navbar with dropdown, works really well! |
| [Terril Thompson guidance](http://terrillthompson.com/blog/474) | Slightly outdated, but very relevant recommendations |
#### Libraries
| Links | Description |
|-|-|
| [React Router](https://reacttraining.com/react-router/)| When combined with advice above can produce great menus |
| [React Bootstrap](https://react-bootstrap.github.io/components.html#navigation)| Accessible bootstrap navigation bar |
| [React Tray](http://instructure-react.github.io/react-tray/basic/) | Instructure library - Very well made! |

### General Components
#### Dialogs
##### Learn more
| Link | Description | 
|-|-|
| [Mozilla Guidance](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_dialog_role) | Mozilla's advice on managing dialogs |
| [Smashing Magazine Guidance](https://www.smashingmagazine.com/2014/09/making-modal-windows-better-for-everyone/) | Detailed post by smashing magazine recommending best practices | 

##### Libraries
| link | Description |
|-|-|
| [A11y Dialog](http://edenspiekermann.github.io/a11y-dialog/) | Lightweight library, html, js api  |
| [React Modal](https://github.com/reactjs/react-modal) | Good community who actively test with assistive tools |

#### WYSIWYG editors
##### Learn more
##### Libraries

## Testing
### Tools
#### In Browser
| Link | Description | 
|-|-|
| [aXe](https://www.deque.com/products/aXe/) | Chrome/Firefox extension, pretty in depth | 
| [Google Lighthouse](https://developers.google.com/web/tools/lighthouse/) | Chrome extension for Progressive Web Apps. Uses aXe for accessibility assesment |
| [Html CodeSniffer](http://squizlabs.github.io/HTML_CodeSniffer/)| Bookmark with different levels of WCAG | 
| [Tenon](https://tenon.io/) | (Online only) Type your url in and off you go |
| [Tota11y](http://khan.github.io/tota11y/)| Bookmark covers the very basics |

#### CLI 
| Link | Description | 
|-|-|
| [aXe Cli](https://github.com/dequelabs/axe-cli)| Uses aXe framework - Any browser supported using Webdriver |
| [Pa11y](http://pa11y.org/)| Collection of tools uses PhantomJS |

#### IDE (Could be considered CLI)
| Link | Description | 
|-|-|
| [ESLint - JSX](https://github.com/evcohen/eslint-plugin-jsx-a11y)| ESLint plugin for spotting issues in JSX | 

### Tool Testing 
| Link | Description |
| --- | --- |
| [Terrible HTML page](https://alphagov.github.io/accessibility-tool-audit/test-cases.html) | Useful tool to test the effectiveness of accessibility testers |
