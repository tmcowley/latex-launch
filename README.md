# latex-launch
Bash script that:
1. Opens the given LaTeX file in VS code
2. Compiles that file (using `pdflatex`)
3. Opens the resulting pdf

For Mac-OS and Linux based Machines.

# Initialisation
1. Download the script using the following link: [project zip download](https://github.com/tmcowley/latex-launch/archive/master.zip)
2. Move to the directory in which the script is located: for example: 
```
cd ~/Downloads
```
3. Ensure the script has sufficient permissions: 
```
chmod 700 launch
```

# Usage
1. Move to the directory in which the script is located: 
```
cd ~/Downloads
```
2. Execute the script with the LaTeX file name as an argument: 
```
./launch latexFile
```
