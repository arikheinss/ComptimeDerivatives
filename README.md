# ComptimeDerivatives
The purpose of this small project is to demonstrate how one can use the type system to infuse types with a ton of information, and how the compiler can utilize this information to create highly performant code for very specialized usecases without the programmer having to lift a finger.

To this end, I write a framework that can calculate and derive mathematical expressions depending on multiple variables, where the compiler can (often) determine the correct formula to calculate the derivative at compiletime, and I strive to do so in less than 100 lines of code, including whitespace and comments.

It is not feature complete, since its purpose is just to be a demonstration. Feel free to test if you could implement the missing pieces.

I use a handful of more advanced techniques, but I nonetheless encourage everyone including beginners to at least have a look, it might give you an idea of whats possible, even if you don't understand it all yet.


