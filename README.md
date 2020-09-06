# Multi-language-blog-website

This repository contains a blog website which was made using HTML, CSS, javascript and google ttranslate.

## What is a multi-lingual website?

A multi-lingual website is a website where the content is written in more than one language. The information displayed in different languages is often the same, but maybe tailored for different audiences.

# Setting the primary language

First of all you will need to choose the primary language for your pages. This is the language the majority of your content is written in. For example if your page is predominantly written in English then your primary language should be set as English.

Once the primary language of your pages has been chosen, you will need to find the language code which corresponds to that language. Language codes usually consist of two letters, however four letter codes can be used for further defining the language into different dialects.

A two letter language code 'en' could be used to define 'English', whereas the four letter language code 'en-GB' could be used to distinguish British English from American English 'en-US'. Please note 'en-UK' is not a valid four letter language code. Next we need to apply the language code to our page.

To set the primary language of our page as English we use the 'lang' attribute along with our 'en' language code and apply this to the HTML element at the beginning of each page.


When a service or device consumes content on a page, it looks for specific clues in the form of HTML tags to give it information about the details on the page. This includes language. The Internal Organization for Standardization (ISO) has defined the two-character codes for each language. The web uses these codes to identify the language used within content on a page.

Each well-formed webpage has a top-level "html" tag. This tag should identify the default human-read language on the page. This is true even if there are multiple languages used on a single page, there should be a "default" language set.

 
But what happens if we have content on the page in a different language other than the default?

We can have a page in English with some of the content in another language, and still identify that to the content reader. The same —lang— attribute can be applied to any markup tag.

