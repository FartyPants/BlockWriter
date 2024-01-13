# BlockWriter
WebUI extension for fiction writing (experiment) using LLM assistance in blocks (writing in scene by scene)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Q5Q5MOB4M)


This is WIP (basic idea is done, but I HAVE BIGGER PLANS, whoaaa). It needs to reside in extensions/BlockWriter

It's basically a structured way how to write short scenes where you instruct LLM what should be in the next scene. Unlike normal chat you can change the prompt and response at any time and history (by simply overwriting the text), regenerate, etc... and the full text dynamically adjust to that.

## Note
I have a parallel project called DynaChat that is oriented on chatting with the model while uses simillar idea of dynamic history. https://github.com/FartyPants/DynaChat

![image](https://github.com/FartyPants/BlockWriter/assets/23346289/8b1639c6-4cd0-4542-9c28-4f07946b4f9d)

Note, you are always working on the selected scene. So rewriting prompt and hitting Generate will replace the text in the currently selected scene. Each time you want new scene you need to create new empty scene.

![image](https://github.com/FartyPants/BlockWriter/assets/23346289/b5baf84f-e3e8-40cd-8c82-5700bc363000)

Full text is always a dynamic reflection of the scenes

![image](https://github.com/FartyPants/BlockWriter/assets/23346289/c0bca09d-cb8a-4436-a8df-0eaee052fc45)


The project can be saved under unique name and then loaded later.

![image](https://github.com/FartyPants/BlockWriter/assets/23346289/2bce2bcf-0bc4-4f7b-ad84-d7333a5b6050)


# TODO
- A block can be turned into Summary
- create summary of the previous scenes
- Settings how many previous blocks to insert before the prompt.

