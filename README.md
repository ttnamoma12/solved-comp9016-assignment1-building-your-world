Download Link: https://assignmentchef.com/product/solved-comp9016-assignment1-building-your-world
<br>
The purpose of this assignment is to assess the following <strong>LearningOutcomes</strong>:

<ul>

 <li>LO1 Appraise domain specific formalisms used in knowledge representation schemes.</li>

 <li>LO2 Compare and contrast current knowledge representation approaches integrated in systems relevant to AI.</li>

 <li>LO3 Select, apply and evaluate a knowledge representation scheme for a specified domain.</li>

</ul>

To that end, you are going to build upon the theory discussed in lectures and the practical work carried out as part of your lab work. You will construct a 2-dimensional (2D) task environment along with a number of agent types that demonstrate your understanding of knowledge representation in a domain specific manner. You will investigate the utility of search techniques and articulate a rationale for where, when and why a search approach is appropriate. Finally you will investigate and critique two approaches for inferring state in your environment discussing and demonstrating the pro’s and con’s of each.

<h3>1.1 BUILDING YOUR WORLD</h3>

Create a 2D world that will play host to a game to be played by your agent types. Provide context for the mechanics of the world and the conditions under which the game is complete. Theintentofthisexerciseisforyoutodemonstrateyourunderstandingofhowaproblemcan be modeled abstractly. To this end, provide a well a defined task environment, implement three <strong>different </strong>agent types and provide a PEAS description for each.

<ul>

 <li>Critique the advantages and disadvantages of each agent type.</li>

 <li>Demonstrate each agents ability to perform or under-perform in the 2-dimensional world.</li>

 <li>Discuss, and evaluate, the agents suitability to operate in world of varying sizes.</li>

</ul>

The solution should be implemented in Python, you may use any of the libraries made available from the AIMA python repository but they must be clearly referenced (see note on importing code under submission), you will be graded on your contribution and this should be clearly highlighted.

Write a clear and concise description of the agent-based world. The purpose of this is to articulate an understanding of the underlying concepts being implemented both from a theoretical and practical perspective.

<h3>1.2 SEARCHING YOUR WORLD</h3>

<ul>

 <li>Formulate a well defined <strong>problem statement </strong>and identify a <strong>goal-state </strong>under which your game is complete. Why is this important to search? As part of your solution you should be including the initial state, the set of actions, the transition model, a goal test function and a path cost function.</li>

 <li>Select three <strong>uninformed search </strong>techniques and discuss their appropriateness to your world under appropriate headings for evaluating problem-solving performance. Implement the <strong>uninformedsearch </strong>techniques and discuss the results.</li>

 <li>Select three <strong>informed search </strong>techniques and discuss their appropriateness to your world under appropriate headings for evaluating problem-solving performance. Implement the <strong>informedsearch </strong>techniques and discuss the results.</li>

</ul>

Write a clear and concise report detailing the search techniques performance in your agentbased game for the relevant agent types. The purpose of this is to articulate an understanding of the underlying concepts, and limitations, being implemented both from a theoretical and practical perspective.

<h3>1.3 FORWARD-CHAINING AND BACKWARD-CHAINING</h3>

Forward-Chaining and Backward-Chaining introduces the capacity for inference in an environment. How does this benefit the operation of an agent, in particularly in your world? Provide a short critical analysis of both approaches. Thereafter demonstrate their applicability by utilising them in your world.

<h2>2 TIPS</h2>

<ul>

 <li><strong>Tip for Part 1</strong>: Review “agents.ipynb” and Chapter 2 of the recommended text. <strong>Do not </strong>overthinkthis, startfastandfailfaster, defineyourtaskenvironment, outlineyourPEAS for the three agent tpyes. You can start with basic environments first and iteratively increase the complexity of the mechanics of the world – just be sure to do so.</li>

 <li><strong>TipforPart2</strong>: Review “search.ipynb” and Chapter 3 and 4 of the recommended text.</li>

 <li><strong>Tip for Part 3</strong>: Forward and backward-chaining are instances of <em>AND-OR </em>search trees, read up on them on <a href="https://en.wikipedia.org/wiki/And%E2%80%93or_tree">wikipedia</a><a href="https://en.wikipedia.org/wiki/And%E2%80%93or_tree">,</a> review Chapters 4, 7 and 8 from the recommended text particularly (Section 4.3.2). Review “AND-OR Graph Search” in “search.ipynb” and backward/forward chaining in “logic.ipynb”.</li>

 <li><strong>TipforallParts</strong>: Do not provide masses of text lifted from the text/online or wikipedia. Be your own editor, focus on what is important and articulate that in a rationale way that is technically accurate. Demonstrating a capacity to explain complex topics in a clear and concise manner is indicative of a higher level of understanding and will be rewarded with an appropriate grade. Use results derived from experimental runs to back your claims and make sure your narrative is coherent and consistent.</li>

</ul>

<h2>3 SUBMISSION</h2>

You submission will contain:

<ul>

 <li>A 1500 word report <em>≤ </em>7 pages in “.pdf” format.</li>

 <li>A <strong>single </strong>“.py’ file</li>

</ul>

Prepare your submission by archiving it as a single “.zip” file using the following naming convention.

“A1_COMP9016_&lt;Surname&gt;_&lt;First name&gt;_&lt;Student Number&gt;.zip” e.g.

“A1_COMP9016_OReilly_Ruairi_R123456.zip”

<h3>3.1 WORD COUNT – 1500 WORD MAX</h3>

There are three distinct questions as part of this assignment Q1.1-Q1.3. In answering these it is important that you demonstrate an understanding of the underlying theory as applied in the context of your environment. There is a suggested word limit of 500 words per question, your ability to articulate your answer succinctly is indicative of a deeper understanding in itself. I <strong>highly recommend </strong>the use of well formatted tables for any experimental results and/or diagrams/visualisations if they aid the message you are trying to convey. Boilerplate text articulating “what an agent is” and “what a search algorithm is” should be kept succinct and to the point.

Prepare your solution by the due date as a single “.pdf” file using the following naming convention.

“A1_COMP9016_&lt;Surname&gt;_&lt;First name&gt;_&lt;Student Number&gt;.pdf”

e.g.

“A1_COMP9016_OReilly_Ruairi_R123456.pdf”

<h3>3.2 CODE SUBMISSION</h3>

A <strong>single </strong>“.py’ file should be prepared containing all code for questions 1.1-1.3. Encapsulate these in three individual functions called from the end of your submitted “.py” file. <strong>NB</strong>: Your code will be run from a “subdir” of the AIMA libraries (I have already provided a solution for importing these libraries from a parent directory – <a href="https://cit.instructure.com/courses/38151/files/707548?module_item_id=232253">see link</a> – I expect you to follow these guidelines).

Prepare your solution by the due date as a single “.py” file using the following naming convention.

“A1_COMP9016_&lt;Surname&gt;_&lt;First name&gt;_&lt;Student Number&gt;.py” e.g.

“A1_COMP9016_OReilly_Ruairi_R123456.py”