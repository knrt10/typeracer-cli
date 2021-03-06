<p align="center">
<img src="https://user-images.githubusercontent.com/24803604/39766933-2386f1d8-5303-11e8-9f34-76c3b53f58c7.png" />
</p>


Typing practice from your terminal and features like practice mode and online competition mode.

# Installation

run `npm i --global typeracer-cli` from your command line

# Possible Errors

When you have installed this tool some times later you could find some error when you start **typerace**.

This may be because new update might have been rolled out and you have to update to latest version.

**How to update**

Its same as installation just run `npm i --global typeracer-cli` from your command line

Now even after that if you see any errors, follow the below steps

- find **.nvm** folder in your home directory.

-  cd to `.nvm/versions/node/${your node version}/bin` and delete **typerace file**
-  cd to `.nvm/versions/node/${your node version}/lib/node_modules` and delete **typeracer-cli folder**
- run `npm - -global typeracer-cli`

These steps should resolve the isssue. If it does not please open an isssue.

# Features

- Practice mode
- Online mode (can ask for a rematch)

# Usage

run `typerace` or `typerace -h` to its usage

**Output**

```
Usage: typerace [options] [command]

  Options:

    -h, --help          output usage information

  Commands:

    practice|p          Start typeracer
    online|o [options]  Start game in online mode
```

# Commands

**Practice mode**

- `typerace p` to start practice mode.

**Preview of practice mode**

![practice](https://user-images.githubusercontent.com/24803604/39727452-565bb37a-5270-11e8-82ad-4c882147dc03.gif)


**Online mode**

**Prevew of online mode**

![online](https://user-images.githubusercontent.com/24803604/39727662-431d9b60-5271-11e8-80fb-40698302c22d.gif)


 - `typerace o -f` to start online mode which will prompt a question

**Are you starting server for race (y/N) ?**

Now 2 cases are there

- If **yes**
  - You will share **Room to join for race**, **Number of racers**, **Number(sort of password)**
  - All the above will be prompted if you select yes and all of your friends should fill them out same.

- If **no**  
  - Ask for **Room to join for race**, **Number of racers**, **Number(sort of password)** from your friend who created a private room to race.

Enjoy :fire:
