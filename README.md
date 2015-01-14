# ebrary-konversio

KUVAUS

Pääasiassa Melinda-kirjastoille suunnattu USEMARCON-konversiosääntö ebraryn verkkokirjojen tietueille. 

Paketti sisältää merkkikonversion. Alkuperäiset Ebrary-tietueet ovat MARC-8 -merkistöä, ja ne muunnetaan konversiopaketin avulla UTF-8 decomposed -merkistöön (skandit composed).

Lisätietoja USEMARCON-ohjelmasta: http://www.nationallibrary.fi/libraries/format/usemarcon.html.

KÄYTTÖ

Kopioi konversiopaketti päätteellesi "Download ZIP" -painikkeesta. Pura paketti haluamaasi sijaintiin esimerkiksi C:\Usemarcon\ -hakemiston alle. USEMARCON GUI -käyttöliittymän käyttöä konversiossa suositellaan, saat sen käyttöösi Kansalliskirjaston USEMARCON-sivulta: http://www.nationallibrary.fi/libraries/format/usemarcon.html. 

USEMARCON GUI -käyttöliittymää käyttäessäsi varmista, että alkuperäinen merkistö (MARC-8) on näkyvissä. Se löytyy kohdasta Tools -> Edit INI file -> MARC File Attributes -> Character Set (liukuvalikosta): MARC-8. Kun lataat tällä paketilla konvertoidut tietueet kirjastotietokantaan, merkistönä tulee olla "MARC21 UTF-8".

=================

DESCRIPTION

A USEMARCON rule for Finnish libraries for processing MARC 21 records of ebrary e-books.
