# Tests

[![Build
Status](https://travis-ci.org/rgevaert/grok-patterns.svg?branch=master)](http://travis-ci.org/rgevaert/grok-patterns)

## Grok Tests

As well as being a set of patterns for people to use in logstash, this
repo also contains test suites for those patterns and a rspec matcher
that might be useful to anyone else who wants to write and test grok
patterns. You can run the test suite with:

    bundle install
    bundle exec rake

## Logstash tests

Currently manually and WIP

Assumes logstash is in your path.

## Contributing

1. Fork this repository
2. Add a pattern to the patterns directory
3. Add passing tests to the spec directory
4. Update the list of patterns in the README
5. Send a pull request

## License

Copyright (c) 2014,2015, Rudy Gevaert

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 
