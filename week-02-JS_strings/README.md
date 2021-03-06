## Week 02:
---

## javascript syntax and objects // strings and generative text

##### February 8, 2016

*Much of this class adapted from Daniel Shiffman's Processing A2Z material.*

---



### Quiz

1. create a variable that stores a boolean in javascript.
2. create an array of numbers in javascript.
3. do strings use ‘ ‘ or “ “ in javascript?
4. What is ‘\n’ and what does it do?
5. What is ‘NaN’?
6. Write a line of code that shows an example of string concatenation.
7. What’s the result of (50 > 30 && 20 < 10)?
8. What’s the result of (100 || 1 - 1)?
9. Write a while loop that will never stop looping.
10. Write a for loop that loops 20 times, starting at i = -10.

Push your results to your class-02 folder in github.

### Javascript!

What is javascript? What makes it hard for us if we're expecting Java? Java vs. Javascript?

- Javascript is a high-level, dynamic, untyped, and interpreted programming language.
	- **High-level**: strong abstraction from the details of the computer.
	- **Dynamic**: executes behaviors at runtime that static programming languages execute during compilation.
	- **Untyped**: no ints, chars, strings, booleans, floats. All loosey goosey. If you're used to strictly typed languages, this is a pain.
	- **Interpreted**: each instruction executes directly, without compiling the whole thing to machine language first.

- Executing javascript in the browser - *command-option-i*

- Objects as *functions* vs. objects as *variables*

- Arrays as dynamic

- "==" vs. "==="

- String methods
	- .indexOf()
	- .substring()
	- .concat()
	- .split()
	- .replace()
	- .slice()
	- .charAt()

### DADA and "the Cut Up Method", Oulipo, Erasures

Magnetic poetry - http://www.nsftools.com/tips/MagneticPoetry.htm

Tristan Tzara - Romanian and French avant-garde poet, essayist, performance artist, one of the founders and central figures of the anti-establishment, anti-war, anti-bourgeois Dada movement of the early 20th century. Dada has ties to other avant garde artists of the time, notably Marcel Duchamp. 

At a surrealist rally in the 1920, Tzara created a poem by pulling words out of a hat, and a riot ensued.

From wikipedia:

*Many Dadaists believed that the 'reason' and 'logic' of bourgeois capitalist society had led people into war. They expressed their rejection of that ideology in artistic expression that appeared to reject logic and embrace chaos and irrationality. For example, George Grosz later recalled that his Dadaist art was intended as a protest "against this world of mutual destruction."*

*According to Hans Richter Dada was not art: it was "anti-art." Dada represented the opposite of everything which art stood for. Where art was concerned with traditional aesthetics, Dada ignored aesthetics. If art was to appeal to sensibilities, Dada was intended to offend.*

*As Hugo Ball expressed it, "For us, art is not an end in itself ... but it is an opportunity for the true perception and criticism of the times we live in."*

*A reviewer from the American Art News stated at the time that "Dada philosophy is the sickest, most paralyzing and most destructive thing that has ever originated from the brain of man." Art historians have described Dada as being, in large part, a "reaction to what many of these artists saw as nothing more than an insane spectacle of collective homicide."*

**TO MAKE A DADAIST POEM**

1. Take a newspaper.
2. Take some scissors.
3. Choose from this paper an article of the length you want to make your poem.
4. Cut out the article.
5. Next carefully cut out each of the words that makes up this article and put them all in a bag.
6. Shake gently.
7. Next take out each cutting one after the other.
8. Copy conscientiously in the order in which they left the bag.
9. Them poem will resemble you.
10. And there you are – an infinitely original author of charming sensibility, even though unappreciated by the vulgar herd.

[Burrough's cut up method](http://www.writing.upenn.edu/~afilreis/88v/burroughs-cutup.html)

ERASURES:

*Erasure is a form of found poetry or found art created by erasing words from an existing text in prose or verse and framing the result on the page as a poem. The results can be allowed to stand in situ or they can be arranged into lines and/or stanzas. Erasure is a way to give an existing piece of writing a new set of meanings, questions, or suggestions. It lessens the trace of authorship but requires purposeful decision making. What does one want done to the original text? Does a gesture celebrate, denigrate, subvert, or efface the source completely? One can erase intuitively by focusing on musical and thematic elements or systematically by following a specific process regardless of the outcome.*

[Erasure](https://en.wikipedia.org/wiki/Erasure_(artform))

**OULIPO**

*Oulipo (French pronunciation: short for French: Ouvroir de littérature potentielle; roughly translated: "workshop of potential literature") is a loose gathering of (mainly) French-speaking writers and mathematicians who seek to create works using constrained writing techniques.*

*Constraints are used as a means of triggering ideas and inspiration, most notably Perec's "story-making machine" which he used in the construction of Life: A User's Manual. As well as established techniques, such as lipograms (Perec's novel A Void) and palindromes, the group devises new techniques, often based on mathematical problems such as the Knight's Tour of the chess-board and permutations.*

### Partner Workshopping

On paper, invent an algorithm to create generative text from existing text. No randomness. Write it down step-by-step on paper, and create a text from it.

---
---
---

## Homework 02

---- *NO CLASS 2/15 - Due midnight Sunday, 2/21/16* ----

1. write an algorithm to generate new text from existing text as a single page program in P5. Use [javascript string methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) to realize the algorithm. Use P5’s text methods to display it. No randomness is allowed - every single aspect is predetermined by you. Post to your week 2 page in your github.io.

	* Suggestions:

		* Create a programmatic version of the one you workshopped in class.
		
		* Create a re-making of an oulipo or Dada technique.
		
		* Create an algorithm that creates a slightly different effect each time you run it (some randomness here is ok)
		
		* Create a [mad libs generator](http://www.projectlabyrinth.com/MadLibs/MadLibGen.php).
		
		* Create an actual [magnetic poetry simulator](http://www.nsftools.com/tips/MagneticPoetry.htm) that generates the words from arbitrary string input.
		
		* Have your finished code be a function that takes in a string as input to generate the result.		
	* Techniques to try:
	
		* Replace all words *x* with word *y*.
		
		* Add word *x* after instances of word *y*.
		
		* Remove all words that belong to array["\_\_\_\_", "\_\_\_\_", "_\_\_\_", etc.];
		
		* Split all words from a given string, re-order according to ...
		
		* Display text in the canvas in relationship to its appearance in the text. (size? color? orientation?)
		
		* Use a very deliberately chosen text source material.

2. Read and do exercises from **Chapter 2 and 3** of [Eloquent Javascript](http://eloquentjavascript.net/02_program_structure.html), and experiment with Javascript in the in-browser console.

3. If you need practice with p5.js, check out [Daniel Shiffman's excellent video series](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA).