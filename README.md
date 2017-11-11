# Julia Workshop Intel HPC DevCon 2017

## Instructions 

0. Download the ssh key at the URL given on your sheet by entering it on your browser. 

1. Login to the URL you've been assigned by running:
```
ssh julia@ip -i path/to/pemfile
```
or [login via PuTTy](https://devops.profitbricks.com/static/img/tutorials/linux/putty_ssh_auth.png).

2. Run the following commands:
```
cd HPCDC
git pull
~/.julia/v0.6/Conda/deps/usr/bin/jupyter notebook --ip=0.0.0.0 --no-browser
```
You should find a URL come up on your screen which looks something like this:
```
http://0.0.0.0:8888?token=SomeAlphaNumericCode
```
3. Copy this URL and paste it in your browser. Before you hit Enter, replace `0.0.0.0` by the IP you've been assigned.

### Instructions ( JuliaBox | *next.juliabox.com*)

1. Log in to the URL that has been emailed to you. 

2. Click 'Packages' / 'Yours', and add the following packages by typing their name in the text box, and clicking the '+' button.
    - SymPy
    - Flux
    - BenchmarkTools

3. Click the 'Start' button to begin the installation process.

4. Clone these notebooks onto your instance: 
    - Copy `https://github.com/JuliaComputing/HPCDC.git`
    - Click 'Git', paste. 
    - Click on the '+' button. 

