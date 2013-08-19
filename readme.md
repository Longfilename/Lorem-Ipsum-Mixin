# Lorem Ipsum Mixin

I got tired of going to content generation websites, so I made this mixin. lipsum() is an easy-to-use mixin that will insert as much (random) content as you ask for into the page. No HTML, just content.

It takes two parameters - amount of content, and type ("words", "characters", or "sentaces").

## Usage:

lipsum(3, "words") > "maecenas accumsan aliquet"; always lowercase, no punctuation;  
lipsum(32, "characters") > "Cras pede libero, dapibus necp u";  
lipsum(2, "sentances") > "Nam quis nulla. Integer malesuada.";  
lipsum(2, "sentances") > "Aenean vel massa quis mauris vehicula lacinia tincidunt scelerisque libero. Maecenas dictum tincidunt diam.";

Each time lipsum() is called the content is randomized again.