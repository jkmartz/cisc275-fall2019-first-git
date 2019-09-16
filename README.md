# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
	Three dog objects, a list of Dog objects and a Comparator object for Animal types are made.

3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?
	The Comparator constructor call is "new Comparator<Animal>()  within the Collections.sort method call. There is no class definition for the Comparator
	wwithin Dog or Animal. The constructor is in the Object class and is able to be used for type Animal due to polymorphism.