# Simple Game Trainer

A simple game trainer that's not so simple after all.

## Features

- Feature-rich game trainer
- Inject custom Lua code
- Hot swap script system
- Decentralized script source with OTA updates
- Enhanced user safety and search systems

## Tech Stack

Cheat Engine (CE) compiler, CELua/Lua, Assembly, GitHub CDN

## Installation

Install this project by downloading the Trainer.CT file.

Certain URL calls have been redacted within the CT file for security reasons and all references to the broken URLs must be removed or replaced prior to running the program.

Create a new CT file and transfer the contents from Trainer.CT into the Script portion of the new CT. Do not include `<LuaScript>` tags from Trainer.CT.

Next, create the applicable CE Forms, which serve as the UI. Form elements will need to conform to the Lua references.

Compile and launch the trainer.
    
## License

[GNU GPLv3](https://www.gnu.org/licenses/)

## Lessons Learned

Creating and constantly maintaining this trainer was a very unique experience. I learned a lot about producing quality software and writing code. One large regret I had with this project is with my absolute spaghetti meal of code. It's only through each re-write that I was able to improve my structuring and refactoring methodology, and learn new ways to bring ideas to life.

This trainer was used by thousands of unique users from around the world. As of the end of life for the trainer (December 2019), the original post for this project amassed over 7,000 unique user likes, with one release version of the trainer having over 3,600 confirmed downloads. During its time of active development, hundreds of hours of work was put into the project. I would also spend a decent portion of that time troubleshooting and resolving issues that would be reported by users (and subsequently fixed as soon as I could).