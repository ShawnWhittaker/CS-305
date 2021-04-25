# CS305

Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their patrons.
They desire to modernize their operations and, as a crucial part of the success of its custom software, implement and apply the most current and effective software security. Artemis Financial has a RESTful web application programming interface (API) and is seeking expertise in taking steps to protect the organization from external threats

Using the maven dependency check, I was able to find security vulnerabilities that come from using third party code. Upon review, we are able to see where any known vunerabilities in the third party code may be, and the impact they can have on my program.

I was never able to successfully deploy the cipher and use the checksum to covert the HTTP protocol to HTTPS.

In order to increase layers of security, we implemented all updated versions of the spring framework, as well as the maven plug in for the dependency check. From there, we implemented the SHA-256 algorithm cipher which was able to encript our data. We deployed the cipher and used the checksum verification to add the secure HTTPS allowing secure online access to Artemis Financial's customers. We generated a certificate for authentication, which allows other's machines to trust our program, even though they haven't tested it themselves. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
All code was properly tested, although I was never able to successfully run the checksum verification. I used manual testing to scan through the code and read line by line to find any other security vulerabilities which is what led to having the updated version of the spring framework boot.

Knowing how to create secure code from the drawing board is a skill very helpful for future assignments.

I would showcase my ability to suggest an algorithm cipher that is strong, yet convenient to use, and my implementation of the dependency check.
