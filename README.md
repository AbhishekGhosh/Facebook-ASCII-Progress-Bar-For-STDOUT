# Facebook ASCII Progress Bar

Run this on shell to get some fun :

````
echo -e "\x1B[31m █ \x1B[0m" && echo -e "\x1B[32m ██ \x1B[0m" && echo -e "\x1B[96m ███ \x1B[0m" && echo -e "\x1B[01;96m ████ \x1B[0m" && echo -e "\x1B[01;95m █████ \x1B[0m" && echo -e "\x1B[01;94m ██████ \x1B[0m" && echo -e "\x1B[01;93m ███████ \x1B[0m" && echo -e "\x1B[01;91m ████████ \x1B[0m" && echo -e "\x1B[01;90m █████████ \x1B[0m"&& echo -e "\x1B[01;89m ██████████ \x1B[0m"
````

Inside Loop (just an typical format) :

````
for (( i = 0; i < 17; i++ )); 
do echo "$(tput setaf $i)This is ($i) $(tput sgr0)"; 
done
````

Facebook ASCII Progress Bar For STDOUT. Proper calculation done for data visualization and printing on Facebook APP or Status Update with Python, Ruby, Perl, PHP etc.

````
█
██ 
███
████
█████
██████
███████
████████
█████████
██████████
███████████
████████████
█████████████
██████████████
███████████████
████████████████
█████████████████
██████████████████
███████████████████
████████████████████
█████████████████████
██████████████████████
███████████████████████
████████████████████████
█████████████████████████

````

See Example-Explanation.sh for explanation. See : https://github.com/yiisoft/yii2/pull/3367 for issues.
