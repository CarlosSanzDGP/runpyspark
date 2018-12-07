# Easy to use apache spark script

Just copy the `runPySpark.sh` script into your prefered directory and inside it run:

```bash
    $ bash runPySpark.sh
```

**IMPORTANT:** Before running the `runPySpark.sh` script, ensure you have followed the checklist for your OS.

## Checklist for Ubuntu
* Install spark following this [medium post](https://medium.com/@josemarcialportilla/installing-scala-and-spark-on-ubuntu-5665ee4b62b1)
* Create an alias of spark in your home directory or rename the installation to just "spark"

```bash
    $ ln -s ~/spark-2.4.0-bin-hadoop2.7 ~/spark
```

* Ensure you have spark-shell in your $PATH variable (**Note:** this suposes you are running zsh or oh-my-zsh terminal, if that's not the case or you are not sure, just change `.zshrc` to `.bashrc` in the following command).

```bash
    $ echo 'export PATH="$PATH:~/spark/bin"' >> ~/.zshrc
    $ source ~/.zshrc
```
To check it works, you must be able to run `spark-shell` from your terminal.

* Run the `runPySpark.sh` script and enjoy!

## Checklist for MacOSX
* You need brew installed
* brew install jq 
* brew install spark-shell
* Run the `runPySpark.sh` script and enjoy!