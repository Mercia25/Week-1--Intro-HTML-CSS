# Week-1--Intro-HTML-CSS
WEEK 1 NOTES✔😊
HTML (HyperText Markup Language) is the foundational technology behind the web, used to structure and present content on web pages. It's a markup language that defines the structure and layout of a web page using a series of tags and attributes.
Here's a summary of what you need to know about HTML:
HTML documents are made up of HTML elements, which are represented by tags enclosed in angle brackets (<>).
HTML has a predefined set of elements, such as <h1> for headings, <p> for paragraphs, <a> for links, and <img> for images.
HTML elements can have attributes that provide additional information about the element, such as src for images and href for links.
HTML uses a simple, easy-to-learn syntax and is not a programming language.

HTML works together with other technologies like CSS (Cascading Style Sheets) and JavaScript to create interactive and visually appealing web pages.
HTML documents are served by web servers and are interpreted by web browsers to display content to users.
HTML has evolved over time, with newer versions adding new features and capabilities. The latest version is HTML5, which includes new elements like <video>, <audio>, and <canvas>.
HTML is an open standard maintained by the World Wide Web Consortium (W3C).


✔HTML Text formatting

In HTML, you can format text using various elements and attributes. Here's a summary of the most common ways to format text in HTML:
Headings: Use the <h1> to <h6> elements to create headings, with <h1> being the largest and <h6> being the smallest.
Paragraphs: Use the <p> element to create paragraphs. Paragraphs are automatically separated by a single line break.
Bold and italic: Use the <strong> and <em> elements to add emphasis or importance to text. Alternatively, you can use the <b> and <i> elements for stylistic purposes.
Line breaks: Use the <br> element to manually insert a line break within a paragraph.

Preformatted text: Use the <pre> element to display text exactly as it's written in the HTML code, preserving spaces, tabs, and line breaks.
Quotations: Use the <blockquote> element to display a long quotation, or the <q> element to display a short quotation.
Address: Use the <address> element to display contact information, such as an author's address or email.
Inline code: Use the <code> element to display inline code snippets within a paragraph.
Keyboard input: Use the <kbd> element to display text that should be entered from a keyboard, such as a command or key combination.
Deleted and inserted text: Use the <del> and <ins> elements to display deleted and inserted text, respectively.
Subscript and superscript: Use the <sub> and <sup> elements to display subscript and superscript text.


✔HTML Capabilities

TML (HyperText Markup Language) is a powerful language that enables you to create structured, interactive web pages. Here's a summary of its capabilities:
Structuring content: HTML provides a variety of elements to structure your content, such as headings, paragraphs, lists, and tables.
Embedding media: HTML allows you to embed a wide range of media, including images, videos, audio, and embedded content from other sites using the <img>, <video>, <audio>, and <iframe> elements, respectively.
Creating links: HTML enables you to create hyperlinks to other web pages using the <a> element.
Forms and user interaction: HTML lets you create forms with various input types, such as text, email, password, and file upload, using the <form> and <input> elements. You can also add buttons, checkboxes, and radio buttons using the <button>, <input type="checkbox">, and <input type="radio"> elements.
Semantic markup: HTML5 introduces new elements like <header>, <nav>, <section>, <article>, <aside>, and <footer>, which help search engines and screen readers understand the structure of your content.
Accessibility: HTML provides attributes like alt and aria to improve accessibility for users with disabilities.

Canvas: HTML5's <canvas> element allows you to create interactive graphics and animations using JavaScript.
Web storage: HTML5 includes APIs like localStorage and sessionStorage for storing data on the client-side.
Web workers: HTML5's WebWorker API enables you to run JavaScript in the background without blocking the main execution thread.
Offline support: HTML5's applicationCache API allows you to create offline-capable web applications.
Real-time communication: HTML5's WebRTC API enables real-time communication between browsers without plugins.

✔ HTML Navigation and Linking 

HTML provides various elements and attributes to help you create a navigable and well-linked web page. Here's a summary of the most important ones:
Anchor element ( <a> ): The anchor element is used to create hyperlinks. You can link to other web pages using the href attribute, link to specific parts of the same page using the id and name attributes, and download files using the download attribute.
Navigation element ( <nav> ): The navigation element is used to group navigation links and create a navigation section on your web page.
Link element ( <link> ): The link element is used to link to external resources like CSS stylesheets, RSS feeds, and external JavaScript files.
Base element ( <base> ): The base element is used to specify the base URL for all relative links on a web page.
Area element ( <area> ): The area element is used to define clickable areas in an image map.
Target attribute: The target attribute can be used on the anchor element to specify where the linked document should be opened, such as in a new tab or window. Possible values include _blank, _self, _parent, and _top.
Rel attribute: The rel attribute is used on the anchor and link elements to specify the relationship between the current document and the linked document. Possible values include stylesheet for CSS stylesheets, alternate for alternative representations of the current document, and next or prev for documents in a series.
Href lang attribute: The href lang attribute is used to indicate the language of the linked document.
Download attribute: The download attribute is used on the anchor element to specify that the linked file should be downloaded instead of being displayed in the browser.
Ping attribute: The ping attribute is used on the anchor element to specify a list of URLs to send a ping to when the link is clicked.

✔ HTML Working with Graphics and Images

HTML provides the ability to embed and work with graphics and images on web pages. Here are five key elements and attributes related to working with graphics and images in HTML:
Image element ( <img> ): The image element is used to embed images on a web page. The required src attribute specifies the URL of the image file. Other attributes like alt (for alternative text), width and height (for dimensions), and srcset and sizes (for responsive images) are also commonly used.
Canvas element ( <canvas> ): The canvas element is used to create graphics and animations on a web page using JavaScript. The required width and height attributes specify the dimensions of the canvas.
Video element ( <video> ): The video element is used to embed video content on a web page. The src attribute specifies the source of the video file, and the poster attribute specifies an image to be shown while the video is downloading. The controls attribute adds video controls like play/pause, volume, and seeking.
Audio element ( <audio> ): The audio element is used to embed audio content on a web page. The src attribute specifies the source of the audio file. The controls attribute adds audio controls like play/pause and seeking.
Picture element ( <picture> ): The picture element is used to provide multiple source files for an image, allowing the browser to choose the best one based on the user's device and network conditions. The srcset attribute specifies the list of source files, and the media attribute specifies the media query for each source.



✔ HTML Working with Media
HTML includes elements and attributes that enable you to work with media content like audio, video, and interactive elements. Here are five key elements and attributes related to working with media in HTML:
Audio element ( <audio> ): The audio element is used to embed audio content on a web page, such as music or podcasts. It supports various audio formats like MP3, OGG, and WAV. The required src attribute specifies the source of the audio file, and the controls attribute adds audio controls like play/pause and seeking.
Video element ( <video> ): The video element is used to embed video content on a web page. It supports various video formats like MP4, WebM, and OGV. The required src attribute specifies the source of the video file, and the controls attribute adds video controls like play/pause, volume, and seeking.
Track element ( <track> ): The track element is used to add subtitles or captions to a video element. It supports various subtitle formats like WebVTT and SRT. The required kind attribute specifies the type of track (subtitles or captions), and the src attribute specifies the source of the subtitle file.
Source element ( <source> ): The source element is used inside the picture, audio, and video elements to provide multiple source files for the media content, allowing the browser to choose the best one based on the user's device and network conditions. The required src attribute specifies the source file, and the type attribute specifies the MIME type of the source file.
Media attribute: The media attribute is used on the link, source, and style elements to specify the media query for each resource, allowing the browser to choose the best resource based on the user's device and media features. For example, media="(min-width: 600px)" specifies that the resource should be used when the viewport is at least 600 pixels wide.

WEEK 2 NOTES✔😊
UNIT 5-  Working with Graphics and Images


📸📸📸Images

📸When we want to add an image to a webpage, we use the image element, which is simply written as IMG. 
📸Here is the cool part: there are four attributes that need to be included for every image. 

1.First, we have the source attribute (SRC), which tells the browser which image file to load. 
2.Then we have the alt attribute (ALT), which provides a text description of the image. 
3.Lastly, we have the width and height attributes, which determine the size of the image. So, every image should have all four of these attributes.

NOTE
It does not matter whether the height or the width is specified first. In HTML, the order of attributes within an element can be whatever you prefer.

📸😊Image Formats






