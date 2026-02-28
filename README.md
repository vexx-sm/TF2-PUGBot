<div align="center">
  
# <img src="https://github.com/user-attachments/assets/ff931ac2-d3ed-492f-b083-25659f92a83c" width="38" height="36"> TF2 PUG Bot

[![Latest Release](https://img.shields.io/github/v/release/vexx-sm/TF2-PUGBot?label=Download&color=success&style=for-the-badge)](https://github.com/vexx-sm/TF2-PUGBot/releases)
[![Players Tracked](https://img.shields.io/badge/Tracking-174+%20Players-6f42c1?style=for-the-badge)](https://github.com/vexx-sm/TF2-PUGBot)
</div>



<div align="center">


**An all in one SourceMod plugin and Discord Bot to set up, track, and manage 6s & Highlander PUGs.**<br>
*Features XYXY turn picks, Discord integration, Offclass ruling, ELO & Game History,  fully managed VCs and much more.*


<a href="https://discord.com/oauth2/authorize?client_id=1429868144322936895&permissions=272067664&scope=bot%20applications.commands">
  <img src="https://img.shields.io/badge/Invite%20Discord%20Bot-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=4f5bd5" alt="Invite Bot" scale="1.5"/>
</a>

<br>
<br>

**[ How It Works ](#how-it-works) • [ Commands ](#commands) • [ Installation ](#installation)**
</div>

---

<div align="center">

https://github.com/user-attachments/assets/fb3d677a-5315-4551-b1b8-d51c46d8e3a1

  
| Announcements (auto timezones) | Reserving free servers |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/296089c7-1980-4bcd-bcfd-06eae05cdfdf" width="420" /> | <img src="https://github.com/user-attachments/assets/ca0e23ac-dbbc-43da-a5dc-f99e75b26248" /> |

| Player Stats | Game History |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/46eb3d57-06f0-4706-b1a4-c948b72acba1" width="420" /> | <img src="https://github.com/user-attachments/assets/041b1933-92b3-4a03-98bb-529c0caa98a1" width="420" /> |

| Discord integration ex. | Slot PUG on discord |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/06095e99-0625-4f01-8ba8-a981d200cd0f" width="420" /> | <img src="https://github.com/user-attachments/assets/f901ff39-4d73-4ae0-b13e-d111bc44abd5" width="420" /> |


<br>

</div>

---

## How It Works

### `1` Pre-Game
> Players become captains using `!captain` or `!cap`. Once two captains are picked **and 12 players are present**, the plugin moves everyone to spectator. Captains are randomly assigned to RED or BLU.

### `2` Draft
> Captains take turns picking players using `!pick` *(Draft format: **XYXY XYXY XY**)*. 
> - Want to trade? Propose a `!swap x y` 
> - Need out? Use `!remove`
> 
> *Once teams are drafted, the server triggers **RUP (Ready Up)** and players are moved to their Team VCs on Discord.*

### `3` Live Game 
> Players can request a class swap with teammates with `!swap`

> If a player needs to sub out, they can request a rep (`!rep x`) right through Discord or in-game. 

---

## In-Game Commands

**Prefix:** `!` or `/`  
> *Most commands support 3+ aliases (e.g. `!restart`, `!redraft`, `!reset` all map to the same vote).*

<br>

<div align="center">

| Player Commands | Description |
| :--- | :--- |
| `!captain` / `!cap` | Become or drop as a captain |
| `!draft` / `!pick` | Open a menu of available picks *(Current captain only)* |
| `!draft <name>` | Pick a player by name *(Partial names work!)* |
| `!swap` | Captains suggest a player swap between teams. |
| `!swap` | Players request a class swap with a teammate. |
| `!remove` | Remove yourself or a teammate if you're a captain *(Draft/RUP phases only)* |
| `!offclass` | Initiate a vote to toggle offclassing on or off |
| `!rep <x>` | Request a replacement *(Live Game phase only)* |
| `!restart` | Call a vote to restart the draft *(Requires 2/3 majority)* |
| `!helpmix` / `!help` | Display the help menu of commands |

<br>

| Admin Commands | Description |
| :--- | :--- |
| `!setcaptain <p>` | Force assign or remove a player's captain status |
| `!adminpick <p>` | Force-pick a player for the currently drafting team |
| `!autodraft` | Randomly draft players into the remaining open slots |
| `!randommix` | a Quick start game, 2 random captains and random players |
| `!cancel` | Immediately cancel the current pug |
| `!rup` | Force both teams to ready up |
| `!cleanupstuck` | *(Discord-only)* Safely clears bot/game state if completely stuck |

</div>

<br>

---

## Installation

1. **Download** the latest version from the [Releases](https://github.com/vexx-sm/TF2-Mixes/releases) page.  
2. **Move** `mixes.smx` and `mixes_dm.smx` to your server's `sourcemod/plugins`.
3. **Extract** `configs.zip` to `tf2/tf/addons/sourcemod/`.
4. **Restart** your server or reload the plugin.

> [!TIP]
> You don't need a server to host, You can now host your PUG in 2 steps using the discord bot, **try `/host`** to reserve a pre configured server running [these](https://github.com/melkortf/tf2-servers?tab=readme-ov-file#tf2-competitive) plugins. Add [me](https://steamcommunity.com/id/57FN) for extra hosts/regions.

> [!WARNING]
> This plugin currently conflicts with SOAPdm. temporarily disable it for a proper experience.


<br>

<p align="right">
   <a href="#-tf2-pug-bot">
      <img src="https://img.shields.io/badge/Back%20to%20Top-↑-gray?style=for-the-badge" />
   </a>
</p>

