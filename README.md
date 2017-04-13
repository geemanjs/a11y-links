# a11y-links
A collection of useful accessibility links

**Table of Contents**

   * [Components](#components)
      * [Forms](#forms)
         * [Learn more](#learn-more)
         * [Libraries](#libraries)
      * [Menus](#menus)
         * [Learn more](#learn-more-1)
         * [Libraries](#libraries-1)
      * [Select](#select)
         * [Learn more](#learn-more-2)
         * [Libraries](#libraries-2)
      * [Dialogs](#dialogs)
         * [Learn more](#learn-more-3)
         * [Libraries](#libraries-3)
   * [Testing](#testing)
      * [Tools](#tools)
         * [In Browser](#in-browser)
         * [CLI](#cli)
         * [IDE (Could be considered CLI)](#ide-could-be-considered-cli)
      * [Tool Testing](#tool-testing)

## How this list was formed
I will test with:
   * JAWS
   * Dragon
   * Zoomtext
   
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

## Components
### Forms
#### Learn more

#### Libraries

### Navbars/Menus
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

### Select
#### Learn more

#### Libraries

### Dialogs
#### Learn more
| Link | Description | 
|-|-|
| [Mozilla Guidance](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_dialog_role) | Mozilla's advice on managing dialogs |
| [Smashing Magazine Guidance](https://www.smashingmagazine.com/2014/09/making-modal-windows-better-for-everyone/) | Detailed post by smashing magazine recommending best practices | 

#### Libraries
| link | Description |
|-|-|
| [A11y Dialog](http://edenspiekermann.github.io/a11y-dialog/) | Lightweight library, html, js api  |
| [React Modal](https://github.com/reactjs/react-modal) | Good community who actively test with assistive tools |

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
