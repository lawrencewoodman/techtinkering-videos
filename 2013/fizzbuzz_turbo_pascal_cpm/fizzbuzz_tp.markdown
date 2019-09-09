Turbo Pascal 3 is a great choice for programming in CP/M.
It is an IDE that allows you to edit, compile and run all from a single
application.

For this demonstration I'm going to create a fizzbuzz program. For those not familiar with FizzBuzz, it's a children's game, where players count up from 1 each taking a turn with the next number.  If the number the player is on is divisible by 3, they replace the number with Fizz, if divisible by 5 they replace it with Buzz and hence if divisible by 3 and 5 with FizzBuzz.

So it would go 1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz11 Fizz 13 14 FizzBuzz 16, 17, etc

  My set up is running at 4Mhz and has two disk drives.  The CP/M files are on disk A and turbo pascal is on disk B.

If we take a look at the Turbo Pascal files we can see just how small it is.  The total size of the files here is 68k and once you have configured turbo pascal you no longer need the TINST files.  This would leave the total file size at 34k, so there would be plenty of room for your source code.

To start Turbo Pascal we execute the 'turbo' command.

This then displays the splash screen showing the version and which terminal is configured.  We'll include error messages by pressing 'Y'.

We can now see the main IDE screen and the various options open to us.

I'm going to create a FizzBuzz program to demonstrate the use of TP.

First I need to create a pascal file, so I'll press W to specify the work file and then enter 'fizzbuzz.pas'.  To edit this file I press E.

I'm now presented with the editor and as you can see in the top right, I am editing fizzbuzz.pas.

I'll now enter the fizzbuzz program.  

The editor uses many of the Worstar key combinations which should be familiar to most CP/M users.

Now the program has been entered I press control K, then d to leave the editor and put me back at the IDE prompt.

To run and compile our program I press R.  TP uses a one pass compiler and by
 default is set to compile to memory and hence this process is very quick.  At the bottom of the screen you can the correct result of playing FizzBuzz.

From the IDE prompt, if you hit return the menu is redisplayed.

I said previously that TP defaults to compiling to memory and if I press D and leave the directory mask blank you can see that no new files have been created.  You can also see that there is no fizzbuzz.pas.  This is currently held in memory and will only be saved after TP prompts you to, or if you press S from the IDE menu.

If I wanted to compile to a Com file, then I would press O to go to the compiler options and then C to choose compile to com file.  Pressing Q takes me back to the main menu.

Now when I press R you can see that the compilation has been to b:fizzbuzz.com.  I'll now save my pascal file so that the ide can be replaced with fizzbuzz.com.

Again you can see the output of running the command.

Looking again at the directory we can now see both fizzbuzz.pas and the compiled fizzbuzz.com.

Pressing C instead of R, allows us to compile without running the program.

I now leave the IDE by pressing Q, run fizzbuzz from the CP/M command prompt and look at the disk using stat.

Here, you can see that the fizzbuzz.com file is 9k, which is quite big considering that we haven't done much.  However, this is mainly library and if you were using TP to create an application you would probably use quite a bit of the library functionality so this wouldn't be so wasteful.  You would also find that the com file would grow much slower from this point.

I hope that this demonstration showed that Turbo Pascal is practical, quick and easy to use environment for programming on CP/M.  If you are interested in similar videos or articles, please subscribe to the techtinkering video chanel and visit techtinkering.com.

