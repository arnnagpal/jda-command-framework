# jda-command-framework
My first real project on JDA

**This project is licensed under the terms of the MIT license**


* Example Usage:
```java
    @Command(name = "example", usage = "example", description = "The example command", permission = "ADMINISTRATOR")
    public void exampleCommand(CommandInfo cmd) {
        Message message = cmd.getGuildMessageEvent().getMessage();
        TextChannel channel = message.getTextChannel();

        channel.sendMessage(new MessageBuilder("This is an example command!").build()).queue();
    }
```


Being released soon.

Sneak peaks:

![Example #1](https://media.discordapp.net/attachments/635910982887014422/750613368985092126/unknown.png)

![Example #2](https://media.discordapp.net/attachments/635910982887014422/750614080565280818/unknown.png)

![Example #4](https://cdn.discordapp.com/attachments/746170234955628547/750627155523928095/unknown.png)
