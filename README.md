# 0x09. Implement a design from scratch
## Details
 By: Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School Weight: 3Project over - took place fromAug 11, 2022 12:00 AMto Aug 16, 2022 12:00 AMManual QA review was done by onAug 26, 2022 3:15 AM#### In a nutshell…
* Manual QA review:          0.0/116 mandatory            &            0.0/30 optional      
* Altogether:         0.0%* Mandatory: 0.0%
* Optional: 0.0%
*               Calculation:                   0.0%                    + (0.0% * 0.0%)               == 0.0%

### Concepts
For this project, we expect you to look at this concept:
* [Implement a design](https://intranet.hbtn.io/concepts/220) 

In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously. 
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.
Here the final result:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220924%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220924T113942Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0a241c03a33d109005165a873e27697daf08d1d7ef5192d10d157f50df1ad53b) 

This webpage has been designed by Nicolas Philippot, UI/UX designer.You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip) 

### Requirements
* you are not allowed to import external CSS framework (like Bootstrap)
* you are not to use Javascript
## Tasks
### 0. Read and be familiar with Figma
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create an account in  [Figma](https://intranet.hbtn.io/rltoken/eumOUW-eMS4X9ZDZg9KPLg) 
  and open this  [project](https://intranet.hbtn.io/rltoken/2ED3P1a2wnbQqRLi8aXJKw) 
  and “Duplicate to your Drafts” to have access to all design details.
If you can’t access to it, please find here the  [Figma file](https://intranet.hbtn.io/rltoken/NxsDNicWs5KSlsR94kt52A) 

 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220924%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220924T113942Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5bc7e212500aa2033f3e59202230d762e423a1baea7484363a51d6c8b9c62ed7) 

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
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Building a web page the right way, is not easy - expect if you put in place strong foundations:
* reset CSS styling
* use variables
* simple/“as generic as you can” CSS selectors
* avoid using super specific CSS selectors as much as possible
* simple HTML structure -  ` div `  containers are your friend!
Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.
Now, your turn!
For this first task:  create the header/hero piece
Here an archive of all assets needed:  [images_0x09.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220924%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220924T113942Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=d9f81551de50470422231ff0fb55cc239b3b4fbeebfbb4a988b7e164f6867602) 

Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/4a93441c93989ad7ea72.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220924%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220924T113942Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a375201ef8c1605c85c008aaffa5998696e480515102e59c6a9f2618d08c9d4a) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220924%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220924T113942Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9a77e86b0b1a951d520092424ff3742b9ad58f09b956ed6e26beb75a055f7956) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 0-index.html, 0-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 2. "What we do..." section
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Copy files from the previous task.
For this second task:  create the “What we do…” section
In this section, you will need custom font icons. Here the archive of it:  [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220924%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220924T113942Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=6ff568dd20354cf819d1d32d32892cb7f7253d0238b1843f0e581a785162fc6a) 
  Inside you will find demo page of how to use it.
Important:  try to build as generic as you can… you will probably need some components in next section.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 1-index.html, 1-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 3. "Our results" section
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Copy files from the previous task.
For this third task:  create the “Our results” section
Now you can reuse components form the previous task!
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 2-index.html, 2-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 4. Contact us
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Copy files from the previous task.
A good landing page has always a contact form.
You are free to add any animations and/or constraints on fields.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 3-index.html, 3-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 5. Footer
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Copy files from the previous task.
Last piece of the page… the Footer!
When you are done, here the result:
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220924%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220924T113942Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=dbf701f68833007cdac5e9ca7d9d2d5530b07ac4d04f67f57eccba1499bffc6d) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220924%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220924T113942Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=35ba16bc74035161baef87a9c7a4c3cdcda1d1a8e40809471461abbe38501450) 

And you are done! 
Good job!
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 4-index.html, 4-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 6. Replace background image with... code!
          #advanced         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body In the section “Our results”; without the use of an image file, draw each pentagon using HTML and CSS.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 100-index.html, 100-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 7. Let's animate items
          #advanced         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body From   ` 4-index.html `   and   ` 4-styles.css `  , add fun animations to “What we do…” and “Our results” sections items row. Either all the time, either when hover.
Scaling, opacity, rotation, bouncing… many options!
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 101-index.html, 101-styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 8. And SASS??
          #advanced         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Take your   ` 101-styles.css `   file and create a   ` 102-styles.scss `   that will be the SASS version of it.
 ` $ sass 102-styles.scss > 101-styles.css
 `  Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-headphones ` 
* File:  ` 102-styles.scss ` 
 Self-paced manual review  Panel footer - Controls 
Ready for a new manual review