# Image Crawler
Google, Naver multiprocess image crawler
<br><br>

## How to use
1. Install ChromeDriver
   * ```cd chromedriver```
   * Select suitable chromeDriver for the operating system and extract it to install.   
   * You can install various chromedriver [here](http://chromedriver.storage.googleapis.com/index.html)
   
2. clone this repository: ```git clone https://github.com/ruby-kim/Image-Crawler.git```
3. ```cd Image-Crawler```
2. ```pip install -r requirements.txt```
3. Write search keywords in keywords.txt
4. **Run "main.py"** (Refer to the subsection below: [Arguments](#Arguments))
5. Files will be downloaded to 'download' directory.
<br>

## Arguments
usage:
```
python3 main.py [--skip true] [--threads 4] [--google true] [--naver true] [--full false] [--face false]
```

```
--skip true        Skips keyword if downloaded directory already exists. This is needed when re-downloading.

--threads 4        Number of threads to download.

--google true      Download from google.com (boolean)

--naver true       Download from naver.com (boolean)

--full false       Download full resolution image instead of thumbnails (slow)

--face false       Face search mode
```
