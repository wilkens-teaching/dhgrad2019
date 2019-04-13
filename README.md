# Computational Literary History

## Contact

[Matthew Wilkens](https://english.nd.edu/people/faculty/wilkens/), University of Notre Dame\
ENGL 90128, Spring 2019\
T 3:30-6:15, [246 Hesburgh Library](https://cds.library.nd.edu/spaces/)\
Office hours: Th 9:00-5:00 ([reserve slots](https://bit.ly/wilkens_appointments)), 320 Decio Hall. 
>**Note:** I'm generally in my office all day on Thursdays, but I do sometimes have a conflict or need to step out. Reservations are strongly recommended.

## Summary
A graduate-level introduction to problems and methods in computationally assisted literary studies, with an emphasis on large-scale historical issues. Includes substantial instruction in programming techniques.

## Description

Contemporary criticism has a problem. We long ago gave up the idea that our task was to appreciate and explain a handful of great texts, replacing that goal with a much more important and ambitious one: to understand cultural production -- both today and in centuries past -- as a whole by way of the aesthetic objects it creates. But we have continued to practice our craft as if the methods developed in pursuit of the old project were the only ones suited to the new task. In consequence, we have remained less successful and less persuasive concerning the operations of large-scale cultural production than we would like to be.

This course is devoted to new methods and new objects in cultural and literary studies, specifically those enabled by digital media. It is not, however, a course in media studies. We'll spend most of our time covering both what kinds of criticism are made possible by the availability of digital cultural objects (especially digitized texts), whether those objects are born digital or are post facto electronic surrogates, and how to perform the technical operations necessary to carry out such criticism. The course thus has a substantial technical component, one no more difficult than -- but often quite different from -- most of your existing experience in literary studies. That said, the idea is certainly not to replace the methods you've previously mastered, but to supplement them with new approaches, issues, and questions that will allow you to do better the kinds of cultural and literary criticism you've already begun to practice.

We'll begin with some reflections on the origins of computational literary studies and the rationale for pursuing quantitative work in cultural domains. We'll move quickly to engagements with representative work in the field and to learning how to perform computational analysis. Much of what we read will fall under the broad heading of data mining; we'll study what that term means and how to do it. We'll aim for a mix of theoretical elaborations concerning what is and is not implied by quantitative methods and how those methods integrate with conventional humanities approaches to interpretation, and (the second part of the mix) specific examples of achieved work in the field, plus technical exercises that will help you carry out similar work on your own.

We'll read as widely as possible in both the major works of computational literary studies and in the often-divisive debates about the value of that work. Much of the schedule is set out below, but be aware that this is a rapidly evolving field; we'll adjust our readings in response to new developments that emerge over the course of the semester and to our collective interests or hangups.

Four notes:

1. I'll repeat that this is a course with significant technical components. There's no assumption that you'll enter with any particular computational or mathematical expertise and there will be plenty of help (along with prebuilt tools) available along the way, but you *must* be willing to work outside your presumptive comfort zone as literary critics to develop the skills necessary to conduct the kinds of research we'll explore. This is really exciting stuff and it's not tremendously difficult, but if you shut down early in the face of the command line or a list of numbers, it'll be impossible to do well.

2. Our week-to-week assignments and work will be somewhat different from what you're probably accustomed to. Most notably, there will be -- in addition to the usual books and articles to read -- graded problem sets or other exercises to complete. We'll talk more about the form these will take as the semester progresses.

3. Your final project will also take an unconventional form. You will prepare the narrative portion of a grant application describing a piece of substantial computationally assisted criticism that you would undertake had you world enough, and time. Alternatively, you may work with one or two other students to produce an achieved piece of such scholarship. Details to follow in due course.

4. When we perform our own analyses, we'll work primarily with a set of prepared corpora. This limits in some ways the range of problems we might address, but it helps with the well-known issue that 90% of real-world data-related effort is cleaning up your sources. That said, we can explore other corpora as our needs, desires, and technical abilities dictate.

## Texts

* Guttag, John V. [_Introduction to Computation and Programming Using Python_](https://mitpress.mit.edu/books/introduction-computation-and-programming-using-python-second-edition). 2nd. ed. MIT, 2016.
* Moretti, Franco. [_Graphs, Maps, Trees_](https://www.versobooks.com/books/261-graphs-maps-trees). Verso, 2007.
* Piper, Andrew. [_Enumerations_](https://www.press.uchicago.edu/ucp/books/book/chicago/E/bo28465405.html). Chicago, 2018.

Articles and supplements from the scholarly literature will be assigned and available, either via links below or on Sakai.

## Work and grading

You will be evaluated on the basis of your final project (50%), assigned problem sets (20% in sum), and rigorous, consistent, engaged participation (30%). _You must satisfactorily complete all assignments to pass the course._


## Policy statements

### Attendance

One absence, no questions asked. Additional absences will lower your grade.

### Late work

Late work is generally not accepted. If you find yourself in exceptional circumstances, talk to me well in advance of the deadline and we may be able to find an accommodation.

### Collaboration and plagiarism

Talking to other students -- especially those in the course -- about your ideas is a good thing. Taking other people's words, code, or ideas without attribution is plagiarism and will result in honor-code-related unpleasantness. When in doubt, cite. And feel free to ask me about specific cases or problems and about the mechanics of research documentation. For references and guidelines, see the library's [plagiarism](https://libguides.library.nd.edu/friendly.php?s=scholarly-publishing/plagiarism) and [documentation](https://libguides.library.nd.edu/scholarly-publishing/writing-citing) sites and the university's [academic code of honor](https://honorcode.nd.edu/).

### Disabilities

Students with documented disabilities who need accommodations or have questions should speak with me directly and contact [Sara Bea Disability Services](https://sarabeadisabilityservices.nd.edu/).

## Schedule

Detailed assignments will be provided separately.

**Note: All dates and assignments are subject to change.**

**Week 1 (1/15)** 

* Introduction, background, mechanics.

**Week 2 (1/22)** 

* Read
  * Moretti, Franco. _Graphs, Maps, Trees_.
  * Carver, Cecily. ["Things I Wish Someone Had Told Me When I Was Learning How to Code"](http://bit.ly/1a3jLiC).
* Technical
  * Guttag, chapters 1-3.
  * Install [Anaconda Python](https://www.anaconda.com/download/) and make sure you can create and execute Python code in a Jupyter notebook. 
    * Understand how the Jupyter interface relates to your file system.
  * Create an account on [GitHub](https://github.com/).

**Week 3 (1/29)** 

* Read
  * Piper, Andrew. _Enumerations_.
* Technical
  * Guttag, chapters 4-5.
  * ["Finger exercises" from Guttag, chapters 2-3](https://github.com/wilkens-teaching/dhgrad2019/tree/master/exercises/ps1). Note that the finger exercise on p. 27, which asks you to find the roots of an arbitrary integer by exhaustive enumeration, is poorly constructed in a way that produces a trivial answer (because `x**1 = x`). To avoid this issue, search for roots between 2 and 5 (that is, `1 < pwr < 6`).
 
**Week 4 (2/5): Basics** 

* Read
  * Allison, Sarah, Ryan Heuser, Matthew Jockers, Franco Moretti, and Michael Witmore. ["Quanitative Formalism"](https://litlab.stanford.edu/LiteraryLabPamphlet1.pdf).
  * Grimmer, Justin and Brandon M. Stewart. ["Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts"](https://www.cambridge.org/core/journals/political-analysis/article/text-as-data-the-promise-and-pitfalls-of-automatic-content-analysis-methods-for-political-texts/F7AAC8B2909441603FEB25C156448F20).
  * Michel, Jean-Baptiste et al. ["Quantitative Analysis of Culture Using Millions of Digitized Books"](http://science.sciencemag.org/content/331/6014/176).
  * Healy, Kieran. ["Fuck Nuance"](https://journals.sagepub.com/doi/10.1177/0735275117709046#).
* Techincal
  * Guttag, chapters 6-7.

**Week 5 (2/12): Social networks** 

* Read
  * DeWitt, Anne. ["Advances in the Visualization of Data:
The Network of Genre in the Victorian Periodical Press"](https://muse.jhu.edu/article/585966).
  * So, Richard Jean and Hoyt Long. ["Network Analysis and the Sociology of Modernism"](https://read.dukeupress.edu/boundary-2/article-standard/40/2/147/6462/Network-Analysis-and-the-Sociology-of-Modernism).
  * Weingart, Scott and Jessica Otis. ["Gender Inclusivity in Six Degrees"](http://6dfb.tumblr.com/post/136678327006/gender-inclusivity-in-six-degrees).
* Technical
  * Guttag, chapters 8 and 10 (chapter 9, on algorithmic complexity, is recommended but optional).
  * Due: [String manipulation exercise](https://github.com/wilkens-teaching/dhgrad2019/tree/master/exercises/ps2).

**Week 6 (2/19): Gender**

No class meeting (instructor travel).

**Week 7 (2/26): Gender**

* Prof. Jason Ruiz class visit.
* Read
  * Underwood, Ted, David Bamman, and Sabrina Lee. ["The Transformation of Gender in English-Language Fiction"](http://culturalanalytics.org/2018/02/the-transformation-of-gender-in-english-language-fiction).
  * Tatlock, Lynne et al. ["Crossing Over: Gendered Reading Formations at the Muncie Public Library, 1891-1902"](http://culturalanalytics.org/2018/03/crossing-over-gendered-reading-formations-at-the-muncie-public-library-1891-1902/).
* Technical
  * Guttag, chapters 11 and 14.
  * Due: [Parsing XML and JSON exercise](https://github.com/wilkens-teaching/dhgrad2019/tree/master/exercises/ps3).

**Week 8 (3/5): Geography**

* Read
  * Evans, Elizabeth and Matthew Wilkens. ["Nation, Ethnicity, and the Geography of British Fiction, 1880-1940"](http://culturalanalytics.org/2018/07/nation-ethnicity-and-the-geography-of-british-fiction-1880-1940/).
  * Heuser, Ryan, Franco Moretti, and Erik Steiner. ["The Emotions of London"](https://litlab.stanford.edu/LiteraryLabPamphlet13.pdf).

**Week 9. Spring break.** No class meetings.

**Week 10 (3/19): Topics**

* Read
  * Goldstone, Andrew and Ted Underwood. ["The Quiet Transformations of Literary Studies: What Thirteen Thousand Scholars Could Tell Us"](http://muse.jhu.edu/article/558875).
  * Jockers, Matthew and David Mimno. ["Significant themes in 19th-century literature"](https://www.sciencedirect.com/science/article/pii/S0304422X13000673).
  * [_Signs_@40](http://signsat40.signsjournal.org/topic-model/).
* Technical
  * Guttag, chapters 15 and 17.
 
**Weeks 11-12 (3/26-4/2): No class meetings (student and instructor travel)**

No classes these two weeks to accommodate scheduling conflicts. Read Guttag chapters 19-21 (all on statistics) and see next week's assignments, which are heavier than usual.


**Week 13 (4/9): Markets, unsupervised learning**

* Read
  * Sapiro, Gisèle. ["Translation and Symbolic Capital in the Era of Globalization: French Literature in the United States"](https://journals.sagepub.com/doi/full/10.1177/1749975515584080).
  * Bamman, David, Ted Underwood, and Noah Smith. ["A Bayesian Mixed Effects Model of Literary Character"](http://acl2014.org/acl2014/P14-1/pdf/P14-1035.pdf).
  * Wilkens, Matthew. ["Genre, Computation, and the Varieties of Twentieth-Century U.S. Fiction"](http://culturalanalytics.org/2016/11/genre-computation-and-the-varieties-of-twentieth-century-u-s-fiction/).
* Technical
  * Guttag, chapters 22-23.
  * Due: [Entity recognition exercise](https://github.com/wilkens-teaching/dhgrad2019/blob/master/exercises/ps4/PS4%20Entities.ipynb).

**Week 14 (4/16): Supervised learning**

* Read
  * Underwood, Ted. ["The Life Cycles of Genres"](http://culturalanalytics.org/2016/05/the-life-cycles-of-genres/).
* Technical
  * Guttag, chapter 24.
  * Due: [Clustering demo exercise](https://github.com/wilkens-teaching/dhgrad2019/tree/master/exercises/ps5).

**Week 15 (4/23): TBD**

* Readings to be determined by class interests and field developments.
* Project work.
* Technical
  * Due: Classification exercise.

**Week 16 (4/30)**

* Presentations and conclusions.

**Week 17**

Final project due by 5:00pm on Friday, 5/10.
