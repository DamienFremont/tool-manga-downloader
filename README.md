# scan-dl

Extract and download full online manga from websites like http://mangafreak.me/.

## Usage

* launch with command from bin folder
```
java -jar scan-dl.jar -url YOU_SERIE_URL
```
* accept security exception for phantomjs browser
* wait for ending...
* get the result in generated target folder


## Example

URLs for MangaFreak
* This URL will download the serie: http://mangafreak.me/series1/knights-of-sidonia
* This URL will download the chapter: http://mangafreak.me/read1/knights-of-sidonia/1

URLs for MangaHere
* This URL will download the serie: http://www.mangahere.co/manga/sidonia_no_kishi/
* This URL will download the chapter: http://www.mangahere.co/manga/sidonia_no_kishi/v01/c000/

## Example for a serie
```
java -jar scan-dl.jar -url http://mangafreak.me/series1/knights-of-sidonia
```
result: in folder target/2015...

![ScreenShot](screenshots/ScreenShot001.jpg)

![ScreenShot](screenshots/ScreenShot002.jpg)

![ScreenShot](screenshots/ScreenShot003.jpg)

![ScreenShot](screenshots/ScreenShot004.jpg)

![ScreenShot](screenshots/ScreenShot005.jpg)

![ScreenShot](screenshots/ScreenShot006.jpg)

![ScreenShot](screenshots/ScreenShot007.jpg)

## Example for a chapter
```
java -jar scan-dl.jar -url http://www.mangahere.co/manga/sidonia_no_kishi/v01/c000/
```
result: in folder target/2015...

java -jar scan-dl-jar-with-dependencies -url http://www.mangahere.co/manga/sidonia_no_kishi/v01/c000/
result: in folder target/2015...

(WORK IN PROGRESS)
