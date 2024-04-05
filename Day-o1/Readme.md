# What is JavaScript?
JavaScript was initially created to “make web pages alive”.
The programs in this language are called scripts. They can be written right in a web page’s HTML and run automatically as the page loads.
Scripts are provided and executed as plain text. They don’t need special preparation or compilation to run.

The overwhelming majority of websites use JavaScript, and all modern web browsers on desktops, tablets, and phones—include JavaScript interpreters, making JavaScript the most-deployed programming language in history. Over the last decade, Node.js has enabled JavaScript programming outside of web browsers, and the dramatic success of Node means that JavaScript is now also the most-used programming language among software developers. Whether you’re starting from scratch or are already using JavaScript professionally, this book will help you master the language.

# Hello, world!
JavaScript programs can be inserted almost anywhere into an HTML document using the <script> tag.
For instance:
#
<!DOCTYPE HTML>
<html>
<body>
  <p>Before the script...</p>
  <script>
    alert( 'Hello, world!' );
  </script>
  <p>...After the script.</p>
</body>
</html>

# External scripts
If we have a lot of JavaScript code, we can put it into a separate file.
Script files are attached to HTML with the src attribute:
#
<script src="/path/to/script.js"></script>
