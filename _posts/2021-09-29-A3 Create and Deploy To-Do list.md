---
layout: post
title: "Create and Deploy To-Do list"
date: 2021-09-29
---

# Create and Deploy To-Do list
## link
[Github Link](https://github.com/dustinlo/NEUSEA-Chih-WeiLo/tree/444c549a63e1b82c41f3afbe23f5136f4b751a06/TodoApp)

[Android link (not yet reviewed)]()

## Screenshot

<img src="https://i.imgur.com/lE74DOJ.jpg" alt="drawing" width="400"/>

<img src="https://i.imgur.com/9m37747.jpg" alt="drawing" width="400"/>

<img src="https://i.imgur.com/RoaouWE.jpg" alt="drawing" width="400"/>
 
<img src="https://i.imgur.com/LYYFL71.jpg" alt="drawing" width="400"/>
 
## What I have done

I have completed most requirements in the sketch except few minor points. For instance, only a tag can be selected from the spinner at this point. I looked up online and I found an interesting point saying that the spinner is not designed for you do to select multiple items. I may alter it to some other components which fits better in future. Also, although the color does change after you tick the checkbox, once the onCreated is called again, it is lost. I understand I can use savedInstance to resolve this issue but since the checkbox does not really serve any mean, I did not accomplish this restoring state feature which is not listed in the requirements.

This is a really challenging code lab in my opinion because I have a higher expectation on myself so I watched a lot of videos to learn how to use components/viewgroups/view such as RecyclerView/CardView. After all, I do learn quite a bit from it but it is definitely very time consuming (took me more than 30 hours) to come up with a simple To-Do list application. 

The code is a little messy at this point but it works. Currently we are using a Singleton to store information and design-wise, I think my design at this point can be imporved a lot since a lot of references are exposed.

Overall, it is a fun lab!



