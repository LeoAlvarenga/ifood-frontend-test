# iFood Frontend Test

Create a web application called Spotifood used to display the preferred playlists from iFood's customers. The web application has only one page:
* A page that lists the featured playlists at Spotify according to some criteria.

## Business rules

* The page is composed of two elements:
    * One list of featured playlists
    * One filter component
* The filter component should be used to filter the elements displayed by the list of featured playlists.
* The fields of the filter and their possible values or their type should be mounted by consuming this API **[1. Playlists Filters]** (http://www.mocky.io/v2/5a25fade2e0000213aa90776)
* The featured playlists to be displayed should be consumed from this API **[2. See the documentation from Spotify]** (https://developer.spotify.com/web-api/get-list-featured-playlists/)
* Every time the user change any information on the filter component, the list should be refresh accordingly, or in other words, you should recall the playlists API with the filter parameters every time the user changes any filter field.
* Considering that we live in a chaotic and fast-changing world, the page should refresh its content every 30 seconds, to see if any information from the Spotify APIs had been changed.

## Hints or Constraints

We will use one API from Spotify Web API. You should follow the Spotify guide in order to create a token needed to access Spotify's API.
To mount the fields on the filter component, you **must** consume the API that provides the metadata about the fields (Link 1).
You could use Material UI, Bootstrap or any other toolkit to accelerate your resolution. We will not provide any UI prototype or design.

## Non functional requirements

As this application will be a worldwide success, it must be prepared to be fault tolerant, responsive and resilient.
You **must** use React to build the application.
Also, briefly elaborate on your solution architecture details, choice of patterns and frameworks.
Fork this repository and submit your code.
