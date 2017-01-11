# Chapter 4

To perform better in search engine listings, your post important content should be in HTML text format. Images, flash, java applets, and other non-get content are often ignored or devalued by search engine crawlers. 

There are more advanced methods available to those who demand greater formatting or visual display:

1. Provide alt text for images.
2. Supplement search boxes with navigation and crawlable links. 
3. Supplement flash or java plugins with text on the page.
4. Provides a transcript for video and audio content if the words and phrases used are meant to be indexed by the engines.

By using the MozBar, you can see what elements of your content are visible and indexable to the engines. It’s wise to not only check for text content but also use SEO tools to double-check that the pages you’re building are visible to the engines. This applies to your images and your links as well.

### Crawlable Link Structures

A crawlable link structure is vital to allowing search engines find all the pages of your website. Lots of websites make the critical mistake of structuring their navigation in ways that search engines cannot access. 

Crawlers know that they should add links (anchor text) to the engine’s link graph of the web, use it to calculate query-independent variables, and follow it to index the contents of the reference page.

## Some Common Reasons Why Links May Be Unreachable

1. Submission required forms: may require users to complete an online form before accessing certain content. Crawlers generally do not attempt to submit forms, so content will be invisible to the engines.
2. Links in unparseable Javascript: search engines give little weight to the links embedded within javascript. Standard HTML links should replace Javascript on any pages you’d like crawlers to crawl.
3. Links pointing to pages blocked by the Meta Robots tag or robots.txt: the meta robots tag and robots.txt file both allow a site owner to restrict crawler access to a page.
4. Frames or frames: technically, links in both frames and frames are crawl able, but both present structural issues for the engines in terms or organization and following. Unless you’re an advanced user with technical understand, it’s best to stay away from them.
5. Robots don’t search forms: web crawlers don’t perform searches to find content so a search bar won’t do.
6. Links in Flash, Java, and other Plug-ins: links inside these types may be invisible to engines.
7. Links on pages with many hundred or thousands of links: search engines will only crawl so many links on a given page. This restriction is necessary to cut down on spam and conserve rankings.

If you avoid these pitfalls, you’ll have clean, spider able HTML links that will allow the spiders easy access to your content pages.

### rel = “nofollow”

Links can have lots of attributes. The engines ignore nearly all of them with the exception of rel = “nofollow” which tells search engines that the site owners do not want this link to be interpreted as an endorsement of the target page. It instructs the search engines to not follow a link. 

At Google, a nofollow link causes them to drop target links from their overall graph of the web. They do not use them in page rankings.

### Keyword Usage and Targeting

Keywords are fundamental to the search process. They are the building blocks of language and of search. The entire science of information retrieval is based on keywords. If you want your page to have a chance of ranking in the search results for “dog”, it’s wise to make sure the word “dog is part of the crawl able content of your document.

### Keyword Domination

Keywords dominate how we communicate our search intent and interact with the engines. When we enter words to search for, the engine matches pages retrieve based on the words we entered. The order of the words, spelling, punctuation, and capitalization provide additional information that the engines use to help retrieve the right pages.

Search engines measure how keywords are used on pages to help determine the relevance of a particular document to a query. One of the best ways to optimize a page’s rankings is to ensure that the keywords you want to rank for are prominently used in titles, text, and metadata.

Generally speaking, if you make your keywords more specific, you narrow the competition for search results. 

### __Keyword Abuse__

People have abused keywords by stuffing keywords into text, URLs, meta tags, and links. This tactic almost always does more harm than good. 

The best practice is to use your keywords naturally and strategically. If your page targets the keyword “Eiffel Tower” then you might naturally include content about the Eiffel Tower itself, the history of the tower, or even recommended Paris Hotels. If you spam Eiffel Tower and include irrelevant content, your ranking may suffer.

> Keyword density is not part of modern ranking algorithms. It is divorced from content, quality, semantics, and relevance.

The point of keywords is not to rank highly for all keywords but to rank highly for the keywords that people are searching for when they want what your site provides. 

## What should an optimal page look like then?

For the phrase “running shoes”:

Title: Running Shoes for Runners Who Love High Quality, Comfortable Shoes
Heading #1: Find the Best Running Shoes to Fit Your Needs
Body Copy: Some compelling text about the benefits of choosing the right running shoes; finding the brand and sizes comparing running shoes;
Alt attribute to photo: The famous running shoes of an olympian.
URL: http://www.yourdomain.com/runningshoes

### On Page Optimization

Keyword usage and targeting are still part of the search engine’s ranking algorithm and we can apply some effective techniques for keyword usage to help create pages that are well optimized. Use the keyword phrase:

1. In the title tag at least once. Try keeping it as close to the beginning of the title tag as possible. 
2. Once prominently near the top of the page.
3. At least two or three times in the body copy on the page. Adding more instances of a term or phrase tends to have little or no impact on rankings.
4. At least once in the alt attribute of an image on the page. This not only helps in web search but also image search, which can bring in traffic.
5. Once in the URL. 
6. At least once in the meta description tag. The meta description becomes the snippet of test used by the search engines. 

You should generally not use keywords in link anchor text pointing to other pages on your site. This is known as keyword cannibalization.

### Title Tags

The title element of a page is meant to be an accurate, concise description of a page’s content. It is critical to both user experience and search engine optimization.

As title tags are such an important part of search engine optimization, the following best practice for the tag creation makes for terrific low-hanging SEO fruit. The recommendations below cover the critical steps to optimize title tags for search engines and for usability:

1. Be mindful of length. Search engine only displays the first 65-75 characters of a title tag in the search results. After that the engines show ellipsis afterwards. This is also the general limit allowed by most social media sites. If you’re targeting multiple keywords, and having them in the title tag is essential to ranking, it be advisable to go longer.

2. Place important keywords close to the front. The closer to the start of the title tag your keywords are, the more helpful they’ll be for ranking, and the more likely a person will click them.

3. Include branding. Ending every title tag with a brand name mention increase brand awareness, and create a higher click through rate for people who like and are familiar with a brand.

4. Consider readability and emotional impact. Title tags should be descriptive and readable. Creating a compelling title tag will help grab attention on the search results page and attract more visitors to your site. This underscores that SEO is about not only optimization and strategic keyword usage but the entire user experience.

## Meta Tags

Originally intended as a proxy for information about a website’s content.

### Meta Robots

This tag can be used to control search engine crawler activity on a per-page level. There are several ways to use Meta Robots to control how search engines treat a page:

1. index/noindex tells the engines whether the page should be crawled or kept in the engine’s index for retrieval. If you opt to use no index, the page will be excluded from the index. By default, search engines assume they can index all pages, so using the “index” value is generally unnecessary. 

2. follow/nofollow tells the engine whether links on the page should be crawled. If you elect to employ “nofollow”, the engines will disregard the links on the page for discovery, ranking purposes, or both. By default, all pages are assumed to have the follow attribute.

3. noarchive is used to restrict search engines from saving a cached copy of a page. By default, the engines will maintain visible copies of all pages they have indexed, accessible to searchers through the cached link in the search result. 

4. nosnippet informs the engines that they should refrain from displaying a descriptive block of text next to the page’s title and URL in the search results.

5. noodp/noydir are specialized tags telling the engines not to grab a descriptive snippet about a page from the Open Directory Project or the Yahoo directory for display in the search results. The X-Robots-Tag HTTP header directive also accomplishes these same objectives. This technique works especially well for content within non-HTML files, like images.

### Meta Descriptions

The meta description tag exists as a short description of a page’s content. Search engines do not use the keywords or phrases in this tag for rankings but meta descriptions are the primary source for the snippet of text displayed beneath a listing in the results.

The meta description tag serves the function of advertising copy, drawing readers to your site from the results. It is an extremely important part of search marketing. Crafting a readable, compelling description using important keywords (Google bolds keywords) can draw a much higher click-through rate of searchers to your page.

Meta descriptions can be any length, but search engines generally cut snippets longer than 160 characters, so it’s generally wise to stay within these limits.

In the absence of meta descriptions, search engines will create the search snippet from other elements of the page. For pages that target multiple keywords and topics, this is a perfectly valid tactic.

### Not as important Meta Tags

1. Meta keywords: the meta keywords tag had value at one time, but is no longer valuable or important to search engine optimization. 

2. Meta Refresh, Meta Revisit, Meta Content-Type, and others: although these tags can have uses for search engine optimization, they are less critical to the process so we can leave it to Google’s Webmaster Tools Help to discuss in greater detail.

### URL Structure

URLs, the addresses for documents on the web, are of great value from a search perspective. They appear in multiple important locations.

1. URLs impact click-through and visibility. URLs are also used in ranking documents, and those pages whose names include the queried search terms received some benefit from proper, descriptive use of keywords.

2. URLs make an appearance in the web browser’s address bar, and while this generally have little impact on search engines, poor URL structure and design can result in negative user experiences.

### URL Construction Guidelines

1. Employ empathy: place yourself in the mind of a user and look at your URL. If you can easily and accurately predict the content you expect to find on the page, your URL is appropriately descriptive. You don’t need to spell out every last detail but a rough idea is a good starting point.

2. Shorter is better: while a descriptive URL is important, mining length and trailing slashes will make your URLs easier to copy and paste and will be fully visible in the search results.

3. Keyword use is important: if your page is targeting a specific term or phrase, make sure to include it in the URL. However, don’t go overboard by trying to stuff in multiple keywords for SEO purposes. Overuse will result in less usual URLS and can trip spam filters.

4. Go static: the best URLs are human readable and without lots of parameters, numbers, and symbols. Using single dynamic parameters can result in lower overall ranking and indexing.

5. Use hyphens to separate words: not all web applications accurately interpret separators like underscores, plus signs, or spaces so instead use the hyphen character to separate words in a URL.

## Canonical and Duplicate Versions of Content

Duplicate content is one of the most vexing and troublesome problems any website can face. Search engines have cracked down on pages with thin or duplicate content by assigning them lower rankings.

Canonicalization happens when two or more duplicate versions of a webpage appear on different URLs. This is common with modern CMS. 

The engines are picky about duplicate versions of a single piece of material. To provide the best search experience, they will rarely show multiple, duplicate pieces of content, and instead choose which version is most likely to be the original. The end result is all your duplicate content could rank lower than it should.

Canonicalization is the practice of organizing your content in such a way that every unique piece has one, and only one, URL. You may choose to redirect URLs to a strong page to be shown in the listings.

When multiple pages with the potential to rank well are combined into a single page, they not only stop competing with each other, but also create a stronger relevancy and popularity signal overall. This positively impacts your ability to rank well in the search engines.

### Canonical tag to the rescue

A different option from the search engines, called the canonical URL tag, is another way to reduce instances of duplicate content on a single site and canonicalize to an individual URL. This can also be used across different websites, from one URL to one domain to a different URL on a different domain.

Use the canonical tag within the page that contains duplicate content. The target of the canonical tag points to the master URL that you want to rank for.

<link rel=“canonical” href=“http://moz.com/blog” />

This tells search engines that the page in question should be treated as though it were a copy of the URL and that all the link and content metrics the engines applies should flow back to that URL.

From a SEO perspective, the Canonical URL tag attribute is similar to a 301 redirect. In essence, you are telling the engines that multiple pages should be considered as one, but without redirectting visitors to the new URL. 


## Rich Snippets

Rich snippets are a type of structured data that allow webmaster to mark up content in ways that provide information to the search engines. 

While the use of snippets and structured data is not a required element in search engine friendly design, its growing adoption means that webmaster who employ it may enjoy an advantage in some circumstances. 

Structured data means adding makeup to your content so that search engines can easily identify what type of content it is. Often the search engines includes structure data in search results, such as in the case of user reviews, author profiles, hours, addresses, etc.

## Defending your site’s honor

### How Scapers steal your rankings

The web is littered with websites whose business and traffic models depend on plucking content and reusing it on their own domains. To combat this, you can include links back to your site and to specific posts you’ve authored to ensure the search engine see most of the copies linking back to you. To do this, you need absolute, rather than relative links to your internal linking structure.


