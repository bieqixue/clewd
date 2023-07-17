<div align="center">
<a href="https://gitgud.io/ahsk/clewd/">
<h1>Clewd</h1>
  <img
    height="120"
    width="120"
    alt="Clewd"
    title="Clewd"
    src="https://gitgud.io/ahsk/clewd/-/raw/master/logo.png"
    align="left"
  />
</a>

doom & coom

<br>

Warning: Some accounts are getting _hard-blacklisted_ by the **rats**, you might notice it

<br>
<br>
<hr>
<a href="https://gitgud.io/ahsk/clewd/-/archive/master/clewd-master.zip">
   <img src="https://gitgud.io/ahsk/clewd/-/raw/master/program.png">
</a>
<hr>

</div>

## Requirements

nodejs>=19.8.*

## Defaults

### SettingName: (DEFAULT)/opt1/opt2

 1. AdaptClaude: (false)/true
    * tries to make human/assistant prompts uniform between endpoints
    * almost useless with streaming on... for now ;)
    * effective with streaming off
    * Human->H
    * Human<-H

 2. AntiStall: (false)/1/2
    * no effect when using streaming
    * 1 sends whatever was last when exceeding size (might send empty reply)
    * 2 keeps going until it finds something usable or hitting size limit

 3. ClearFlags: (false)/true
    * possibly snake-oil

 4. RecycleChats: (false)/true
    * false is less likely to get caught in a censorship loop

 5. StripAssistant: (false)/true
    * might be good if your prompt/jailbreak itself ends with Assistant: 

 6. StripHuman: (false)/true
    * bad idea without RecycleChats, sends only your very last message

> [Download](https://gitgud.io/ahsk/clewd/-/archive/master/clewd-master.zip)