# 
PicoCTF picoGym Practice Challenges | Python Wrangling

![Thumbnail](https://user-images.githubusercontent.com/111799231/192897489-3bcfb649-8813-4ec7-8c35-7e472e34c3cc.png)

WHAT?

picoCTF{4p0110_1n_7h3_h0us3_ac9bd0ff}

HOW?

You can see there are 3 files, “this Python script”, “this password” and “the flag”. Don’t wait and think just “(w)get” those files on your machine.

<img width="894" alt="wget pw txt" src="https://user-images.githubusercontent.com/111799231/192897529-c6dee0f1-b358-4353-b432-7edb787a6ef6.png">
<img width="886" alt="wget ende py" src="https://user-images.githubusercontent.com/111799231/192897532-bca5255b-ab19-44a9-8e32-24daf65aec10.png">
<img width="889" alt="wget flag" src="https://user-images.githubusercontent.com/111799231/192897534-02e6fc1a-320b-491c-a0b8-656779724931.png">



Now what? Let’s check those hints. Number 1 was “wget” which we already did it. 2nd hint is “man python”. Alright then, let’s do that. Doesn’t cost us any money, does it?
<img width="898" alt="help" src="https://user-images.githubusercontent.com/111799231/192897555-4ae45226-0cd8-4545-a977-51901f9385f6.png">


Oh. Okay.. it’s showing us bunch of commands that we can do with python. But we are still not sure what to do with these files. Wait, huh! A — help command?

<img width="413" alt="ende -h" src="https://user-images.githubusercontent.com/111799231/192897580-9c61f538-4041-49e4-a14e-b8637aec0414.png">

Woooo, Interesting! Let’s try like this then shall we?

<img width="320" alt="what pass" src="https://user-images.githubusercontent.com/111799231/192897625-98b4157e-2075-435b-9f3e-354d494c7d90.png">


TF?! What password? OOhh!! is that in one of those files?

<img width="238" alt="pass" src="https://user-images.githubusercontent.com/111799231/192897646-3ff3a09e-2aee-4b52-8eab-ef200dc77ff7.png">

Gotcha! I’m comin for ya, “ende.py”

<img width="321" alt="flag" src="https://user-images.githubusercontent.com/111799231/192897659-8e27ca67-e215-46d0-8e81-117aa5d7cfe5.png">

Et Voila!

WHY?

Just so we can learn how to work with python files. Like we learned that to run a python file we have to write python file_name Sometimes we have to write python3 then the file name, depending on the available python installed in the machine.

