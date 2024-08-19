-  A declarative region that provides a scope to the identifiers inside it
- An organizational element to group your code into logical units
- Custom namespaces can be created like this:

	namespace Example
	{
		class ObjectManager {
			public: void DoSomething() {}
		};
		void Func(ObjectManager) {}
	}
	