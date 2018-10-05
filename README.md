# CS5278-proj

Vanderbilt Office Directory

As a student, I want there to be an easier way for me to reach out to university offices. Vanderbilt is a very large and complex organization and it can be difficult to find out what offices to contact if a student has a question. In addition, it is oftentimes necessary for students to make appointments with university employees and it is difficult to do so when they don’t know how to reach out to a certain office.
	The app I am building is an app that allows users to find out what university office they need to contact if they have a question and from there schedule appointments or visit their website. They would text a question to the text messaging interface and from there the app would refer them to the correct resource’s website and also provide an interface for scheduling an appointment.
	This app would be useful because it would directly improve the experience of Vanderbilt students, especially newer ones, in getting to know and understand student resources better. Also, for students that value their confidentiality, this provides a more private way to communicate with Vanderbilt organizations without having to involve other people.

# Questions

<ol>
<li>How do you make your appointments with offices at Vanderbilt?</li>
<li>Are you more likely to make an appointment by phone or a website?</li>
<li>How long do you typically take to schedule an appointment?</li>
<li>How comfortable do you feel walking into an office to make an appointment?</li>
<li>Do you enjoy interacting with others while scheduling appointments?</li>
<li>Would it be more convenient to schedule appointments through one central interface?</li>
<li>Have you ever been confused about what university offices to contact to make an appointment?</li>
<li>How difficult do you think it is to contact a university office to make an appointment?</li>
<li>Do you know what university offices to contact when you have a question?</li>
<li>Do you feel you know how to make an appointment with a university office?</li>
</ol?

Question 1:
<ol>
<li>I usually look online to see if there is an online scheduling tool, but there usually isn’t so I’ll call the office to make an appointment.</li>
<li>Usually I look online to see if they have an online schedule type thing.</li>
<li>Usually via email but I tend to not go because I never know exactly who to contact</li>
</ol>

Question 2:
<ol>
<li>I am more likely to make an appointment by phone.</li>
<li>I am more likely to make an appointment by a website.</li>
<li>Phone calls because that’s much faster</li>
</ol>

Question 3:
<ol>
<li>It usually takes me about 5 minutes to look up the phone number and wait for my call to be answered, since I usually get put on hold for a few minutes.</li>
<li>It usually takes me 5 minutes to schedule an appointment online, but a lot of times they will follow up on the phone and that will take an extra minute.</li>
<li>If it takes more than 10 minutes, I’ll probably quit.</li>
</ol>

Question 4:
<ol>
<li>I feel somewhat comfortable but would prefer to make an appointment remotely because it’s more convenient.</li>
<li>It depends on what it is for. I am pretty comfortable walking in and making an appointment, but I would rather make an appointment on my computer.</li>
<li>Very comfortable because it is generally the easiest way.</li>
</ol>

Question 5:
<ol>
<li>No not really.</li>
<li>It is fine. I don’t necessarily “enjoy” it, but sometimes it is easier.</li>
<li>Yes if they work quickly and don’t try to make smalltalk</li>
</ol>

Question 6:
<ol>
<li>Yes, it’s confusing to find all of the different phone numbers.</li>
<li>It would definitely be easier.</li>
<li>For sure</li>
</ol>

Question 7:
<ol>
<li>Yes, it’s hard to keep track since there’s so many different resources.</li>
<li>I haven’t ever been confused about the resources.</li>
<li>Definitely.</li>
</ol>

Question 8:
<ol>
<li>Sometimes it’s difficult to get through if the office doesn’t answer or you get put on hold.</li>
<li>I think that it is more difficult than it should be (especially because the resources are always advertised as being accessible).</li>
<li>After you figure out who to contact, it’s not that hard, but they often take a long time to respond, which is annoying.</li>
</ol>
	
Question 9:
<ol>
<li>Sometimes, but I usually have to look it up.</li>
<li>Yes I do.</li>
<li>Nope. Sometimes googling will find me the answer but other times I’m clueless.</li>
</ol>

Question 10:
<ol>
<li>I usually just look it up, but I don’t necessarily know on my own.</li>
<li>There are a few problems with online scheduling for some university resources, which makes it difficult. Generally, I do feel like I know how to make an appointment with the resource.</li>
<li>Email, right?</li>
</ol>

# Requirements

An text messaging application that users can text to ask for information on university offices. The user should be able to text the app asking for a certain university office. The app then responds with the correct information about the office, namely a website and information that can be used to make an appointment, whether through a website or a phone number. 

# Development Approach 

To develop this application, first, I will read through the user responses and think about what they want in an application. Then I will think about how best I could serve their needs and create a project I want, by telling them about my app idea and asking for their feedback on it. 

Throughout this process I will keep working on a design for the project and trying to anticipate ways in which it could fail and items that would be difficult to maintain. Everytime I alter the design I would think about how this would affect the product as a whole, and if the changes are significant I would ask a potential user how this would affect them in order to maintain empathy with the user. During this step also, I would estimate how long it would take for the individual components of the app to be built. I would make my estimates based on my experience in Clojure and building our previous app in this course.

Before actual implementation of the app, I will write a series of unit tests in order to ensure that the requirements are consistent. This will also make the code more maintainable because if the test are already in place and not modified, future developers can work on the code and keeping consistent requirements.

In actual implementation of the app, I would mostly rely on the architecture similar to the project architecture we already set up in the first few assignments in order to keep the app as simple to implement as possible. In addition, this would allow for the code to be easier to debug since it would be easier to manage side effects since the existing assignment already accounted for that. 

To verify that the product works, first I will unit test the components and then the entire product. I will also give the product to several users in order to make sure that the users are satisfied with the final product before making adjustments to the interface if necessary.

My process will mitigate the risk of failure by ensuring that users are involved in many steps of the process in order to deliver on a product that users would want. By asking users to test out the product, I can ensure that the product is easy for users to operate and that it is something that they want.
