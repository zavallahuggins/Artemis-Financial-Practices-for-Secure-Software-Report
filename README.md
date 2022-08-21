# Artemis-Financial-Practices-for-Secure-Software-Report

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial does handle international transactions. This could include international wire transfers, out-of-country ATM withdrawals/deposits, or purchases through ecommerce originating from foreign countries. 

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

The changes added are heavily hinged on cryptography. The information is stored into 256 bit string, which is then translated into a hash, and then translated back using the public key generated. This facilitates a more secure API transaction than if there was no translation. The translation is encapsulated into one function that can be executed in many different situations. 

These security measures help protect the data of a plethora of people. The information of employees are protected. Also, the information of customers and vendors is more protected with the SHA-256 algorithm. 


What about the process of working through the vulnerability assessment did you find challenging or helpful?

I had a bit of an issue doing the suppression file, but once I got the hang of it, it was an easy concept to understand. These false red flags can waste time looking for problems that are not there. 


How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

Learning about the SHA-256 method was quite interesting. Also seeing how many possibilities it creates is quite amazing once the number of possibilities was verbalized. 


How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

After refactoring the code, I rendered another dependency check. 

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

Keeping my files organized is the most important thing for me. Having different files centralized in their respected catergories makes using them in the project much easier, since you have an idea of where they are supposed to be. 

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would like to showcase my implementation of SHA-256 and how much of an extra layer of security it adds. 
