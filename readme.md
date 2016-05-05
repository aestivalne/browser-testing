# Practical, Browser-based A11y testing

##Jeff Coburn
**Web Services Manager  
Institute for Community Inclusion  
School for Global Inclusion and Social Development  
University of Massachusetts Boston**

<p><a href="https://github.com/coburnicus/browser-testing/blob/master/a11y-browser-coburn.pptx?raw=true"><strong>Download the PowerPoint</strong></a></p>

## Why should we develop web surveys and pages with accessibility in mind?

Because we are not monsters.

# This is the bare minimum of acceptable testing

- User testing with people with disabilities is combined with unit testing is preferable.


##Testing product

|---Launching without testing, FAIL  
|  
|  
| <----------We are here  
|  
|---Unit Testing at code level  
|  
|  
|  
|---Testing with actual users  


##Testing Electrical Socket

|---Touching wires with screwdriver, dying.  
|  
|  
| <----------We are here  
|  
|---Using Multimeter  
|  
|  
|  
|---Calling an electrician  




## What is accessible?

Until the United States Access Board can work through whatever writers block they need to overcome in order to release the Section 508  Refresh, which would be the more formal guidelines, we should use WCAG 2.0.

The preview versions of the 508 Refresh are currently bad cover songs of WCAG 2.0

##What does the WCAG 2.0 say?
https://www.w3.org/WAI/WCAG20/quickref/  
http://webaim.org/standards/wcag/checklist

It says says you web pages and apps should be:

**Perceivable**
- You can detect what is there, and what it's purpose is, using your senses.

**Operable**
- Things behave in an expected way.

**Understandable**
- The content/instructions are comprehensible and useful. Are things labeled correctly.

**Robust**
- The page or app works on appropriate devices and allows for assistive technology.

#Tools you can use
 **Accessibility auditors:**
 - Wave http://wave.webaim.org/ | http://wave.webaim.org/extension/
 - Axe http://www.deque.com/products/axe/
 - Chrome Accessibility https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en
 - Tenon https://tenon.io/

**Other**
 - Web Developer Toolbar http://chrispederick.com/work/web-developer/
 - Specialized testing Tools (color blindness simulators) https://chrome.google.com/webstore/detail/color-contrast-analyzer/dagdlcijhfbmgkjokkjicnnfimlebcll/related?hl=en
 - Screen Reader (simulators) http://www.chromevox.com/

**Browser/device Emulators**
 - Browser simulators (BrowserStack) https://www.browserstack.com/  
![BrowserStack](https://d98b8t1nnulk5.cloudfront.net/production/images/static/header/header-logo.svg?1462450257)


## Let's test against these standards

I will show you tools available in Chrome and or Firefox

<p><strong><a href="http://coburnicus.com/browser-testing/test-form.html">Test Form</a></strong></p>

##Perceivable

Images need alt tags
test: Disable images
Use: Web developer toolbar (chrome and firefox)


Test: Content needs enough contrast from page background)
Use: Auditor, or color blindness simulator


##Operable
Test: Is form keyboard usable and logical.
Use: Keyboard-only to navigate form. Is it usable is it logical?


##Understandable
Test: Does the from implement labels.
Use: Web Developer Toolbar (FORMS --> outline form fields without labels)

##Robust
Test: Does it work with a screenreader
Use: ChromeVox to simulate a screenreader

Test: Does it work on IE 8 or Android 4.8.56.38.58?
Use: Emulators like https://browserstack.com
