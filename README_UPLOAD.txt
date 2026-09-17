UPLOAD THESE FIVE FILES TO THE ROOT OF YOUR GitHub Sales_EPortfolio REPOSITORY

index.html
home.html
about.html
contact.html
address.html

HOW IT WORKS

index.html is the permanent outer page.
home.html, about.html, contact.html, and address.html open inside index.html.
The Spotify Dynamic Island stays in index.html, so changing portfolio pages does not reload the Spotify player.
The Light/Dark Mode button is inside the expanded Dynamic Island and changes the colors without changing your page layout.
The About page still has the 9-song Spotify list. Selecting a song also sends that song to the Dynamic Island.

TEST

1. Open the GitHub Pages root URL.
2. Open About.
3. Select a song.
4. The Dynamic Island expands.
5. Press Play inside the Dynamic Island Spotify player.
6. Click Home, Contact, or Address.
7. The inner page changes while the outer Spotify player remains loaded.
8. Open the Dynamic Island and test Light Mode / Dark Mode.

NOTE

Spotify and the browser control playback permissions. You must normally press Play yourself. Refreshing the whole browser page, closing the browser tab, or opening a different browser tab creates a new page session.


NO-SCROLL UPDATE

Home, Contact, and Address now use a fixed one-screen desktop layout.
The extra browser scrollbar caused by 100vh plus section padding is removed.
About keeps normal scrolling because it contains more content.
On small screens or very short windows, scrolling is automatically allowed so content is not cut off.
