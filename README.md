# EPF, iTunes Search, and Lookup Investigation 

## Enterprise Partner Feed

### File: itunes20160715

* Action: Find Jack Pattern, The Junction in itunes20160715 and isolate Track ID*

* Entry *

1468573200508543580294The Junction (Kindimmer Dub Mix)0Jack PatternKollektiv Traumwelt, Vol. 3http://itunes.apple.com/album/junction-kindimmer-dub-mix/id543580119?i=543580294&uo=52012 08 172012 07 10416188℗ 2012 Budenzauber2011 Alma Soul Musichttp://a784.phobos.apple.com/us/r1000/081/Music/26/59/4d/mzi.ztaejghw.aac.p.m4a301000

* Track ID = 543580294 *

### iTunes Search API

* Action: Confirm Jack Pattern, The Junction query through iTunes Search API matches Track ID 543580294*

* Request: https://itunes.apple.com/search?term=Jack+Pattern+The+Junction&country=GB&media=music&limit=1 *

* Response *
{
	"resultCount": 1,
	"results": [{
		"wrapperType": "track",
		"kind": "song",
		"artistId": 393570363,
		"collectionId": 543580119,
		"trackId": 543580294,
		"artistName": "Jack Pattern",
		"collectionName": "Kollektiv Traumwelt, Vol. 3",
		"trackName": "The Junction (Kindimmer Dub Mix)",
		"collectionCensoredName": "Kollektiv Traumwelt, Vol. 3",
		"trackCensoredName": "The Junction (Kindimmer Dub Mix)",
		"collectionArtistId": 151566958,
		"collectionArtistName": "Various Artists",
		"artistViewUrl": "https://itunes.apple.com/gb/artist/jack-pattern/id393570363?uo=4",
		"collectionViewUrl": "https://itunes.apple.com/gb/album/junction-kindimmer-dub-mix/id543580119?i=543580294&uo=4",
		"trackViewUrl": "https://itunes.apple.com/gb/album/junction-kindimmer-dub-mix/id543580119?i=543580294&uo=4",
		"previewUrl": "http://a784.phobos.apple.com/us/r1000/081/Music/26/59/4d/mzi.ztaejghw.aac.p.m4a",
		"artworkUrl30": "http://is2.mzstatic.com/image/thumb/Music/v4/48/86/e8/4886e86a-f149-9c7f-7fdb-6e2fe9926437/source/30x30bb.jpg",
		"artworkUrl60": "http://is2.mzstatic.com/image/thumb/Music/v4/48/86/e8/4886e86a-f149-9c7f-7fdb-6e2fe9926437/source/60x60bb.jpg",
		"artworkUrl100": "http://is2.mzstatic.com/image/thumb/Music/v4/48/86/e8/4886e86a-f149-9c7f-7fdb-6e2fe9926437/source/100x100bb.jpg",
		"collectionPrice": 7.99,
		"trackPrice": 0.79,
		"releaseDate": "2012-08-17T07:00:00Z",
		"collectionExplicitness": "notExplicit",
		"trackExplicitness": "notExplicit",
		"discCount": 1,
		"discNumber": 1,
		"trackCount": 25,
		"trackNumber": 20,
		"trackTimeMillis": 416188,
		"country": "GBR",
		"currency": "GBP",
		"primaryGenreName": "Electronic",
		"isStreamable": true
	}]
}

* Track ID = 543580294 *

### iTunes Lookup API

* Acton: Confirm Track ID 543580294 matches Jack Pattern, The Junction through Lookup API*

* Request: https://itunes.apple.com/lookup?id=543580294 * 

* Response: *
{
	"resultCount": 1,
	"results": [{
		"wrapperType": "track",
		"kind": "song",
		"artistId": 393570363,
		"collectionId": 543580119,
		"trackId": 543580294,
		"artistName": "Jack Pattern",
		"collectionName": "Kollektiv Traumwelt, Vol. 3",
		"trackName": "The Junction (Kindimmer Dub Mix)",
		"collectionCensoredName": "Kollektiv Traumwelt, Vol. 3",
		"trackCensoredName": "The Junction (Kindimmer Dub Mix)",
		"collectionArtistId": 151566958,
		"collectionArtistName": "Various Artists",
		"artistViewUrl": "https://itunes.apple.com/us/artist/jack-pattern/id393570363?uo=4",
		"collectionViewUrl": "https://itunes.apple.com/us/album/junction-kindimmer-dub-mix/id543580119?i=543580294&uo=4",
		"trackViewUrl": "https://itunes.apple.com/us/album/junction-kindimmer-dub-mix/id543580119?i=543580294&uo=4",
		"previewUrl": "http://a784.phobos.apple.com/us/r1000/081/Music/26/59/4d/mzi.ztaejghw.aac.p.m4a",
		"artworkUrl30": "http://is2.mzstatic.com/image/thumb/Music/v4/48/86/e8/4886e86a-f149-9c7f-7fdb-6e2fe9926437/source/30x30bb.jpg",
		"artworkUrl60": "http://is2.mzstatic.com/image/thumb/Music/v4/48/86/e8/4886e86a-f149-9c7f-7fdb-6e2fe9926437/source/60x60bb.jpg",
		"artworkUrl100": "http://is2.mzstatic.com/image/thumb/Music/v4/48/86/e8/4886e86a-f149-9c7f-7fdb-6e2fe9926437/source/100x100bb.jpg",
		"collectionPrice": 9.99,
		"trackPrice": 0.99,
		"releaseDate": "2012-08-17T07:00:00Z",
		"collectionExplicitness": "notExplicit",
		"trackExplicitness": "notExplicit",
		"discCount": 1,
		"discNumber": 1,
		"trackCount": 25,
		"trackNumber": 20,
		"trackTimeMillis": 416188,
		"country": "USA",
		"currency": "USD",
		"primaryGenreName": "Electronic",
		"isStreamable": true
	}]
}

* artistName = Jack Pattern and trackName = The Junction *