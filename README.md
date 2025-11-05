# Internship Cafe Menu

Software Engineering as a profession is an umbrella term. So many skills and tools that one uses in a SWE role will be useless in another role; for this exact reason, this document will separate the information for applying by the distinct skills and demands in the application process --a separation that is often found to be done by industry. Of course, many skills you have as a SWE are extremely transferable across roles, but the value you get in tailoring by industry is immense in a job market that is notorious for high volumes of applications, and very competitive applicants.
A quick note to make is that applications for placements, internships, insight weeks, and graduate roles tend to be very similar within the respective industries. This is because companies don't want to have to invent entire new hiring processes for students who are separated by one or two years of university experience. This means the key dividing factor between applications is the indsutry and role you apply to.
While this document will not cover visual resume formatting, it will focus on the content, projects, and skills you need to highlight for each category.

## Generalist
A generalist role will be extremely common at any Big Tech company (think MAANG). While this may seem like a cop out, the truth is many roles have a very common slot they fit in which is one of full-stack/back-end development. This is what most people think of when they think of a Software Engineer. We will later observe how a seemingly unrelated role, Data Engineering, is also a perfect fit to the Generalist definition.

### Definition & Skills
Generalist roles will range from anything like full-stack development on a web application, tooling developer (i.e. making internal tools), to back-end development. These roles will almost always require some combination of Java, C#, Python, Go, JS, and SQL where language flexibility is an expectation. Generalist roles are not considered Specialist roles because you will be expected to work with larger architectures (meaning you would benefit from knowledge of Systems Design) where one components constantly interact.
Take the below example of some appliation's back-end architecture:
![Back-end architecture for Spotify microservices](./images/system_microservices.jpg)
A senior developer would not be able to tell you whose architecture this is. Why? -- because the components are very similar to what you might expect out of any other company's application. Every company will have databses; every company will have caches; every company will have authorisation; every company will use APIs; most companies will have their own API design; I could go on forever. This is what defines the Generalist SWE role.

### How to identify a generalist role
Most generalist roles will advertise themselves with common titles like "Software Engineer," "Software Developer," "Backend Engineer," or "Full-Stack Developer."
The key identifier in the job description is a focus on fundamental languages (like Java, Python, C++, or Go) and core CS concepts (algorithms, data structures, APIs, databases) rather than demanding expertise in one specific, niche framework.
The characteristics we can identify as being common across all generalist roles would be: language knowledge for all or some of the languages they use in their stack; some systems desing knowledge or experince --through projects, internships, whatever; knowledge of standard data structures and algorithms --as well as how they can be applied in certain contexts. While it is unlikely you will receive a systems design interview for anything below a graduate role, it's still very useful to demonstrate you have a project that utilises some degree of systems design practices.

#### A Special Case: Why is Data Engineering a Generalist Role?
You might see a role like "Data Engineering" and think it's a specialist role (like Data Science). However, if we look at the characteristics demanded of a Data Engineering role, we'll see it fits the Generalist pattern perfectly:
- Ability to work with large datasets (typically demands Python skill, and will certainly involve using plenty of data structures)
- Ability to work with large databses (typically requires knowledge with SQL or a NoSQL equivalent, where your ability to create good schemas is important)
- Ability to design and work on large data pipelines (typically involves systems design)
For internships, you are never going to be required to know everything. But, it would be a huge boost to your application if you are able to talk about how you constructed a mini-version of an ETL pipeline. This is directly applicable to the role, even if it's not a specific tool they use.
Crucially, the application process is the same as a Generalist: the Online Assessment will be standard LeetCode + SQL, and the interviews will test algorithms, just like a SWE. This is why you should prepare for it like any other Generalist role (plus SQL).

### The Application & Technical Interview Process
Generalist roles will typically ask a coding assessment of you where you can expect very Leetcode style questions. Ultimately, this is to assess your problem-solving abilities in an algorithms context. This means you want to place emphasis on your problem-solving abilities throughout your CV --you can even be as direct as to use 'Problem-solved' as one of your action verbs for a bullet point (where suitable). Interviews may very follow the whiteboard interview style where you are, again, going to be asked Leetcode style questions. Here, they expect to see your communication and teamwork abilities. You are meant to communicate to your interviewer as though they were a peer who you were coding with or helping.
Lets break down what key points will be important to communicate:
- **Thought process:** The toughest aspect on this list, but also the most self-explanatory; talk _slowly_ and don't be scared of long pauses to let you think
- **Progression:** Once you've read and understood the problem, start with the algorithm that genuinely comes to your mind first (this should be the brute force approach). If you can demonstrate a progression in your thought process –from least to most efficient algorithm– the interviewer will give you more brownie points that if you were to immediately solve using the most efficicent algorithm straight away
- **Trade-offs:** Very often, there will be a situation where one approach has a faster time complexity, but greater memory complexity –and vice versa. In such a situation it is crucial that you explain this trade-off as it demonstrated you have technical nuance in your understanding of the problem
    - It is also very possible for trade-offs to appear in different forms that aren't specifically regarding time and space complexity
- **Diagrams:** If you can, draw diagrams. If you are in a video call and can't draw a diagram on you coding environment, draw it in a notebook and show it over the camera. This will help you both solve the problem and give you points with the interviewer
- **Testing & Edge Cases:** You should try and consider any edge cases when you are at a point in your solution where you can assess them: for example, if you have just explained the intermediate solution (not brute force, not most efficient) then consider briefly explaining what edge cases may arise. Do the same for your final solution that you end up implementing. If you still have time after solving a problem, start running test inputs that make sure to cover the following attributes:
    - Basic functionality: Test a simple input that doesn't include edge cases which you can easily determine the solution for by hand. When you do this, make sure to first run through your code with the input by yourself, then run it with the input (if running code is an option)
    - Edge cases: Generate inputs that allow you to test edge cases one at a time. No one input should have to deal with multiple edge cases at once. Make these simple for your sanity

Having structure in your whiteboard interview will help take away some of the mental load that comes with explaining while solving at the same time. With that said, you should still follow all these steps even if the problem you are given is extremely simple.
This goes without saying, but you should practice these questions on Leetcode **often**.

### How to Prepare
Create various projects that help demonstrate your language flexibility. The best type of projects to do this are full-stack projects as they will normally force the use of multiple tools and languages. If you can also demonstrate framework flexibility, this is pretty good, but as a student you will probably get more value from picking a framework adn getting really good at it.
Working on projects alongside doing your degree and other commitments can be tough. The best way to get these full-stack projects on your resume is by attending many hackathons. Hackathons also prove to be goldmines for behavioural questions during interviews as you will be working in a team to ideate, design, develop, debug, and coordinate in the short span of 24 hours. This allows you to talk about your collaborative skills, your problem resolution skills, and –of course– the technical skills you applied/learnt.

---

## Quantative Finance


## Data Science & Machine Learning


## Cybersecurity


## Game Development


## Frontend & Mobile Developer


## Cloud, DevOps & SRE


## Tech Consulting
