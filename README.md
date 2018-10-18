# go-like-generics-proposal
An alternative Go-like proposal for Go2 generics.
Based on the ideas of Burak Serdar here: https://groups.google.com/forum/m/#!topic/golang-nuts/eqaDEb9xtGM

# Generic type parameter specification.

Generic types can be specified with a like clause . 
A like clause mentions one or more concrete types 
that the parameterized type must match. 
The concrete type in like clause can be a primitive type, an interface or a struct type.
