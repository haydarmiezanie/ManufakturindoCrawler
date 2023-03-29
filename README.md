
# Read Me

Glints Crawling is Crawler that aims data from Manufakturindo to xlsx, this scraper works in about 0.8 - 1 sec / page depends on the internet .

## Run Locally

Clone the project

```bash
  git clone 
```

Install dependencies

```bash
  pip install tenacity
  pip install pandas
  pip install timeit
```

Start the scraper

```bash
  python -m manufakturindo_crawler[start_page] [end_page]
```
Example :

```bash
  python -m manufakturindo_crawler 1 210
```
## Crawler Flow

![image](https://user-images.githubusercontent.com/39428898/228453255-15bd3c3a-0fe9-48e9-b301-dbe8a0f934fa.png)


## Limitation

This crawler is only example how to crawl data from Manufakturindo. This method work's very efficient.

## Authors

- [Haydar Miezanie](https://github.com/haydarmiezanie)

