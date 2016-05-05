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
 <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
 	 viewBox="-1076.1 758.6 202.1 43.6" style="enable-background:new -1076.1 758.6 202.1 43.6;" xml:space="preserve">
 <style type="text/css">
 	.st0{fill:#F4B960;}
 	.st1{fill:#E66F32;}
 	.st2{fill:#E43C41;}
 	.st3{fill:#BDD041;}
 	.st4{fill:#6DB54C;}
 	.st5{fill:#AEDAE6;}
 	.st6{fill:#56B8DE;}
 	.st7{fill:#00B1D5;}
 	.st8{fill:url(#XMLID_2_);}
 	.st9{fill:#221F1F;}
 	.st10{fill:#FFFFFF;}
 </style>
 <g>
 	<g id="XMLID_57_">
 		<circle id="XMLID_68_" class="st0" cx="-1054.3" cy="780.4" r="21.7"/>
 		<circle id="XMLID_67_" class="st1" cx="-1056.5" cy="778.2" r="19.6"/>
 		<circle id="XMLID_66_" class="st2" cx="-1053.8" cy="775.7" r="17"/>
 		<circle id="XMLID_65_" class="st3" cx="-1052.5" cy="777" r="15.6"/>
 		<circle id="XMLID_64_" class="st4" cx="-1053.6" cy="778.2" r="14.5"/>
 		<circle id="XMLID_63_" class="st5" cx="-1055.9" cy="775.8" r="12.1"/>
 		<circle id="XMLID_62_" class="st6" cx="-1054" cy="773.8" r="10.2"/>
 		<circle id="XMLID_61_" class="st7" cx="-1052.7" cy="775.2" r="8.9"/>

 			<radialGradient id="XMLID_2_" cx="-1053.988" cy="-164.5" r="7.661" gradientTransform="matrix(1 0 0 -1 0 611.9999)" gradientUnits="userSpaceOnUse">
 			<stop  offset="0" style="stop-color:#797979"/>
 			<stop  offset="1" style="stop-color:#4C4C4C"/>
 		</radialGradient>
 		<circle id="XMLID_60_" class="st8" cx="-1054" cy="776.4" r="7.6"/>
 		<circle id="XMLID_59_" class="st9" cx="-1054" cy="776.4" r="7.6"/>

 			<ellipse id="XMLID_58_" transform="matrix(0.4094 -0.9124 0.9124 0.4094 -1326.5503 -501.9048)" class="st10" cx="-1050.9" cy="773.6" rx="2.4" ry="1.5"/>
 	</g>
 	<path id="XMLID_53_" class="st10" d="M-1025.5,772.2c0-0.1,0.1-0.3,0.3-0.3h6.9c3.9,0,5.7,1.8,5.7,4.5c0,2-1,3-2.2,3.6v0.1
 		c1.1,0.4,2.5,1.8,2.5,3.9c0,3.4-2.3,5-6.3,5h-6.6c-0.1,0-0.3-0.1-0.3-0.3C-1025.5,788.7-1025.5,772.2-1025.5,772.2z M-1018.4,779
 		c1.6,0,2.6-0.9,2.6-2.2c0-1.4-1-2.3-2.6-2.3h-3.7c-0.1,0-0.1,0.1-0.1,0.1v4.2c0,0.1,0.1,0.1,0.1,0.1
 		C-1022.2,779-1018.4,779-1018.4,779z M-1022.2,786.2h3.9c1.8,0,2.8-0.9,2.8-2.4s-1-2.4-2.8-2.4h-3.9c-0.1,0-0.1,0.1-0.1,0.1v4.4
 		C-1022.4,786.2-1022.2,786.2-1022.2,786.2z"/>
 	<path id="XMLID_51_" class="st10" d="M-1010.1,788.8c-0.1,0-0.3-0.1-0.3-0.3v-11.6c0-0.1,0.1-0.3,0.3-0.3h2.5
 		c0.1,0,0.3,0.1,0.3,0.3v1h0.1c0.6-0.9,1.8-1.6,3.4-1.6c1,0,2.1,0.4,2.7,1c0.1,0.1,0.1,0.3,0.1,0.3l-1.4,1.7
 		c-0.1,0.1-0.3,0.1-0.4,0.1c-0.6-0.3-1.2-0.6-2-0.6c-1.7,0-2.5,1.1-2.5,3.1v6.5c0,0.1-0.1,0.3-0.3,0.3L-1010.1,788.8L-1010.1,788.8z
 		"/>
 	<path id="XMLID_48_" class="st10" d="M-1000.6,785.8c-0.3-0.8-0.5-1.6-0.5-3c0-1.4,0.1-2.2,0.5-3c0.8-2.2,2.7-3.3,5.4-3.3
 		c2.7,0,4.6,1.2,5.4,3.3c0.3,0.8,0.5,1.6,0.5,3c0,1.4-0.1,2.2-0.5,3c-0.8,2.2-2.7,3.3-5.4,3.3C-997.9,789.1-999.9,788-1000.6,785.8z
 		 M-992.7,785.1c0.3-0.6,0.3-1.2,0.3-2.2s-0.1-1.6-0.3-2.2c-0.4-1-1.2-1.6-2.5-1.6c-1.2,0-2.1,0.6-2.5,1.6c-0.3,0.7-0.3,1.2-0.3,2.2
 		s0.1,1.6,0.3,2.2c0.4,1,1.2,1.6,2.5,1.6C-994,786.7-993.2,786.1-992.7,785.1z"/>
 	<path id="XMLID_46_" class="st10" d="M-976.3,788.8c-0.1,0-0.3-0.1-0.3-0.3l-2.5-7.8h-0.1l-2.5,7.7c-0.1,0.1-0.1,0.3-0.3,0.3h-2.2
 		c-0.1,0-0.3-0.1-0.3-0.3l-4.1-11.6c-0.1-0.1,0.1-0.3,0.2-0.3h2.6c0.2,0,0.3,0.1,0.3,0.3l2.5,8h0.1l2.5-8c0.1-0.1,0.2-0.3,0.3-0.3h2
 		c0.1,0,0.3,0.1,0.3,0.3l2.6,8h0.1l2.4-8c0.1-0.2,0.1-0.3,0.3-0.3h2.6c0.1,0,0.3,0.1,0.2,0.3l-4,11.6c-0.1,0.1-0.1,0.3-0.3,0.3
 		L-976.3,788.8L-976.3,788.8z"/>
 	<path id="XMLID_44_" class="st10" d="M-969.1,787.2c-0.1-0.1-0.1-0.3,0-0.3l1.6-1.5c0.1-0.1,0.3-0.1,0.4,0c0.9,0.8,2.5,1.4,3.9,1.4
 		c1.6,0,2.4-0.6,2.4-1.4c0-0.7-0.5-1.2-2.2-1.3l-1.4-0.1c-2.6-0.3-4-1.5-4-3.5c0-2.3,1.8-3.9,5-3.9c2,0,3.7,0.6,4.9,1.4
 		c0.1,0.1,0.1,0.3,0.1,0.3l-1.3,1.4c-0.1,0.1-0.3,0.1-0.4,0.1c-0.8-0.5-2.2-1-3.4-1c-1.3,0-2,0.5-2,1.3c0,0.7,0.5,1.1,2.2,1.3
 		l1.4,0.1c2.7,0.3,4,1.6,4,3.5c0,2.4-1.9,4.1-5.5,4.1C-966.1,789.2-968,788.2-969.1,787.2z"/>
 	<path id="XMLID_41_" class="st10" d="M-955.9,785.8c-0.3-0.8-0.5-1.7-0.5-3s0.1-2.2,0.5-3c0.8-2.2,2.7-3.3,5.4-3.3
 		c2.7,0,4.6,1.3,5.4,3.3c0.3,0.8,0.5,1.7,0.5,3.7c0,0.1-0.1,0.3-0.3,0.3h-8.2c-0.1,0-0.1,0.1-0.1,0.1c0,0.3,0.1,0.7,0.2,0.9
 		c0.5,1.2,1.4,1.8,2.9,1.8s2.4-0.5,3.1-1.1c0.1-0.1,0.3-0.1,0.5-0.1l1.6,1.3c0.1,0.1,0.1,0.3,0.1,0.3c-1.1,1.2-3,2.1-5.4,2.1
 		C-953.2,789.2-955.2,788-955.9,785.8z M-948,780.4c-0.3-1-1.3-1.6-2.5-1.6s-2.2,0.6-2.6,1.6c-0.1,0.3-0.1,0.6-0.1,1
 		c0,0.1,0.1,0.1,0.1,0.1h5.2c0.1,0,0.1-0.1,0.1-0.1C-947.9,781.1-947.9,780.7-948,780.4z"/>
 	<path id="XMLID_39_" class="st10" d="M-942.6,788.8c-0.1,0-0.3-0.1-0.3-0.3v-11.6c0-0.1,0.1-0.3,0.3-0.3h2.5c0.1,0,0.3,0.1,0.3,0.3
 		v1h0.1c0.6-0.9,1.8-1.6,3.4-1.6c1,0,2.1,0.4,2.7,1c0.1,0.1,0.1,0.3,0.1,0.3l-1.4,1.7c-0.1,0.1-0.3,0.1-0.4,0.1
 		c-0.6-0.3-1.2-0.6-2-0.6c-1.7,0-2.5,1.1-2.5,3.1v6.5c0,0.1-0.1,0.3-0.3,0.3L-942.6,788.8L-942.6,788.8z"/>
 	<path id="XMLID_37_" class="st10" d="M-933.1,787c-0.1-0.1-0.1-0.3-0.1-0.4l1.7-1.8c0.1-0.1,0.3-0.1,0.4-0.1c1.2,0.9,3,1.8,5,1.8
 		c2.2,0,3.5-1,3.5-2.5c0-1.2-0.8-2-3.3-2.4l-1-0.1c-3.5-0.5-5.5-2-5.5-4.8c0-3.1,2.5-5.2,6.2-5.2c2.3,0,4.5,0.7,5.9,1.7
 		c0.1,0.1,0.1,0.2,0.1,0.3l-1.3,1.8c-0.1,0.1-0.3,0.1-0.4,0.1c-1.5-0.9-2.9-1.3-4.4-1.3c-1.9,0-2.9,0.9-2.9,2.3c0,1.2,0.9,2,3.4,2.3
 		l1,0.1c3.5,0.5,5.5,2,5.5,5s-2.4,5.3-6.9,5.3C-929.1,789.2-931.7,788.2-933.1,787z"/>
 	<path id="XMLID_35_" class="st10" d="M-913.8,789.1c-2.6,0-3.7-1.2-3.7-3.5v-6.4c0-0.1-0.1-0.1-0.1-0.1h-0.8
 		c-0.1,0-0.3-0.1-0.3-0.3v-1.7c0-0.1,0.1-0.3,0.3-0.3h0.8c0.1,0,0.1-0.1,0.1-0.1v-3.3c0-0.1,0.1-0.3,0.3-0.3h2.5
 		c0.1,0,0.3,0.1,0.3,0.3v3.3c0,0.1,0.1,0.1,0.1,0.1h1.8c0.1,0,0.3,0.1,0.3,0.3v1.7c0,0.1-0.1,0.3-0.3,0.3h-1.8
 		c-0.1,0-0.1,0.1-0.1,0.1v6.3c0,0.8,0.4,1.1,1.2,1.1h0.7c0.1,0,0.3,0.1,0.3,0.3v2c0,0.1-0.1,0.3-0.3,0.3L-913.8,789.1L-913.8,789.1z
 		"/>
 	<path id="XMLID_32_" class="st10" d="M-902.3,788.8c-0.1,0-0.3-0.1-0.3-0.3v-0.9l0,0c-0.6,0.8-1.8,1.4-3.7,1.4
 		c-2.4,0-4.4-1.1-4.4-3.7c0-2.6,2-3.9,5.2-3.9h2.6c0.1,0,0.1-0.1,0.1-0.1v-0.6c0-1.4-0.7-2-2.9-2c-1.4,0-2.4,0.4-3,0.8
 		c-0.1,0.1-0.3,0.1-0.4-0.1l-1-1.6c-0.1-0.1-0.1-0.3,0.1-0.3c1-0.7,2.5-1.2,4.6-1.2c4,0,5.4,1.3,5.4,4.2v7.8c0,0.1-0.1,0.3-0.3,0.3
 		L-902.3,788.8L-902.3,788.8z M-902.6,784.8v-0.9c0-0.1-0.1-0.1-0.1-0.1h-2.2c-2,0-2.8,0.5-2.8,1.6c0,1,0.8,1.5,2.3,1.5
 		C-903.7,786.8-902.6,786.2-902.6,784.8z"/>
 	<path id="XMLID_30_" class="st10" d="M-897.4,785.8c-0.3-0.8-0.5-1.7-0.5-3s0.1-2.2,0.5-3c0.8-2.2,2.8-3.3,5.4-3.3
 		c2,0,3.5,0.7,4.5,1.9c0.1,0.1,0.1,0.3-0.1,0.3l-1.7,1.4c-0.1,0.1-0.3,0.1-0.4-0.1c-0.7-0.7-1.3-1-2.4-1c-1.2,0-2.1,0.5-2.5,1.6
 		c-0.3,0.6-0.3,1.3-0.3,2.2s0.1,1.6,0.3,2.3c0.4,1,1.3,1.6,2.5,1.6c1.1,0,1.8-0.4,2.4-1c0.1-0.1,0.3-0.1,0.4-0.1l1.7,1.4
 		c0.1,0.1,0.1,0.3,0.1,0.3c-1,1.1-2.6,1.8-4.5,1.8C-894.6,789.2-896.6,788-897.4,785.8z"/>
 	<path id="XMLID_28_" class="st10" d="M-876.9,788.8c-0.2,0-0.3-0.1-0.5-0.3l-3.3-5l-1.8,1.9v3.1c0,0.1-0.1,0.3-0.3,0.3h-2.5
 		c-0.1,0-0.3-0.1-0.3-0.3V772c0-0.1,0.1-0.3,0.3-0.3h2.5c0.1,0,0.3,0.1,0.3,0.3v9.8l4.5-4.8c0.1-0.2,0.3-0.3,0.5-0.3h2.8
 		c0.1,0,0.3,0.1,0.1,0.3l-4.2,4.4l4.7,7.2c0.1,0.1,0.1,0.3-0.1,0.3L-876.9,788.8L-876.9,788.8z"/>
 </g>
 </svg>



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
