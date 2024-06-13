# timedrun

Sometimes you can get lost if you're repeatedly executing the same script over and over again, maybe with slightly edited lines or different inputs. When this happens, it's helpful to store metadata about each run. To keep results straight, it would be helpful to know

- the date and time the command was run
- how long the whole thing took
- what the script looked like when you ran it. 

Much like prepending `time` to the beginning of a command, `timedrun` can be added to a command to help store metadata about a particular run. Information is stored in a file in your current working directory. The name of the file is `output_<currentdateandtime>.txt` In that file will be the timing information as well as the contents of the script that was run. 

