# CPSC354-HW3
* Name: Emma Garofalo
* Email: garofalo@chapman.edu

## Using Large Language Models for Literature Review
* Assignment purpose: I will be having a "conversation" with a LLM about a particular topic in order to see if it is able to give me concise and accurate information in an efficient time to execute a literature review
* Chosen LLM: [Chat GPT 4o](https://chatgpt.com/)

* **Question Topic**: From the beginning of video game development until now, different programming languages have been used in order to develop video games. I want to explore these changes and why they took place historically. I also want to compare the more commonly used programming languages today in the career field of games and why one may be more preferred than another in differing game development situations.

**Relevant Concepts:**
* [Video games](https://books.google.com/books?hl=en&lr=&id=ErhNEAAAQBAJ&oi=fnd&pg=PA23&dq=video+game+development+history&ots=jx-k4Vcim7&sig=h7BrXaohpBwVoA0VBpoE3xo2TzQ#v=onepage&q=video%20game%20development%20history&f=false)
* [Comparing different programming languages](https://ieeexplore.ieee.org/abstract/document/876288)
* [Video game development](https://en.wikipedia.org/wiki/Video_game_development)
* [Concepts in programming languages](https://books.google.com/books?hl=en&lr=&id=7Uh8XGfJbEIC&oi=fnd&pg=PA1&dq=limitations+of+programming+languages&ots=7HQW0kEbZJ&sig=GgaLflkPOiiBlAvWILPdanHJUTI#v=onepage&q=limitations%20of%20programming%20languages&f=false)

## LLM Conversation:
Below I have included the more interesting parts of the conversation that I had with the LLM, and a small explanation of why I find them interesting.
#### My first question:
> How has the choice in programming languages from video game development varied from the start of video games until present day?
#### LLM Response:
>Here's a broad overview of how these choices have varied over time:

>**Early Days (1950s-1970s)**
Assembly Language: In the very early days of video games, assembly language was often used. This low-level language allowed developers to write code that was highly optimized for the hardware of the time. Games like Pong (1972) and Space Invaders (1978) were programmed in assembly language for their specific platforms.

>**Machine Code:** For some very early games, developers worked directly with machine code, the most basic level of programming, which is specific to each type of CPU.

>**1980s**
C: By the 1980s, C had become the dominant language for game development. It provided a good balance between low-level control and higher-level abstraction. Many classic games, including some for early home computers and consoles, were written in C.

>**Basic:** On early home computers like the Commodore 64, BASIC was popular for simpler games. It was relatively easy to learn and allowed for quick development of games, though it was less efficient than compiled languages like C.

>**1990s**
C++: With the advent of more complex games and more powerful hardware, C++ became increasingly popular. It offered object-oriented features, which were beneficial for managing the complexity of modern games. Games like Doom (1993) and Quake (1996) were developed using C++.

>**Scripting Languages:** As game development became more complex, scripting languages like Lua and Python began to be used for game logic and scripting within game engines. Lua, for instance, has been widely adopted for its flexibility and ease of embedding.

>**2000s**
Java: Java found some use in game development, particularly for mobile games and online games. It was known for its portability across different platforms, which was an advantage in the early mobile game market.

>**C#:** The release of the Unity game engine in the mid-2000s popularized C# in game development. Unity's ease of use and C#'s modern features made it a popular choice for both indie and professional developers.

>**2010s-Present**
C++: C++ remains a dominant language in game development, especially for high-performance, AAA games. Its powerful features and ability to work close to the hardware continue to make it a staple in the industry.

>**C#:** C# has solidified its place in game development thanks to Unity. It is used extensively for both 2D and 3D game development, and Unity’s extensive asset store and ecosystem have contributed to its popularity.

>**JavaScript and TypeScript:** For web-based games and mobile games, JavaScript has become prominent. Frameworks and libraries like Phaser and Babylon.js allow developers to create games that run directly in web browsers. TypeScript, a superset of JavaScript, is also gaining traction for its static typing and other modern features.

>**Python:** While not as common for high-performance games, Python is used in game development for scripting, tooling, and educational purposes. Its simplicity makes it a good choice for prototyping and learning.

>**Rust:** An emerging language, Rust is gaining interest in game development for its memory safety features and performance. While not yet mainstream, it is being explored for its potential to provide a safer and more performant coding experience.

**My Thoughts:**
Obviously this is an extremely broad answer. Nothing is super specific, there are no sources, and a lot of general information. But it is a good start. It gives us a lot of key words to further the conversation with the LLM so that more can be learned quickly.
#### My question: 
> Give me a detailed explanation of the very first programming languages for video games
#### LLM Response(Summarized):
* Machine Code: The lowest level programming language, made up of binary code. Pong was built in machine code due to lack of higher level languages. This language is highly complex and error prone. 

#### My question:
> Give me a detailed explanation of why particular programming languages are used today for particular video game types
#### LLM Response(Summarized):
* The LLM gave me a very helpful response to this question with game examples that use each type of programming language (obviously I double checked these examples to confirm that they were accurate)
* C++ - AAA Games such as The Witcher 3, Call of Duty. The main pros are high performance and high control which is necessary for the graphics that exist in these games. Allows for direct manipulation of memory and hardware, and supports multithreading.
* C# - Indie games such as Hollow Knight, Cuphead. This language is known for readability with a low entry barrier for new developers. Handles memory management and garbage collection. Can be integrated with Unity.
* JavaScript/TypeScript - Web games such as Cookie Clicker. Primary language for web development. Ease of deployment.
**My Thoughts:**
There were more detailed explanations of other languages, but they followed the same general pattern. They were very informative and I appreciate how all of the information is structured in the same general way so it is very easy to analyze. From this I learned that the primary languages used are C++, C#, and Swift (among some others).

## Conversation Analysis/Conclusion:
By researching this through Chat GBT, I was quickly able to learn very detailed information about how the choices in programming languages has drastically changed in such a short amount of time in the space of video game development. It began with very difficult to understand machine code, which was extremely unreadable for programmers, but has greatly changed to become what we know today. Motivated by the desire to make programming easier, but also more effective, this has allowed us to create much more complicated games. The present games have differing strengths and weaknesses, and because of that they are used in different gaming situations. But we can expect the innovation and complexity of games to continue to increase as developers continue to come up with better and better ways to employ the programming languages that we have at our disposal today. 



## References:
Oddly enough, a lot of the resources the LLM originally provided me with were to learn how to code in particular programming languages. After some more direct questions I was given articles that I could not locate online. The ones listed below are resources that I found myself.
1. Kowert, R. (2015). [Video game debate.](https://www.taylorfrancis.com/chapters/edit/10.4324/9781315736495-1/brief-history-video-games-james-ivory) Taylor and Francis. 
2. C. M. Kanode and H. M. Haddad, ["Software Engineering Challenges in Game Development,"](https://ieeexplore.ieee.org/abstract/document/5070627) 2009 Sixth International Conference on Information Technology: New Generations, Las Vegas, NV, USA, 2009,
3. TSCHANG, F. T. (2005). [VIDEOGAMES as interactive experiential products and their manner of development.](https://doi.org/10.1142/s1363919605001198) International Journal of Innovation Management, 09(01), 103–131.
