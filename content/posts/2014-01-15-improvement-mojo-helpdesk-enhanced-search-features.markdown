---
author: supercobra thatbytes
comments: false
date: 2014-01-15 11:34:00+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2014/01/improvement-mojo-helpdesk-enhanced-search-features/
slug: improvement-mojo-helpdesk-enhanced-search-features
title: 'IMPROVEMENT: Mojo Helpdesk Enhanced Search Features'
wordpress_id: 71
categories:
- Product Updates
tags:
- free help desk software
- Help desk
- help desk software
- mojo help desk
- new feature
---




 Mojo Helpdesk is pleased to announce new upgrades to our search engine which will assist users in quickly locating specific tickets.









Most importantly, users can now **search ticket comments and custom field values** for specific words or phrases.

For example, if the help desk technician searches the word "test" as in the example below, all comments where those words appear will appear in the results.


We recommend users take advantage of more advanced search techniques in order to efficiently navigate through tickets.




Below find a few tips that will help you find tickets quickly:




** Use Wild Card searches if you're "not sure" of the exact search phrase.**







 Examples:





	
  * Searching for `serv*s` will match both `servers` and `services`.

	
  * Searching `*123` will match `xyz123`.

	
  * Searching `inv?te` will match `invite` but not `invente`.

	
  * Searching for `abc` will match only exact word `abc`.







### Proximity searches can help locate keywords that are not spaced together.










Mojo supports finding words are a within a specific distance away. To do a proximity search use the tilde, `~`, symbol at the end of a Phrase.


Examples



	
  * `"www.mojohelpdesk.com/blog users"~10` searches for a "www.mojohelpdesk.com/blog" and "users" within 10 words of each other.




### Boolean Operators specify which words are included or left out of search.







**
**


Boolean operators allow terms to be combined through logic operators. Mojo supports `AND`, `+`, `OR`, `NOT` and `-` as Boolean operators (Note: **Boolean operators must be ALL CAPS**).




### OR operator




The `OR` operator is the default conjunction operator. This means that if there is no Boolean operator between two terms, the`OR` operator is used. The `OR` operator links two terms and finds a matching document if either of the terms exist in a document. This is equivalent to a union using sets. The symbol `||` can be used in place of the word `OR`.




To search for documents that contain either "www.mojohelpdesk.com/blog apache" or just "www.mojohelpdesk.com/blog" use the query:



    
    <code>"www.mojohelpdesk.com/blog apache" www.mojohelpdesk.com/blog
    </code>




or



    
    <code>"www.mojohelpdesk.com/blog apache" OR www.mojohelpdesk.com/blog
    </code>




### AND operator




The `AND` operator matches documents where both terms exist anywhere in the text of a single document. This is equivalent to an intersection using sets. The symbol `&&` can be used in place of the word `AND`.




To search for documents that contain "www.mojohelpdesk.com/blog apache" and "Apache Lucene" use the query:



    
    <code> "www.mojohelpdesk.com/blog apache" AND "Apache Lucene"
    </code>




### + operator
**
**




The `+` or required operator requires that the term after the `+` symbol exist somewhere in a the field of a single document.




To search for documents that must contain "www.mojohelpdesk.com/blog" and may contain "lucene" use the query:



    
    <code> +www.mojohelpdesk.com/blog lucene
    </code>




### NOT operator




The `NOT` operator excludes documents that contain the term after `NOT`. This is equivalent to a difference using sets. The symbol `!` can be used in place of the word `NOT`.




To search for documents that contain "www.mojohelpdesk.com/blog apache" but not "Apache Lucene" use the query:



    
    <code>"www.mojohelpdesk.com/blog apache" NOT "Apache Lucene"
    </code>




Note: The NOT operator cannot be used with just one term. For example, the following search will return no results:



    
    <code>NOT "www.mojohelpdesk.com/blog apache"
    </code>




### - operator




The `-` or prohibit operator excludes documents that contain the term after the `- symbol.




To search for documents that contain "www.mojohelpdesk.com/blog apache" but not "Apache Lucene" use the query:



    
    <code>"www.mojohelpdesk.com/blog apache" -"Apache Lucene"<b>
    </b></code>




### Grouping




Mojo supports using parentheses to group clauses to form sub queries. This can be very useful if you want to control the boolean logic for a query.




To search for either "www.mojohelpdesk.com/blog" or "apache" and "website" use the query:



    
    <code>(www.mojohelpdesk.com/blog OR apache) AND website</code>




This eliminates any confusion and makes sure that website must exist and either term www.mojohelpdesk.com/blog or apache may exist.




Finally, our search functionality is much faster, which will help users swiftly navigate through the content with ease.




###







### 






