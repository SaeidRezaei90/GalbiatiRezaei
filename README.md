# GalbiatiRezaei
## About the Course (Software Engineering 2)
The software process and software standards; lifecycles (waterfall, prototype-based, evolutionary/incremental, spiral, agile); standards (ISO2001, SPICE, CMM); software business models, licensing, intellectual properties, open-source software. Requirements engineering. Software technologies: middleware, componenti models (J2EE and .NET). Design patterns. Software architectures and architectural styles. Methods and notations for specification: FSMs, StateCharts, Petri nets, temporal logics, Alloy. Verification and validation: testing and analysis, model checking.

## About the Project
SafeStreets is a crowd-sourced application that intends to provide users with the possibility to notify
authorities when traffic violations occur, and in particular parking violations. The application
allows users to send to authorities pictures of violations, including their date, time and position.
Examples of violations are: vehicles parked in the middle of bike lanes, in places reserved for
people with disabilities, on foothpats, double parking etc.
SafeStreets stores the information provided by users, completing it with suitable meta-data
every time it recieves a picture. In paricular it is able to read automatically the license plate of
a vehicle and store it without asking the user to type it. Also it stores the type of the violation
which is input by the user from a provided list. Lastly it stores the name of the street where the
violation occurred, rereiving it automatically from the geographical position where the user took
the picture. Then the application allows both end users and authorities to mine the information
crowd-souced. Two visualizations are offfered: the first is an interactive map where are high-
lighted with a gradient color the streets with the highest frequency of violations. The second is a
list of the vehicles that committed the most violations (available only to authority users).
In addition the app offers a service that creates automatically traffic tickets which can be
approved and sent to citizens by the local police. This is done using the data crowd-soucred
by the users. The application guarantees that every picture used to generate a ticket has’t been
altered. In addition, the information about issued tickets is used to build statistics. Two kind of
statistics are offered: a list of people who received the highest number of tickets and some trends
of the issued tickets over time and the ratio of approved tickets over the violations reported.

## Team members
[Tiberio Galbiati](https://github.com/TiberioG)
[Saeid Rezaei](https://github.com/SaeidRezaei90)
