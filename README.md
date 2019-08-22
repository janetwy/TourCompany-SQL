# TourCompany-SQL
SQL implementation of a tour company database for Intro to Databases class.

# Project Description
Paradise Tours and Travels is a travel agency with 3 branches. They want to develop a database
system that allows to maintain consistency among all the three branches. The agency has five
main modules: Employee, Customer, Booking, Branch and Payment.

Employees are salespersons, managers, or receptionist. Salespersons are further classified as
floor salesperson or internet salesperson. Employees work for branches and each branch can
have one manager. The Employee ID, Name (First, Middle ,Last), Address (Street, city, pin
code), Date of birth, Phone number(can have more than one phone number), Date of joining and
Salary of each employee is recorded. The Employee ID must be in the format “EXXX” where X
can have a value from 0 to 9.

A customer can either be an individual or a company. Customer details such as Customer ID,
Name (First, Middle, Last), Address (Street, city, pin code), Phone Number, Email Address,
Date of Visit (either online or in person) are recorded. Date of Birth (must be in the year 2001 or
before) is recorded for an individual. One person can have more than one phone number or
email. Each branch has a Branch ID, Branch Name, Address(Street, city, pincode), Phone
number and email. Customers have choice to be members in the agency. The membership details
such as membership ID, membership level and other information are stored. Members are
entitled to cash gift cards.

Different branches offer promotions. Each promotion has a promotion ID and other promotion
information such as name and promotion description. Each promotion ID is not unique and
cannot be used to identify a promotion in the agency.

Booking details of the purchases made by the customer such as booking ID, destination, travel
date (arrival and departure), number of individuals travelling are stored. Each booking contains
details of package tour. One booking can have one associated package tour. Promotions offered
at branches are applied to the package tours. Booking also contains transportation details such as
mode of transport and other information.

A customer makes a booking and the booking details, payment details, customer details, the
salesperson details who made the booking and the date of booking is stored together.
Package Tour contains details such as hotel details, number of days offered in the package,
destination and other information are stored. The hotel details such as hotel name, ID and
location are stored separately. Each package includes hotel information.

Each payment transaction has a unique payment ID, payment amount, payment type and
transaction date. A customer can pay using more than one payment method for the same
transaction. A person can pay by cash, or by gift card or pay via a combination of both. The cash
amount is recorded if a person pays by cash. For gift card, the membership details along with the
gift card ID are recorded.
