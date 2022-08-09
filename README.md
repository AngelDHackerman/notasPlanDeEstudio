# notasPlanDeEstudio

Aqui guardo el numero de la pagina o el numero de episodo de lo que este estudiando.

## Why this repo?

Here I will save my notes about in what page I'm in or in which episode I leaft the videos that I see when I'm stydding in Platzi about programming. 

This is meant to a proof that __I'm not just leaving code just because I want__, actually I want to show to the world that even __if I not writing code, I'm
learning something about linux.__


#### Note for myself: 


Hi this is a note about __how to recover access to linux__, just in case you lost the root password. 

1. You must have physical access to the computer
2. Reboot the computer 
3. Once you see the grub manager, selec the option of your computer (normally it is the first option in the grup manager)
4. __hit "e"__ in your keyboard. 

5. You'll see and script, inside it you have to look for the word __ro__ 
6. erase the __ro__ and put in there __rw init=/sysroot/bin/sh__
7. hit __ctrl + x__
8. then continue with the command __chroot /syhsroot__
9. then the command __passwd root__
10. Once you change the password, always has the root user "#" run the next command __touch /.autorelabel__
11. and then __exit and reboot__.
12. Login in as a root and you'll have root access again. 