# 09_home_work
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