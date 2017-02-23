Observer Pattern

	When to Use the Observer Pattern
	
When you need many other objects to recieve an update when another object changes.

	Stock market with thousands of stocks needs to send updates to
	objects representing individual stocks.
	
	The Subject(publisher) sends many stocks to the Observers.
	
	The Observers(subscribers) takes the ones they want and use them.
	
Loose coupling is a benefit

	The Subject (publisher) doesn't need to know anything about the
	Observers(subscribers).
	
Negatives: The Subject (publisher) may send updates that don't
matter to the Observer(subscriber).