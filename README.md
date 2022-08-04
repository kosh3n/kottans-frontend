# kottans-frontend

 <!-- 
- <em>What's was new:</em>

- <em>Thing(-s) that amazed you:</em>

- <em>Thing(-s) that you are going to use in future:</em> -->

# General
## Git та GitHub
Well, that was interesting. Now I think I know how to work with Git better than I used to. There were also a lot of things that are new to me, like patch and fetch commands. I found these two very useful and saving a lot of time, especially the last one. And I've learned what to do with merge conflict because until now I have never faced it before. Will definitely use all new commands in the future. Besides I guess I will read more about merge and rebase differences because this thing I still not quite understood :c

<details>
 
![Знімок екрана 2022-08-03 123158](https://user-images.githubusercontent.com/95924961/182576043-de9f1610-0453-4ac9-ad68-8cb009f25ecb.png)
 
</details>

***

## Linux, Command Line, HTTP Tools

<strong>1. Linux Survival (4 modules)</strong>
This was really hard for me, mainly 3 & 4 modules. Most every command was new to me. There were some commands which I knew before from the Git (like mkdir, cd, ls,  rm...) but the rest of the things were completely new:
* File security. You can read, write or/and execute the file if it's a programm. the owner in Linux seems to be like administration rights in windows. For changing right permission you shoul use <strong>chmod</strong>;
* The difference between <strong>find ~ -name "poem*"</strong> and <strong>find . -name "poem*"</strong> is in that if you're not sure whether the file is called "poem", "poems", or even "poem-favorite" you can use '*'. But if you are already in the right directory, you can type command with "find .". It's just saving time;
* The hard disk file system in Linux and Windows is different. On a Linux system, however, there is only one directory tree. I find it not very suitable for a common windows user (like me);
* <strong>grep</strong> is used to find patterns in data (is one of the most obscure and easily-forgotten command names in Linux). 

I'm going to practice with these commands and hope to using them in future.
<details>
 
![Знімок екрана 2022-08-02 164613](https://user-images.githubusercontent.com/95924961/182572498-9046ef5b-956a-4059-936b-39090d282bd6.png)
![Знімок екрана 2022-08-03 125353](https://user-images.githubusercontent.com/95924961/182589189-4b3921f4-785f-4c46-bb5b-1cc17e5b9027.png)
 
</details>

---

<strong>2. HTTP: Протокол, який повинен розуміти кожний веб-розробник - Частина 1</strong>

- <em>What's was new:</em>  
I knew only GET/POST methods. Now I know that there are others: PUT, DELETE, HEAD, TRACE and OPTIONS. 

- <em>Thing(-s) that amazed you:</em>  
That HTTP Responses have a lot of information: status line, headers and body. Every response from the server will have a status code. The status code is important and tells the client how to interpret the server response. There' 1**, 2**, 3**, 4** and 5** statuses.

- <em>Thing(-s) that you are going to use in future:</em>  
I have studied a bit of Node.js and Express so I hope that I will use received knowledge in future work.

---

<strong>3. HTTP: Протокол, який повинен розуміти кожний веб-розробник - Частина 2</strong>

- <em>What's was new:</em>  
Almost everything. But most of all how does the Authentication and the Caching working. 

- <em>Thing(-s) that amazed you:</em>  
That you can control the cachability both from the server and client side.

- <em>Thing(-s) that you are going to use in future:</em>  
I have studied a bit of Node.js and Express so I hope that I will use received knowledge in future work.

***

## Git Collaboration

I've heard and wanted to try learngitbranching for a long time. It turned out to be quite heavy for me. There was two very difficult themes for me: rebase (cherry-pick I understand better) and the advanced topics on both sides. 

-<em>What's was new:</em>  

Have never heard out hit describe before. I know now differences between rebase and merge command. Rebasing makes your commit tree look very clean since everything is in a straight line but it modifies the history of the commit tree, while merge “merges two or more development histories”.

-<em>Thing(-s) that amazed you: </em> 

 I like tag command, find it very useful.
 
-<em>Thing(-s) that you are going to use in future:</em>  

git tag, git cherry-pick, git fetch, git rebase.  

<details>
 
![Знімок екрана 2022-08-03 204151](https://user-images.githubusercontent.com/95924961/182674340-c28e970a-c32c-4c2d-8e4d-2d4a5c21df88.png)
![Знімок екрана 2022-08-03 211054](https://user-images.githubusercontent.com/95924961/182806189-972d9173-4996-4947-988d-062abc3d5620.png)
 
 </details>
 
 ***
 
# Front-End Basics
## Intro to HTML & CSS

1. 1 & 2 weeks of "HTML, CSS, and Javascript for Web Developers":

- <em>What's was new:</em>

 I always forgot that inline element like span, can NOT contain a 'div', which is a block-level element. CSS rules conflict resolution was interesting part.
 
- <em>Thing(-s) that amazed you:</em>

 I heard only abot w3c, didnt know about WHATWG.
 
- <em>Thing(-s) that you are going to use in future:</em> 

Bootstrap maybe.
 
<details>
![Знімок екрана 2022-08-04 165604](https://user-images.githubusercontent.com/95924961/182865519-20ee1588-245e-40cb-b100-11d03fcae70e.png)
</details>

---

2. Learn HTML(Eng)

---

3. Learn CSS(Eng)


 <!-- 
- <em>What's was new:</em>

on codelearn: i absolutely didnt like neither html course nor html. Because there is no full task only step by step and if you make all it wont засчитается and it tske so much time to just finish it.   А если ты выполняешь все здание сразу, то оно не засчитывается а просто переходит к следующему этапу задания (которые ты уже выполнил) и ты думаешь что сделла что-то не так, но нет, надо просто несколько раз нажать на некст. Было ыб гораздо лучше вместо этого тренажора freecodecamp или любой другой, которій обрабатівает задания нормально. 👺 Прикол ещ' если ті удалил свойтсов и переписала его, но в другом месте (например внизу) то его не засчитают пока не перенес'шь на место где біло напсиано свойтсво. чзх

1)type[attribute*=value] прикольная вещь типа a[href*='florence'] { color: lightgreen;} 
2)Chaining
When writing CSS rules, it’s possible to require an HTML element to have two or more CSS selectors at the same time.
This is done by combining multiple selectors, which we will refer to as chaining. For instance, if there was a special class for <h1> elements, the CSS would look like below:
h1.special {}
3)Descendant Combinator
In addition to chaining selectors to select elements, CSS also supports selecting elements that are nested within other HTML elements, also known as descendants. For instance, consider the following HTML:
<ul class='main-list'>
  <li> ... </li>
  <li> ... </li>
  <li> ... </li>
</ul>
The nested <li> elements are descendants of the <ul> element and can be selected with the descendant combinator like so:
.main-list li {
}

4)For cases when we want user input to follow specific guidelines, we use the pattern attribute and assign it a regular expression, or regex
5) понравилось что статья в блоке хтмл про медведей. я люблю медведей.
6) embed tag wtf

![Знімок екрана 2022-08-04 163803](https://user-images.githubusercontent.com/95924961/182860992-325ce936-0e12-41cd-8163-70f1c9ba78f7.png)




- <em>Thing(-s) that amazed you:</em>


- <em>Thing(-s) that you are going to use in future:</em> -->

