# 0x09. Implement a design from scratch
## Details
 By: Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School Weight: 3Project will startDec 22, 2022 12:00 AM, must end byJan 3, 2023 12:00 AMManual QA review must be done(request it when you are done with the project)### Concepts
For this project, we expect you to look at this concept:
* [Implement a design](https://intranet.hbtn.io/concepts/220) 

In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously. 
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.
Here the final result:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230102%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230102T224036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=29d133e2ea2290b51a388b3faf84ef9091ad33213501bbee07c38b02db0403d2) 

This webpage has been designed by Nicolas Philippot, UI/UX designer.You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip) 

### Requirements
* you are not allowed to import external CSS framework (like Bootstrap)
* you are not to use Javascript
## Tasks
### 0. Read and be familiar with Figma
          mandatory         Progress vs Score  Task Body Create an account in  [Figma](https://intranet.hbtn.io/rltoken/eumOUW-eMS4X9ZDZg9KPLg) 
  and open this  [project](https://intranet.hbtn.io/rltoken/2ED3P1a2wnbQqRLi8aXJKw) 
  and “Duplicate to your Drafts” to have access to all design details.
If you can’t access to it, please find here the  [Figma file](https://intranet.hbtn.io/rltoken/NxsDNicWs5KSlsR94kt52A) 

 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230102%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230102T224036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b8d87b79daecc296dc994b37c1a1a40c6ac7e6c09aaa02cb0f0b16c48bdcc39f) 

Important notes with Figma:
* if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/wltHny-KZP3B8JFRvpmVjA) 
 and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/Qb96K4nTPQJO1paP_OBELw) 

* some values are in float - feel free to round them
For this task, please write an amazing   ` README.md ` 
Interactions note:
* the web page must switch to the mobile version when the screen width is 480px or less
* links hover/active:  ` #FF6565 ` 
* button hover/active:  ` opacity: 0.9 ` 
* max width of the content: 1000px centered in the page
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` README.md ` 
 Self-paced manual review  Panel footer - Controls 
### 1. Header
          mandatory         Progress vs Score  Task Body Building a web page the right way, is not easy - expect if you put in place strong foundations:
* reset CSS styling
* use variables
* simple/“as generic as you can” CSS selectors
* avoid using super specific CSS selectors as much as possible
* simple HTML structure -  ` div `  containers are your friend!
Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.
Now, your turn!
For this first task:  create the header/hero piece
Here an archive of all assets needed:  [images_0x09.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230102%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230102T224036Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=6e9d75d54c38ab5caaa33eba703f5e9927f30c9da059891ff0fbaee11ab6db1c) 

Desktop:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/4a93441c93989ad7ea72.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230102%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230102T224036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4dc43f72d77de6aa0194328f1b1632eda7a8619a1ad0156978f86c529a0741e3) 

Mobile:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230102%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230102T224036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ba4485df2a422e72e586e120310b23079c93ea6d8920d82c51aadfda245341d0) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 0-index.html, 0-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 2. "What we do..." section
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
For this second task:  create the “What we do…” section
In this section, you will need custom font icons. Here the archive of it:  [holberton_school-icon.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230102%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230102T224036Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=21306ada428a4ce1d7a0454ff4e0824576324b237178073381dbeeea41faa91f) 
  Inside you will find demo page of how to use it.
Important:  try to build as generic as you can… you will probably need some components in next section.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 1-index.html, 1-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 3. "Our results" section
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
For this third task:  create the “Our results” section
Now you can reuse components form the previous task!
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 2-index.html, 2-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 4. Contact us
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
A good landing page has always a contact form.
You are free to add any animations and/or constraints on fields.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 3-index.html, 3-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 5. Footer
          mandatory         Progress vs Score  Task Body Copy files from the previous task.
Last piece of the page… the Footer!
When you are done, here the result:
Desktop:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230102%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230102T224036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=26da8e4dbfc7dc2847c05fdb3b0fec44407a4882303ec1f7d916f60b2b69b0ed) 

Mobile:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230102%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230102T224036Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d17d3d0413df2d818d84089aa451a55d38f8c5828207ab26ced4b76c862fdce8) 

And you are done! 
Good job!
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 4-index.html, 4-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
[Done with the mandatory tasks? Unlock 3 advanced tasks now!](https://intranet.hbtn.io/projects/622/unlock_optionals) 

Ready for a  manual review