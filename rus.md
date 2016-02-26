# Оценка задачи фронтендера 

## Вступление

Давайте, черт побери, будем честны: оценка это худшая часть нашей работы.
Мы на такое не подписывались. В школе этому не учат. Но если вы у вас всё
вышло правильно то жизнь становится значительно легче. Нет ничего хуже
облажаться с оценкой и либо проебать дедлайн или превысить бюджет, работая 
допозна, что бы патчить и так далее. 

Let’s be damn honest here. Estimating is for most of us the worst part of our
job. We didn’t sign up for this. They didn’t teach us this in school. But if you
get it right it will make your life so much better. There’s nothing worse than 
screwing up an estimation and having to deal with either not making a deadline, 
going over budget, working late hours to patch it up and so on.
.

## Пример процесса

## Process examples {#process-examples}

Работая в области рекламы я был свиделетем наихудщих способов оценки проектов,
большинство из которых сводилось к следующему: *«— Эй, есть проектик. Дизайн готов,
надо сверстать и прикрутить функционал до 12 декабря, 12 стартует реклама
на ТВ. За сколько управишься?»*.

Having worked in advertisement I witnessed the worst ways to estimate projects
which went pretty much like this:*“Hey, I’ve got a project for you. The
design is finished and needs to be implemented and functional by December 12th 
because that’s when the TV ads go live. How much time do you need? Thanks!
”*

В примере выше процесс протекал следующим образом. Давайте назовем этот процесс
**дата-центрическим**:

In the example above the process went something like this. Let’s call this
process a**release date centered process:**

1. Кто то продает проект клиенту с заранее оговоренной датой релиза 
2. Кто то делает для него дизайн
3. Кто то реализует дизайн

1.  Someone sells the project to a client and defines a release date
2.  Someone designs it
3.  Someone implements the design

Вместо того что бы сфокусироваться прежде всего на пользователе, процесс 
фокусируется на том, что бы сделать что то к определенной дате. Иногда 
на кону масса времени и денег, что дает возможность итеративно улучшать продукт
Но в основном всё делается в спешке от начала и до конца, так как **дедлайн
определяется не разработчиками проекта**.

Instead of having the main focus on the user, this process focuses on the
client getting something done by a deadline. Sometimes there is a lot of time 
and money on the table which gives people involved some slack to actually 
iterate and do some improvements on the UX. But it’s mostly a rush from start to
finish because**the deadline isn’t set by the doers in the project.**

Процесс, сторонником которого я являюсь и который сейчас использую: 
**пользователе-центрический**. Так как я работаю в мультипрофильном консультационном 
дизайнерском агенстве, которое работает и над цифровыми, и над физическими продуктами,
пользователь всегда в центре внимания, от начала и до конца процесса. Я вовлечен в
работу над цифровыми продуктами и процессы выглядят приблизительно следующим образом:

The process I’m the biggest fan of and it’s the one I’m currently working
with these days. It’s a**user centered process.** Since I work in a
multidisciplinary design consultancy which does digital, physical products and 
services, the user is always in focus from start to finish. I’m involved in the 
digital projects and the process looks something like this:

1. Разработчик сервиса продает проект клиенту организовывая воркшоп, где
   они с клиентом вместе определяют «узкие места» продукта
2. Анализ, на протяжении которого мы должны определить потребности пользователей 
   и точки соприкосновения с ними
3. Дизайн, на протяжении которой мы должны привести продукт в соответствие 
   с потребностями пользователей, определенными в процессе анализа
4. Прототипирование с помощью кода или какого то инструмента, например 
   Proto.io][1] или [Framer.js][2]
5. Внедрение дизайна


1.  A service designer sells the project to a client by having a workshop where
    they together define the bottleneck of their current product
2.  Insight phase where we define user needs and touch points
3.  Design phase with a goal to meet user needs discovered in insight phase
4.  Prototype design with some mock code or a prototyping tool such as 
    [Proto.io][1] or [Framer.js][2] 
5.  Implementation phase


## Оценки в пользователе-центрических процессах

## Estimating in a user centered process 

Скажем, проект находится в состоянии когда мы знаем, что мы будем разрабатывать
цифровой сервис, например, сайт или веб-приложение. Но, что бы продолжить
клиент хочет получить оценку того, сколько это будет стоить. Естественно. 
Что делать дальше? Давайте я расскажу как мы обычно поступаем с 90% вероятностью
успеха.

Let’s say the project is at a point where we know there’s going to
developed a digital service like a website or a web app. But to go further the 
client wants an estimate on how much it is going to cost them. Naturally. Where 
do you take it from here? Let me tell you how we usually do it with a 90% 
success rate.


## Пользовательские сценарии

### User stories {#user-stories}

Возможно вы слышали про [пользовательские сценарии][3], а может и нет. Это ключевой
момент для успешной оценки и профессионально сделанному предложению клиенту. Это должно 
быть ключевой частью любого процесса разработки, и если вы разработчик, то скорее всего
уже используете их в рамках [скрама][4]. Всмысле, это первое, о чем вы говорите на самом
первом митинге с клиентом. Они помогают клиенту действительно понятно рассказать что он хочет.
Если клиент не знает — вам следует помочь ему и вы выясните это вместе. Это можно сделать
в формате воркшопа, как я уже упоминал ранее. Если у вас есть ресурсы следует также 
пообщаться с потенциальными пользователями, прислушаться к их потребностям и включить их в 
пользовательские сценарии.

Maybe you’ve heard of [user stories][3] and maybe you haven’t. It’s the
essential key to making a successfull estimate and a professional offer to the 
client. It should be a central part of any design process, and if you’re a 
developer you’ve probably been using them already in a[Scrum][4] project. I
want to say it should be the first thing you talk about in the first meeting 
with the client. It will help the client tell you what they want in a really 
clear way. If they don’t know then you should help them out and you will figure 
it out together. You could do this in a workshop format like I mentioned earlier.
If you have the resources you should also talk to potential users and listen to 
their needs and plot them in a user story format.

Вот шаблон пользовательского сценария: *«Как пользователь я хотел бы … что бы 
я смог …»*.

Here is a user story template: *“As a user I would like to ……… so that
I can
……… “.*

Когда у вас есть набор пользовательских сценариев следует сделать следующее:

When you have a set of user stories ready you will be able to do this:

* Обозначить их как критичные и не критичные. Если бюджет ограничен то будет
  ясно на чем следует сосредоточится. 
* Можете теперь начинать создавать дизайн, который бы соответствовал сценариям.
  Каждый из них будет отдельной задачей.
* В процессе импелментации дизайна сценарии можно использовать для постановки
  задач. 


*   Rate them from crucial to nice-to-have. If there is a limited budget you
    now know what you should focus on.
   
*   You can now design to meet the user stories. Every design decision should
    be taken based to meet a a user story. Each user story will be a design task.
   
*   In the technical implementation phase we can use the user stories in a lean
    project where each user story is a topic with a set of sub tasks to meet the 
    needs of the user story.

Как видно из этого списка, если использовать сценарии в качестве краеугольного
камня проекта мы получим продукт полностью сконцентрированный на удовлетворении
потребностей пользователей.    

As you can see from the list above, by having user stories as the core purpose
of the project we should eventually sit with a product which is completely 
centered around meeting needs of the users.


## Оценка задач фронтендера на базе сценариев использования

### Estimating a frontend web job based on user stories

Как упоминалось ранее, вы будете использовать сценарии при постановке задач в 
проекте. Если вы были вовлечены в проект непосредственно перед фазой внедрения
дизайна и должны оценить его, то это исключительно просто, если работа построена
вокруг сценариев использования. Если нет — то предстоит серьезная работа. Придется
создать искуственные сценарии на базе разработанных мокапов. Это наихудший случай,
но вам все равно следует их сделать, так как это, вероятно, поможет обнаружить
прощеты в UX.

As mentioned above, you will use user stories as a topic when creating tasks in
the project. If you as a developer get involved in the project right before the 
implementation phase and you’re assigned to estimate it, the job is extremely 
simple if the designers have centered their work around user stories. If not, 
you have a big job to do. You’ll have to create fake user stories based on 
already designed mockups. This is worst case, but you should do it anyways cause
you’ll probably help the designers find some holes in their UX.

И так … скажем все сценарии готовы и можно начинать оценку. Предположим, сервис, 
который вы разрабатываете это веб-приложение для управления ресурсами команды. 
Есть список сценариев вида: *«Как пользователь я хочу иметь возможность запросто 
увидеть есть ли у работников свободный временной слот на протяжении определенного
периода времени, что бы я мог назначить его в проект»*.

So.. let’s say you have all of your user stories ready and you’re ready to
estimate. Let’s also say that the service you’re creating is a web app for 
managing resources in a team. You have a list of stories like:*“As a user I
want to easily see if an employee has an empty time slot during a certain period
of time so that I can allocate him/her to a project
”*

С конкретным сценарием, приведенным выше, можно создать множество задач и подзадач.
Например: 

With the particular user story above, you could possibly end up with a lot of
tasks each with their own sub tasks. Example:

* Создать календарь, который показывает занятость работника
    * Создать компоненту календаря (14 часов)
    * Реализовать API календаря (2 часа)
    * Задача 3 (4 часа)
    * Задача 4 (2 часа)
    * Задача 5 (10 часов)

*   Create a calendar which displays an employee’s allocation 
    *   Create a calendar component (14h)
    *   Implement a calendar API (2h)
    *   Task 3 (4h)
    *   Task 4 (2h)
    *   Task 5 (10h)

После того, как вы перечислили всё, что нужно для того, что бы удовлетворить 
потребности пользователей, описанные в сценарии, у вас на руках оказывается 
количество часов, которое можно использовать в процессе оценки. Этот конкретный
сценарий требует на реализацию 32 часа. Теперь у вас есть не только количество 
часов, которые можно назвать клиенту, но и причина по которой эту работу можно
вам доверить. Для клиента это будет похоже на поход к зеленщику. Что бы сделать 
яблочный пирог нужно определенное количество ингридиентов — некоторые из них важнее, 
чем другие. Но они все перед вами, что бы вы могли выбрать и приготовить вкусный пирог. 

After you have listed up everything that is needed to fullfill the user needs
in the user story, you end up with a set of hours you can use in your estimate. 
This particular user story will take 32 hours. Now you not only have a number of
hours to tell the client, you also have a reason you’re worth these hours. It 
will be like going to the grocery store for the client. To be able to make an 
apple pie you’ll need some ingredients – some more important than others. But 
they are all there for a purpose, which is to make one delicious pie.

Ваша оценка и коммерческое предложение должны включать следующее: 

Your estimation and offer document to the client should now consist of these
things:

* Резюме того, что должно быть сделано (что бы убедиться, что между клиентом
  и вами нет недопонимания)
* Резюме концепции (что бы клиент видел что вы её поняли)
* Список пользовательских сценариев, созданных на базе резюме
* Список задач, созданный на базе сценариев
* Оценка, которая включает
    * Задачу
    * Результат
    * Количество часов
    * Стоимость (стоимость часа вашего времени умноженная на необходимое количество часов)
* Резюме

*   A summary of your understanding of the brief (to make sure you’re seeing
    eye to eye on what needs to be done
    )
*   A summary of the concept (to make sure you let your client know you have
    understood the concept
    )
*   A list of user stories based on the understanding of the brief
*   A list of tasks based on the user stories
*   The actual estimate including: 
    *   The task
    *   Delivery
    *   Hours needed
    *   Cost (hourly rate * hours needed)
*   Summary

Эй! К процессу создания последнего комерческого предложение и оценки, которые я делал вчера, 
я привлек клиента, выслав ему ссылку на Google Document, в котором мы вместе закончили список 
сценариев и задач. Это действительно важно, так как теперь я не просто сделал оценку и выслал 
ему красиво оформленный PDF с которым они могли согласится или нет. Это привело к возникновению
дискуссии и пониманию. И теперь клиент уже сам принимал участие в формировании стоимости проекта
а не получал с моей стороны количество необходимых мне часов


PS! The last offer and estimation job I did, which was yesterday, I involved
the client by sending them a link to a Google Document where we finished the 
user story list and the task list together. This really made a huge difference 
as it shifts the game from where I usually would do the estimation job myself 
and send the client a nice PDF where they either would say yes or no. It created
a discussion and understanding. And now they were involved in creating the costs
for themselves rather than me claiming I needed the hours.

 [1]: https://proto.io/
 [2]: http://framerjs.com/
 [3]: https://en.wikipedia.org/wiki/User_story
 [4]: https://en.wikipedia.org/wiki/Scrum_(software_development)