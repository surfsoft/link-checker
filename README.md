Link Checker
---
This is a command line application. Example:

	mvn package
	java -jar target/link-checker-1.0.0-jar-with-dependencies.jar http://www.alexecollins.com

http://www.alexecollins.com broken link to http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>: java.net.URISyntaxException: Illegal character in query at index 80: http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>
http://www.alexecollins.com/ broken link to http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>: java.net.URISyntaxException: Illegal character in query at index 80: http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>
http://www.alexecollins.com/?q=blogs/alex broken link to http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>: java.net.URISyntaxException: Illegal character in query at index 80: http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>
http://www.alexecollins.com/?q=category/java broken link to http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>: java.net.URISyntaxException: Illegal character in query at index 80: http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>
http://www.alexecollins.com/?q=category/snippet broken link to http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>: java.net.URISyntaxException: Illegal character in query at index 80: http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>
http://www.alexecollins.com/?q=content/swing-plaf-example: failed to process link http://www.alexecollins.com/content/tutorial-swing-synth-plaf-template-part-1: java.io.FileNotFoundException: http://www.alexecollins.com/content/tutorial-swing-synth-plaf-template-part-1
http://www.alexecollins.com/?q=node broken link to http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>: java.net.URISyntaxException: Illegal character in query at index 80: http://www.google.com/search?hl=en&q=allinurl%3Afile+java.sun.com&btnI=I%27m%20F</body></html>
http://www.alexecollins.com/?q=node&page=3: failed to process link http://www.alexecollins.com/http//covestor.com/: java.io.FileNotFoundException: http://www.alexecollins.com/http//covestor.com/


