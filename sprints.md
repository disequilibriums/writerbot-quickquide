# Using writerbot for sprinting<br><br>

This guide will go over how to use the writerbot for writing sprints!<br><br>

## Quick Links:
* [Starting a new sprint](#sprint-start)
* [Joining a sprint](#sprint-join)
* [Finishing or leaving a sprint](#sprint-end) 

---
<span id="sprint-basics"></span>
## Starting a sprint:<br><br>

1. If there is not currently a sprint running, you can start your own! Use the `sprint for` command and enter a value for the sprint length:

![img](/img/1_sprint_start.png)  

2. If you click ***+4 more***, you can add additional settings:  

* **in**: the # of minutes until the sprint begins
* **at**: set a specific time the sprint will begin at
* **initial**: set your initial wordcount for the sprint (this will be subtracted from your final wordcount)
* **project**: set a project to sprint in (this will add the words from the sprint to your project total)  

![img](/img/1b_sprint_start.png)  

![img](/img/1c_sprint_start.png)  

3. Your sprint will begin!

![img](/img/1e_sprint_start.png)  

---  

<span id="sprint-join"></span>
## Joining a sprint:<br><br>

1. If you want to get notified when new sprints are starting, use the `/sprint notify` command and set it to 'Yes':  

![img](/img/1d_sprint_start.png)  

2. To join a sprint that someone else has started, use `/sprint join`. There are a few options here:  

* `/sprint join normal` lets you choose an **initial** wordcount (ie. the wordcount of your document before the sprint), and a **project** to add your sprint wordcount to.
  * The default settings, unless you change them using the `sprint join set_default` command, are initial = 0, project = none.
* `/sprint join no-wordcount` lets you sprint without needing to add a wordcount (ie. for editing/art/other creative purposes). You can still select a **project**.
* `/sprint join same` lets you join with the same wordcount you had at the end of your last sprint.
* `/sprint join set default_join` lets you set your default join condition. 

![img](/img/1j_sprint_start.png)   

3. If you want your wordcount to increase for a specific project, you can also use `/sprint project ` to tell the bot to add your words from the current sprint to that project:  

![img](/img/1f_sprint_settings.png)  

![img](/img/1h_sprint_settings.png)  

4. __If you join with the wrong wordcount__, I haven't found an easy way to correct it... I would suggest leaving the sprint using `/sprint leave` and rejoining with the correct wordcount!

---  

<span id="sprint-end"></span>
## Finishing a sprint:<br><br>

1. When the sprint concludes, you will be pinged. Enter your updated wordcount using `/sprint wc`:

![img](/img/1g_sprint_start.png)  

2. Once all sprint participants have entered their word counts, you will receive a nice little scorecard:  

![img](/img/1k_sprint_end.png)  

3. If you need to leave a sprint before it concludes, you can use `/sprint leave`:  

![img](/img/1h_sprint_start.png)  

4. If you need to cancel a sprint you started, you can use `/sprint cancel `:

![img](/img/1f_sprint_cancel.png)  


