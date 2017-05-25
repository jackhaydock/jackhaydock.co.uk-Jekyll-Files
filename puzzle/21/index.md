---
layout: puzzle
title: "Puzzle #21"
heading: Pointless Puzzle

char: "05"
next: "22"

hint: "Einstein is alleged to have written a puzzle similar to this."

answera: "green"
answerb: "Green"
answerc: "four"
answerd: "4"

response: "This is a rewritten version of Einstein's five house puzzle which he claimed only 2% would be able to solve. Well you solved it so...well he had to be wrong somewhere. That is assuming you did solve it, not just entered each possible answer till the correct one came up, you wouldn't do that...right?
<table style=width:100>
 <tr>
  <th></th>
  <th>#1</th>
  <th>#2</th>
  <th>#3</th>
  <th>#4</th>
  <th>#5</th>
 </tr>
 <tr>
  <th>Door</th>
  <td>Black</td>
  <td>Blue</td>
  <td>Red</td>
  <td>Green</td>
  <td>White</td>
 <tr>
 <tr>
  <th>Language</th>
  <td>Java</td>
  <td>Ruby</td>
  <td>C++</td>
  <td>PHP</td>
  <td>Basic</td>
 <tr>
 <tr>
  <th>Drink</th>
  <td>Mango Juice</td>
  <td>Cola</td>
  <td>Blue Ox</td>
  <td>Water</td>
  <td>Coffee</td>
 <tr>
 <tr>
  <th>Music</th>
  <td>Classical</td>
  <td>Jazz</td>
  <td>Jpop</td>
  <td>Rock</td>
  <td>Dubstep</td>
 <tr>
 <tr>
  <th>Hat</th>
  <td>Top Hat</td>
  <td>Fedora</td>
  <td>Straw Hat</td>
  <td>Beanie</td>
  <td>Baseball Cap</td>
 <tr>
</table>
"

sanswera: "black"
sanswerb: "blue"
sanswerc: "red"
sanswerd: "white"

sresponsea: "It has occurred to me, you could just list of the possible answers till you get the right one. All this work for nothing? Please at least try to do it properly."
sresponseb: "It has occurred to me, you could just list of the possible answers till you get the right one. All this work for nothing? Please at least try to do it properly."
sresponsec: "It has occurred to me, you could just list of the possible answers till you get the right one. All this work for nothing? Please at least try to do it properly."
sresponsed: "It has occurred to me, you could just list of the possible answers till you get the right one. All this work for nothing? Please at least try to do it properly."

1room: "Black"
1lang: "Java"
1drink: "Mango Juice"
1music: "Classical"
1hat: "Top Hat"

2room: "Blue"
2lang: "Ruby"
2drink: "Cola"
2music: "Jazz"
2hat: "Fedora"

3room: "Red"
3lang: "C++"
3drink: "Blue Ox"
3music: "Jpop"
3hat: "Straw Hat"

4room: "Green"
4lang: "PHP"
4drink: "Water"
4music: "Rock"
4hat: "Beanie"

5room: "White"
5lang: "Basic"
5drink: "Coffee"
5music: "Dubstep"
5hat: "Baseball Cap"
---

* There are five rooms in the office identified by a different coloured door.
* In each room works a different developer with a different language.
* Each developer prefers a: different drink, different music genre and a different hat. 
* Nobody can have the same room, drink, music or hat.

<h4>What door does the person who wears the {{ page.4hat }} work behind?</h4>

* The <b>{{ page.3lang }}</b> developer works behind the <b>{{ page.3room }}</b> door.
* The <b>{{ page.5lang }}</b> developer wears a <b>{{ page.5hat }}</b>.
* The <b>{{ page.2lang }}</b> developer drinks <b>{{ page.2drink }}</b>.
* The <b>{{ page.4room }}</b> is to the left of the <b>{{ page.5room }}</b> door.
* The developer behind the <b>{{ page.4room }}</b> door drinks <b>{{ page.4drink }}</b>.
* The person who listens to <b>{{ page.3music }}</b> wears a <b>{{ page.3hat }}</b>.
* The developer behind the <b>{{ page.1room }}</b> door listens to <b>{{ page.1music }}</b>
* The person in the centre office drinks <b>{{ page.3drink }}</b>.
* The <b>{{ page.1lang }}</b> developer works in the first office from the left.
* The person who listens to <b>{{ page.2music }}</b> works next to the one who wears a <b>{{ page.1hat }}</b>.
* The developer who wears a <b>{{ page.2hat }}</b> works next to the one who listens to <b>{{ page.1music }}</b>.
* The one who listens to <b>{{ page.5music }}</b> drinks <b>{{ page.5drink }}</b>.
* The <b>{{ page.5lang }}</b> developer listens to <b>{{ page.5lang }}</b>.
* The <b>{{ page.1lang }}</b> works next to the <b>{{ page.2room }}</b> room.
* The person who likes <b>{{ page.2music }}</b> has a neighbor who drinks <b>{{ page.1drink }}</b>


