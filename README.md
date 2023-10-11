


```
An open source infomation grathering & reconnaissance framework!
```

<p align=center>
         <a href='https://www.w3schools.in/ethical-hacking/information-gathering-techniques/'><img src="https://img.shields.io/badge/Etical Hacking-OSINT-yellow.svg?logo=sharp"></a>
         <a href='https://github.com/13xsa5/WEEK-TOOL'><img src="https://img.shields.io/badge/Version-v3.1.0-orange.svg?logo=vectorworks"></a>
         <a href='https://www.python.org/'><img src="https://img.shields.io/badge/Python-3-blue.svg?style=flat&logo=python"></a>
         <a href='LICENSE'><img src="https://img.shields.io/badge/License-GPL%20v3.0-brightgreen.svg"></a>
         <a href=''><img src="https://img.shields.io/badge/Disclaimer-With great power comes great responsibility-red.svg?logo=hackaday"></a>
</p>
      
<br>

<h1 align=center>WEEK-TOOL: osint framework</h1>



<br>

## What is WEEL-TOOL?

- `WEEK-TOOL` is a one-stop tool for your information gathering and reconnaissance needs
- It can help you gather multiple types of information (such as phone numbers, ip addr, whois, etc.) from various publicly available sources about the target
> Previously, `WEEK-TOOL` was a tool used to gather information about a phone number, but now it has been upgraded to a ___framework___ with many _scanners_ available!



<br>
<br>

## Quick Guide
> Install, Update, Usage

<br>

### Installation:
- __git clone__
```
git clone https://github.com/13xsa5/WEEK-TOOL
cd WEEK-TOOL
pip3 install -r requirements.txt
```
- __pip__
```
pip install WEEK TOOL
```

<br>

### Update:
- __git clone__ (assuming you are in the `WEEK-TOOL` directory)
```
git pull
```

- __pip__
```
pip install --upgrade WEEK-TOOL
```


<br>

### Usage:
- __git clone__ (assuming you are in the `WEEK-TOOL` directory)
```
python3 weektool.py
```

- __pip__
```
WEEL-TOOL
```

- Help menu
```
    ┌────────────────────────────────────────────────────┐
    | COMMANDS      | DESCRIPTION                        |
    |----------------------------------------------------|
    |                 <(Basic Commands)>                 |
    |----------------------------------------------------|
    | help          | Display this help menu             | 
    | exit/quit     | Exit the framework                 |
    | dork          | Show a random google dork query *  |  
    | exp           | Show info about all available      |       
    |               | expressions                        |
    | check         | Check internet connection          |
    | clear         | Clear screen                       |
    | save          | Save output of previous scanner    |
    |               | command in a file                  |
    | shell <cmd>   | Execute native shell/cmd commands  |
    | info          | Show info about framework & system |
    | change        | Change user command input color    |
    |----------------------------------------------------|
    |                <(Scanner Commands)>                |
    |----------------------------------------------------|
    | number        | Reverse phone number lookup *      |
    | ip            | Reverse ip address lookup *        |
    | mac           | Reverse mac address lookup         |
    | whois         | Reverse whois lookup *             |
    | dns           | Reverse or normal DNS lookup *     |
    └────────────────────────────────────────────────────┘
```

#### Pro tips:
- Type `help` to get a list of commands
- Type `help <command>` to see more info about a command
- Use `Tab` key to auto-complete commands
- Try silent mode by using `-s`/`--silent` flag
- You can also use `Ctrl+C` to exit
- Descriptions ending with `*` needs internet connection


<br>
<br>


### NOTES:
```
- `WEEK-TOOL` is back with all new features and user interface
- `v3` has osint tools with no _api key_ requirement
- ADD: custom-scanner feature; create, distribute and deploy your own scanner
- Release windows (exe) & linux (lsb) direct executables, no python req.
```
