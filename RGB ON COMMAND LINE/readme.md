
 void *mmap(void *addr, size_t length, int prot, int flags,
                  int fd, off_t offset);
       int munmap(void *addr, size_t length);
       
       m map is a sysytem call simlerally works like malloc( )but when we execute the m map system call it creats a memory  with file size space of certain bytes on to the heap   segment and we can write or read the data on to the particukar memeory location 
       
       bu using this concept i have developed an application dev rgb function to write some colours on to the command line monitor interface by using mmap and open system calls 
