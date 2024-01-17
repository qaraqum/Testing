# Testing methods

## Black box testing	
- No knowledge of the internal structure or code
- The focus remains on input and output
- Examples include higher levels of testing like system or acceptance testing

## White box testing	
- Testing based on the internal logic, structure, and code of the software
- Examples include lower levels of testing like unit testing

## Grey box testing	
- Combination of black box and white box testing
- Partial knowledge of the product’s internal structure is available
- Examples include integration testing

#Testing methods for integration testing
## Top-down approach	
- Starts with testing the higher-level modules or components first and gradually integrates lower-level modules.
- Stubs (simplified implementations of lower-level components) may be used for simulating the behavior of lower-level modules.

## Bottom-up approach	
- Begins with testing the lower-level modules or components first and gradually integrates higher-level modules.
- Drivers (programs that simulate higher-level components) may be used to provide inputs and test the behavior of higher-level modules.

## Sandwich approach	
- Also known as mixed integration testing, this approach combines elements of both top-down and bottom-up approaches.
- Allows for faster testing of critical modules by integrating lower-level modules and higher-level modules simultaneously.
