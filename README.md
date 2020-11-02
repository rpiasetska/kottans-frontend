# kottans-frontend



![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/img/kot.jpg)



### General
- [x] 0. Git Basics
- [x] 1. Linux CLI and Networking
- [ ] 2. VCS (hello gitty), GitHub and Collaboration
### Front-End Basics
- [ ] 3. Intro to HTML & CSS
- [ ] 4. Responsive Web Design
- [ ] 5. HTML & CSS Practice
- [ ] 6. JavaScript Basics
- [ ] 7. Document Object Model - practice
### Advanced Topics
- [ ] 8. Building a Tiny JS World (pre-OOP) - practice
- [ ] 9. Object oriented JS - practice
- [ ] 10. OOP exercise - practice
- [ ] 11. Offline Web Applications
- [ ] 12. Memory pair game — real project!
- [ ] 13. Website Performance Optimization
- [ ] 14. Friends App - real project!
***
General
===============

## 0. Git Basics**
--------------
* Finished the course <a href="https://www.udacity.com/course/version-control-with-git--ud123">Version Control with Git</a>
![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/git_basics/udacity_course.png)
* Completed the following levels at <a href="https://learngitbranching.js.org/">learngitbranching.js.org:</a>
<details>
  <summary>screenshots</summary>
I. Main: Introduction Sequence
  
![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/git_basics/learngit1.png)

II. Remote: Push & Pull -- Git Remotes
  
![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/git_basics/learngit2.png)
</details>

#### Impressions:
I liked the materials. I think they are useful and necessary.<br> 
I also realized that I need to be more careful because I accidentally completed all the levels of learngitbranching.js.org !!! =))) <br> 
It was difficult but I was brave to finish it! :-D <br> 
![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/git_basics/cartoon_hero.png)

## Linux CLI, and HTTP
--------------
### 1.1. Linux, Command Line
Finished the course [Linux Survival (4 modules)](https://linuxsurvival.com/)
<details>
  <summary>screenshots</summary>
  
  ![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/2_vcs_github_collaboration/Linux_Quiz1.png)
  
  ![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/2_vcs_github_collaboration/Linux_Quiz2.png)
  
  ![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/2_vcs_github_collaboration/Linux_Quiz3.png)
  
  ![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/2_vcs_github_collaboration/Linux_Quiz4.png)
</details>

#### Impressions:
I had dealt with Linux earlier, so many commands were familiar to me. This was a good chance to refresh my memory and also gain new knowledge. 
The training was in a humorous manner. Excellent! Humor always helps to better remember material and keep attention


### 1.2. Linux CLI, and HTTP

URL (Uniform Resource Locator)

  ![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/task_linux_cli/http1-url-structure.png)
  
  HTTP. The default port is 80 
  HTTPS (HTTP Secured). The default port is 443
  
  #### HTTP verbs:
  
**GET:** fetch an existing resource

**POST:** create a new resource

**PUT:** update an existing resource

**DELETE:** delete an existing resource

**HEAD:** this is similar to GET, but without the message body

**TRACE:** used to retrieve the hops that a request takes to round trip from the server

**OPTIONS:** used to retrieve the server capabilities

#### Status Codes:

1xx: Informational Messages

2xx: Successful

3xx: Redirection

4xx: Client Error

5xx: Server Error

#### Request and Response Message Formats:

  ![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/task_linux_cli/http1-req-res-details.png)
  
#### Tools to View HTTP Traffic
* **Chrome/Webkit** inspector is a favorite amongst web developers
* Web debugging proxies: **Fiddler** on Windows and **Charles Proxy** for OSX

#### Authentication
HTTP does support a rudimentary form of authentication called **Basic Authentication**, as well as the more secure **Digest Authentication**

#### HTTPS
HTTP uses port 80 TCP
HTTPS uses port 443 TCP

Для того чтобы ваше веб-приложение работало по HTTPS, на вашей сервере должен иметься действительный цифровой сертификат. ЦС - небольшой файл, зашифрованное содержимое которого уникальным образом идентифицирует пользователя или сайт, показывая, что вы можете доверять определённой информации, и обеспечивая безопасную конфиденциальную связь в Интернете. Он связывает имя объекта, принимающего участие в секретной транзакции (адрес электронной почты или сайта), с открытым ключом. В шифровании с открытыми ключами существует проблема пересылки таких ключей через Интернет. В основе цифровых сертификатов лежит идея цифровой подписи.

При выполнении клиентом запроса по HTTPS он вначале пытается получить сертификат от сервера. В случае успеха клиент сверяет его с центрами сертификации, имеющимися в его списке. Если издатель сертификата не совпадает с каким-либо из них, то клиент может показать пользователю диалог с предупреждением насчет сертификата веб-сайта.

Как только подлинность сертификата установлена, SSL-рукопожатие завершено и начинается безопасная передача данных.

#### HTTP Caching
**Private:**
within a browser, caches usernames, passwords, URLs, browsing history and web content. They are generally small and specific to a user.

**Public:**
deployed as caching proxies between the server and client. These are much larger because they serve multiple users. A common practice is to keep multiple caching proxies between the client and the origin-server. This helps to serve frequently accessed content, while still allowing a trip to the server for infrequently needed content.

![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/task_linux_cli/http2-cache-topo.png)

#### Cache Control Headers:
Cash-Control, Expires

#### Impressions:
Some of the information was new for me or more detailed then I had. It was useful for me to learn about the peculiarities of the difference between HTTP and HTTPS, headers and caching. To be honest the material in the provided articles was difficult to read, so I often used Google to clarify some of the points. But the result pleases me - I have updated my knowledge. Thanks to everyone who read this and were happy for me 

## 2. Git Collaboration

### GitHub & Collaboration

### The following levels was completed at learngitbranching.js.org:

![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/task_git_collaboration/Main_learngitbranching.png)

![screenshot of sample](https://github.com/rpiasetska/kottans-frontend/blob/main/task_git_collaboration/Remote__learngitbranching.png)
