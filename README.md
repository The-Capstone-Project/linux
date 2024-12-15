# The Capstone Project - AI-Optimized Linux Kernel  

This is a custom Linux kernel built specifically for **AI workloads** as part of *The Capstone Project*. The goal was to strip out unnecessary features, reduce system overhead, and optimize performance for tasks like machine learning and data processing on modern hardware.  

## What’s Different?  

- **Faster Startup**: Kernel compression switched to **LZ4**, trading a bit of compression for quicker boot times.  
- **Simplified Features**: Removed legacy functionality (like old hardware emulation and outdated system calls) to make the system leaner and more efficient.  
- **Optimized for Modern PCs**: Stripped out support for hardware that's currently never used, like non-PC x86 platforms and configurations meant for servers or older systems.  
- **Better Memory Handling**: Tweaked memory settings to better support AI workloads without bloating the system.  

---  

For more details on changes read the .changes file.  
For more details on the kernel, visit https://docs.kernel.org
