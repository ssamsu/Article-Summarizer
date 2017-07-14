**ARTICLE SUMMARIZER**


Get summary of any online articles.

**USAGE**


Say an article `http://timesofindia.indiatimes.com/world/china/china-under-pressure-to-free-ailing-nobel-laureate/articleshow/59574334.cms` from Times of India which has 16 lines that need to be summarized. First, this URL needs to be passed as an argument to `extractText(url)` function to get the text content. Then, we need to decide on a number of sentences that our summarizer should have, let us consider that value as 3. Finally, the obtained text and the number of sentences value (which is 3), should be passed as an argument to `summarizer(text, N)` function.

**OUTPUT**


`['  shenyang: china faced sustained international pressure on thursday to let cancer-stricken nobel laureate liu xiaobo seek treatment abroad, as official hospital updates suggest the democracy champion is close to death.',
 'the doctors said liu needed to be on artificial ventilation to be kept alive, but his family declined, according to the first hospital of china medical university in the northeastern city of shenyang.',
 'a german and a us doctor visited liu last weekend and said he was still strong enough to fulfil his wish to travel overseas, but the hospital has issued increasingly pessimistic reports every day since then.']`

**NOTE:**


The code can be modified to use for any website articles, all you have to do is edit the `soup.find()` according to your site  in `extractText(url)` function.
