TwitterTimeline
===============

A data-mining project performed at MHacks 2014. The program would mine a live tweet stream from twitter, filtering tweets based on keywords given by the user, then it would analyze the sentiment of the tweet. Sentiment analysis based of training set of 1k words provided by UCB CS Staff, then extrapolated to the a larger set of 22k words by constructing a thesaurus as a graph and averaging the sentiment based off the average of its neighbors. Following this the geo-location would be plotted on a SVG map of the globe (D3 API) with the tweets color coded based on tweet sentiment. (Back-end including tweet mining and sentiment analysis is operational, some bugs on the front end still with the javascript code.) Work in progress.


The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
