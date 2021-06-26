# object literals # 

### calling function that need information ###

** In JavaScript all functions are object methods. **

** If a function is not a method of a JavaScript object, it is a function of the global object . **

** The example below creates an object with 3 properties, firstName, lastName, fullName. **

const myObject = {
  firstName:"John",
  lastName: "Doe",
  fullName: function () {
    return this.firstName + " " + this.lastName;
  }
}

// This will return "John Doe":
myObject.fullName();  


** GETTING MULTIPLE VALUES **
OUT OF A FUNCTION
Functions can return more than one value using an array.
For example, this function calculates the area and volume of a box.
First, a new function is created
ca lled get Size(). The area of
the box is calculated and stored
in a variable called area.
The volume is calculated and
stored in a variable called
vo 1 ume. Both are then placed
into an array called shes.
This array is then returned to the
code that called the getSize()
function, allowing the values to
be used.
function getSize (width, height, depth) {
var area = width * height;
}
var volume = width * height * depth;
var sizes= [area , volume];
return sizes;
var areaOne = getSize (3, 2, 3)[0];
var volumeOne = getSize (3, 2, 3)[1];
# document object #
Functions allow you to group a set of related
statements together that represent a single task.
Functions can take parameters (informatiorJ required
to do their job) and may return a value.
An object is a series of variables and functions that
represent something from the world around you.
In an object, variables are known as properties of the
object; functions are known as methods of the object.
Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.
JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
Arrays and objects can be used to create complex data
sets (and both can contain the other).

# Understanding The Problem Domain #

Programming is easy if you understand the problem domain
A long time ago, I worked for Hewlett Packard writing software for multi-function printers.

Most of the work at the time was basic waterfall development.  There wasn’t much Agile happening there—at least at the time I was there.waterfall can define problem domains


There was however something really interesting about the waterfall approach and the extreme amount of specification that was done before anything was built—it was very easy to write the code for a feature.

I remember writing a tab control for the user interface of a printer and having the complete pixel perfect specs handed to me before I began to write any code.  I was also given all the possible use cases and told exactly how it should function and what it should do under just about every circumstance.

Guess how easy it was to write the code to produce this tab control?  Super easy.

As much as I frown upon this approach for software development today, there is something interesting to think about here.

I was essentially given the entire problem domain in the form of a spec that was clear and unambiguous.  I was easily able to learn that problem domain and because of it, I was able to write the code very easily as well.

Perhaps you have had a similar experience, not necessarily working on a waterfall project where you were given the spec, but perhaps on an Agile project where you took the time to clearly understand the problem domain before writing any code.

I’ve spent days trying to implement a feature only to finally go back and talk to a product owner and hash out completely how something should work and why it should work in a particular way, only to go back to my desk and crank out the code in a matter of hours.


The more and more I write code, the more I learn that understanding the problem is the most critical piece to the equation. It is very difficult to solve a problem before you know the question.  It’s like buzzing in on Jeopardy before you hear the clue and shouting out random questions...

