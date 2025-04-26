# cop3502-lab-6-the-cow-strikes-back-solved
**TO GET THIS SOLUTION VISIT:** [COP3502 Lab 6: The Cow Strikes Back Solved](https://www.ankitcodinghub.com/product/cop3502-lab-6-the-cow-strikes-back-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;30205&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp;COP3502 Lab 6: The Cow Strikes Back Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<h1>&nbsp;Overview</h1>
This lab’s purpose is to provide students with experience in inheritance of classes and working with multiplace classes. It is recommended that students use command line tools and editors for this lab (though it is not strictly speaking required). This lab will require students to build on their previous lab experience, in which a version of the cowsay utility was created.

&nbsp;

<h1>Specification</h1>
Students will update the driver program class (Cowsay) and also create two new classes – Dragon and IceDragon. The Dragon class just extend the Cow class, and IceDragon must be derived from Dragon. As before, HeiferGenerator.java is provided for you – but updated to handle the new Dragon class and its subtypes. (Please refer to specification for previous lab for a refresher.) <u>Students may implement protected attributes and</u> <u>methods if they chose to do so.</u> This is not required – it is purely optional. No public attributes / methods should be added to the specification!

&nbsp;

<h2>Cowsay Class (Program Driver)</h2>
Your program must accept <u>command line arguments</u> as follows:

&nbsp;

java cowsay -l &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Lists the available cows

java cowsay MESSAGE Prints out the MESSAGE using the default COW java cowsay -n COW MESSAGE Prints out the MESSAGE using the specified COW

&nbsp;

In addition, this version of the utility handles a special set of Cow-derived Dragon classes (and its subclasses).&nbsp; Whenever a dragon-type cow is selected, the display of the message must be followed by a line stating whether or not the dragon is fire-breathing:

<table width="707">
<tbody>
<tr>
<td width="414">&gt;java Cowsay -n dragon Fiery RAWR

&nbsp;

Fiery RAWR

\

\

\

|\___/|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /\&nbsp; //|\\

/0&nbsp; 0&nbsp; \__&nbsp;&nbsp; /&nbsp; \// | \ \

/&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp; \/_ /&nbsp;&nbsp; //&nbsp; |&nbsp; \&nbsp; \

\_^_\’/&nbsp;&nbsp; \/_&nbsp;&nbsp; //&nbsp;&nbsp; |&nbsp;&nbsp; \&nbsp;&nbsp; \

//_^_/&nbsp;&nbsp;&nbsp;&nbsp; \/_ //&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp; \

( //) |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \ //&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp; \

( / /) _|_ /&nbsp;&nbsp; )&nbsp;&nbsp; //&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp; _\

( // /) ‘/,_ _ _/&nbsp; ( ; -.&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp; _ _\.-~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .-~~~^-.

(( / / )) ,-{&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.|.-~-.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.

(( // / ))&nbsp; ‘/\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~-. _.-~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .-~^-.&nbsp; \

(( /// ))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.&nbsp;&nbsp; {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp; \

(( / ))&nbsp;&nbsp;&nbsp;&nbsp; .—-~-.\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \-‘&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp; `.&nbsp;&nbsp; __

///.—-..&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _ -~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.&nbsp; ^-`&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ///-._ _ _ _ _ _ _}^ – – – – ~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `—–‘

This dragon can breathe fire.
</td>
<td width="18"></td>
<td width="275">&gt;java Cowsay -n ice-dragon Ice-cold RAWR

&nbsp;

Ice-cold RAWR

\

\

\

|\___/|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /\&nbsp; //|\\

/0&nbsp; 0&nbsp; \__&nbsp;&nbsp; /&nbsp; \// | \ \

/&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp; \/_ /&nbsp;&nbsp; //&nbsp; |&nbsp; \&nbsp; \

\_^_\’/&nbsp;&nbsp; \/_&nbsp;&nbsp; //&nbsp;&nbsp; |&nbsp;&nbsp; \&nbsp;&nbsp; \

//_^_/&nbsp;&nbsp;&nbsp;&nbsp; \/_ //&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp; \

( //) |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \ //&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp; \

( / /) _|_ /&nbsp;&nbsp; )&nbsp;&nbsp; //&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp; _\&nbsp;&nbsp;&nbsp; ( // /) ‘/,_ _ _/&nbsp; ( ; -.&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp; _ _\.-~

(( / / )) ,-{&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.|.-~-.

(( // / ))&nbsp; ‘/\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~-. _.-~

(( /// ))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.&nbsp;&nbsp; {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }

(( / ))&nbsp;&nbsp;&nbsp;&nbsp; .—-~-.\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \-‘

///.—-..&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _

///-._ _ _ _ _ _ _}^ – – – – ~

&nbsp;

This dragon cannot breathe fire.
</td>
</tr>
</tbody>
</table>
<h2>Cow Class</h2>
The Cow class must have all of the same methods as previously required, though students may add protected and private methods.) The methods are repeated here, briefly, for reference.

&nbsp;

<table width="704">
<tbody>
<tr>
<td width="309">public Cow(String name)</td>
<td width="395">// Constructor</td>
</tr>
<tr>
<td width="309">public String getName()</td>
<td width="395">// Returns name of this cow object</td>
</tr>
<tr>
<td width="309">public String getImage()</td>
<td width="395">// Return image for this cow object</td>
</tr>
<tr>
<td width="309">public void setImage(String image)</td>
<td width="395">// Sets the image for this cow object to image</td>
</tr>
</tbody>
</table>
&nbsp;

<h2>Dragon Class</h2>
The Dragon class must be derived from the Cow class and must make all of its methods available. In addition, Dragon must provide the following methods:

public Dragon(String name, String image)

Constructor; creates a new Dragon object with the given name and image. This should be the only public constructor for the Dragon class!

&nbsp;

public boolean canBreatheFire()

This method should exist in every Dragon class. For the default Dragon type, it should always return true.

&nbsp;

<h2>IceDragon Class</h2>
The IceDragon class must be derived from the Dragon class and must make all of its methods available:

public Dragon(String name, String image)

Constructor; creates a new IceDragon object with the given name and image. This should be the only public constructor for the IceDragon class!

&nbsp;

public boolean canBreatheFire()

For the IceDragon type, this method should always return false.

&nbsp;

<h1>Submissions</h1>
NOTE: Your output must match the example output *exactly*. If it does not, you will not receive full credit for your submission!

&nbsp;

Files:&nbsp; Cowsay.java, Cow.java, Dragon.java, IceDragon.java, HeiferGenerator.java Method: Submit on ZyLabs

<h1>Sample Output</h1>
&nbsp;

&gt;javac Cowsay.java

&gt;java Cowsay Hello World!

&nbsp;

Hello World!

\

\

\

^__^

(oo)\_______

(__)\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; )\/\

||—-w |

||&nbsp;&nbsp;&nbsp;&nbsp; ||

&nbsp;

&gt;java Cowsay -n kitteh Moew-Moew!

Moew-Moew!

\

\

\

(“`-‘&nbsp; ‘-/”) .___..–‘ ‘ “`-._

` *_ *&nbsp; )&nbsp;&nbsp;&nbsp; `-.&nbsp;&nbsp; (&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ) .`-.__. `)

(_Y_.) ‘ ._&nbsp;&nbsp; )&nbsp;&nbsp; `._` ;&nbsp; “ -. .-‘

_.. `–‘_..-_/&nbsp;&nbsp; /–‘ _ .’ ,4

( i l ),-”&nbsp; ( l i),’&nbsp; ( ( ! .-‘

&nbsp;

&gt;java Cowsay -l

Cows available: heifer kitteh dragon ice-dragon

&nbsp;

&gt;java Cowsay -n ninja Hello world!

Could not find ninja cow!

&nbsp;

&gt;java Cowsay -n dragon Firey RAWR

&nbsp;

Fiery RAWR

\

\

\

|\___/|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /\&nbsp; //|\\

/0&nbsp; 0&nbsp; \__&nbsp;&nbsp; /&nbsp; \// | \ \

/&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp; \/_ /&nbsp;&nbsp; //&nbsp; |&nbsp; \&nbsp; \

\_^_\’/&nbsp;&nbsp; \/_&nbsp;&nbsp; //&nbsp;&nbsp; |&nbsp;&nbsp; \&nbsp;&nbsp; \

//_^_/&nbsp;&nbsp;&nbsp;&nbsp; \/_ //&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp; \

( //) |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \ //&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp; \

( / /) _|_ /&nbsp;&nbsp; )&nbsp;&nbsp; //&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp; _\

( // /) ‘/,_ _ _/&nbsp; ( ; -.&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp; _ _\.-~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .-~~~^-.

(( / / )) ,-{&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.|.-~-.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.

(( // / ))&nbsp; ‘/\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~-. _.-~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .-~^-.&nbsp; \

(( /// ))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.&nbsp;&nbsp; {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp; \

(( / ))&nbsp;&nbsp;&nbsp;&nbsp; .—-~-.\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \-‘&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp; `.&nbsp;&nbsp; __

///.—-..&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _ -~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.&nbsp; ^-`&nbsp; \

///-._ _ _ _ _ _ _}^ – – – – ~&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`—–‘

&nbsp;

This dragon can breathe fire.

&nbsp;

&gt;java Cowsay -n ice-dragon Ice-cold RAWR

&nbsp;

Ice-cold RAWR

\

\

\

|\___/|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /\&nbsp; //|\\

/0&nbsp; 0&nbsp; \__&nbsp;&nbsp; /&nbsp; \// | \ \

/&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp; \/_ /&nbsp;&nbsp; //&nbsp; |&nbsp; \&nbsp; \

\_^_\’/&nbsp;&nbsp; \/_&nbsp;&nbsp; //&nbsp;&nbsp; |&nbsp;&nbsp; \&nbsp;&nbsp; \

//_^_/&nbsp;&nbsp;&nbsp;&nbsp; \/_ //&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp; \

( //) |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \ //&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp; \

( / /) _|_ /&nbsp;&nbsp; )&nbsp;&nbsp; //&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp; _\

( // /) ‘/,_ _ _/&nbsp; ( ; -.&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp; _ _\.-~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .-~~~^-.

(( / / )) ,-{&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.|.-~-.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.

(( // / ))&nbsp; ‘/\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~-. _.-~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .-~^-.&nbsp; \

(( /// ))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.&nbsp;&nbsp; {&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp; \

(( / ))&nbsp;&nbsp;&nbsp;&nbsp; .—-~-.\&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \-‘&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp; `.&nbsp;&nbsp; __

///.—-..&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _ -~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `.&nbsp; ^-`&nbsp; \

///-._ _ _ _ _ _ _}^ – – – – ~&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `—–‘

&nbsp;

This dragon cannot breathe fire.

&nbsp;
