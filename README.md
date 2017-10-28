# Core Python Applications Programming
## by Wesley Chun
### My Solutions to the Rigorous Exercises in the Excellent Book
(Most of them in Python 3)
***
[Library Requirements File (For Python2)][req2]
***

* [Chapter 3: WebClient Programming][chap3]
* [Chapter 4: Multithreaded Programming][chap4]
    * [Example 4-10: Locks and More Randomness (mtsleepF.py)][e4-10]
    * [Example 4-11: Candy Vending Machines and Semaphores (candy.py)][e4-11]
    * [Example 4-12: Producer-Consumer Problem (prodcons.py)][e4-12]
    * [Example 4-13: Higher-Level Job Management (bookrank3CF.py)][e4-13]
    * ***
    * [Exercise 4-1: Processes vs. Threads (processes_vs_threads.md)][4-1]
    * [Exercise 4-2: Utility of multithreading in Python (python_threads.md)][4-2]
    * [Exercise 4-3: Mulithreading on Multicore System (threads_multicore.md)][4-3]
    * [Exercise 4-4-a: Simple Byte Count (bytes_count.py)][4-4-a]
    * [Exercise 4-4-b: Multithreaded Byte Count (mt_bytes_count.py)][4-4-b]
    * Exercise 4-5: Threads, Files and Regex ([mt_simple_header_analysis.py][4-5-i], [simple_header_analysis.py][4-5-ii])
    * Exercise 4-6: Threads and Networking ([mt_duplex_chat_serv.py][4-6-i], [mt_duplexc_chat_clnt.py][4-6-ii])
    * [Exercise 4-7: Threads and Web Programming (Optional, to be done)(mtcrawl.py)][4-7]
    * [Exercise 4-8: Thread Pools (thread_pools.py)][4-8]
    * [Exercise 4-9: Files (mt_lines_counter.py) Single threaded version runs faster than the multithreaded one.][4-9]
    * [Exercise 4-10: Concurrent Processing (concurrent_processing.py)][4-10]
    * [Exercise 4-11: Synchronization Primitives (sync_prim.md)][4-11]
    * [Exercise 4-12: Porting to Python 3 (already built Example 4-11 in Python3) (candy.py)][e4-11]
***

* [Chapter 5: GUI Programming][chap5]
    * [Example 5-1: Label Widget Demo (changed in Exercise 5-3) (tkhello1.py)][e5-1]
    * [Example 5-2: Button Widget Demo (tkhello2.py)][e5-2]
    * [Example 5-3: Label and Button Widget Demo (Changed in Exercise 5-4) (tkhello3.py)][e5-3]
    * [Example 5-4: Label, Button and Scale Demonstration (tkhello4.py)][e5-4]
    * [Example 5-5: Road Signs PFA GUI Application (pfaGUI.py)][e5-5]
    * [Example 5-6: File System Traversal GUI (listdir.py)][e5-6]
    * [Example 5-7: Tix GUI Demo (animalTix.pyw)][e5-7]
    * [Example 5-8: Pmw GUI Demo (modified in Exercise 5-10) (animalPmw.pyw)][e5-8]
    * [Example 5-9: wxPython GUI Demo (modified in Exercise 5-10) (animalWx.pyw)][e5-9]
    * [Example 5-10: PyGTK GUI Demo (animalGtk.pyw)][e5-10]
    * [Example 5-11: Tile/Ttk GUI Demo (animalTtk.pyw)][e5-11]
    * [Example 5-12: Tile/Ttk Python 3 GUI Demo (animalTtk3.pyw)][e5-12]
    * ***
    * Exercise 5-1: Client/Server Architecture ([client\_server\_architecture.md][5-1])
    * Exercise 5-2: Object-Oriented Programming ([oop.md][5-2])
    * Exercise 5-3: Label Widgets ([tkhello1.py][5-3])
    * Exercise 5-4: Label and Button Widgets (modified in Exercise 5-5) ([tkhello3.py][5-4])
    * Exercise 5-5: Label, Button and Radiobutton Widgets (modified in Exercise 5-6) ([tkhello3.py][5-5])
    * Exercise 5-6: Label, Button and Entry Widgets ([tkhello3.py][5-6])
    ![Output for Exercise 5-6](/Chap5/screenshots/E5-6.png)
    * Exercise 5-7: Label and Entry Widgets and Python I/O (extra credit stuff will be done later) ([file_reader.py][5-7])
    ![Output for Exercise 5-7](/Chap5/screenshots/E5-7.png)
    * Exercise 5-8: Simple Text Editor ([text_editor.py][5-8])
    ![Output for Exercise 5-8](/Chap5/screenshots/E5-8-0.png)
    ![Output for Exercise 5-8](/Chap5/screenshots/E5-8-1.png)
    * Exercise 5-9: Multithreaded Chat Applications ([chat_serv.py][5-9-1], [chat_clnt_GUI.py][5-9-2])
    ![Output for Exercise 5-9](/Chap5/screenshots/E5-9-1.png)
    ![Output for Exercise 5-9](/Chap5/screenshots/E5-9-2.png)
    ![Output for Exercise 5-9](/Chap5/screenshots/E5-9-0.png)
    * Exercise 5-10: Using Other GUIs (some are not working on my system, so very little modification is done.) ([animalPmw.pyw][5-10-0], [animalWx.pyw][5-10-1])
    * Exercise 5-11: Using GUI Builders. I had problems in either installation, download or running of the builders (some of them maybe due to version mismatch). Thus, perhaps later.
***

* [Chapter 6: Database Programming][chap6]
    * [Example 6-1: Database Adapter Example][e6-1]
    * [Example 6-2: SQLAlchemy ORM Example][e6-2]
    * [Example 6-3: SQLObject ORM Example][e6-3]
    * [Example 6-4: MongoDB Example][e6-4]

[req2]: /requirements.txt
[chap3]: /Chap3
[chap4]: /Chap4
[e4-10]: /Chap4/mtsleepF.py
[e4-11]: /Chap4/candy.py
[e4-12]: /Chap4/prodcons.py
[e4-13]: /Chap4/bookrank3CF.py
[4-1]: /Chap4/processes_vs_threads.md
[4-2]: /Chap4/python_threads.md
[4-3]: /Chap4/threads_multicore.md
[4-4-a]: /Chap4/bytes_count.py
[4-4-b]: /Chap4/mt_bytes_count.py
[4-5-i]: /Chap4/simple_header_analysis.py
[4-5-ii]: /Chap4/mt_simple_header_analysis.py
[4-6-i]: /Chap4/mt_duplex_chat_serv.py
[4-6-ii]: /Chap4/mt_duplexc_chat_clnt.py
[4-7]: /Chap4/mtcrawl.py
[4-8]: /Chap4/thread_pools.py
[4-9]: /Chap4/mt_lines_counter.py
[4-10]: /Chap4/concurrent_processing.py
[4-11]: /Chap4/sync_prim.md

[chap5]: /Chap5
[e5-1]: /Chap5/tkhello1.py
[e5-2]: /Chap5/tkhello2.py
[e5-3]: /Chap5/tkhello3.py
[e5-4]: /Chap5/tkhello4.py
[e5-5]: /Chap5/pfaGUI.py
[e5-6]: /Chap5/listdir.py
[e5-7]: /Chap5/animalTix.pyw
[e5-8]: /Chap5/animalPmw.pyw
[e5-9]: /Chap5/animalWx.pyw
[e5-10]: /Chap5/animalGtk.pyw
[e5-11]: /Chap5/animalTtk.pyw
[e5-12]: /Chap5/animalTtk3.pyw
[5-1]: /Chap5/client_server_architecture.md
[5-2]: /Chap5/oop.md
[5-3]: /Chap5/tkhello1.py
[5-4]: /Chap5/tkhello3.py
[5-5]: /Chap5/tkhello3.py
[5-6]: /Chap5/tkhello3.py
[5-7]: /Chap5/file_reader.py
[5-8]: /Chap5/text_editor.py
[5-9-1]: /Chap5/chat_clnt.py
[5-9-2]: /Chap5/chat_clnt_GUI.py
[5-10-0]: /Chap5/animalPmw.pyw
[5-10-1]: /Chap5/animalWx.pyw

[chap6]: /Chap6
[e6-1]: /Chap6/ushuffle_dbU.py
[e6-2]: /Chap6/ushuffle_sad.py
[e6-3]: /Chap6/ushuffle_so.py
[e6-4]: /Chap6/ushuffle_mongo.py
