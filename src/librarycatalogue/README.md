#Description:

This project is part of a larger project I am working on.

It was repurposed from this tutorial -> https://www.youtube.com/watch?v=ul0sdBqrivw
with some modifications.


##Modifications:
* All time properties should be in actual time measure not an integer count

* Build/Create a LIBRARY Class,
* and put a build/create catalogue method for cataloging all the library's book collection when the library(Library Catalogue) is just being setup; this method should just call the createBook method repeatedly.
* Transfer checkOutBook, ReturnBook, and BookAlreadyCheckout methods to the Library class.
* LengthOfCheckoutPeriod, InitialLateFee, FeePerDay, and currentDay properties should be in the Library class.
* Create a createBook method in Library for adding new Books to the LibraryCollection.
* When the book is returned late, calls the student class's addDept method and update the Library late fees dept by the totalLateFee [create a local, totalLateFee variable in the returnBook method]
* Add an option to pay for lateFee if any during the returnBook method. i.e. calls the Student class's makePayment method when selected. And if payment is made adjusts the studentDept property.

* create a STUDENT class,
* with one of its properties being studentDept(which has amounts and description). E.g. Library late fees -> $###.
* student class should have a method called addDept; which adds a new dept to the studentDept property
* Have a makePayment method. [Accepts amount, dept description; displays/prints dept status/balance for that dept description/type after payment has been completed]
* Other student properties: name, regNumber, DateOfBirth, DateOfAdmission, ExpectedYearOfGraduation, CurrentClass, Department