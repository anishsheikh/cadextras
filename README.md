# cadextras

here will be updated files that dont align with any copyright infringement and can be posted for helping others
 if you don't know what it is, kindly stay away.

SMIC180/icc.rules --> IC Custom router rules which were not included in various forums in chinese forums where i got it from. so i ported it and fixed the parameters a bit to work with it , still in beta, can't be used in anything great.

kernels.hip, kernels.hiph, ops.hip, ops.hiph --> latest bitsandbytes cuda code ported and compilation errors mitigated. logic isn't tested yet. needs to be fixed with cmake or 
make and python scripts. adding here because i might not continue it, becaause the code is not well organized and maintainablity is complicated because even tho the code is good enough as logic but complicated to maintain it without some sort of Frontend-Backend code API abstraction. 
Doesn't use miopen or  migraphx. so might be possible to compile and work on windows also.
hipblaslt doesn't support hipify. as of MAR 30 2.05 AM IST. would probably not worth it because uses torch python bindings rather than just simple hip/cudevicegetproperties()
we can try but i'm too lazy to add too much work.

//extra note:: Long story short . it's not like i wasn't aware of these. but i did have an rtx 2060. i do still have it. i had to RMA my computer 6 times. had to cut off intel
core i9 9900k which i bought in 2021 or 2020 i don't remember. it's just like it didn't work out for me. more like in early 2021 or midway, i got some people who wanted me to work
on their cuda project for money which i denied for some uncertain reasons. then i just had to rma the whole computer 4-5 times until i got fed up and bought the AMD stuff.
im sure its a painful experience to maintain. but i do get good support from amd. and on my actual things which matters are CAD modelling andd circuit designs. it works.
now for ROCm side it will get better with time. So its just a relatively opposite experience for me. i like wayland. i had it set up on a wayland ubuntu distro. but nvidia linux 
drivers has issues with wayland. you can use only x11 or pure cli. now i dont want my keystrokes passed around in all apps open lol. i prefer wayland comopositors.
its the same thing with those wmma cores like rtx2060 but performance close to rtx4060. but i don't want that hassle anymore. i had a laptop intel+amdgpu which was fine performing
for all my life when i was a *non-engineer* just a tech enthusiast from 2016. so im happy with it. i fix and work on what is workable. most of things will eventually get better.
as the problem with reset is not hardware generated but rather a bug in firmware related to instruction queue scheduler. which will eventually be fixed. its more like the pipeline, clock goes out of sync sometimes. so to keep the clock in sync check what nvidia does. mostly its not because of rocm either. its related to some code that might have been written for abstaction on both nvidia cuda and rocm hip in mind. this problem occurs. but it's all fixable. 

All files here are only for Educational Purpose, Downloading here means you abide that it is your sole responsiblity if you download it from here and if you use it for illegal purposes, you will be responsible by it, i am not responsible by any manner
