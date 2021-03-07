1. As Martin Fowler puts it: "Test Double is a generic term for any case where you replace a production object for testing purposes."
2. Stubs are canned results typically returned from a method call. Mocks are sekeletal class implementation typically used to verify correct set of interactions are made between the class under test and the mock. Dummys are objects that are  passed around to get the (test) code to compile but are not used in any meaningful/sophisticated manner or are not used at all.
3. State-based testing is based on making assertions on the state of the software after running a test. Behavior-based testing is based on verifying the interactions among different unit/components. 
4. If a dependency is available and undemanding state-based testing is preferred? If it is demanding though, we can use interaction-based testing.


