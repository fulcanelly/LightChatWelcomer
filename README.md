# LightChatWelcomer 


Simple minecraft plugin for on join messages 

#config example

you can specify colorful message on first or latter joins for player in config 


```yml

# plgugins/LightChatWelcomer/config.yml
first-join-message: "Welcome to the server! %player%, look to [&red&Hello](https://example.com)"
welcome-back-message: "Welcome back to the server! You were last seen on %lastseen%"

```

# Variables

- `%player%` variable to get user name
- `%lastseen%` to get formatted date of user last login

# Colors

you can specify text color in legacy way:

```
&6Text    # gold color
```

or by color name

```
&gold&Text 
```

# Links

you can also can make clicable link

```
[Text](https://example.com)                             
```

for advanced formatting take a look at 

or 

Modrinth = https://modrinth.com/plugin/welcomer
