# Length of Last Word<br>

<br><b>"Given a string s consisting of words and spaces, return the length of the last word in the string."</b><br><br>

The question tells us to return the length of a string's last word. e.g "Hello World" should return the number 5.<br>
We do this through indexing the last word as a substring with tart with s.split()[-1], and then returning the length of it with len()
