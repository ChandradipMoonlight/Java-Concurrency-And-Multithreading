# <span style="color: #FAB5733">Java Concurrency And Multithreading</span>
***
## <span style="color: #FF5733">1. Introduction</span>

### Multitasking

1. **Process-based Multitasking:**
    - Executing several tasks simultaneously, where each task is a separate, independent program.
    - Uses separate address space in memory.
    - Examples:
        1. Typing a Java program in an editor.
        2. Listing audio songs from the same system.
        3. Downloading files from the internet.

   Note: Process-based multitasking is best suited at the OS level.

2. **Thread-based Multitasking:**
    - Involves executing several tasks simultaneously, where each task is a separate, independent thread of the same program.
    - Shares the same address space in memory.
    - Note: Thread-based multitasking is best suited at the programmatical level.

### Advantages Of Multitasking
The main objectives of multitasking, whether it is process-based or thread-based, include reducing response time and improving overall system performance. By allowing multiple tasks or threads to execute concurrently, a system can make better use of its resources and enhance its responsiveness to user inputs.

The main important applications of multithreading are:
1. To Develop multimedia graphics.
2. To develop animations.
3. To develop video games.
4. To develop Web servers and Application servers.

When compared with older languages, developing multithreaded applications in Java is very easy because Java provides inbuilt support for multithreading with a rich API, including the Thread class, Runnable interface, and ThreadGroup class.

## <span style="color: #FF5733">2. Two ways to define the Thread.</span>

- By extending Thread class.
- By implementing Runnable Interface.

## <span style="color: #FF5733">3. Getting and Setting the name of Threads.</span>

## <span style="color: #FF5733">4. Thread Partition.</span>

## <span style="color: #FF5733">5. Methods to Prevent Thread Execution.</span>

- yield()
- join()
- sleep()

## <span style="color: #FF5733">6. Synchronization</span>

## <span style="color: #FF5733">7. Inter Thread Communication</span>

## <span style="color: #FF5733">8. DeadLock</span>

## <span style="color: #FF5733">9. Daemon Thread</span>

## <span style="color: #FF5733">10. Multithreading Enhancement</span>

<span style="color: #33FF4E">Thread group, Thread Local, Executor Framework</span>
