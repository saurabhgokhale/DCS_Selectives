# What does it mean to have a Bitcoin

Let's talk about a simple use case where friends go out to eat, and it can be inconvenient to keep exchanging cash among themselves

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/56bd248d-d610-4fe8-94c5-20b325d0f56e" />

This ledger can be public and accessible to everyone, like a website where anyone can go and just add new lines.
At the end of every month, you all look through the list of transactions and tally everything. If you’ve spent more 
than you received, you put that money into the pot, and if you’ve received more than you spent, you take that much money out.

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/3238380a-7335-4f01-b161-c190306c084f" />

> One problem with a public ledger like this is that when anyone can add a line, what’s to prevent Bob from going in and writing “Alice pays Bob $100” without Alice's approval?

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/381878e3-7282-4686-82ab-994e8863d5d0" />

## Digital Signatures
This is where the first bit of cryptography comes in: Digital signatures.

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/74533f72-3a34-4752-aa50-d4c5a3faf2cc" />

Like a handwritten signature, the idea here is that Alice should be able to add something next to a transaction that proves that she has seen it and approved of it.
And it should be infeasible for anyone else to forge her signature.





