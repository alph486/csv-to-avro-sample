csv-avro-sample
===============

Sample Python script that reads a unicode data file and transforms it into an avro file compressed with deflate.

The data included with this sample is from the Million Song Dataset project: http://labrosa.ee.columbia.edu/millionsong/ . The data is subject to their license which is summarized here: http://developer.echonest.com/docs/v4/#ground-rules.

To use:

- Clone the repo (have pip and virtualenv installed)
- virtualenv env
- source env/bin/activate
- pip install -r requirements.txt
- Unzip data/unique_tracks.zip to the data/ directory
- In the root directory: python avro-convert.py
