# Prime Minister Narendra Modi's speeches (Aug '14 - Aug '20)

## Context

[Narendra Damodardas Modi](https://en.wikipedia.org/wiki/Narendra_Modi) is an Indian politician serving as the 14th Prime Minister of India since 2014. He was the Chief Minister of Gujarat from 2001 to 2014 and the Member of Parliament for Varanasi. 

## Content

- Transcript of the speeches given by Narendra Modi made publicly available at https://www.pmindia.gov.in/

- The same speeches are available in both CSV and JSON format.

- Scraped from https://www.pmindia.gov.in/en/tag/pmspeech/ using Selenium and Python's Beautiful Soup package.

- Metadata for each speech contains:

    1. `date`: Date on which the speech was given.

    2. `title`: Title of the speech, as mentioned on the website.

    3. `url`: Link to the HTML version on the official site.

    4. `lang`: Language of the speech<sup>[1]</sup>.

    5. `words`: Total number of words<sup>[2]</sup> in the speech. 

    6. `text`: The transcript of the speech.


##### [1]: As detected using `langdetect` library.

##### [2]: Note that Python does NOT store Hindi words the same way as English words.