Koodin esittely 

ProductController.cs: 
- tarkoitetaan homeController.cs? jokatapauksessa se sisältää product metodin joka lukee products.json tiedoston sisällön ja deserialisoi sen listaksi tuotteita (products). Näin sovellus pystyy näyttämään tuotetiedot käyttäjälle. 

products.json: 
- sijaitsee wwwroot kansiossa ja se sisältää tuotteiden tiedot json muodossa (nimi, hinta, kuvaus ja kuva tuotteesta). Tämän tiedoston avulla ladataan ja käsitellään tuotteet. 

Products.cshtml
- Tämä tiedosto on yhteydessä Product.cs product metodiin ja käyttää JSON tiedostosta haettuja tuotteita luodakseen tuotteiden listauksen käyttäen HTML:ää ja CSS. 

PS. laitoin site.js koodit kommenttiin, että tuotteiden hinnat näkyvät oikein.