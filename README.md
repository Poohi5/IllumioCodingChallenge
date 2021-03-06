# IllumioCodingChallenge
#

# Implementation

- I have implemented the code in Python using Pandas data frame. The input file is csv file and is read using Pandas data frame.
- I have created a Class &#39;Firewall&#39; which has a default constructor, and takes csv file as input.
- The default constructor initializes the Database which stores the input data.
- During Database initialization, the IP-Address and Port Range data is flattened, I.e. converted to integer format for faster lookup as well as to check whether the Ports and IP-Addresses are within the range.
- Database is initialized as empty, if the file does not exist in the specified file path or if there is any error during initiation.
- The Class Firewall has a Function **accept** \_ **packet** , which accepts Direction, Port, Protocol, IP-Address as parameters.
- This Function returns Boolean value &#39;T&#39; if the rules are matches or &#39;F&#39; if rules does not match.

# Testing

- I have tested the code using a testdata csv file which has an input and an expected output, to generate accuracy of the firewall rules predicted correctly based on the rules defined in the above Function.

# Improvements
**:**

If I had more time, I would have implemented the same functionality using Dictionaries as Dictionaries have less memory footprint and faster access due to optimized usage of keys.

**I would like to be part of the &quot;Data&quot; team.**
