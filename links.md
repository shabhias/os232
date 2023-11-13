---
permalink: LINKS/
---

# LINKS

* [Linux Crash Course - Easy Terminal Commands for Inspecting Hardware](https://youtu.be/oGyJr-iUwt8?si=59V2boc0XfmlFekg) --- 
Some easy-to-use commands you can use to inspect hardware. 
These commands will help you list PCI devices, view information about your CPU, and more.
<br>
<hr>

## WEEK 4
* [Operating Systems: Crash Course Computer Science #18](https://www.youtube.com/watch?v=26QPDBe-NB8)--- discuss evololution of OS. OSes evolved to support multitasking, virtual memory, and time-sharing, allowing multiple programs and users to run simultaneously. Popular OSes today, like Mac OS, Windows, Linux, iOS, and Android, have advanced features such as multitasking, virtual memory, and memory protection.

* [File Systems as Fast As Possible](https://www.youtube.com/watch?v=BV0-EPUYuQc)--- The search results include a variety of sources, ranging from grammar and language topics to book summaries, travel information, and technology explanations. The first source discusses compound nouns in English and the use of possessives. The second source mentions the spelling of the possessive form of "boss" and its pronunciation. The third source provides examples of subject pronouns in sentences. The fifth source reviews Bluetooth trackers and describes their different designs. The seventh source talks about Bali's beaches and provides information about one specific beach. The last part of the search results includes a transcript of a video discussing different file systems used in computers, particularly in Windows-based PCs.
  
<br>
<hr>

## WEEK 6
* [Server-side code - Inter process Communication](https://www.youtube.com/watch?v=4lCXmZTApiY&list=PLPEkNm3Pt05_EVg1sn_KPdMpEfUZ_8ISz&index=3)--- The server creates, writes data, and waits indefinitely for the client's signal, ensuring data integrity. The client reads and processes data from the shared memory, then signals the server to indicate completion. The code demonstrates basic interprocess communication using shared memory in a server-client model.
* SERVER SIDE
  - Shared memory is created and a key is generated.
  - Shared memory is attached, and successful attachment is checked.
  - A character pointer is created to access the shared memory as character data.
  - Alphabets from 'a' to 'z' are written to the shared memory.
  - A null terminator (0) is added to signify the end of the message.
  - The server enters an infinite loop, waiting for a signal from the client.
  - The server does not detach or delete the shared memory while waiting for the client to finish its work.

<br>
<hr>

## WEEK 7
* [Process Synchronization](https://www.youtube.com/watch?v=ph2awKa8r5Y&list=PLBlnK6fEyqRjDf_dmCEXgl6XjVKDDj0M2)---
1. Introduction to Process Synchronization: The video introduces the concept of process synchronization, emphasizing its crucial role in maintaining data consistency among cooperating processes in an operating system.

2. Cooperating Processes: Processes that can affect or be affected by others in the system are termed cooperating processes, which can share either a logical address space or data through files or messages.

3. Data Inconsistency Problem: The primary issue addressed is the potential for data inconsistency when multiple processes concurrently access shared data, leading to unpredictable outcomes.

4. Race Conditions: The concept of race conditions is explained, wherein several processes accessing and manipulating the same data concurrently can result in an unpredictable final outcome dependent on the order of access.

5. Illustrative Example - Bounded Buffers: The lecture employs the example of the producer-consumer problem within bounded buffers to illustrate how concurrent execution can lead to incorrect data values.

6. Importance of Process Synchronization: The video emphasizes the need for process synchronization to prevent race conditions, ensuring the orderly execution of cooperating processes and maintaining data consistency.

7. Objective of the Lecture Series: The video concludes by stating its objective — to delve into various mechanisms that facilitate orderly execution among cooperating processes that share a logical address space.


