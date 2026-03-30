# Block Noscript/iframes userscript.
Simple userscript to block both the NOSCRIPT & Frames within the DOM and website source. There is also an exception section to add sites that you wish not to havet he script to run on

You can use any userscript manager to install this script. 

<a href="https://addons.mozilla.org/en-US/firefox/addon/tampermonkey">Tampermonkey</a>
<a href="https://addons.mozilla.org/en-US/firefox/addon/violentmonkey">ViolentMonkey</a>

You can add excepmtions within this section of the code

// Add any sites you want to exclude from blocking
    const EXCEPTED_SITES = [
        'youtube.com',
        'yahoo.com',
    ];

    If you'd like to file an issue to add a site to the list please do and ill update the script as time permits.
