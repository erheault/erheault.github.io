![Image of Pinhead Larry](https://i.pinimg.com/originals/9f/1d/da/9f1dda10df1ba896fd432ff21169de72.jpg)

```java
public void onGuildJoin(GuildMemberJoinEvent event) {
        JDA jda = event.getJDA();                       //JDA, the core of the api.
        long responseNumber = event.getResponseNumber();//The amount of discord events that JDA has received since the last reconnect.
        
        //do something
        
    }
```