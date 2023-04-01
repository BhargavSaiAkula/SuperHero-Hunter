# SuperHero-Hunter
Host Link : https://bhargavsaiakula.github.io/SuperHero-Hunter/
I Have used the<a href=""> Marvel superhero api</a> 

![Screenshot (9146)](https://github.com/BhargavSaiAkula/SuperHero-Hunter/blob/main/image/homepage.png)


![Screenshot (9146)](https://github.com/BhargavSaiAkula/SuperHero-Hunter/blob/main/image/about.png)

![Screenshot (9146)](https://github.com/BhargavSaiAkula/SuperHero-Hunter/blob/main/image/likedpage.png)


1. We are using vanilla JS plus basic HTML and CSS for development
2. Three pages are present 
  1. Index (which is the Homapage)
  2. charDetails (which is the individual superhero page)
  3. likedHeros (which is the Liked Heros page)
3. User can search for the SuperHeros.
4. User can add the searched heros into liked heros list.
5. User can see the liked heros in a liked heros page and can remove the heros from there.
6. I have used the localStorage of browser so that the list is presistant.

<h1>Features</h1> 
<h3>Home Page</h3>
Fetch and display a list of SuperHeros (Characters) on the home page. Also create a search bar that will filter out the character based on search query. Suppose I type “bat” in the search box, it should show “batman”. 
[ API example https://gateway.marvel.com:443/v1/public/characters?ts=<time-stamp>&apikey=<public-key>&hash=<md5(ts+privateKey+publicKey)>]
Each search result of the superhero should have a favorite button, clicking on which superhero should be added to “My favorite superheroes” (a list).
On clicking any particular search result (any superhero), open a new page with more information about that superhero (Superhero page).

<h3>Superhero Page</h3>
Should show a lot of information about the superhero like their name, photo, bio and other information provided by the API (comics, events, series, stories, etc).

<h3>My favourite superheroes Page</h3>
Display a list of all the favourite superheroes.
Make this list persistent (should have the same number of superheroes before and after closing the browser).
Remove from favourites button: Each superhero should have remove from favourites button, clicking on which should remove that superhero from the lis
