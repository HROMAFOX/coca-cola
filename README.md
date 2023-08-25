# coca-cola
Minecraft coca kola



Кен с фанта image soon



Ефекти от бирата (Всички ефекти са по 15 секунди) image soon



Така се поставят командните блокове image soon




<pre class="wp-block-code">
🥤Команден блок 1(Repeat/Unconditional/Always Active) 
/execute as @e[type=player, nbt={Inventory:[{Slot:-106b, id:"minecraft:player_head", tag:{display:{Name:"{\"text\":\"ken with Fanta\",\"color\":\"white\"}", Lore:['{"color":"yellow","text":"с вкус на лимон"}','{"color":"green","text":"Пие се с F"}']}}}]}] at @s run playsound minecraft:entity.generic.drink player @s ~ ~ ~ 0.65 1 0

🥤Команден блок 2(Chain/Conditional/Always Active) 
/execute as @e[type=player, nbt={Inventory:[{Slot:-106b, id:"minecraft:player_head", tag:{display:{Name:"{\"text\":\"ken with Fanta\",\"color\":\"white\"}", Lore:['{"color":"yellow","text":"с вкус на лимон"}','{"color":"green","text":"Пие се с F"}']}}}]}] at @s run scoreboard players add @s FantaDrinking 1

🥤Команден блок 3(Chain/Conditional/Always Active) 
/execute as @e[type=player, scores={FantaDrinking=20..}] at @s run clear @s minecraft:player_head{display:{Name:"{\"text\":\"ken with Fanta\",\"color\":\"white\"}", Lore:['{"color":"yellow","text":"с вкус на лимон"}','{"color":"green","text":"Пие се с F"}']}} 1

🥤Команден блок 4(Chain/Conditional/Always Active) 
/execute as @e[type=player, scores={FantaDrinking=5..}] at @s run playsound minecraft:entity.player.burp player @s ~ ~ ~ 10 1 1

🥤Команден блок 5(Chain/Conditional/Always Active) 
/execute as @e[type=player, scores={FantaDrinking=5..}] as @s run effect give @s minecraft:Saturation 15 0 true

🥤Команден блок 6(Chain/Conditional/Always Active) 
/execute as @e[type=player, scores={FantaDrinking=5..}] at @s run scoreboard players set @s FantaDrinking 0

🥤Тази команда трябва да бъди написана в чата веднъж! 
/scoreboard objectives add FantaDrinking dummy

🥤Обикновен Команден блок с бутон за взимане на бирата! 
/summon minecraft:item ~ ~1 ~ {Item:{id:"minecraft:player_head",Count:1b,tag:{display:{Name:"{\"text\":\"ken with Fanta\",\"color\":\"white\"}", Lore:['{"color":"yellow","text":"с вкус на лимон"}','{"color":"green","text":"Пие се с F"}']},SkullOwner:{Id:[I;-546016941,-447004517,-1363775203,966134724],Properties:{textures:[{Value:"eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvZjM2MDgzNmUxZjY1MzNhMWZiNjQ4NGYzOTk1NjliODlhNGU4YTQwYmNjYTgxZTc1OWRmOTcxZGRkOGI1Y2Q0In19fQ=="}]}}}}}
</code></pre>
