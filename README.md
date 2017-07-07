# links

**

kthread_park / kthread_unpark

https://lwn.net/Articles/500338/

http://www.informit.com/articles/article.aspx?p=414983&seqNum=2

http://www.linuxjournal.com/article/5600

https://kukuruku.co/post/multitasking-in-the-linux-kernel-interrupts-and-tasklets/

http://learnlinuxconcepts.blogspot.de/2014/01/bottom-halves.html

https://0xax.gitbooks.io/linux-insides/content/Concepts/per-cpu.html

https://kukuruku.co/post/multitasking-management-in-the-operating-system-kernel/

https://en.wikipedia.org/wiki/Symmetric_multiprocessing


**

**

tracing user/kernel-space:

<s>https://opensource.com/article/17/7/dynamic-tracing-linux-user-and-kernel-space</s>

https://www.kernel.org/doc/Documentation/trace/

perf mem

**

**

kernel/module.c

modprobe/insmod

http://www.linuxjournal.com/article/6896?page=0,2


**

affinity:

<s>https://www.systutorials.com/239953/sched_setaffinity-works-inside-of-linux-kernel/</s>

<s>https://www.systutorials.com/239971/migration-thread-works-inside-linux-kernel/</s>

**

** 

kworker/u8:25

https://www.kernel.org/doc/Documentation/kernel-per-CPU-kthreads.txt

**

**

Schedule:

<s>https://en.wikipedia.org/wiki/Completely_Fair_Scheduler</s>

https://en.wikipedia.org/wiki/Run_queue

https://www.cs.columbia.edu/~smb/classes/s06-4118/l13.pdf

http://martinbj2008.github.io/blog/2013/07/26/draft-how-to-select-a-realtime-task-when-schedule/

**

** 

Completion:

https://www.mjmwired.net/kernel/Documentation/scheduler/completion.txt

http://www.makelinux.net/ldd3/chp-5-sect-4

https://stackoverflow.com/questions/4764945/difference-between-completion-variables-and-semaphores

http://elixir.free-electrons.com/linux/latest/source/kernel/sched/completion.c

**

**

Mutex:

https://lwn.net/Articles/575460/

https://mortoray.com/2011/12/16/how-does-a-mutex-work-what-does-it-cost/

https://0xax.gitbooks.io/linux-insides/content/SyncPrim/sync-4.html

**

Memory

https://lwn.net/Articles/691631/ [Virtual memory map for stack]

https://emilics.com/notebook/enblog/p871.html [Memory consumption in Linux]

https://utcc.utoronto.ca/~cks/space/blog/linux/LinuxMemoryStats [Find out about mem usage Linux programs]

https://lwn.net/Articles/230975/ [How much memory are applications really using]

http://careers.directi.com/display/tu/Understanding+and+optimizing+Memory+utilization [Understand and opt. mem usage]

https://en.wikipedia.org/wiki/Thrashing_(computer_science) [Trashing]

https://en.wikipedia.org/wiki/Paging [Paging] ***

https://people.freebsd.org/~lstewart/articles/cpumemory.pdf [What every programmer should know about memory]

http://landley.net/writing/memory-faq.txt [Memory summary explanations]

https://www.kernel.org/doc/gorman/pdf/understand.pdf [Understanding the Linux Virtual Memory Manager]

https://xorl.wordpress.com/2011/01/16/linux-kernel-aslr-implementation/ [Linux Kernel ASLR implementation]

https://lwn.net/Articles/569635/ [KASLR]

https://stackoverflow.com/questions/37047977/which-segments-are-affected-by-a-copy-on-write [COW segments]

https://linux-mm.org/PageAllocation

https://stackoverflow.com/questions/29056097/how-does-linux-allocate-memory-for-its-physical-allocator

https://www.cs.columbia.edu/~junfeng/10sp-w4118/lectures/l23-vm-linux.pdf [Segmentation, COW, etc.]

http://wiki.osdev.org/Page_Frame_Allocation

https://groups.google.com/forum/#!topic/linux.kernel/7oKtsQavV6Q [RFC buddy allocator without bitmap]

https://linux-mm.org/OOM_Killer

https://en.wikipedia.org/wiki/Buddy_memory_allocation

https://www.kernel.org/doc/gorman/html/understand/understand011.html

http://www.johnchukwuma.com/training/UnderstandingTheLinuxKernel3rdEdition.pdf



*****
<s>http://blog.scoutapp.com/articles/2015/04/10/understanding-page-faults-and-memory-swap-in-outs-when-should-you-worry</s>

<s>https://0xax.gitbooks.io/linux-insides/content/Theory/Paging.html</s>


