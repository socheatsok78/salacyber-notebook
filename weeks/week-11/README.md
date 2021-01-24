# Week 11

**Homework**

```
Informations
- Virtual environnement chosen : Quaoar
- Description : 
    Welcome to Quaoar

    This is a vulnerable machine created for the Hackfest 2016 CTF : http://hackfest.ca/

    Goal: This machine is intended to be doable by someone who is interested in learning computer security. Get a shell and get root to get the flag in the file /passwd.
    Game duration : 240 min

- Validation flag is stored in the file /passwd
- Only registered players for this game can attack the virtual environnement.
- A tempo prevent game starting to early or too late.
- Game will start when one player has choosen his virtual environnement and declared himself as ready.
```

**Tools**

- [linPEAS](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS)
- [rebootuser/LinEnum](https://github.com/rebootuser/LinEnum)

**Check logs**

```sh
cat logs/linpeas.log | less
cat logs/LinEnum.log | less
```
