# OmniAuth strategy for ResourceGuruApp

[![Gem Version](https://badge.fury.io/rb/omniauth-resourceguru.png)](http://badge.fury.io/rb/omniauth-resourceguru)
[![CI Build Status](https://secure.travis-ci.org/kamerblauwlicht/omniauth-resourceguru.png?branch=master)][travis]
[![Code Climate](https://codeclimate.com/repos/52612ea256b10226a210067f/badges/e2eb8729541ee2783171/gpa.png)](https://codeclimate.com/repos/52612ea256b10226a210067f/feed)
[![Coverage Status](https://coveralls.io/repos/kamerblauwlicht/omniauth-resourceguru/badge.png)](https://coveralls.io/r/kamerblauwlicht/omniauth-resourceguru)
[![Dependency Status](https://gemnasium.com/kamerblauwlicht/omniauth-resourceguru.png)](https://gemnasium.com/kamerblauwlicht/omniauth-resourceguru)

[travis]: http://travis-ci.org/kamerblauwlicht/omniauth-resourceguru
[codeclimate]: https://codeclimate.com/github/kamerblauwlicht/omniauth-resourceguru


## Basic Usage

    use OmniAuth::Builder do
      provider :resource_guru, ENV['RESOURCE_GURU_CLIENT_ID'], ENV['RESOURCE_GURU_SECRET']
    end


## License

Copyright (c) 2013 Daniël van Gils and Steam Advertising B.V.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
