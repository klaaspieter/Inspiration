# Articles

A collection of articles I like. This is rather short because, while I have
a massive [Pocket](https://getpocket.com/) archive, up until now I never bothered to safe the good ones.

## Life

- [The reign of recycling](https://www.nytimes.com/2015/10/04/opinion/sunday/the-reign-of-recycling.html)
    > As you sort everything into the right bins, you probably assume that recycling is helping your community and protecting the environment. But is it? Are you in fact wasting your time?

- [White gold: the unstoppable rise of alternative milks](https://www.theguardian.com/news/2019/jan/29/white-gold-the-unstoppable-rise-of-alternative-milks-oat-soy-rice-coconut-plant)

    Key quotes (emphasis mine).

    > Besides the ill-treatment of animals, evidence has mounted that the dairy industry is catastrophic for the environment. **Animal agriculture contributes more greenhouse gases than aviation, shipping and road vehicles combined**. One recent study led by Oxford University claimed that **observing a vegetarian or vegan diet is the single most effective way to reduce your own environmental footprint**.

    > We are all born milk drinkers. Babies’ guts produce the enzyme lactase, which breaks down lactose, the sugar in breastmilk (and cow’s milk), into the simpler sugars glucose and galactose. But for the majority of humans, production of the enzyme lactase plummets after weaning. “From a human perspective – no, to go further than that, from a mammalian perspective – **the norm is to be able to tolerate your mother’s breast milk**, and then as you get past infancy, to stop producing lactase and become lactose intolerant,” said Adam Fox, a consultant paediatric allergist at Guy’s and St Thomas’s hospitals, and one of the UK’s leading food allergy experts. **“Then you’ve got a small group of humans that have a mutation which means they maintain production of lactase into adulthood. Northern Europeans, the Masai [in east Africa], some Arab groups as well. But that’s the exception, not the rule.”**


## Software

- [Haskell's kind system - a primer](https://diogocastro.com/blog/2018/10/17/haskells-kind-system-a-primer/#fnref:void) 🤯
- [The Wrong Abstraction](https://www.sandimetz.com/blog/2016/1/20/the-wrong-abstraction)
- [Repeat yourself, do more than one thing, and rewrite everything](
https://programmingisterrible.com/post/176657481103/repeat-yourself-do-more-than-one-thing-and)
- [Why Doctors Hate Their Computers](https://www.newyorker.com/magazine/2018/11/12/why-doctors-hate-their-computers)
    
    How software designed with an infinite amount of requirements is preventing doctor's from interacting with patients and forces them to focus on their computers. I especially liked how the author wrote about mutation and selection.
    > Adaptation requires two things: mutation and selection. Mutation produces variety and deviation; selection kills off the least functional mutations. Our old, craft-based, pre-computer system of professional practice—in medicine and in other fields—was all mutation and no selection. There was plenty of room for individuals to do things differently from the norm; everyone could be an innovator. But there was no real mechanism for weeding out bad ideas or practices.
    >
    > Computerization, by contrast, is all selection and no mutation. Leaders install a monolith, and the smallest changes require a committee decision, plus weeks of testing and debugging to make sure that fixing the daylight-saving-time problem, say, doesn’t wreck some other, distant part of the system.
    
    There is also a great daylights savings time story in there; just another reason to get rid of it:
    
    > Last fall, the night before daylight-saving time ended, an all-user e-mail alert went out. The system did not have a way to record information when the hour from 1 a.m. to 1:59 a.m. repeated in the night. This was, for the system, a surprise event. The only solution was to shut down the lab systems during the repeated hour. Data from integrated biomedical devices (such as monitoring equipment for patients’ vital signs) would be unavailable and would have to be recorded by hand. Fetal monitors in the obstetrics unit would have to be manually switched off and on at the top of the repeated hour.
    
- [6 rules of programming](https://twitter.com/rob_pike/status/998681790037442561)
    >    Most programs are too complicated - that is, more complex than they need to be to solve their problems efficiently.  Why? Mostly it's because of bad design, but I will skip that issue here because it's a big one.  But programs are often complicated at the microscopic level, and that is something I can address here.
    > 
    > Rule 1.  You can't tell where a program is going to spend its time.  Bottlenecks occur in surprising places, so don't try to second guess and put in a speed hack until you've proven that's where the bottleneck is.
    > 
    > Rule 2.  Measure.  Don't tune for speed until you've measured, and even then don't unless one part of the code overwhelms the rest.
    > 
    > Rule 3.  Fancy algorithms are slow when n is small, and n is usually small.  Fancy algorithms have big constants. Until you know that n is frequently going to be big, don't get fancy.  (Even if n does get big, use Rule 2 first.)   For example, binary trees are always faster than splay trees for workaday problems.
    > 
    > Rule 4.  Fancy algorithms are buggier than simple ones, and they're much harder to implement.  Use simple algorithms as well as simple data structures.
    > 
    >   The following data structures are a complete list for almost all practical programs:
    > 
    >   - array
    >   - linked list
    >   - hash table
    >   - binary tree 
    > 
    >   Of course, you must also be prepared to collect these into compound data structures.  For instance, a symbol table might be implemented as a hash table containing linked lists of arrays of characters.
    > 
    > Rule 5.  Data dominates.  If you've chosen the right data structures and organized things well, the algorithms will almost always be self-evident.  Data structures, not algorithms, are central to programming.  (See The Mythical Man-Month: Essays on Software Engineering by F. P. Brooks, page 102.)
    > 
    > Rule 6.  There is no Rule 6. 

## Business

- [Come here and work on hard problems… except the ones on our doorstep](https://programmingisterrible.com/post/50421878989/come-here-and-work-on-hard-problems-except-the)
- [The Parable of the Mexican Fisherman](http://renewablewealth.com/the-parable-of-the-mexican-fisherman/)

## Parenting

- [The Overprotected Kid](https://www.theatlantic.com/features/archive/2014/03/hey-parents-leave-those-kids-alone/358631/)
- [The Play Deficit](http://aeon.co/magazine/culture/children-today-are-suffering-a-severe-deficit-of-play/)
- [10 Common Mistakes Parents Today Make (Me Included)](http://m.huffpost.com/us/entry/4753451?ncid=fcbklnkushpmg00000037)

    > Prepare your child for the road, not the road for your child."

- [How to land your kid in therapy - Lori Gottllieb](https://www.theatlantic.com/magazine/archive/2011/07/how-to-land-your-kid-in-therapy/308555/)
- [Finland schools: Subjects scrapped and replaced with ‘topics’ as country reforms it’s education system](https://www.independent.co.uk/news/world/europe/finland-schools-subjects-are-out-and-topics-are-in-as-country-reforms-its-education-system-10123911.html)

- [What the best education systems are doing right](https://ideas.ted.com/what-the-best-education-systems-are-doing-right/)
  > Today, the American culture of choice puts the onus on parents to find the “right” schools for our kids, rather than trusting that all schools are capable of preparing our children for adulthood. 
- [The Six-Lesson Schoolteacher](http://www.cantrip.org/gatto.html)
- [In an age of robots, schools are teaching our children to be redundant](https://www.theguardian.com/commentisfree/2017/feb/15/robots-schools-teaching-children-redundant-testing-learn-future)
- [No grammar schools, lots of play: the secrets of Europe’s top education system](https://www.theguardian.com/education/2016/sep/20/grammar-schools-play-europe-top-education-system-finland-daycare)
- [The Anti-Helicopter Parent’s Plea: Let Kids Play!](https://www.nytimes.com/2016/10/23/magazine/the-anti-helicopter-parents-plea-let-kids-play.html)
