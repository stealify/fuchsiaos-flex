# FuchsiaOS Flex
FuchsiaOS Flex - Run FuchsiaOS in the Cloud or in Your Local Hardware as long as it has Multi Core CPU this Implements most of the Fuchsia Core Principels on top of Linux via a Low Level VMM Based Zirkon Kernel Implementation 

## Why? 
I am HPC InterOp Expert and i see something more in Fuchsia then maybe the Most FuchsiaOS Engineers. So i start Porting the most importent concepts like the FIDL based IPC via the Component Manager Exchanging Handels and Include Capability based Security on it. That are The Importent Core Concepts of Fuchsia as Also the event driven modular Kernel. 

Many People that are not v8/Chromium Engineers are not aware of What is in that Stack and so are not aware about the big Compatability Effort that is put into that Platform and that it also contains everything you need for a Operating System. It goes so deep that it even uses a Own LLVM and tq asm generator engine. It is able to do Sandboxing in a OS Indipendent way and many more as it contains everything needed for WebGPU which is a HighLevel Vulkan Powered API for Graphics. A Window Manager Aurora and Many More.

It is not just that to be fair. This is also a small Building Block of my Effort to Design a Universal Component System as also deprecating many of the none needed stuff for today many Systems do contain a lot of bloat and unmaintained code and no one knows it. The Universal Component System is Part of a Compiler Infrastructure That i call Stealify which does not directly target Hardware it creates a IR that can be Deployed to any Hardware as long as it supports the Types and or it can at last Convert the Types to Perform Operations. The keywords here are long long and __int128 the nerds will know what i am talking about.



