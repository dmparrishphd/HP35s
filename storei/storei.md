# Store Indirect

Store a value in the unnamed indirect variable space.

Stack Requirement: 3

On entry, the stack contains a _value_ and a valid indirect variable _address_, with the address being the most recent item.

`I` is used internally, but is saved and restored, so there is no net change in `I`.

On exit, the _value_ is stored in the specified _address_ .
