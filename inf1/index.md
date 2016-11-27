---
layout: page
title: Inf1
permalink: /inf1/
---


### Computation & Logic ([course page](https://www.inf.ed.ac.uk/teaching/courses/inf1/cl/), [piazza](https://piazza.com/class/iu3zmbur1uk392), [tutorials](https://portal.theon.inf.ed.ac.uk/reports/upt/open/TP072_Tutorial_Groups/inf1-cl.shtml))

*   **Hint**: Don't worry too much about refutation, it may or **may not** be on the exam
*   [Convert a truth table into a logical expression / logic circuit](http://www.32x8.com/)
*   [The venn diagram generator (based on the official version)](/venn)
*   [CNF cheat sheet](/cl-cnf-cheat-sheet.png)
*   [Propositional formula to CNF converter](http://logictools.org/)
*   [Visualizing satisfiability, validity & entailment](http://blog.ezyang.com/2012/10/visualizing-satisfiability-validity-and-entailment/)
*   **Finite State Machines**
    *   [FSM Workbench](http://homepages.inf.ed.ac.uk/s1020995/fsmworkbench/index.html)
    *   [Learn about regular expressions (has a great cheatsheet)](http://regexr.com/)
    *   [simulator](http://ivanzuzak.info/noam/webapps/fsm_simulator/), [regex/automaton converter](http://ivanzuzak.info/noam/webapps/fsm2regex/)


### Functional Programming ([course page](https://www.inf.ed.ac.uk/teaching/courses/inf1/fp/), [piazza](https://piazza.com/class/ititlgx4mhn31t), [tutorials](https://portal.theon.inf.ed.ac.uk/reports/upt/open/TP072_Tutorial_Groups/inf1-fp.shtml))

  *   **Tip by a tutor for the final exam**: the exam is open book, so taking in a copy of the previous year's exam paper and solutions may be beneficial
  *   [Past papers](https://www.inf.ed.ac.uk/teaching/courses/inf1/fp/exams/)
  *   Allocations: [mock](https://www.inf.ed.ac.uk/teaching/courses/inf1/fp/exams/mock-exam-allocation-2016.pdf), [final](https://www.inf.ed.ac.uk/teaching/courses/inf1/fp/exams/exam-allocation-2016.pdf)
  *   [Tree traversal algorithms (view in desktop mode!)](https://en.wikibooks.org/wiki/A-level_Computing_2009/AQA/Problem_Solving,_Programming,_Operating_Systems,_Databases_and_Networking/Programming_Concepts/Tree_traversal_algorithms_for_a_binary_tree)
  *   [Learn You A Haskell (official online book)](http://learnyouahaskell.com/chapters)
  *   [Handy basic function cheat sheet](/inf1-handy-functions.pdf)
  *   [Emacs: Haskell has died](emacs.html)
  *   `import Test.QuickCheck` doesn't work!  
      Open up the command line / Terminal, and type `cabal install quickcheck`
  *   "I'm doing `cabal install quickcheck`, but it doesn't work because of something related to satisfying packages... random-1-1...?"  
      Solution: Try `sudo ghc-pkg recache`. Then try `cabal install quickcheck` again.

### Introduction to Linear Algebra

*   **Tip from a (current) 3rd year**: the maths exams are also open book, so I'd recommend taking in past papers with solutions as they reuse questions a lot. They might not necessarily be the same, but they'll likely be close enough to give you a hand.
*   [Explanatory videos from Mathapptician](https://www.youtube.com/watch?v=S6yJY2NrVL0&list=PL9NlTZRdFADdc4yn_OVDpv-2pDiOKU7KH&index=3)
*   [Khan Academy videos](https://www.khanacademy.org/math/linear-algebra)
*   [Essence of Linear Algebra (videos)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
*   [Answers for Poole](http://slader.com/textbook/9781285463247-linear-algebra-a-modern-introduction-4th-edition/)
*   **The Exam** - 3 hours - Open Book  
    Section A: 40% - 6 questions - conceptual questions, a bit like Tophat  
    Section B: 60% - 4 questions (pick 3) - longer, conceptual questions  
    You may bring:
    *   the Poole textbook
    *   any notes (written / printed notes, _nothing bound_)


### Exam Dates ([search](http://www.scripts.sasg.ed.ac.uk/registry/examinations/index3.cfm))

<small>**More from a 3rd year**: It's only first year. **You only need 40% and it doesn't contribute to your final grade.** Chill, it's no big deal.</small>
<table>
    <tr>
        <th>Exam</th>
        <th>Location</th>
        <th>Date</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <td>ILA</td>
        <td>See 'View'</td>
        <td>Thur, 08th 09:30-12:30 (3hrs)</td>
        <td class="examTime" data-time="1481189400"></td>
        <td>
            <form target="__blank" method="post" name="form" action="http://www.scripts.sasg.ed.ac.uk/registry/examinations/index3.cfm">
                <input type="hidden" name="searchfrm" value="yes">
                <input type="submit" value="View">
                <input name="code" type="hidden" id="code" size="15" maxlength="11" value="MATH08057">
            </form>
        </td>
    </tr>
    <tr>
        <td>CL</td>
        <td>Pleasance Sports Hall</td>
        <td>Thur, 15th 14:30-16:30 (2hrs)</td>
        <td class="examTime" data-time="1481812200"></td>
        <td>
            <form target="__blank" method="post" name="form" action="http://www.scripts.sasg.ed.ac.uk/registry/examinations/index3.cfm">
                <input type="hidden" name="searchfrm" value="yes">
                <input type="submit" value="View">
                <input name="code" type="hidden" id="code" size="15" maxlength="11" value="INFR08012">
            </form>
        </td>
    </tr>
    <tr>
        <td>FP Group A</td>
        <td>FH Computer Lab</td>
        <td>Tues, 20th 09:30-11:30 (2hrs)</td>
        <td class="examTime" data-time="1482226200"></td>
        <td>
            <form target="__blank" method="post" name="form" action="http://www.scripts.sasg.ed.ac.uk/registry/examinations/index3.cfm">
                <input type="hidden" name="searchfrm" value="yes">
                <input type="submit" value="View">
                <input name="code" type="hidden" id="code" size="15" maxlength="11" value="INFR08013/1">
            </form>
        </td>
    </tr>
    <tr>
        <td>FP Group B</td>
        <td>FH Computer Lab</td>
        <td>Tues, 20th 14:30-16:30 (2hrs)</td>
        <td class="examTime" data-time="1482244200"></td>
        <td>
            <form target="__blank" method="post" name="form" action="http://www.scripts.sasg.ed.ac.uk/registry/examinations/index3.cfm">
                <input type="hidden" name="searchfrm" value="yes">
                <input type="submit" value="View">
                <input name="code" type="hidden" id="code" size="15" maxlength="11" value="INFR08013/2">
            </form>
        </td>
    </tr>
    <tr class="hoverRow">
        <td>Physics 1A</td>
        <td>Pleasance Sports Hall</td>
        <td>Fri, 16th 09:30-11:30 (2hrs)</td>
        <td class="examTime" data-time="1481880600"></td>
        <td>
            <form target="__blank" method="post" name="form" action="http://www.scripts.sasg.ed.ac.uk/registry/examinations/index3.cfm">
                <input type="hidden" name="searchfrm" value="yes">
                <input type="submit" value="View">
                <input name="code" type="hidden" id="code" size="15" maxlength="11" value="PHYS08016">
            </form>
        </td>
    </tr>
    <tr class="hoverRow">
        <td>Persian 1a</td>
        <td>Patersons Land - G1</td>
        <td>Mon, 19th 09:00-12:00 (3hrs)</td>
        <td class="examTime" data-time="1482138000"></td>
        <td>
            <form target="__blank" method="post" name="form" action="http://www.scripts.sasg.ed.ac.uk/registry/examinations/index3.cfm">
                <input type="hidden" name="searchfrm" value="yes">
                <input type="submit" value="View">
                <input name="code" type="hidden" id="code" size="15" maxlength="11" value="IMES08046">
            </form>
        </td>
    </tr>
    <tr class="hoverRow">
        <td>Intro to CogSci</td>
        <td>Outreach Centre</td>
        <td>Wed, 21st 09:30-11:30 (2hrs)</td>
        <td class="examTime" data-time="1482312600"></td>
        <td>
            <form target="__blank" method="post" name="form" action="http://www.scripts.sasg.ed.ac.uk/registry/examinations/index3.cfm">
                <input type="hidden" name="searchfrm" value="yes">
                <input type="submit" value="View">
                <input name="code" type="hidden" id="code" size="15" maxlength="11" value="PPLS08002">
            </form>
        </td>
    </tr>
</table>



### Other

*   [View the Quizlet class (see next item to join)](https://quizlet.com/class/3543715/)
*   [Join Quizlet directly here](/quizlet.html), username: `quizlet`, password: "name of where the drill hall is currently located, lowercase, no spaces"
*   [Common Outside Course Options for Informatics Students (2016/17)](http://homepages.inf.ed.ac.uk/imurray2/pt/outside_courses_16-17.html)
*   [Reset your DICE password](http://pp.inf.ed.ac.uk/)
*   [Access DICE files online](https://ifile.inf.ed.ac.uk/)
*   [CompSoc's website](http://comp-soc.com/)
