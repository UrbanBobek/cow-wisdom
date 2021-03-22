# cow-wisdom
Run the following commands to get a quote from a wise cow every fifth (or so) time you open your terminal.
```shell
  sudo apt install fortune-mod
  sudo apt install cowsay
  echo 'if [ $((1 + $RANDOM % 5)) -eq 2 ]
  then
  fortune | cowsay	
  fi' 
  >> ~/.bashrc 
 ```


