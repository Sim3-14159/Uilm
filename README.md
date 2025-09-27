# Uilm
**Uilm** is a nonlinear interacitve survival game where you are trapped on a tropical island.

## 🎮 How to Play
Just go to [this website](https://Sim3-14159.github.io/Uilm) to play the game. If you want to see the code for it yourself, the file is [`index.html`](index.html) The code was created in [*Twine*](https://twinery.org) and converted to html.

## 🗺️ Plot

> You wake up. 
> 
> You are on the Reyches Islands, 200 miles north–northeast of the island of Hawai’i. The Reyches have many different climate zones, each filled with unique creatures, some of which are native only to these islands—including the extremely rare roundworm Chordodes uilm, which infects other animals and can use its host’s DNA as its own through horizontal gene transfer (HGT).
> 
> Which is why you are here.
> 
> You are a scientist that is working on creating a cure for cystic fibrosis—a life threatening genetic disease—by harnessing C. uilm’s ability to use HGT; if humans with cystic fibrosis could use HGT on themselves, they could replace all of the DNA that causes the disease with disease-free genes!
> 
> You and your team of scientists: Henry, Sarah, and Jole are receiving funding from the government, but since your research can save lives, it is profitable, and it needs to be kept a secret. Partially because of that, and partially because C. uilm lives only on the Reyches, you and your team do their research on those remote islands.
> 
> Everybody came to this island at the same time.
> 
> You don’t know any one on your team very well except for Henry, who was your childhood friend and grew up in the same neighborhood as you. Both of you have always wanted to find a new species, and knowing that the Pacific was the easiest place to do that, because of its high biodiversity, that was where you went. Then the US government offered you both a job (with a much higher paycheck) working with C. uilm, and Henry and you immediately switched gears.
> 
> Sarah and Jole have been working with you for the last 3 months, but you don’t know much about them, except that Sarah used to be a botanist. Sarah is very studious but Jole goofs around more.
> 
> Your laboratory is located near the base of the island, because that is where there are the most freshwater ponds, the perfect environment for C. uilm. Unfortunately, being near the coastline makes it more susceptible to natural disasters. 
> 
> This morning, you feel a few tremors. You think nothing of it, as they aren’t uncommon near the tectonic boundaries, until you get an emergency alert from the weather station on O’ahu. You look at your phone:
> 
>> ***Emergency Alert*** &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;  `4hrs ago`
>> 
>>  The National Weather Service has issued a TSUNAMI WARNING. A series of powerful waves and strong currents may impact coasts near you. You are in danger. Get away from coastal waters. Move to high ground or inland now. Keep away from the coast until local officials say it is safe to return.
>
> There is a small runway near the lab, and you know how to fly the plane. You could go back to the mainland, but you don’t want to leave your team behind if they choose not to come with you. After all, they will want to lose the research as much as you do. 
> 
> If you leave, you will probably lose all of your research, but if you don’t, you may risk your life. Any wrong move could be fatal.


## 📚 Story line
```mermaid
graph

0{#0 Start} --#1 Escape--> 1{Jole & Sarah won't come}
0 --#2 Stay--> 2{Files not backed up}
1 --#3 Up the Mountain--> 3{Centipede bite}
1 --#4 Fly Away--> ______{{Research lost}} -->___{{Sarah & Jole die}} -->4(survive)
1 --#5 Save It--> ________{{Lower time}} --> _______{{Save things}} --> 5{Wild boar}
2 --#6 Leave--> 6{{Only time for mountain}}
2 --#7 Flash Drive--> 7{Won't work}
2 --#8 Upload--> _{{Tsunami hits}} ---> 8((Die))
3 --#9 Go Back--> _____{{trip}}--> 9((Injured))
3 --#10 Stay Still---> 10([Surive])
5 --#? Swim--> alksjdf{{Boar chase}} -->asd{{Pulled out}}--> rip{Rip Current}
5 --#? Run--> ___________{{Be mauled}} --> ??????((Die))
5 --#? Climb--> Survive
6 --> 5
rip --#? Swim Sideways--> ????????((Survive))
rip --#? Swim Toward Shore--> ????????????{{Sucked out}} --> aklsdjlf((Die))
7 --#_ Grab Computer--> __{{Tsunami hits}} --> ??((Die))
7 --#_ Run---> ???[Survive]
```
