# billboardpy

### Simple Python API to access billboard charts

## Usage

#### Clone the repo and copy the billboard.py file to the folder you want to access it in.

```sh
git clone https://github.com/deepjyoti30/billboardpy
```

## Quickstart

#### For any chart the ```Billboard``` class is used

#### To fetch the (https://www.billboard.com/charts/youtube)youtube chart.

```python
>>> import billboard
>>> Chart = billboard.Billboard("youtube")
```

#### To access the songs

```python
>>> print(Chart.chart[0].title, 'by', Chart.chart[0].artist)
Thank U, Next by Ariana Grande
```

#### The name of the playlist from the webpage can be accessed in the following way

```python
>>> Chart.chart_name
'YOUTUBE'
```

## Datatype

#### Every song has three accessible properties

 * ```title``` - Title of the song
 * ```artist``` - Name of the artist
 * ```rank``` - Current rank of the song

 ## Dependencies

 * BeautifulSoup
 * Requests

 ## Feature Requests

 #### Feel free to ask for a feature by tagging the issue as Feature Request.
