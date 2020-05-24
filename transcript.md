Hello dear friends, I am Andrew and that is very nice to see you on my online course “Design patterns”.
I am super excited to be your instructor and let me give a quick view, what about we are going to speak today. 
The main today’s topic is going to be “Using Design patterns in java Script”
(right) So, what does it mean Design patterns? Wikipedia describes this concept the following way: - In software engineering, a software design pattern is a general reusable solution to a commonly occurring problem within a given context in software design. It is not a finished design that can be transformed directly into a source or machine code. It is a description or template for how to solve a problem that can be used in many different situations.
(bottom) This concept seems to be very difficult, isn’t it? That’s why we will try to describe it by mere words: Design patterns are solutions to recurring problems guidelines on how to tackle certain problems. They are not classes, packages or libraries that you can plug into your application and wait for the magic to happen. These are, rather, guidelines on how to tackle certain problems in certain situations.
(bottom) Let us consider the main advantages:
Design patterns
• No need to reinvent the wheel (lazy programmer is a good programmer);
• Find a common language with developers;
• You look cool and professional;
• These patterns go through all programming languages.
(bottom) But at the same time, you should always keep in your mind that:
• Design patterns are not a silver bullet to all your problems;
• Do not try to force them bad things are supposed to happen, if done so. Remember that design patterns are solutions to problems, not solutions finding problems;
• If you will use it correctly, Design patterns can be a savior otherwise they can be a reason for a horrible mess of a code. I suppose, this is the main disadvantage.
(right)
The next very important thing we should know about is the classification. Design patterns are divided into 3 classes:
• Creational
• Structural
• Behavioral

Unfortunately, due to lack of time I will briefly review this classification.
(bottom) Creational Design Patterns - Creational patterns are focused on how to instantiate an object or group of related objects.
(bottom) Structural Design Patterns - Structural patterns are mostly concerned with object composition or in other words how the entities can use each other. Or yet another explanation would be, they help in answering the question: How to build a software component?
(bottom) Behavioral Design Patterns - It is concerned with the assignment of responsibilities between the objects. What makes them different from structural patterns is they just specify the structure but also outline the patterns for message passing/communication between them. Or in other words, they assist in answering the question: How to run a behavior in a software component?

(right) Today we will consider Creational Design Patterns category in detail, and give any implementation examples. 
(bottom) The first one is Factory Method; it is used when we need to create many objects of the same type, with the same structure but with different data.
Let me give you one simple example:
(bottom)There are 2 classes. The first class generates a new object, and the second class calls this object with certain parameters.

(bottom) The second one will be Abstract Factory. This pattern creates interface and makes groups, which are logically connected to each other.
Example
(bottom) You can see that the factory receives an order for a common droid object production, but depending on the chosen model, the factory applies the necessary class.
(bottom) The next Pattern is Builder. This structural pattern is used for objects creating with complex states.
I hope after my example everything will get clear.
(bottom)We’ve got a class Car with our future object features but for this object modification we will use class CarBuilder.
(bottom) The last Pattern we are going to take an example is Singleton. This is just an object present in the system as a single instance, with no copies. Singleton pattern, which ensures that a class only has one instance, and provides a global point to it.
Now, no matter how many copies we would create with the help of constructor, all of them will refer only to one exemplar.
(right) Thank you for watching this video, I hope you enjoyed it. 
If that was useful and interesting for you so you can subscribe my channel, give me a thumb or leave the comment.
Have a good day, bye.
