## hi.

I'm a security researcher at [Active Countermeasures](https://www.activecountermeasures.com) that ponders one specific question: **how to detect C2 frameworks**.

While most tackle this problem by looking at the endpoint, my interest lies in taking a **network threat hunting** approach.

Why? Because **all applications stand naked before the Network Gods**. That's my pretentious way of saying that on the network, there's nowhere to hide. The issue isn't whether it's there, but rather **how to find it buried inside of the chaotic deluge of legitimate traffic**.

In the quest to become hopefully somewhat competent at this I like tackling the challenge from both angles.

Donning my defensive hat I think about ways to tease out C2/RAT communication by taking a **statistical + fingerprinting approach to analyze network traffic**. Though the specifics differ depending on the exact question I'm asking, the common thread almost always involves the use of **Zeek + custom Python tooling**.

And to better understand exactly how C2 communicates, as well as how it could still potentially communicate, I **develop C2 emulation tools**, mostly in Go and .NET. 

If you have any questions or feedback, feel free to connect with me - **moi@faanross.com**. 

Live long and prosper.

Faan

___

“If you wish to make an apple pie from scratch, you must first invent the universe.” – Carl Sagan
