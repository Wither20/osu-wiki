# Chat Console

From most screens in osu! you can press `F8` or click the `Show Chat` button on the lower right to overlay the Chat Console on the lower third of the screen.

![Chat Console](Chatconsole1.png "Chat Console")

-   The tabs list the currently available channels. Simply click on a tab to move to that channel. Click `New` to display a list of new channels to join.
-   The colours of the user names mean different things.

| Colour | Who?                                                                                                                                                                                                     |
|--------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **White**  | You                                                                                                                                                                                                      |
| **Pale**   | Non-supporters                                                                                                                                                                                           |
| **Yellow** | [osu!supporter](/wiki/osu!supporter/ "osu!supporter")                                                                                                                                           |
| **Red**    | [Global Moderation Team](/wiki/People/Global_Moderation_Team/ "Global Moderation Team") or [Quality Assurance Team](/wiki/People/Quality_Assurance_Team/ "Quality Assurance Team") member      |
| **Green**  | Line contains your name or certain keywords that you have added to trigger a "highlight". A copy of the message will also appear in a dedicated channel, `#highlight`, which contains all of these lines. |
| **Blue**   | Private Message                                                                                                                                                                                          |
| **Cyan**   | [peppy](https://osu.ppy.sh/u/2 "peppy"), the creator of osu!                                                                                                                                            |
| **Pink**   | [BanchoBot](/wiki/BanchoBot/ "BanchoBot")                                                                                                                                                           |

-   Click the `Show Ticker` box to display the newest chat message at the bottom of the screen when the chat console is not visible.
-   Click the `Auto-Hide` box to automatically hide the chat during gameplay (excluding beatmap intro, outro and breaks).
-   Click the `Hide Chat` box or press F8 again to hide the chat console.

## Extended Chat Console

*[osu!academy](/wiki/osu!academy/ "osu!academy") covered this page in [Episode 6 (6:52)](https://www.youtube.com/watch?v=cyYRl-a5xII) along with [Multiplayer](/wiki/Multi/ "Multiplayer").*

From most screens in osu! you can press `F9` or click the `Online Users` button at the lower right of the Intro Screen to toggle the Extended Chat Console. In addition to the Chat Console, Extended Chat overlays a list of panels in the remaining two thirds of the screen, displaying information on the users currently logged in osu!

![Extended chat console](Chat_Console-Extended.png "Extended chat console")

Each user logged in osu has a user panel displayed in Extended Chat. By default, it displays general information (name, total ranked score, rank, accuracy, play count and the user's avatar, if any). When the mouse cursor is placed over it, it displays a different set of information (name, rank, avatar if any, local time, time zone, location by country and, if allowed by the user, city, and what they are doing).

-   Friends only limits the display to your friends.
-   Lock Panels stops the panels from jumping round this also includes new users.
-   Click on a tab to sort user panels according to that attribute.
-   Click on the world map to display a world map that shows where everyone is.
-   You can click and drag on the white box to scroll, you can also use the mouse wheel.
-   Users without stats in their panels are connected to chat using their IRC clients.

| Panel colour                                                                                          | Description                                                                                                    |
|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| ![Player is idle](Chat_Console-Idle.png "Player is idle")                                             | Dark Blue - Players is currently idle or not doing anything or just chatting.                                  |
| ![Player is playing](Chat_Console-Playing.png "Player is playing")                                    | Grey - Playing a beatmap in solo.                                                                              |
| ![Player is watching](Chat_Console-Watching.png "Player is watching")                                 | Light Blue - Watching a replay or spectating someone.                                                          |
| ![Player is editing a beatmap](Chat_Console-Editing.png "Player is editing a beatmap")                | Red - Editing their own beatmap.                                                                               |
| ![Player is testing a beatmap](Chat_Console-Testing.png "Player is testing a beatmap")                | Purple - Test playing a beatmap either it's their beatmap or not.                                              |
| ![Player is submitting a beatmap](Chat_Console-Submitting.png "Player is submitting a beatmap")       | Turquoise - Submitting (either uploading or updating) the beatmap that they have made.                         |
| ![Player is modding a beatmap](Chat_Console-Modding.png "Player is modding a beatmap")                | Green - Modding or editing someone else's beatmap.                                                             |
| ![Player in Mulitplayer](Chat_Console-Multiplayer.png "Player in Mulitplayer")                        | Brown - User is in multiplayer, but not playing.                                                               |
| ![Player is playing in Multiplayer](Chat_Console-Multiplaying.png "Player is playing in Multiplayer") | Yellow - Currently playing in multiplayer.                                                                     |
| ![Player is Afk](Chat_Console-Afk.png "Player is Afk")                                                | Black - Inactive or away from keyboard (afk).                                                                  |
| ![Player is connected via IRC](Chat_Console-IRC.png "Player is connected via IRC")                    | Dark Blue without content - Player is not ingame, but logged in from an IRC client or stats are not available. |

Clicking on any user panel brings up an options screen.

![User panel options](Chat_Console-Userpaneloptions.jpg "User panel options")

Press the number or click the bar to activate:

1.  `Start Spectating`: If the user is playing a beatmap and you have the beatmap, you can watch them while they play. Your name will be in their Spectators list.
2.  `View Profile`: Opens the player profile webpage in your browser.
3.  `Start Chat`: Opens a private chat tab with the user.
4.  `Invite to game`: (If you are in the Multi room) Request the user to come to your room.
5.  `Add (Remove) as Friend`: Adds (Removes) the user at your friends list
6.  `Report User`: Report the user for misbehavior. Should never be used unless stated otherwise. You can report a user in-game for a number of things, but also on the web, like the forums.
7.  `Ignore User`: Any chat entry by the user will not appear in your chat console.
8.  `Close`: Closes the panel.

## Commands list

### /help

| Command        | Effect                                                                                         | Example           | BanchoBot response                                                               | 
|------------------|------------------------------------------------------------------------------------------------|--------------------|----------------------------------------------------------------------------------|
| `/addfriend [user]`   | Add `[user]` to your friends list.      | `/addfriend Amigo` | You are now friends with Amigo. |
| `/delfriend [user]`   | Remove `[user]` from your friends list. | `/delfriend Amigo` | You are no longer friends with Amigo. |
| `/away [message]` | Sets an away message (sent to users PMing you). Leave message blank to cancel. | `/away I am John Smith.` | You have been marked as being away: I am John Smith. When Amigo /msg John Where are you~?  BanchoBot: I am John Smith.|
| `/bb` | Sends a message to bancho like rank `[number]` | `/bb rank 1` | [15/11/12] Stats for Uan: Score: 47,323,299,680 (#1) Plays: 176293 (lv102) Accuracy: 98.95% |
| `/chat [user]` | Open a new chat tab with specified user. | `/chat Amigo` | (Amigo tab is opened) | 
| `/clear` | Clears the current chat buffer. | `/clear` | (Clears basically everything on the current tab) | 
| `/ignore [user][@chp]` | Ignore all messages from specified user for this session. By adding an @ followed by the letters, c, h, and/or p, you may ignore them in chat, highlights, or PMs respectively. | `/ignore Amigo@chp` | BanchoBot: You will no longer hear Amigo {chat} {highlights} {PM} (Your chat console is set to: ignore any text written by Amigo [c], any possible text highlighting you by Amigo [h] any Private Message sent to you by Amigo [p]) | 
| `/j [channel]` or `/join [channel]` | Joins the specified channel | `/join #lobby` | (#lobby tab is opened) | 
| `/p` or `/part` | Leaves the current channel you're parting or leaving. | `/part` | n/a | 
| `/unignore [user]` | Stop ignoring this user for this session. | `/unignore Amigo` | You may now hear Amigo. (Your chat console will allow any comment made by Amigo available to your chat console) | 
| `/me [action]` | Perform a third-person action. | `/me is at home` | * John is at home | 
| `/msg [user] [msg]` | Send a private message to `[user]`. | `/msg Amigo I am sick at home.` | (At Amigo tab) John: I am sick at home. | 
|`/np`| Print to chat the current song you are listening to or playing.| `/np`| (If playing) * John is playing [Peter Lambert - osu! tutorial \[Gameplay Basics\]](https://osu.ppy.sh/b/22538) | 
| `/reply` or `/r` | Reply to the last received private message. | `/r Do you know any good doctor?` | (At Amigo tab) [Previous comments] John: I am sick at home. Amigo: Really? John: Do you know any good doctor? | 
| `/savelog` | Saves current chat tab to a text file. | `/savelog` | (A folder called "Chat" will be created at the osu! directory which will contain all the future chat tab saves) | 
| `/watch [user]` | Start spectating `[user]`. | `/watch Amigo` | * Started spectating Amigo. (When Amigo plays a beatmap that you have, you will spectate his play [after some buffering] with your name on the left of Amigo screen) | 
| `/nopm` | Toggle to allow private messages either from everyone or friends only | `/nopm` | (A pop-up banner will appear at the center detailing you are allowing everyone/friends only for private messages) | 
| `/invite [user]` | Invites `[user]` to the multiplayer room along with the link. | `/invite Nathanael` | * Nathanael has been invited to the game | 


### /keys

| Keyboard keys     | Effect                                                   |
|-------------------|----------------------------------------------------------|
| `Page Up` / `Page Down` | Scroll the chat window.You may also use the mouse-wheel. |
| `Tab`               | Auto-complete currently typing nickname.                 |
| `F8`                | Toggle chat console.                                     |
| `F9`                | Toggle extended chat console.                            |
| `Ctrl` + `C` / `V`        | Copy/Paste.                                              |
| `Alt` + `0` - `9`         | Switch to respective tab.                                |
