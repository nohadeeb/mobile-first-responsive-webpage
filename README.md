# mobile-first-responsive-webpage + lighthouse SEO + cross platform testing documentation.
Lighthouse SEO reports added through NPM with twoo Json reports file added .

cross platform testing was made through comparium app , we can also use testcafe through npm with lambdatest which is paid platform and many other tools and apps.
crossplatform test browser comparison here : https://front.comparium.app/?url=https://nohadeeb.github.io/mobile-first-responsive-webpage/&browser=10WINDOWS_firefox_82.0_1024&browser=10WINDOWS_chrome_87.0_1024&browser=WINDOWS_chrome_87.0_1024&browser=OSX_chrome_87.0_1024

in this task the challenge was duplicating and develop a mobile first fully responsive web page with the best code structure.

 I used javascript only on the header and menu section , to convert the regular desktop header to a mobile header with burger menu added. javascript code : close-btn() open-btn() and dropwn internal menu.

for all elemnet and sections on the webpage I used either the percentage or the EM to set the width - height - padding- marging in order to achieve fully responsive items .

lastly for implementing media query using preprocessor SASS after finishing all sections and for the best code organizing and refactoring I chose to use mixins and seperate each section in a file which will include it's media query code. But unfortunatley I faced a conflict between breakpoints mixins and flexbox which was weird , and this strategy implemented only the the slider section for revealing the concept and all SCSS files are added.

cross platform :
cross platform test is a responsive test tools to experience an application or a website on all available platforms. 
Solve UI bugs and problems and deliver the best user experience serfing through your app or website.
this test can be made throguh a javascript code or a cross platform tools which brings us also to cross browser test which is only testing on different browsers.
