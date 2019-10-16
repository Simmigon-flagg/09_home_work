# 09_home_work

Create a script, called args.sh. As a sanity check, add the line: echo "hello, world", and run the script.

from `sh args.sh`
```bash
echo "Hello, world"
echo $0
echo $1
```
Print out $0.
Answer: args.sh

What does this contain?
Print out $1.

Answer: args.sh Then, 1 argument

What happens when you run the script with arguments?
The application receives commandline input?

What happens when you run the script without arguments?
bNothing will happen but the `$0` will print.



Write a script that accepts three arguments from the user, then prints out the following:

The name of the script
The value of each argument

from `sh print3argument.sh`
``` bash
if [ $# -gt 0 ]
then
  echo "List of arguments:"
  for arg in $@
  do
    echo "The value of each argument "$arg""
  done

else
  echo "Done."
fi
````
mkdircd
![Screenshot (147)](https://user-images.githubusercontent.com/8258629/66887185-16593500-efa8-11e9-86c0-3568a7b3be59.png)
