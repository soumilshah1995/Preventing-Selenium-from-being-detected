# Preventing-Selenium-from-being-detected
'''
To automate a variety of online browser operations, Selenium uses Python as a library and tool. Web scraping is one of them. I've been testing Selenium with Chromedriver and discovered that some pages may identify that you're using Selenium even if there is no automation at all. Even when I'm merely surfing manually in Chrome using Selenium, I frequently receive a page stating that suspicious behavior was identified. I verified my user agent and browser fingerprint, and they are both like the standard Chrome browser. I have started exploring lot of blogs and post to understand how can we prevent selenium from being blocked or tracked here are some of suggestions I think would be relevant.
'''

* Using Spoofing User Agents
*  using Proxies 
* Changing the property value of navigator for webdriver to undefined as follows:
*  disable-blink-features
* Exclude the collection of enable-automation switches
*  Turn-off useAutomationExtension


##### After reading all the articles I decided to have everything in classes so I can reuse it here is starting code which takes care of all the Point A to F 


![image](https://user-images.githubusercontent.com/39345855/132962620-22447829-a0fd-4d2c-9182-b4ae79c49840.png)



References

“Can a Website Detect When You Are Using Selenium With Chromedriver?.” Stackover flow. Accessed September 11, 2021. https://stackoverflow.com/questions/33225947/can-a-website-detect-when-you-are-using-selenium-with-chromedriver.


“Selenium Webdriver: Modifying Navigator.webdriver Flag To Prevent Selenium Detection.” newbedev. Accessed September 11, 2021. https://newbedev.com/selenium-webdriver-modifying-navigator-webdriver-flag-to-prevent-selenium-detection.







