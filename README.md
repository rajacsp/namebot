[![Build Status](https://travis-ci.org/Automotron/namebot.svg?branch=master)](https://travis-ci.org/Automotron/namebot)

# Namebot
A company/product name generating tool written in Python. Powers parts of Automotron.com

## Notes:
This project is ongoing, but feel free to contribute! There's much more to add, but it's a full-fledged suite of tools that can help you get started generating ideas and names.

## Modules:
### Examples
Some pregenerated examples for testing. This should be used for marshalling data into the views.

### Metrics
A class of utilities for generating all kinds of linguistic metrics for a set of words.

### NLP
Natural language processing tools for finding word relationships - uses NLTK for all of the heavy-lifting.

### Normalization
Some tools for normalizing and formatting content for use with the rest of the library.

### Scoring
Some scoring algorithms, primarily for classifying pronunciation, such as Soundex or Double Metaphone.

### Techniques
The major chunk of work represented in this library. The many techniques I've created after researching hundreds of corporate names and naming agency techniques

### Strainer
Similar to normalization, but for filtering based on rules, like length, count, etc... good for mapping 1:1 with UI inputs or just calling from the functions directly.

## How to setup server and test:

Check out https://github.com/Automotron/namebot-flask to see an example app
and configuration setup to use namebot and generate results with test data.

## Library Dependencies
See `requirements.txt` for details.

## Tests

Tests are available in the `tests/` folder. They are not super comprehensive, but there is coverage. Test runner is provided by nose and can be run via `make`.

----

#### Support the development, if you want :)
<div class="donate-button">
    <a class="donate-button-link" href="#">
        <img src="http://ef3ae845b6eed6ec4024-8a0a46e5f1a5cc9854958bc3503f0f88.r40.cf1.rackcdn.com/donate_64.png" alt="Donate Ƀitcoin" />
    </a>
    <div class="bitcoin-address">Ƀitcoin address: <code>1G5MdiPHCnPJUKXW1SJwWmUTDVjG1aG7xj</code></div>
</div>
