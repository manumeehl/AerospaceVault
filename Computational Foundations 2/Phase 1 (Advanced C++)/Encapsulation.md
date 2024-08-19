### The include directive
- Tells the pre-processor to include the contents of a specific file at the point where the directive appears
- Helps to modularize the code and reusing functionalities from other files and libraries
- Syntax:  `#include “path-spec”`

---
### Include Guards
... are used to prevent multiple inclusions of the same header file

`ifndef CIRCLE_H`
`#define CIRCLE_H,`
	`// CODE`
`endif`

