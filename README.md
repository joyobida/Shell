# Shell

read -p "what is your name " NAME
echo "Your name is $NAME"

read -p "what is today's date" DATE
echo "Today's date is: $(date)"
echo "Hello, World!"

echo "Checking disk usage..."
df -h


# No line 
read -p "please enter your age " AGE
 if  [ $AGE -lt 21 ]
 then
echo "Help Mommy wash dishes"
else echo " Please choose your beer"

 fi
